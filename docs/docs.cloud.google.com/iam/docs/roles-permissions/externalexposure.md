---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/externalexposure
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure
title: External Exposure roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for External Exposure. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## External Exposure roles

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
<td><h4 id="externalexposure.admin" class="role-title add-link" data-text="External Exposure Admin Beta" tabindex="-1">External Exposure Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p>Full access to external exposure resources.</p></td>
<td><p><code dir="ltr" translate="no">externalexposure.*</code></p>
<ul>
<li><code dir="ltr" translate="no">externalexposure.locations.get</code></li>
<li><code dir="ltr" translate="no">externalexposure.  locations.  list</code></li>
<li><code dir="ltr" translate="no">externalexposure.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">externalexposure.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">externalexposure.  operations.  get</code></li>
<li><code dir="ltr" translate="no">externalexposure.  operations.  list</code></li>
<li><code dir="ltr" translate="no">externalexposure.  scanMetrics.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="externalexposure.viewer" class="role-title add-link" data-text="External Exposure Viewer Beta" tabindex="-1">External Exposure Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p>Read only access to external exposure resources.</p></td>
<td><p><code dir="ltr" translate="no">externalexposure.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">externalexposure.locations.get</code></li>
<li><code dir="ltr" translate="no">externalexposure.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">externalexposure.  operations.  get</code></p>
<p><code dir="ltr" translate="no">externalexposure.  operations.  list</code></p>
<p><code dir="ltr" translate="no">externalexposure.  scanMetrics.  get</code></p>
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
<td><h4 id="externalexposure.serviceAgent" class="role-title add-link" data-text="External Exposure Service Agent" tabindex="-1">External Exposure Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  externalexposure.serviceAgent</code> )</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.get</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.instanceSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
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
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getRegionEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
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
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authzPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpointAssociations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  firewallEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  gatewaySecurityPolicyRules.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.locations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  sacAttachments.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.sacRealms.list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfileGroups.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  securityProfiles.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  tlsInspectionPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.urlLists.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  authzExtensions.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.get</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## External Exposure permissions

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
<td><h4 id="externalexposure.locations.get" class="permission-name add-link" data-text="externalexposure.locations.get" tabindex="-1"><code dir="ltr" translate="no">externalexposure.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="externalexposure.locations.list" class="permission-name add-link" data-text="externalexposure.locations.list" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="externalexposure.operations.cancel" class="permission-name add-link" data-text="externalexposure.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="externalexposure.operations.delete" class="permission-name add-link" data-text="externalexposure.operations.delete" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="externalexposure.operations.get" class="permission-name add-link" data-text="externalexposure.operations.get" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="externalexposure.operations.list" class="permission-name add-link" data-text="externalexposure.operations.list" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="externalexposure.scanMetrics.get" class="permission-name add-link" data-text="externalexposure.scanMetrics.get" tabindex="-1"><code dir="ltr" translate="no">externalexposure.  scanMetrics.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
