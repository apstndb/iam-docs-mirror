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
<td>External Exposure Admin <sup>Beta</sup>
<p>( <code>roles/ externalexposure.admin</code> )</p>
<p>Full access to external exposure resources.</p></td>
<td><p><code>externalexposure.*</code></p>
<ul>
<li><code>externalexposure.locations.get</code></li>
<li><code>externalexposure. locations. list</code></li>
<li><code>externalexposure. operations. cancel</code></li>
<li><code>externalexposure. operations. delete</code></li>
<li><code>externalexposure. operations. get</code></li>
<li><code>externalexposure. operations. list</code></li>
<li><code>externalexposure. scanMetrics. get</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>External Exposure Viewer <sup>Beta</sup>
<p>( <code>roles/ externalexposure.viewer</code> )</p>
<p>Read only access to external exposure resources.</p></td>
<td><p><code>externalexposure.locations.*</code></p>
<ul>
<li><code>externalexposure.locations.get</code></li>
<li><code>externalexposure. locations. list</code></li>
</ul>
<p><code>externalexposure. operations. get</code></p>
<p><code>externalexposure. operations. list</code></p>
<p><code>externalexposure. scanMetrics. get</code></p>
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
<td>External Exposure Service Agent
<p>( <code>roles/ externalexposure.serviceAgent</code> )</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.autoscalers.get</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instanceSettings.get</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute. instances. getScreenshot</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listReferrers</code></p>
<p><code>compute. interconnectAttachmentGroups. get</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
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
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute. networks. getRegionEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. regionBackendBuckets. get</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. get</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkPolicies. get</code></p>
<p><code>compute. regionNetworkPolicies. list</code></p>
<p><code>compute. regionNotificationEndpoints. get</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute.regionSslPolicies.get</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. listAvailableFeatures</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.getRoutePolicy</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.listBgpRoutes</code></p>
<p><code>compute. routers. listRoutePolicies</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. listAvailableFeatures</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.targetGrpcProxies.get</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
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
<p><code>networksecurity. authorizationPolicies. get</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authzPolicies. get</code></p>
<p><code>networksecurity. authzPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. get</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. firewallEndpointAssociations. get</code></p>
<p><code>networksecurity. firewallEndpointAssociations. list</code></p>
<p><code>networksecurity. firewallEndpoints. get</code></p>
<p><code>networksecurity. firewallEndpoints. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicies. list</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. get</code></p>
<p><code>networksecurity. gatewaySecurityPolicyRules. list</code></p>
<p><code>networksecurity.locations.*</code></p>
<ul>
<li><code>networksecurity.locations.get</code></li>
<li><code>networksecurity.locations.list</code></li>
</ul>
<p><code>networksecurity.operations.get</code></p>
<p><code>networksecurity. operations. list</code></p>
<p><code>networksecurity. sacAttachments. get</code></p>
<p><code>networksecurity. sacAttachments. list</code></p>
<p><code>networksecurity.sacRealms.get</code></p>
<p><code>networksecurity.sacRealms.list</code></p>
<p><code>networksecurity. securityProfileGroups. get</code></p>
<p><code>networksecurity. securityProfileGroups. list</code></p>
<p><code>networksecurity. securityProfiles. get</code></p>
<p><code>networksecurity. securityProfiles. list</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. tlsInspectionPolicies. get</code></p>
<p><code>networksecurity. tlsInspectionPolicies. list</code></p>
<p><code>networksecurity.urlLists.get</code></p>
<p><code>networksecurity.urlLists.list</code></p>
<p><code>networkservices. authzExtensions. get</code></p>
<p><code>networkservices. authzExtensions. list</code></p>
<p><code>networkservices. endpointPolicies. get</code></p>
<p><code>networkservices. endpointPolicies. list</code></p>
<p><code>networkservices.gateways.get</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices.grpcRoutes.get</code></p>
<p><code>networkservices. grpcRoutes. list</code></p>
<p><code>networkservices. httpFilters. get</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices.httpRoutes.get</code></p>
<p><code>networkservices. httpRoutes. list</code></p>
<p><code>networkservices. httpfilters. get</code></p>
<p><code>networkservices. httpfilters. list</code></p>
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
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## External Exposure permissions

| Permission                             | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|----------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `externalexposure.locations.get`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [External Exposure Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer) ( `roles/ externalexposure.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `externalexposure. locations. list`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [External Exposure Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer) ( `roles/ externalexposure.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                      |
| `externalexposure. operations. cancel` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `externalexposure. operations. delete` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `externalexposure. operations. get`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [External Exposure Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer) ( `roles/ externalexposure.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `externalexposure. operations. list`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [External Exposure Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer) ( `roles/ externalexposure.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                      |
| `externalexposure. scanMetrics. get`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [External Exposure Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin) ( `roles/ externalexposure.admin` ) [External Exposure Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer) ( `roles/ externalexposure.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
