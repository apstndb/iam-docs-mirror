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
<td><h4 id="meshconfig.admin" class="role-title add-link" data-text="Mesh Config Admin Beta" tabindex="-1">Mesh Config Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  meshconfig.admin</code> )</p>
<p>Full access to all mesh configuration resources</p></td>
<td><p><code dir="ltr" translate="no">meshconfig.projects.init</code></p></td>
</tr>
<tr class="even">
<td><h4 id="meshconfig.viewer" class="role-title add-link" data-text="Mesh Config Viewer Beta" tabindex="-1">Mesh Config Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  meshconfig.viewer</code> )</p>
<p>Read access to mesh configuration</p></td>
<td></td>
</tr>
<tr class="odd">
<td><h4 id="trafficdirector.admin" class="role-title add-link" data-text="Trafficdirector Admin Beta" tabindex="-1">Trafficdirector Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  trafficdirector.admin</code> )</p>
<p>Admin role for trafficdirector</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">trafficdirector.*</code></p>
<ul>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></li>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="trafficdirector.viewer" class="role-title add-link" data-text="Trafficdirector Viewer Beta" tabindex="-1">Trafficdirector Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  trafficdirector.viewer</code> )</p>
<p>Viewer role for trafficdirector</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="trafficdirector.client" class="role-title add-link" data-text="Traffic Director Client Beta" tabindex="-1">Traffic Director Client <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  trafficdirector.client</code> )</p>
<p>Fetch service configurations and report metrics.</p></td>
<td><p><code dir="ltr" translate="no">trafficdirector.*</code></p>
<ul>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></li>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></li>
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
<td><h4 id="anthosservicemesh.serviceAgent" class="role-title add-link" data-text="Anthos Service Mesh Service Agent" tabindex="-1">Anthos Service Mesh Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</p>
<p>Gives the Anthos Service Mesh service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.backendServices.create</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  detachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.use</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  detachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.regions.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusterRoles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.configMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.create</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.delete</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.get</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.getStatus</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.list</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.update</code></p>
<p><code dir="ltr" translate="no">container.deployments.get</code></p>
<p><code dir="ltr" translate="no">container.deployments.list</code></p>
<p><code dir="ltr" translate="no">container.events.get</code></p>
<p><code dir="ltr" translate="no">container.events.list</code></p>
<p><code dir="ltr" translate="no">container.jobs.create</code></p>
<p><code dir="ltr" translate="no">container.jobs.delete</code></p>
<p><code dir="ltr" translate="no">container.jobs.get</code></p>
<p><code dir="ltr" translate="no">container.jobs.list</code></p>
<p><code dir="ltr" translate="no">container.jobs.update</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  create</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  update</code></p>
<p><code dir="ltr" translate="no">container.namespaces.create</code></p>
<p><code dir="ltr" translate="no">container.namespaces.get</code></p>
<p><code dir="ltr" translate="no">container.namespaces.list</code></p>
<p><code dir="ltr" translate="no">container.operations.get</code></p>
<p><code dir="ltr" translate="no">container.pods.get</code></p>
<p><code dir="ltr" translate="no">container.pods.list</code></p>
<p><code dir="ltr" translate="no">container.secrets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></p>
<p><code dir="ltr" translate="no">container.services.get</code></p>
<p><code dir="ltr" translate="no">container.services.list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">meshconfig.projects.init</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  authorizationPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networksecurity.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.operations.get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  gateways.  create</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  delete</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.get</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.list</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  update</code></p>
<p><code dir="ltr" translate="no">networkservices.gateways.use</code></p>
<p><code dir="ltr" translate="no">networkservices.grpcRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.grpcRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  grpcRoutes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  create</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  delete</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  update</code></p>
<p><code dir="ltr" translate="no">networkservices.httpRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.httpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  httpRoutes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.meshes.create</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.delete</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.get</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.list</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.update</code></p>
<p><code dir="ltr" translate="no">networkservices.meshes.use</code></p>
<p><code dir="ltr" translate="no">networkservices.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.operations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  serviceLbPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.tcpRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tcpRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tcpRoutes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.tlsRoutes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.get</code></li>
<li><code dir="ltr" translate="no">networkservices.tlsRoutes.list</code></li>
<li><code dir="ltr" translate="no">networkservices.  tlsRoutes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">trafficdirector.*</code></p>
<ul>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></li>
<li><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  create</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="meshconfig.serviceAgent" class="role-title add-link" data-text="Mesh Config Service Agent" tabindex="-1">Mesh Config Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  meshconfig.serviceAgent</code> )</p>
<p>Apply mesh configuration</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.backendServices.create</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  setSecurityPolicy</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.use</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  setTarget</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  setUrlMap</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setUrlMap</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  setBackendService</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  setProxyHeader</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  setSslCertificates</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  update</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.create</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.delete</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  invalidateCache</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.update</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.use</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.validate</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  clientTlsPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  create</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  delete</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  update</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  create</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  delete</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  get</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  list</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpfilters.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="meshdataplane.serviceAgent" class="role-title add-link" data-text="Mesh Data Plane Service Agent" tabindex="-1">Mesh Data Plane Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  meshdataplane.serviceAgent</code> )</p>
<p>Run user-space Istio components</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudtrace.traces.patch</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">telemetry.traces.write</code></p></td>
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
<td><h4 id="meshconfig.projects.init" class="permission-name add-link" data-text="meshconfig.projects.init" tabindex="-1"><code dir="ltr" translate="no">meshconfig.projects.init</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshconfig.admin">Mesh Config Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshconfig.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="trafficdirector.networks.getConfigs" class="permission-name add-link" data-text="trafficdirector.networks.getConfigs" tabindex="-1"><code dir="ltr" translate="no">trafficdirector.  networks.  getConfigs</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.client">Traffic Director Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="trafficdirector.networks.reportMetrics" class="permission-name add-link" data-text="trafficdirector.networks.reportMetrics" tabindex="-1"><code dir="ltr" translate="no">trafficdirector.  networks.  reportMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.client">Traffic Director Client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  trafficdirector.client</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  meshcontrolplane.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
