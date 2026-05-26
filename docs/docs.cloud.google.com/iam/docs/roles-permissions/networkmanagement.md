---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement
title: Network Management API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Network Management API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Network Management API roles

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
<td><h4 id="networkmanagement.admin" class="role-title add-link" data-text="Network Management Admin" tabindex="-1">Network Management Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p>Full access to Network Management resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">networkmanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  rerun</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  update</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  downloadConfig</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  generateProviderAccessToken</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  topologygraphs.  read</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  update</code></li>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.editor" class="role-title add-link" data-text="Networkmanagement Editor" tabindex="-1">Networkmanagement Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p>Editor role for networkmanagement</p></td>
<td><p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  create</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  delete</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  rerun</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  update</code></p>
<p><code dir="ltr" translate="no">networkmanagement.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  topologygraphs.  read</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.webpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.viewer" class="role-title add-link" data-text="Network Management Viewer" tabindex="-1">Network Management Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p>Read-only access to Network Management resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  topologygraphs.  read</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.webpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.CloudNetworkInsightsAdmin" class="role-title add-link" data-text="Cloud Network Insights Admin Beta" tabindex="-1">Cloud Network Insights Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p>Full access to Cloud Network Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">networkmanagement.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  downloadConfig</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  generateProviderAccessToken</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.webpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.CloudNetworkInsightsEditor" class="role-title add-link" data-text="Cloud Network Insights Editor Beta" tabindex="-1">Cloud Network Insights Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p>Editor access to Cloud Network Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">networkmanagement.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  downloadConfig</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.providers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  create</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  delete</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  generateProviderAccessToken</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.webpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.CloudNetworkInsightsViewer" class="role-title add-link" data-text="Cloud Network Insights Viewer Beta" tabindex="-1">Cloud Network Insights Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p>Read-only access to Cloud Network Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  networkpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  generateProviderAccessToken</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></p>
<p><code dir="ltr" translate="no">networkmanagement.webpaths.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></li>
<li><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
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
<td><h4 id="networkmanagement.serviceAgent" class="role-title add-link" data-text="GCP Network Management Service Agent" tabindex="-1">GCP Network Management Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  networkmanagement.serviceAgent</code> )</p>
<p>Grants the GCP Network Management API the authority to complete analysis based on network configurations from Compute Engine and Container Engine.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
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
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  getEffectiveFirewalls</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.get</code></p>
<p><code dir="ltr" translate="no">compute.packetMirrorings.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
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
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.nodes.get</code></p>
<p><code dir="ltr" translate="no">container.nodes.list</code></p></td>
</tr>
</tbody>
</table>

## Network Management API permissions

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
<td><h4 id="networkmanagement.connectivitytests.create" class="permission-name add-link" data-text="networkmanagement.connectivitytests.create" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.createTagBinding" class="permission-name add-link" data-text="networkmanagement.connectivitytests.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.connectivitytests.delete" class="permission-name add-link" data-text="networkmanagement.connectivitytests.delete" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.deleteTagBinding" class="permission-name add-link" data-text="networkmanagement.connectivitytests.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.connectivitytests.get" class="permission-name add-link" data-text="networkmanagement.connectivitytests.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.serviceAgent">External Exposure Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.getIamPolicy" class="permission-name add-link" data-text="networkmanagement.connectivitytests.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.connectivitytests.list" class="permission-name add-link" data-text="networkmanagement.connectivitytests.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.serviceAgent">External Exposure Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  externalexposure.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.listEffectiveTags" class="permission-name add-link" data-text="networkmanagement.connectivitytests.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.connectivitytests.listTagBindings" class="permission-name add-link" data-text="networkmanagement.connectivitytests.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.rerun" class="permission-name add-link" data-text="networkmanagement.connectivitytests.rerun" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  rerun</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.connectivitytests.setIamPolicy" class="permission-name add-link" data-text="networkmanagement.connectivitytests.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.connectivitytests.update" class="permission-name add-link" data-text="networkmanagement.connectivitytests.update" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.locations.get" class="permission-name add-link" data-text="networkmanagement.locations.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.locations.list" class="permission-name add-link" data-text="networkmanagement.locations.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.monitoringpoints.downloadConfig" class="permission-name add-link" data-text="networkmanagement.monitoringpoints.downloadConfig" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  downloadConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.monitoringpoints.get" class="permission-name add-link" data-text="networkmanagement.monitoringpoints.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.monitoringpoints.list" class="permission-name add-link" data-text="networkmanagement.monitoringpoints.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  monitoringpoints.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.networkpaths.get" class="permission-name add-link" data-text="networkmanagement.networkpaths.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  networkpaths.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.networkpaths.list" class="permission-name add-link" data-text="networkmanagement.networkpaths.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  networkpaths.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.operations.cancel" class="permission-name add-link" data-text="networkmanagement.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.operations.delete" class="permission-name add-link" data-text="networkmanagement.operations.delete" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.operations.get" class="permission-name add-link" data-text="networkmanagement.operations.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.operations.list" class="permission-name add-link" data-text="networkmanagement.operations.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.providers.create" class="permission-name add-link" data-text="networkmanagement.providers.create" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  providers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.providers.delete" class="permission-name add-link" data-text="networkmanagement.providers.delete" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  providers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.providers.generateProviderAccessToken" class="permission-name add-link" data-text="networkmanagement.providers.generateProviderAccessToken" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  providers.  generateProviderAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.providers.get" class="permission-name add-link" data-text="networkmanagement.providers.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  providers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.providers.list" class="permission-name add-link" data-text="networkmanagement.providers.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  providers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.topologygraphs.read" class="permission-name add-link" data-text="networkmanagement.topologygraphs.read" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  topologygraphs.  read</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.vpcflowlogsconfigs.create" class="permission-name add-link" data-text="networkmanagement.vpcflowlogsconfigs.create" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.vpcflowlogsconfigs.delete" class="permission-name add-link" data-text="networkmanagement.vpcflowlogsconfigs.delete" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.vpcflowlogsconfigs.get" class="permission-name add-link" data-text="networkmanagement.vpcflowlogsconfigs.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.vpcflowlogsconfigs.list" class="permission-name add-link" data-text="networkmanagement.vpcflowlogsconfigs.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.vpcflowlogsconfigs.update" class="permission-name add-link" data-text="networkmanagement.vpcflowlogsconfigs.update" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  vpcflowlogsconfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="networkmanagement.webpaths.get" class="permission-name add-link" data-text="networkmanagement.webpaths.get" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.webpaths.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="networkmanagement.webpaths.list" class="permission-name add-link" data-text="networkmanagement.webpaths.list" tabindex="-1"><code dir="ltr" translate="no">networkmanagement.  webpaths.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkmanagement.CloudNetworkInsightsViewer</code> )</p></td>
</tr>
</tbody>
</table>
