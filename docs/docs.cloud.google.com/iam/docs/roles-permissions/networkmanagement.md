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
<td>Network Management Admin
<p>( <code>roles/ networkmanagement.admin</code> )</p>
<p>Full access to Network Management resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>networkmanagement.*</code></p>
<ul>
<li><code>networkmanagement. connectivitytests. create</code></li>
<li><code>networkmanagement. connectivitytests. createTagBinding</code></li>
<li><code>networkmanagement. connectivitytests. delete</code></li>
<li><code>networkmanagement. connectivitytests. deleteTagBinding</code></li>
<li><code>networkmanagement. connectivitytests. get</code></li>
<li><code>networkmanagement. connectivitytests. getIamPolicy</code></li>
<li><code>networkmanagement. connectivitytests. list</code></li>
<li><code>networkmanagement. connectivitytests. listEffectiveTags</code></li>
<li><code>networkmanagement. connectivitytests. listTagBindings</code></li>
<li><code>networkmanagement. connectivitytests. rerun</code></li>
<li><code>networkmanagement. connectivitytests. setIamPolicy</code></li>
<li><code>networkmanagement. connectivitytests. update</code></li>
<li><code>networkmanagement. locations. get</code></li>
<li><code>networkmanagement. locations. list</code></li>
<li><code>networkmanagement. monitoringpoints. downloadConfig</code></li>
<li><code>networkmanagement. monitoringpoints. get</code></li>
<li><code>networkmanagement. monitoringpoints. list</code></li>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
<li><code>networkmanagement. operations. cancel</code></li>
<li><code>networkmanagement. operations. delete</code></li>
<li><code>networkmanagement. operations. get</code></li>
<li><code>networkmanagement. operations. list</code></li>
<li><code>networkmanagement. providers. create</code></li>
<li><code>networkmanagement. providers. delete</code></li>
<li><code>networkmanagement. providers. generateProviderAccessToken</code></li>
<li><code>networkmanagement. providers. get</code></li>
<li><code>networkmanagement. providers. list</code></li>
<li><code>networkmanagement. topologygraphs. read</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. create</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. delete</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. get</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. list</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. update</code></li>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Networkmanagement Editor
<p>( <code>roles/ networkmanagement.editor</code> )</p>
<p>Editor role for networkmanagement</p></td>
<td><p><code>networkmanagement. connectivitytests. create</code></p>
<p><code>networkmanagement. connectivitytests. delete</code></p>
<p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. getIamPolicy</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networkmanagement. connectivitytests. rerun</code></p>
<p><code>networkmanagement. connectivitytests. update</code></p>
<p><code>networkmanagement.locations.*</code></p>
<ul>
<li><code>networkmanagement. locations. get</code></li>
<li><code>networkmanagement. locations. list</code></li>
</ul>
<p><code>networkmanagement. monitoringpoints. get</code></p>
<p><code>networkmanagement. monitoringpoints. list</code></p>
<p><code>networkmanagement. networkpaths.*</code></p>
<ul>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
</ul>
<p><code>networkmanagement.operations.*</code></p>
<ul>
<li><code>networkmanagement. operations. cancel</code></li>
<li><code>networkmanagement. operations. delete</code></li>
<li><code>networkmanagement. operations. get</code></li>
<li><code>networkmanagement. operations. list</code></li>
</ul>
<p><code>networkmanagement. providers. generateProviderAccessToken</code></p>
<p><code>networkmanagement. providers. get</code></p>
<p><code>networkmanagement. providers. list</code></p>
<p><code>networkmanagement. topologygraphs. read</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs.*</code></p>
<ul>
<li><code>networkmanagement. vpcflowlogsconfigs. create</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. delete</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. get</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. list</code></li>
<li><code>networkmanagement. vpcflowlogsconfigs. update</code></li>
</ul>
<p><code>networkmanagement.webpaths.*</code></p>
<ul>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Network Management Viewer
<p>( <code>roles/ networkmanagement.viewer</code> )</p>
<p>Read-only access to Network Management resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>networkmanagement. connectivitytests. get</code></p>
<p><code>networkmanagement. connectivitytests. getIamPolicy</code></p>
<p><code>networkmanagement. connectivitytests. list</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networkmanagement.locations.*</code></p>
<ul>
<li><code>networkmanagement. locations. get</code></li>
<li><code>networkmanagement. locations. list</code></li>
</ul>
<p><code>networkmanagement. monitoringpoints. get</code></p>
<p><code>networkmanagement. monitoringpoints. list</code></p>
<p><code>networkmanagement. networkpaths.*</code></p>
<ul>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
</ul>
<p><code>networkmanagement. operations. get</code></p>
<p><code>networkmanagement. operations. list</code></p>
<p><code>networkmanagement. providers. generateProviderAccessToken</code></p>
<p><code>networkmanagement. providers. get</code></p>
<p><code>networkmanagement. providers. list</code></p>
<p><code>networkmanagement. topologygraphs. read</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs. get</code></p>
<p><code>networkmanagement. vpcflowlogsconfigs. list</code></p>
<p><code>networkmanagement.webpaths.*</code></p>
<ul>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Network Insights Admin
<p>( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p>Full access to Cloud Network Insights resources.</p></td>
<td><p><code>networkmanagement.locations.*</code></p>
<ul>
<li><code>networkmanagement. locations. get</code></li>
<li><code>networkmanagement. locations. list</code></li>
</ul>
<p><code>networkmanagement. monitoringpoints.*</code></p>
<ul>
<li><code>networkmanagement. monitoringpoints. downloadConfig</code></li>
<li><code>networkmanagement. monitoringpoints. get</code></li>
<li><code>networkmanagement. monitoringpoints. list</code></li>
</ul>
<p><code>networkmanagement. networkpaths.*</code></p>
<ul>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
</ul>
<p><code>networkmanagement. operations. get</code></p>
<p><code>networkmanagement. operations. list</code></p>
<p><code>networkmanagement.providers.*</code></p>
<ul>
<li><code>networkmanagement. providers. create</code></li>
<li><code>networkmanagement. providers. delete</code></li>
<li><code>networkmanagement. providers. generateProviderAccessToken</code></li>
<li><code>networkmanagement. providers. get</code></li>
<li><code>networkmanagement. providers. list</code></li>
</ul>
<p><code>networkmanagement.webpaths.*</code></p>
<ul>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud Network Insights Editor
<p>( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p>Editor access to Cloud Network Insights resources.</p></td>
<td><p><code>networkmanagement.locations.*</code></p>
<ul>
<li><code>networkmanagement. locations. get</code></li>
<li><code>networkmanagement. locations. list</code></li>
</ul>
<p><code>networkmanagement. monitoringpoints.*</code></p>
<ul>
<li><code>networkmanagement. monitoringpoints. downloadConfig</code></li>
<li><code>networkmanagement. monitoringpoints. get</code></li>
<li><code>networkmanagement. monitoringpoints. list</code></li>
</ul>
<p><code>networkmanagement. networkpaths.*</code></p>
<ul>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
</ul>
<p><code>networkmanagement. operations. get</code></p>
<p><code>networkmanagement. operations. list</code></p>
<p><code>networkmanagement.providers.*</code></p>
<ul>
<li><code>networkmanagement. providers. create</code></li>
<li><code>networkmanagement. providers. delete</code></li>
<li><code>networkmanagement. providers. generateProviderAccessToken</code></li>
<li><code>networkmanagement. providers. get</code></li>
<li><code>networkmanagement. providers. list</code></li>
</ul>
<p><code>networkmanagement.webpaths.*</code></p>
<ul>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Network Insights Viewer
<p>( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p>Read-only access to Cloud Network Insights resources.</p></td>
<td><p><code>networkmanagement. monitoringpoints. get</code></p>
<p><code>networkmanagement. monitoringpoints. list</code></p>
<p><code>networkmanagement. networkpaths.*</code></p>
<ul>
<li><code>networkmanagement. networkpaths. get</code></li>
<li><code>networkmanagement. networkpaths. list</code></li>
</ul>
<p><code>networkmanagement. providers. generateProviderAccessToken</code></p>
<p><code>networkmanagement. providers. get</code></p>
<p><code>networkmanagement. providers. list</code></p>
<p><code>networkmanagement.webpaths.*</code></p>
<ul>
<li><code>networkmanagement.webpaths.get</code></li>
<li><code>networkmanagement. webpaths. list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
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
<td>GCP Network Management Service Agent
<p>( <code>roles/ networkmanagement.serviceAgent</code> )</p>
<p>Grants the GCP Network Management API the authority to complete analysis based on network configurations from Compute Engine and Container Engine.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
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
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute. globalNetworkEndpointGroups. list</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.packetMirrorings.get</code></p>
<p><code>compute.packetMirrorings.list</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
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
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.nodes.get</code></p>
<p><code>container.nodes.list</code></p></td>
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
<td><code>networkmanagement. connectivitytests. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. connectivitytests. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. connectivitytests. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.serviceAgent">External Exposure Service Agent</a> ( <code>roles/ externalexposure.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. connectivitytests. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.serviceAgent">Database Migration Service Agent</a> ( <code>roles/ datamigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.serviceAgent">External Exposure Service Agent</a> ( <code>roles/ externalexposure.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. connectivitytests. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. rerun</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. connectivitytests. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. connectivitytests. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. monitoringpoints. downloadConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. monitoringpoints. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. monitoringpoints. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. networkpaths. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. networkpaths. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. providers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. providers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. providers. generateProviderAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. providers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. providers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. topologygraphs. read</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. vpcflowlogsconfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. vpcflowlogsconfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. vpcflowlogsconfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement. vpcflowlogsconfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. vpcflowlogsconfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>networkmanagement.webpaths.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>networkmanagement. webpaths. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
