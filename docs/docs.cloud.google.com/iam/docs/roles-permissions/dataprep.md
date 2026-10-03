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
<td>Dataprep Admin <sup>Beta</sup>
<p>( <code>roles/ dataprep.admin</code> )</p>
<p>Admin role for dataprep</p></td>
<td><p><code>dataprep.projects.use</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
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
<tr class="even">
<td>Dataprep User <sup>Beta</sup>
<p>( <code>roles/ dataprep.projects.user</code> )</p>
<p>Use of Dataprep.</p></td>
<td><p><code>dataprep.projects.use</code></p>
<p><code>resourcemanager.projects.get</code></p>
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
<td>Dataprep Service Agent
<p>( <code>roles/ dataprep.serviceAgent</code> )</p>
<p>Dataprep service identity. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.bireservations.get</code></p>
<p><code>bigquery. capacityCommitments. get</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery.config.get</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery. reservationAssignments. list</code></p>
<p><code>bigquery. reservationAssignments. search</code></p>
<p><code>bigquery.reservationGroups.get</code></p>
<p><code>bigquery. reservationGroups. list</code></p>
<p><code>bigquery.reservations.get</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery. reservations. listFailoverDatasets</code></p>
<p><code>bigquery.reservations.use</code></p>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery.savedqueries.get</code></p>
<p><code>bigquery.savedqueries.list</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.createIndex</code></p>
<p><code>bigquery.tables.createSnapshot</code></p>
<p><code>bigquery.tables.delete</code></p>
<p><code>bigquery.tables.deleteIndex</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery.tables.replicateData</code></p>
<p><code>bigquery. tables. restoreSnapshot</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>bigquery.tables.updateIndex</code></p>
<p><code>bigquery.tables.updateTag</code></p>
<p><code>bigquery.transfers.get</code></p>
<p><code>bigquerymigration. translation. translate</code></p>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>cloudbuild.builds.update</code></p>
<p><code>cloudbuild.locations.*</code></p>
<ul>
<li><code>cloudbuild.locations.get</code></li>
<li><code>cloudbuild.locations.list</code></li>
</ul>
<p><code>cloudbuild.operations.*</code></p>
<ul>
<li><code>cloudbuild.operations.get</code></li>
<li><code>cloudbuild.operations.list</code></li>
</ul>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute.advice.capacity</code></p>
<p><code>compute.advice.capacityHistory</code></p>
<p><code>compute.autoscalers.get</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute. backendBuckets. getIamPolicy</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute. backendServices. getIamPolicy</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute.commitments.get</code></p>
<p><code>compute.commitments.list</code></p>
<p><code>compute. commitments. listEffectiveTags</code></p>
<p><code>compute. commitments. listTagBindings</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute.diskSettings.get</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute.firewallPolicies.get</code></p>
<p><code>compute. firewallPolicies. getIamPolicy</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. getIamPolicy</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute. futureReservations. listEffectiveTags</code></p>
<p><code>compute. futureReservations. listTagBindings</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalFrontendSettings. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. globalNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute. globalOperations. getIamPolicy</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. get</code></p>
<p><code>compute. globalPublicDelegatedPrefixes. list</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute.hosts.*</code></p>
<ul>
<li><code>compute.hosts.get</code></li>
<li><code>compute.hosts.getVersion</code></li>
<li><code>compute.hosts.list</code></li>
</ul>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.getFromFamily</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute.instanceSettings.get</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. getIamPolicy</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getEffectiveFirewalls</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute.instances.getIamPolicy</code></p>
<p><code>compute. instances. getScreenshot</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute. instances. getShieldedInstanceIdentity</code></p>
<p><code>compute. instances. getShieldedVmIdentity</code></p>
<p><code>compute. instances. getVmExtensionState</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listReferrers</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instances. listVmExtensionStates</code></p>
<p><code>compute.instances.troubleshoot</code></p>
<p><code>compute. instantSnapshotGroups. get</code></p>
<p><code>compute. instantSnapshotGroups. getIamPolicy</code></p>
<p><code>compute. instantSnapshotGroups. list</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
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
<p><code>compute.licenseCodes.get</code></p>
<p><code>compute. licenseCodes. getIamPolicy</code></p>
<p><code>compute.licenseCodes.list</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.machineImages.get</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.managedRulesets.*</code></p>
<ul>
<li><code>compute.managedRulesets.get</code></li>
<li><code>compute.managedRulesets.list</code></li>
</ul>
<p><code>compute.multiMig.get</code></p>
<p><code>compute.multiMig.list</code></p>
<p><code>compute.multiMigMembers.*</code></p>
<ul>
<li><code>compute.multiMigMembers.get</code></li>
<li><code>compute.multiMigMembers.list</code></li>
</ul>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. getIamPolicy</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEdgeSecurityServices. get</code></p>
<p><code>compute. networkEdgeSecurityServices. list</code></p>
<p><code>compute. networkEdgeSecurityServices. listEffectiveTags</code></p>
<p><code>compute. networkEdgeSecurityServices. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute. networkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. networkEndpointGroups. listTagBindings</code></p>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute. networks. getRegionEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.nodeGroups.get</code></p>
<p><code>compute. nodeGroups. getIamPolicy</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute.nodeTemplates.get</code></p>
<p><code>compute. nodeTemplates. getIamPolicy</code></p>
<p><code>compute.nodeTemplates.list</code></p>
<p><code>compute.nodeTypes.*</code></p>
<ul>
<li><code>compute.nodeTypes.get</code></li>
<li><code>compute.nodeTypes.list</code></li>
</ul>
<p><code>compute.orgRolloutPlans.get</code></p>
<p><code>compute.orgRolloutPlans.list</code></p>
<p><code>compute.orgRollouts.get</code></p>
<p><code>compute.orgRollouts.list</code></p>
<p><code>compute. organizations. listAssociations</code></p>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute.previewFeatures.get</code></p>
<p><code>compute.previewFeatures.list</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. publicAdvertisedPrefixes. get</code></p>
<p><code>compute. publicAdvertisedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. get</code></p>
<p><code>compute. publicDelegatedPrefixes. list</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. recoverableSnapshots. get</code></p>
<p><code>compute. recoverableSnapshots. getIamPolicy</code></p>
<p><code>compute. recoverableSnapshots. list</code></p>
<p><code>compute. regionBackendBuckets. get</code></p>
<p><code>compute. regionBackendBuckets. getIamPolicy</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. getIamPolicy</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionFirewallPolicies. get</code></p>
<p><code>compute. regionFirewallPolicies. getIamPolicy</code></p>
<p><code>compute. regionFirewallPolicies. list</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. get</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. regionNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. regionNetworkPolicies. get</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNotificationEndpoints. get</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute. regionOperations. getIamPolicy</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSecurityPolicies. get</code></p>
<p><code>compute. regionSecurityPolicies. list</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.get</code></p>
<p><code>compute. regionSslPolicies. getIamPolicy</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. listAvailableFeatures</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute.regionUrlMaps.validate</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reliabilityRisks.*</code></p>
<ul>
<li><code>compute.reliabilityRisks.get</code></li>
<li><code>compute.reliabilityRisks.list</code></li>
</ul>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.get</code></p>
<p><code>compute.reservationSlots.list</code></p>
<p><code>compute. reservationSubBlocks. get</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute.resourcePolicies.get</code></p>
<p><code>compute. resourcePolicies. getIamPolicy</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute.rolloutPlans.get</code></p>
<p><code>compute.rolloutPlans.list</code></p>
<p><code>compute.rollouts.get</code></p>
<p><code>compute.rollouts.list</code></p>
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
<p><code>compute.securityPolicies.get</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. getIamPolicy</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute.snapshotGroups.get</code></p>
<p><code>compute. snapshotGroups. getIamPolicy</code></p>
<p><code>compute.snapshotGroups.list</code></p>
<p><code>compute. snapshotRecycleBinPolicy. get</code></p>
<p><code>compute.snapshotSettings.get</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute. snapshots. getEffectiveRecycleBinRule</code></p>
<p><code>compute.snapshots.getIamPolicy</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute.spotAssistants.get</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute. sslPolicies. getIamPolicy</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. listAvailableFeatures</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute.storagePools.get</code></p>
<p><code>compute. storagePools. getIamPolicy</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute. subnetworks. getIamPolicy</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute.targetGrpcProxies.get</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute.urlMaps.validate</code></p>
<p><code>compute. vmExtensionPolicies. get</code></p>
<p><code>compute. vmExtensionPolicies. list</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute. zoneOperations. getIamPolicy</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dataflow.jobs.*</code></p>
<ul>
<li><code>dataflow.jobs.cancel</code></li>
<li><code>dataflow.jobs.create</code></li>
<li><code>dataflow.jobs.get</code></li>
<li><code>dataflow.jobs.list</code></li>
<li><code>dataflow.jobs.snapshot</code></li>
<li><code>dataflow.jobs.updateContents</code></li>
</ul>
<p><code>dataflow.messages.list</code></p>
<p><code>dataflow.metrics.get</code></p>
<p><code>dataflow.snapshots.*</code></p>
<ul>
<li><code>dataflow.snapshots.delete</code></li>
<li><code>dataflow.snapshots.get</code></li>
<li><code>dataflow.snapshots.list</code></li>
</ul>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataplex.datascans.cancel</code></p>
<p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.delete</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.getData</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.datascans.run</code></p>
<p><code>dataplex.datascans.update</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>recommender. dataflowDiagnosticsInsights.*</code></p>
<ul>
<li><code>recommender. dataflowDiagnosticsInsights. get</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. list</code></li>
<li><code>recommender. dataflowDiagnosticsInsights. update</code></li>
</ul>
<p><code>remotebuildexecution.blobs.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
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
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.managedFolders.create</code></p>
<p><code>storage.managedFolders.delete</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.managedFolders.update</code></p>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.*</code></p>
<ul>
<li><code>storage.objects.create</code></li>
<li><code>storage.objects.createContext</code></li>
<li><code>storage.objects.delete</code></li>
<li><code>storage.objects.deleteContext</code></li>
<li><code>storage.objects.get</code></li>
<li><code>storage.objects.getIamPolicy</code></li>
<li><code>storage.objects.list</code></li>
<li><code>storage.objects.move</code></li>
<li><code>storage. objects. overrideUnlockedRetention</code></li>
<li><code>storage.objects.restore</code></li>
<li><code>storage.objects.setIamPolicy</code></li>
<li><code>storage.objects.setRetention</code></li>
<li><code>storage.objects.update</code></li>
<li><code>storage.objects.updateContext</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Dataprep by Trifacta permissions

| Permission              | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `dataprep.projects.use` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Dataprep Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin) ( `roles/ dataprep.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Dataprep User](https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user) ( `roles/ dataprep.projects.user` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
