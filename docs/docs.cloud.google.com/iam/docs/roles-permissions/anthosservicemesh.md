---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh
title: Cloud Service Mesh roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Service Mesh. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Service Mesh roles

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
<td>Mesh Config Admin <sup>Beta</sup>
<p>( <code>roles/ meshconfig.admin</code> )</p>
<p>Full access to all mesh configuration resources</p></td>
<td><p><code>meshconfig.projects.init</code></p></td>
</tr>
<tr class="even">
<td>Mesh Config Viewer <sup>Beta</sup>
<p>( <code>roles/ meshconfig.viewer</code> )</p>
<p>Read access to mesh configuration</p></td>
<td></td>
</tr>
<tr class="odd">
<td>Trafficdirector Admin <sup>Beta</sup>
<p>( <code>roles/ trafficdirector.admin</code> )</p>
<p>Admin role for trafficdirector</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Trafficdirector Viewer <sup>Beta</sup>
<p>( <code>roles/ trafficdirector.viewer</code> )</p>
<p>Viewer role for trafficdirector</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>trafficdirector. networks. getConfigs</code></p></td>
</tr>
<tr class="odd">
<td>Traffic Director Client <sup>Beta</sup>
<p>( <code>roles/ trafficdirector.client</code> )</p>
<p>Fetch service configurations and report metrics.</p></td>
<td><p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
</ul></td>
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
<td>Anthos Service Mesh Service Agent
<p>( <code>roles/ anthosservicemesh.serviceAgent</code> )</p>
<p>Gives the Anthos Service Mesh service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.backendServices.create</code></p>
<p><code>compute.backendServices.delete</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.backendServices.update</code></p>
<p><code>compute.backendServices.use</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. globalNetworkEndpointGroups. create</code></p>
<p><code>compute. globalNetworkEndpointGroups. delete</code></p>
<p><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></p>
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute. globalNetworkEndpointGroups. use</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute.healthChecks.use</code></p>
<p><code>compute. healthChecks. useReadOnly</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. networkEndpointGroups. create</code></p>
<p><code>compute. networkEndpointGroups. delete</code></p>
<p><code>compute. networkEndpointGroups. detachNetworkEndpoints</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute. networkEndpointGroups. use</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute. regionNetworkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. regionNetworkEndpointGroups. create</code></p>
<p><code>compute. regionNetworkEndpointGroups. delete</code></p>
<p><code>compute. regionNetworkEndpointGroups. detachNetworkEndpoints</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. use</code></p>
<p><code>compute.regions.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>container.backendConfigs.*</code></p>
<ul>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
</ul>
<p><code>container. clusterRoleBindings.*</code></p>
<ul>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
</ul>
<p><code>container.clusterRoles.*</code></p>
<ul>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
</ul>
<p><code>container.clusters.connect</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.update</code></p>
<p><code>container.configMaps.*</code></p>
<ul>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
</ul>
<p><code>container. customResourceDefinitions. create</code></p>
<p><code>container. customResourceDefinitions. get</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container. customResourceDefinitions. update</code></p>
<p><code>container.daemonSets.create</code></p>
<p><code>container.daemonSets.delete</code></p>
<p><code>container.daemonSets.get</code></p>
<p><code>container.daemonSets.getStatus</code></p>
<p><code>container.daemonSets.list</code></p>
<p><code>container.daemonSets.update</code></p>
<p><code>container.deployments.get</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.events.get</code></p>
<p><code>container.events.list</code></p>
<p><code>container.jobs.create</code></p>
<p><code>container.jobs.delete</code></p>
<p><code>container.jobs.get</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container.jobs.update</code></p>
<p><code>container. mutatingWebhookConfigurations. create</code></p>
<p><code>container. mutatingWebhookConfigurations. get</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container. mutatingWebhookConfigurations. update</code></p>
<p><code>container.namespaces.create</code></p>
<p><code>container.namespaces.get</code></p>
<p><code>container.namespaces.list</code></p>
<p><code>container.operations.get</code></p>
<p><code>container.pods.get</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.secrets.*</code></p>
<ul>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
</ul>
<p><code>container. serviceAccounts. create</code></p>
<p><code>container. serviceAccounts. delete</code></p>
<p><code>container.serviceAccounts.get</code></p>
<p><code>container.serviceAccounts.list</code></p>
<p><code>container. serviceAccounts. update</code></p>
<p><code>container.services.get</code></p>
<p><code>container.services.list</code></p>
<p><code>container. thirdPartyObjects. create</code></p>
<p><code>container. thirdPartyObjects. get</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. thirdPartyObjects. update</code></p>
<p><code>container. validatingWebhookConfigurations.*</code></p>
<ul>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
</ul>
<p><code>gkehub.features.get</code></p>
<p><code>gkehub.gateway.delete</code></p>
<p><code>gkehub. gateway. generateCredentials</code></p>
<p><code>gkehub.gateway.get</code></p>
<p><code>gkehub.gateway.patch</code></p>
<p><code>gkehub.gateway.post</code></p>
<p><code>gkehub.gateway.put</code></p>
<p><code>gkehub.locations.*</code></p>
<ul>
<li><code>gkehub.locations.get</code></li>
<li><code>gkehub.locations.list</code></li>
</ul>
<p><code>gkehub.memberships.get</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>meshconfig.projects.init</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>networksecurity. authorizationPolicies. create</code></p>
<p><code>networksecurity. authorizationPolicies. delete</code></p>
<p><code>networksecurity. authorizationPolicies. get</code></p>
<p><code>networksecurity. authorizationPolicies. list</code></p>
<p><code>networksecurity. authorizationPolicies. update</code></p>
<p><code>networksecurity. authorizationPolicies. use</code></p>
<p><code>networksecurity. clientTlsPolicies. create</code></p>
<p><code>networksecurity. clientTlsPolicies. delete</code></p>
<p><code>networksecurity. clientTlsPolicies. get</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. update</code></p>
<p><code>networksecurity. clientTlsPolicies. use</code></p>
<p><code>networksecurity.operations.*</code></p>
<ul>
<li><code>networksecurity. operations. cancel</code></li>
<li><code>networksecurity. operations. delete</code></li>
<li><code>networksecurity.operations.get</code></li>
<li><code>networksecurity. operations. list</code></li>
</ul>
<p><code>networksecurity. serverTlsPolicies. create</code></p>
<p><code>networksecurity. serverTlsPolicies. delete</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. serverTlsPolicies. update</code></p>
<p><code>networksecurity. serverTlsPolicies. use</code></p>
<p><code>networkservices. endpointPolicies.*</code></p>
<ul>
<li><code>networkservices. endpointPolicies. create</code></li>
<li><code>networkservices. endpointPolicies. delete</code></li>
<li><code>networkservices. endpointPolicies. get</code></li>
<li><code>networkservices. endpointPolicies. list</code></li>
<li><code>networkservices. endpointPolicies. update</code></li>
</ul>
<p><code>networkservices. gateways. create</code></p>
<p><code>networkservices. gateways. delete</code></p>
<p><code>networkservices.gateways.get</code></p>
<p><code>networkservices.gateways.list</code></p>
<p><code>networkservices. gateways. update</code></p>
<p><code>networkservices.gateways.use</code></p>
<p><code>networkservices.grpcRoutes.*</code></p>
<ul>
<li><code>networkservices. grpcRoutes. create</code></li>
<li><code>networkservices. grpcRoutes. delete</code></li>
<li><code>networkservices.grpcRoutes.get</code></li>
<li><code>networkservices. grpcRoutes. list</code></li>
<li><code>networkservices. grpcRoutes. update</code></li>
</ul>
<p><code>networkservices. httpFilters. create</code></p>
<p><code>networkservices. httpFilters. delete</code></p>
<p><code>networkservices. httpFilters. get</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices. httpFilters. update</code></p>
<p><code>networkservices.httpRoutes.*</code></p>
<ul>
<li><code>networkservices. httpRoutes. create</code></li>
<li><code>networkservices. httpRoutes. delete</code></li>
<li><code>networkservices.httpRoutes.get</code></li>
<li><code>networkservices. httpRoutes. list</code></li>
<li><code>networkservices. httpRoutes. update</code></li>
</ul>
<p><code>networkservices.meshes.create</code></p>
<p><code>networkservices.meshes.delete</code></p>
<p><code>networkservices.meshes.get</code></p>
<p><code>networkservices.meshes.list</code></p>
<p><code>networkservices.meshes.update</code></p>
<p><code>networkservices.meshes.use</code></p>
<p><code>networkservices.operations.*</code></p>
<ul>
<li><code>networkservices. operations. cancel</code></li>
<li><code>networkservices. operations. delete</code></li>
<li><code>networkservices.operations.get</code></li>
<li><code>networkservices. operations. list</code></li>
</ul>
<p><code>networkservices. serviceLbPolicies.*</code></p>
<ul>
<li><code>networkservices. serviceLbPolicies. create</code></li>
<li><code>networkservices. serviceLbPolicies. delete</code></li>
<li><code>networkservices. serviceLbPolicies. get</code></li>
<li><code>networkservices. serviceLbPolicies. list</code></li>
<li><code>networkservices. serviceLbPolicies. update</code></li>
</ul>
<p><code>networkservices.tcpRoutes.*</code></p>
<ul>
<li><code>networkservices. tcpRoutes. create</code></li>
<li><code>networkservices. tcpRoutes. delete</code></li>
<li><code>networkservices.tcpRoutes.get</code></li>
<li><code>networkservices.tcpRoutes.list</code></li>
<li><code>networkservices. tcpRoutes. update</code></li>
</ul>
<p><code>networkservices.tlsRoutes.*</code></p>
<ul>
<li><code>networkservices. tlsRoutes. create</code></li>
<li><code>networkservices. tlsRoutes. delete</code></li>
<li><code>networkservices.tlsRoutes.get</code></li>
<li><code>networkservices.tlsRoutes.list</code></li>
<li><code>networkservices. tlsRoutes. update</code></li>
</ul>
<p><code>orgpolicy.policy.get</code></p>
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
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
</ul>
<p><code>workloadcertificate. locations.*</code></p>
<ul>
<li><code>workloadcertificate. locations. get</code></li>
<li><code>workloadcertificate. locations. list</code></li>
</ul>
<p><code>workloadcertificate. operations. get</code></p>
<p><code>workloadcertificate. workloadCertificateFeature. get</code></p>
<p><code>workloadcertificate. workloadRegistrations. create</code></p>
<p><code>workloadcertificate. workloadRegistrations. get</code></p>
<p><code>workloadcertificate. workloadRegistrations. list</code></p></td>
</tr>
<tr class="even">
<td>Mesh Config Service Agent
<p>( <code>roles/ meshconfig.serviceAgent</code> )</p>
<p>Apply mesh configuration</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.backendServices.create</code></p>
<p><code>compute.backendServices.delete</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. setSecurityPolicy</code></p>
<p><code>compute.backendServices.update</code></p>
<p><code>compute.backendServices.use</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute. globalForwardingRules. create</code></p>
<p><code>compute. globalForwardingRules. delete</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalForwardingRules. setLabels</code></p>
<p><code>compute. globalForwardingRules. setTarget</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute.healthChecks.use</code></p>
<p><code>compute. healthChecks. useReadOnly</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute. networkEndpointGroups. use</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute. regionTargetTcpProxies. create</code></p>
<p><code>compute. regionTargetTcpProxies. delete</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. use</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. targetHttpProxies. create</code></p>
<p><code>compute. targetHttpProxies. delete</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpProxies. setUrlMap</code></p>
<p><code>compute.targetHttpProxies.use</code></p>
<p><code>compute. targetHttpsProxies. create</code></p>
<p><code>compute. targetHttpsProxies. delete</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute. targetHttpsProxies. setSslCertificates</code></p>
<p><code>compute. targetHttpsProxies. setSslPolicy</code></p>
<p><code>compute. targetHttpsProxies. setUrlMap</code></p>
<p><code>compute.targetHttpsProxies.use</code></p>
<p><code>compute. targetSslProxies. create</code></p>
<p><code>compute. targetSslProxies. delete</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute. targetSslProxies. setBackendService</code></p>
<p><code>compute. targetSslProxies. setProxyHeader</code></p>
<p><code>compute. targetSslProxies. setSslCertificates</code></p>
<p><code>compute.targetSslProxies.use</code></p>
<p><code>compute. targetTcpProxies. create</code></p>
<p><code>compute. targetTcpProxies. delete</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. update</code></p>
<p><code>compute.targetTcpProxies.use</code></p>
<p><code>compute.urlMaps.create</code></p>
<p><code>compute.urlMaps.delete</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute. urlMaps. invalidateCache</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute.urlMaps.update</code></p>
<p><code>compute.urlMaps.use</code></p>
<p><code>compute.urlMaps.validate</code></p>
<p><code>networksecurity. clientTlsPolicies. create</code></p>
<p><code>networksecurity. clientTlsPolicies. delete</code></p>
<p><code>networksecurity. clientTlsPolicies. get</code></p>
<p><code>networksecurity. clientTlsPolicies. list</code></p>
<p><code>networksecurity. clientTlsPolicies. update</code></p>
<p><code>networksecurity. serverTlsPolicies. create</code></p>
<p><code>networksecurity. serverTlsPolicies. delete</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. serverTlsPolicies. update</code></p>
<p><code>networkservices. httpFilters. create</code></p>
<p><code>networkservices. httpFilters. delete</code></p>
<p><code>networkservices. httpFilters. get</code></p>
<p><code>networkservices. httpFilters. list</code></p>
<p><code>networkservices. httpFilters. update</code></p>
<p><code>networkservices. httpfilters. create</code></p>
<p><code>networkservices. httpfilters. delete</code></p>
<p><code>networkservices. httpfilters. get</code></p>
<p><code>networkservices. httpfilters. list</code></p>
<p><code>networkservices. httpfilters. update</code></p></td>
</tr>
<tr class="odd">
<td>Mesh Data Plane Service Agent
<p>( <code>roles/ meshdataplane.serviceAgent</code> )</p>
<p>Run user-space Istio components</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudtrace.traces.patch</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>telemetry.traces.write</code></p></td>
</tr>
</tbody>
</table>

## Cloud Service Mesh permissions

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
<td><code>meshconfig.projects.init</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshconfig.admin">Mesh Config Admin</a> ( <code>roles/ meshconfig.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>trafficdirector. networks. getConfigs</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code>roles/ trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code>roles/ trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.client">Traffic Director Client</a> ( <code>roles/ trafficdirector.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>trafficdirector. networks. reportMetrics</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code>roles/ trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.client">Traffic Director Client</a> ( <code>roles/ trafficdirector.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
