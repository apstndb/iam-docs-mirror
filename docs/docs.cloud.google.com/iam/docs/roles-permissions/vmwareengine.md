---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine
title: Google Cloud VMware Engine roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud VMware Engine. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud VMware Engine roles

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
<td>Vmwareengine Admin
<p>( <code>roles/ vmwareengine.admin</code> )</p>
<p>Admin role for vmwareengine</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.*</code></p>
<ul>
<li><code>vmwareengine.clusters.create</code></li>
<li><code>vmwareengine.clusters.delete</code></li>
<li><code>vmwareengine.clusters.get</code></li>
<li><code>vmwareengine. clusters. getIamPolicy</code></li>
<li><code>vmwareengine.clusters.list</code></li>
<li><code>vmwareengine. clusters. mountDatastore</code></li>
<li><code>vmwareengine. clusters. setIamPolicy</code></li>
<li><code>vmwareengine. clusters. unmountDatastore</code></li>
<li><code>vmwareengine.clusters.update</code></li>
<li><code>vmwareengine.datastores.create</code></li>
<li><code>vmwareengine.datastores.delete</code></li>
<li><code>vmwareengine.datastores.get</code></li>
<li><code>vmwareengine. datastores. getIamPolicy</code></li>
<li><code>vmwareengine.datastores.list</code></li>
<li><code>vmwareengine. datastores. setIamPolicy</code></li>
<li><code>vmwareengine.datastores.update</code></li>
<li><code>vmwareengine. dnsBindPermission. get</code></li>
<li><code>vmwareengine. dnsBindPermission. grant</code></li>
<li><code>vmwareengine. dnsBindPermission. revoke</code></li>
<li><code>vmwareengine.dnsForwarding.get</code></li>
<li><code>vmwareengine. dnsForwarding. update</code></li>
<li><code>vmwareengine. externalAccessRules. create</code></li>
<li><code>vmwareengine. externalAccessRules. delete</code></li>
<li><code>vmwareengine. externalAccessRules. get</code></li>
<li><code>vmwareengine. externalAccessRules. list</code></li>
<li><code>vmwareengine. externalAccessRules. update</code></li>
<li><code>vmwareengine. externalAddresses. create</code></li>
<li><code>vmwareengine. externalAddresses. delete</code></li>
<li><code>vmwareengine. externalAddresses. get</code></li>
<li><code>vmwareengine. externalAddresses. list</code></li>
<li><code>vmwareengine. externalAddresses. update</code></li>
<li><code>vmwareengine. hcxActivationKeys. create</code></li>
<li><code>vmwareengine. hcxActivationKeys. get</code></li>
<li><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></li>
<li><code>vmwareengine. hcxActivationKeys. list</code></li>
<li><code>vmwareengine. hcxActivationKeys. setIamPolicy</code></li>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
<li><code>vmwareengine. loggingServers. create</code></li>
<li><code>vmwareengine. loggingServers. delete</code></li>
<li><code>vmwareengine. loggingServers. get</code></li>
<li><code>vmwareengine. loggingServers. list</code></li>
<li><code>vmwareengine. loggingServers. update</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. create</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. delete</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. get</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. list</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. repair</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. update</code></li>
<li><code>vmwareengine. networkPeerings. create</code></li>
<li><code>vmwareengine. networkPeerings. createTagBinding</code></li>
<li><code>vmwareengine. networkPeerings. delete</code></li>
<li><code>vmwareengine. networkPeerings. deleteTagBinding</code></li>
<li><code>vmwareengine. networkPeerings. get</code></li>
<li><code>vmwareengine. networkPeerings. list</code></li>
<li><code>vmwareengine. networkPeerings. listEffectiveTags</code></li>
<li><code>vmwareengine. networkPeerings. listPeeringRoutes</code></li>
<li><code>vmwareengine. networkPeerings. listTagBindings</code></li>
<li><code>vmwareengine. networkPeerings. update</code></li>
<li><code>vmwareengine. networkPolicies. create</code></li>
<li><code>vmwareengine. networkPolicies. createTagBinding</code></li>
<li><code>vmwareengine. networkPolicies. delete</code></li>
<li><code>vmwareengine. networkPolicies. deleteTagBinding</code></li>
<li><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></li>
<li><code>vmwareengine. networkPolicies. get</code></li>
<li><code>vmwareengine. networkPolicies. list</code></li>
<li><code>vmwareengine. networkPolicies. listEffectiveTags</code></li>
<li><code>vmwareengine. networkPolicies. listTagBindings</code></li>
<li><code>vmwareengine. networkPolicies. update</code></li>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
<li><code>vmwareengine.operations.delete</code></li>
<li><code>vmwareengine.operations.get</code></li>
<li><code>vmwareengine.operations.list</code></li>
<li><code>vmwareengine. privateClouds. create</code></li>
<li><code>vmwareengine. privateClouds. createTagBinding</code></li>
<li><code>vmwareengine. privateClouds. delete</code></li>
<li><code>vmwareengine. privateClouds. deleteTagBinding</code></li>
<li><code>vmwareengine.privateClouds.get</code></li>
<li><code>vmwareengine. privateClouds. getIamPolicy</code></li>
<li><code>vmwareengine. privateClouds. list</code></li>
<li><code>vmwareengine. privateClouds. listEffectiveTags</code></li>
<li><code>vmwareengine. privateClouds. listTagBindings</code></li>
<li><code>vmwareengine. privateClouds. migrateManagementVms</code></li>
<li><code>vmwareengine. privateClouds. privateCloudDeletionNow</code></li>
<li><code>vmwareengine. privateClouds. resetNsxCredentials</code></li>
<li><code>vmwareengine. privateClouds. resetVcenterCredentials</code></li>
<li><code>vmwareengine. privateClouds. setIamPolicy</code></li>
<li><code>vmwareengine. privateClouds. showNsxCredentials</code></li>
<li><code>vmwareengine. privateClouds. showVcenterCredentials</code></li>
<li><code>vmwareengine. privateClouds. undelete</code></li>
<li><code>vmwareengine. privateClouds. update</code></li>
<li><code>vmwareengine. privateConnections. create</code></li>
<li><code>vmwareengine. privateConnections. createTagBinding</code></li>
<li><code>vmwareengine. privateConnections. delete</code></li>
<li><code>vmwareengine. privateConnections. deleteTagBinding</code></li>
<li><code>vmwareengine. privateConnections. get</code></li>
<li><code>vmwareengine. privateConnections. list</code></li>
<li><code>vmwareengine. privateConnections. listEffectiveTags</code></li>
<li><code>vmwareengine. privateConnections. listPeeringRoutes</code></li>
<li><code>vmwareengine. privateConnections. listTagBindings</code></li>
<li><code>vmwareengine. privateConnections. update</code></li>
<li><code>vmwareengine.projectState.get</code></li>
<li><code>vmwareengine.services.use</code></li>
<li><code>vmwareengine.services.view</code></li>
<li><code>vmwareengine.subnets.get</code></li>
<li><code>vmwareengine.subnets.list</code></li>
<li><code>vmwareengine.subnets.update</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. create</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. delete</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. get</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. list</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Vmwareengine Editor
<p>( <code>roles/ vmwareengine.editor</code> )</p>
<p>Editor role for vmwareengine</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.clusters.create</code></p>
<p><code>vmwareengine.clusters.delete</code></p>
<p><code>vmwareengine.clusters.get</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine. clusters. mountDatastore</code></p>
<p><code>vmwareengine. clusters. unmountDatastore</code></p>
<p><code>vmwareengine.clusters.update</code></p>
<p><code>vmwareengine.datastores.create</code></p>
<p><code>vmwareengine.datastores.delete</code></p>
<p><code>vmwareengine.datastores.get</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine.datastores.update</code></p>
<p><code>vmwareengine. dnsBindPermission.*</code></p>
<ul>
<li><code>vmwareengine. dnsBindPermission. get</code></li>
<li><code>vmwareengine. dnsBindPermission. grant</code></li>
<li><code>vmwareengine. dnsBindPermission. revoke</code></li>
</ul>
<p><code>vmwareengine.dnsForwarding.*</code></p>
<ul>
<li><code>vmwareengine.dnsForwarding.get</code></li>
<li><code>vmwareengine. dnsForwarding. update</code></li>
</ul>
<p><code>vmwareengine. externalAccessRules.*</code></p>
<ul>
<li><code>vmwareengine. externalAccessRules. create</code></li>
<li><code>vmwareengine. externalAccessRules. delete</code></li>
<li><code>vmwareengine. externalAccessRules. get</code></li>
<li><code>vmwareengine. externalAccessRules. list</code></li>
<li><code>vmwareengine. externalAccessRules. update</code></li>
</ul>
<p><code>vmwareengine. externalAddresses.*</code></p>
<ul>
<li><code>vmwareengine. externalAddresses. create</code></li>
<li><code>vmwareengine. externalAddresses. delete</code></li>
<li><code>vmwareengine. externalAddresses. get</code></li>
<li><code>vmwareengine. externalAddresses. list</code></li>
<li><code>vmwareengine. externalAddresses. update</code></li>
</ul>
<p><code>vmwareengine. hcxActivationKeys. create</code></p>
<p><code>vmwareengine. hcxActivationKeys. get</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine.locations.*</code></p>
<ul>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
</ul>
<p><code>vmwareengine.loggingServers.*</code></p>
<ul>
<li><code>vmwareengine. loggingServers. create</code></li>
<li><code>vmwareengine. loggingServers. delete</code></li>
<li><code>vmwareengine. loggingServers. get</code></li>
<li><code>vmwareengine. loggingServers. list</code></li>
<li><code>vmwareengine. loggingServers. update</code></li>
</ul>
<p><code>vmwareengine. managementDnsZoneBindings.*</code></p>
<ul>
<li><code>vmwareengine. managementDnsZoneBindings. create</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. delete</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. get</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. list</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. repair</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. update</code></li>
</ul>
<p><code>vmwareengine. networkPeerings. create</code></p>
<p><code>vmwareengine. networkPeerings. delete</code></p>
<p><code>vmwareengine. networkPeerings. get</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listPeeringRoutes</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPeerings. update</code></p>
<p><code>vmwareengine. networkPolicies. create</code></p>
<p><code>vmwareengine. networkPolicies. delete</code></p>
<p><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></p>
<p><code>vmwareengine. networkPolicies. get</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. update</code></p>
<p><code>vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul>
<p><code>vmwareengine.operations.*</code></p>
<ul>
<li><code>vmwareengine.operations.delete</code></li>
<li><code>vmwareengine.operations.get</code></li>
<li><code>vmwareengine.operations.list</code></li>
</ul>
<p><code>vmwareengine. privateClouds. create</code></p>
<p><code>vmwareengine. privateClouds. delete</code></p>
<p><code>vmwareengine.privateClouds.get</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. migrateManagementVms</code></p>
<p><code>vmwareengine. privateClouds. privateCloudDeletionNow</code></p>
<p><code>vmwareengine. privateClouds. resetNsxCredentials</code></p>
<p><code>vmwareengine. privateClouds. resetVcenterCredentials</code></p>
<p><code>vmwareengine. privateClouds. showNsxCredentials</code></p>
<p><code>vmwareengine. privateClouds. showVcenterCredentials</code></p>
<p><code>vmwareengine. privateClouds. undelete</code></p>
<p><code>vmwareengine. privateClouds. update</code></p>
<p><code>vmwareengine. privateConnections. create</code></p>
<p><code>vmwareengine. privateConnections. delete</code></p>
<p><code>vmwareengine. privateConnections. get</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listPeeringRoutes</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. update</code></p>
<p><code>vmwareengine.projectState.get</code></p>
<p><code>vmwareengine.services.*</code></p>
<ul>
<li><code>vmwareengine.services.use</code></li>
<li><code>vmwareengine.services.view</code></li>
</ul>
<p><code>vmwareengine.subnets.*</code></p>
<ul>
<li><code>vmwareengine.subnets.get</code></li>
<li><code>vmwareengine.subnets.list</code></li>
<li><code>vmwareengine.subnets.update</code></li>
</ul>
<p><code>vmwareengine. vmwareEngineNetworks. create</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. delete</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. get</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. update</code></p></td>
</tr>
<tr class="odd">
<td>Vmwareengine Viewer
<p>( <code>roles/ vmwareengine.viewer</code> )</p>
<p>Viewer role for vmwareengine</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.clusters.get</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine.datastores.get</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine. dnsBindPermission. get</code></p>
<p><code>vmwareengine.dnsForwarding.get</code></p>
<p><code>vmwareengine. externalAccessRules. get</code></p>
<p><code>vmwareengine. externalAccessRules. list</code></p>
<p><code>vmwareengine. externalAddresses. get</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. get</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine.locations.*</code></p>
<ul>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
</ul>
<p><code>vmwareengine. loggingServers. get</code></p>
<p><code>vmwareengine. loggingServers. list</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. get</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. list</code></p>
<p><code>vmwareengine. networkPeerings. get</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listPeeringRoutes</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></p>
<p><code>vmwareengine. networkPolicies. get</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul>
<p><code>vmwareengine.operations.get</code></p>
<p><code>vmwareengine.operations.list</code></p>
<p><code>vmwareengine.privateClouds.get</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. get</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listPeeringRoutes</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine.projectState.get</code></p>
<p><code>vmwareengine.services.view</code></p>
<p><code>vmwareengine.subnets.get</code></p>
<p><code>vmwareengine.subnets.list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. get</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>VMware Engine Service Admin
<p>( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p>Admin has full access to VMware Engine Service</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.clusters.create</code></p>
<p><code>vmwareengine.clusters.get</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine. clusters. mountDatastore</code></p>
<p><code>vmwareengine. clusters. setIamPolicy</code></p>
<p><code>vmwareengine. clusters. unmountDatastore</code></p>
<p><code>vmwareengine.clusters.update</code></p>
<p><code>vmwareengine.datastores.*</code></p>
<ul>
<li><code>vmwareengine.datastores.create</code></li>
<li><code>vmwareengine.datastores.delete</code></li>
<li><code>vmwareengine.datastores.get</code></li>
<li><code>vmwareengine. datastores. getIamPolicy</code></li>
<li><code>vmwareengine.datastores.list</code></li>
<li><code>vmwareengine. datastores. setIamPolicy</code></li>
<li><code>vmwareengine.datastores.update</code></li>
</ul>
<p><code>vmwareengine. dnsBindPermission.*</code></p>
<ul>
<li><code>vmwareengine. dnsBindPermission. get</code></li>
<li><code>vmwareengine. dnsBindPermission. grant</code></li>
<li><code>vmwareengine. dnsBindPermission. revoke</code></li>
</ul>
<p><code>vmwareengine.dnsForwarding.*</code></p>
<ul>
<li><code>vmwareengine.dnsForwarding.get</code></li>
<li><code>vmwareengine. dnsForwarding. update</code></li>
</ul>
<p><code>vmwareengine. externalAccessRules.*</code></p>
<ul>
<li><code>vmwareengine. externalAccessRules. create</code></li>
<li><code>vmwareengine. externalAccessRules. delete</code></li>
<li><code>vmwareengine. externalAccessRules. get</code></li>
<li><code>vmwareengine. externalAccessRules. list</code></li>
<li><code>vmwareengine. externalAccessRules. update</code></li>
</ul>
<p><code>vmwareengine. externalAddresses.*</code></p>
<ul>
<li><code>vmwareengine. externalAddresses. create</code></li>
<li><code>vmwareengine. externalAddresses. delete</code></li>
<li><code>vmwareengine. externalAddresses. get</code></li>
<li><code>vmwareengine. externalAddresses. list</code></li>
<li><code>vmwareengine. externalAddresses. update</code></li>
</ul>
<p><code>vmwareengine. hcxActivationKeys.*</code></p>
<ul>
<li><code>vmwareengine. hcxActivationKeys. create</code></li>
<li><code>vmwareengine. hcxActivationKeys. get</code></li>
<li><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></li>
<li><code>vmwareengine. hcxActivationKeys. list</code></li>
<li><code>vmwareengine. hcxActivationKeys. setIamPolicy</code></li>
</ul>
<p><code>vmwareengine.locations.*</code></p>
<ul>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
</ul>
<p><code>vmwareengine.loggingServers.*</code></p>
<ul>
<li><code>vmwareengine. loggingServers. create</code></li>
<li><code>vmwareengine. loggingServers. delete</code></li>
<li><code>vmwareengine. loggingServers. get</code></li>
<li><code>vmwareengine. loggingServers. list</code></li>
<li><code>vmwareengine. loggingServers. update</code></li>
</ul>
<p><code>vmwareengine. managementDnsZoneBindings.*</code></p>
<ul>
<li><code>vmwareengine. managementDnsZoneBindings. create</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. delete</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. get</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. list</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. repair</code></li>
<li><code>vmwareengine. managementDnsZoneBindings. update</code></li>
</ul>
<p><code>vmwareengine.networkPeerings.*</code></p>
<ul>
<li><code>vmwareengine. networkPeerings. create</code></li>
<li><code>vmwareengine. networkPeerings. createTagBinding</code></li>
<li><code>vmwareengine. networkPeerings. delete</code></li>
<li><code>vmwareengine. networkPeerings. deleteTagBinding</code></li>
<li><code>vmwareengine. networkPeerings. get</code></li>
<li><code>vmwareengine. networkPeerings. list</code></li>
<li><code>vmwareengine. networkPeerings. listEffectiveTags</code></li>
<li><code>vmwareengine. networkPeerings. listPeeringRoutes</code></li>
<li><code>vmwareengine. networkPeerings. listTagBindings</code></li>
<li><code>vmwareengine. networkPeerings. update</code></li>
</ul>
<p><code>vmwareengine.networkPolicies.*</code></p>
<ul>
<li><code>vmwareengine. networkPolicies. create</code></li>
<li><code>vmwareengine. networkPolicies. createTagBinding</code></li>
<li><code>vmwareengine. networkPolicies. delete</code></li>
<li><code>vmwareengine. networkPolicies. deleteTagBinding</code></li>
<li><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></li>
<li><code>vmwareengine. networkPolicies. get</code></li>
<li><code>vmwareengine. networkPolicies. list</code></li>
<li><code>vmwareengine. networkPolicies. listEffectiveTags</code></li>
<li><code>vmwareengine. networkPolicies. listTagBindings</code></li>
<li><code>vmwareengine. networkPolicies. update</code></li>
</ul>
<p><code>vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul>
<p><code>vmwareengine.operations.*</code></p>
<ul>
<li><code>vmwareengine.operations.delete</code></li>
<li><code>vmwareengine.operations.get</code></li>
<li><code>vmwareengine.operations.list</code></li>
</ul>
<p><code>vmwareengine. privateClouds. create</code></p>
<p><code>vmwareengine. privateClouds. createTagBinding</code></p>
<p><code>vmwareengine. privateClouds. delete</code></p>
<p><code>vmwareengine. privateClouds. deleteTagBinding</code></p>
<p><code>vmwareengine.privateClouds.get</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. migrateManagementVms</code></p>
<p><code>vmwareengine. privateClouds. resetNsxCredentials</code></p>
<p><code>vmwareengine. privateClouds. resetVcenterCredentials</code></p>
<p><code>vmwareengine. privateClouds. setIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. showNsxCredentials</code></p>
<p><code>vmwareengine. privateClouds. showVcenterCredentials</code></p>
<p><code>vmwareengine. privateClouds. undelete</code></p>
<p><code>vmwareengine. privateClouds. update</code></p>
<p><code>vmwareengine. privateConnections.*</code></p>
<ul>
<li><code>vmwareengine. privateConnections. create</code></li>
<li><code>vmwareengine. privateConnections. createTagBinding</code></li>
<li><code>vmwareengine. privateConnections. delete</code></li>
<li><code>vmwareengine. privateConnections. deleteTagBinding</code></li>
<li><code>vmwareengine. privateConnections. get</code></li>
<li><code>vmwareengine. privateConnections. list</code></li>
<li><code>vmwareengine. privateConnections. listEffectiveTags</code></li>
<li><code>vmwareengine. privateConnections. listPeeringRoutes</code></li>
<li><code>vmwareengine. privateConnections. listTagBindings</code></li>
<li><code>vmwareengine. privateConnections. update</code></li>
</ul>
<p><code>vmwareengine.projectState.get</code></p>
<p><code>vmwareengine.services.*</code></p>
<ul>
<li><code>vmwareengine.services.use</code></li>
<li><code>vmwareengine.services.view</code></li>
</ul>
<p><code>vmwareengine.subnets.*</code></p>
<ul>
<li><code>vmwareengine.subnets.get</code></li>
<li><code>vmwareengine.subnets.list</code></li>
<li><code>vmwareengine.subnets.update</code></li>
</ul>
<p><code>vmwareengine. vmwareEngineNetworks.*</code></p>
<ul>
<li><code>vmwareengine. vmwareEngineNetworks. create</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. delete</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. get</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. list</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></li>
<li><code>vmwareengine. vmwareEngineNetworks. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>VMware Engine Service Privileged User
<p>( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p>Privileged User has access to VMWare Engine Service Privileged API, including accelerating private cloud deletion.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.clusters.delete</code></p>
<p><code>vmwareengine.clusters.get</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine.datastores.get</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine. dnsBindPermission. get</code></p>
<p><code>vmwareengine.dnsForwarding.get</code></p>
<p><code>vmwareengine. externalAccessRules. get</code></p>
<p><code>vmwareengine. externalAccessRules. list</code></p>
<p><code>vmwareengine. externalAddresses. get</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. get</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine.locations.*</code></p>
<ul>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
</ul>
<p><code>vmwareengine. loggingServers. get</code></p>
<p><code>vmwareengine. loggingServers. list</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. get</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. list</code></p>
<p><code>vmwareengine. networkPeerings. get</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listPeeringRoutes</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></p>
<p><code>vmwareengine. networkPolicies. get</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul>
<p><code>vmwareengine.operations.get</code></p>
<p><code>vmwareengine.operations.list</code></p>
<p><code>vmwareengine.privateClouds.get</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. privateCloudDeletionNow</code></p>
<p><code>vmwareengine. privateConnections. get</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listPeeringRoutes</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine.projectState.get</code></p>
<p><code>vmwareengine.services.*</code></p>
<ul>
<li><code>vmwareengine.services.use</code></li>
<li><code>vmwareengine.services.view</code></li>
</ul>
<p><code>vmwareengine.subnets.get</code></p>
<p><code>vmwareengine.subnets.list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. get</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>VMware Engine Service Viewer
<p>( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p>Viewer has read-only access to VMware Engine Service</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine.clusters.get</code></p>
<p><code>vmwareengine. clusters. getIamPolicy</code></p>
<p><code>vmwareengine.clusters.list</code></p>
<p><code>vmwareengine.datastores.get</code></p>
<p><code>vmwareengine. datastores. getIamPolicy</code></p>
<p><code>vmwareengine.datastores.list</code></p>
<p><code>vmwareengine. dnsBindPermission. get</code></p>
<p><code>vmwareengine.dnsForwarding.get</code></p>
<p><code>vmwareengine. externalAccessRules. get</code></p>
<p><code>vmwareengine. externalAccessRules. list</code></p>
<p><code>vmwareengine. externalAddresses. get</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine. hcxActivationKeys. get</code></p>
<p><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></p>
<p><code>vmwareengine. hcxActivationKeys. list</code></p>
<p><code>vmwareengine.locations.*</code></p>
<ul>
<li><code>vmwareengine.locations.get</code></li>
<li><code>vmwareengine.locations.list</code></li>
</ul>
<p><code>vmwareengine. loggingServers. get</code></p>
<p><code>vmwareengine. loggingServers. list</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. get</code></p>
<p><code>vmwareengine. managementDnsZoneBindings. list</code></p>
<p><code>vmwareengine. networkPeerings. get</code></p>
<p><code>vmwareengine. networkPeerings. list</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listPeeringRoutes</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></p>
<p><code>vmwareengine. networkPolicies. get</code></p>
<p><code>vmwareengine. networkPolicies. list</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code>vmwareengine.nodeTypes.get</code></li>
<li><code>vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul>
<p><code>vmwareengine.operations.get</code></p>
<p><code>vmwareengine.operations.list</code></p>
<p><code>vmwareengine.privateClouds.get</code></p>
<p><code>vmwareengine. privateClouds. getIamPolicy</code></p>
<p><code>vmwareengine. privateClouds. list</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. get</code></p>
<p><code>vmwareengine. privateConnections. list</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listPeeringRoutes</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine.projectState.get</code></p>
<p><code>vmwareengine.services.view</code></p>
<p><code>vmwareengine.subnets.get</code></p>
<p><code>vmwareengine.subnets.list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. get</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. list</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p></td>
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
<td>VMware Engine Service Agent
<p>( <code>roles/ vmwareengine.serviceAgent</code> )</p>
<p>Gives permission to manage network configuration, such as establishing network peering, necessary for GCVE</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.networks.addPeering</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listPeeringRoutes</code></p>
<p><code>compute.networks.removePeering</code></p>
<p><code>compute.networks.update</code></p>
<p><code>compute.networks.updatePeering</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>dns.changes.*</code></p>
<ul>
<li><code>dns.changes.create</code></li>
<li><code>dns.changes.get</code></li>
<li><code>dns.changes.list</code></li>
</ul>
<p><code>dns.dnsKeys.*</code></p>
<ul>
<li><code>dns.dnsKeys.get</code></li>
<li><code>dns.dnsKeys.list</code></li>
</ul>
<p><code>dns.gkeClusters.*</code></p>
<ul>
<li><code>dns. gkeClusters. bindDNSResponsePolicy</code></li>
<li><code>dns. gkeClusters. bindPrivateDNSZone</code></li>
</ul>
<p><code>dns.managedZoneOperations.*</code></p>
<ul>
<li><code>dns.managedZoneOperations.get</code></li>
<li><code>dns.managedZoneOperations.list</code></li>
</ul>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.getIamPolicy</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.managedZones.update</code></p>
<p><code>dns.networks.*</code></p>
<ul>
<li><code>dns. networks. bindDNSResponsePolicy</code></li>
<li><code>dns. networks. bindPrivateDNSPolicy</code></li>
<li><code>dns. networks. bindPrivateDNSZone</code></li>
<li><code>dns. networks. targetWithPeeringZone</code></li>
<li><code>dns.networks.useHealthSignals</code></li>
</ul>
<p><code>dns.policies.create</code></p>
<p><code>dns.policies.delete</code></p>
<p><code>dns.policies.get</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>dns.policies.update</code></p>
<p><code>dns.projects.get</code></p>
<p><code>dns.resourceRecordSets.*</code></p>
<ul>
<li><code>dns.resourceRecordSets.create</code></li>
<li><code>dns.resourceRecordSets.delete</code></li>
<li><code>dns.resourceRecordSets.get</code></li>
<li><code>dns.resourceRecordSets.list</code></li>
<li><code>dns.resourceRecordSets.update</code></li>
</ul>
<p><code>dns.responsePolicies.*</code></p>
<ul>
<li><code>dns.responsePolicies.create</code></li>
<li><code>dns.responsePolicies.delete</code></li>
<li><code>dns.responsePolicies.get</code></li>
<li><code>dns.responsePolicies.list</code></li>
<li><code>dns.responsePolicies.update</code></li>
</ul>
<p><code>dns.responsePolicyRules.*</code></p>
<ul>
<li><code>dns.responsePolicyRules.create</code></li>
<li><code>dns.responsePolicyRules.delete</code></li>
<li><code>dns.responsePolicyRules.get</code></li>
<li><code>dns.responsePolicyRules.list</code></li>
<li><code>dns.responsePolicyRules.update</code></li>
</ul>
<p><code>file.instances.get</code></p>
<p><code>file.instances.list</code></p>
<p><code>netapp.volumes.get</code></p>
<p><code>netapp.volumes.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vmwareengine. externalAddresses. get</code></p>
<p><code>vmwareengine. externalAddresses. list</code></p>
<p><code>vmwareengine.nodes.*</code></p>
<ul>
<li><code>vmwareengine.nodes.get</code></li>
<li><code>vmwareengine.nodes.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Cloud VMware Engine permissions

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
<td><code>vmwareengine.clusters.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.clusters.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.clusters.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. clusters. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.clusters.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. clusters. mountDatastore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. clusters. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. clusters. unmountDatastore</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.clusters.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.datastores.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.datastores.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.datastores.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. datastores. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.datastores.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. datastores. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.datastores.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. dnsBindPermission. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. dnsBindPermission. grant</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. dnsBindPermission. revoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.dnsForwarding.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. dnsForwarding. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. externalAccessRules. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. externalAccessRules. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. externalAccessRules. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. externalAccessRules. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. externalAccessRules. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. externalAddresses. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. externalAddresses. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. externalAddresses. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vmwareengine. externalAddresses. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. externalAddresses. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. hcxActivationKeys. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. hcxActivationKeys. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. hcxActivationKeys. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. hcxActivationKeys. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. hcxActivationKeys. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. loggingServers. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. loggingServers. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. loggingServers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. loggingServers. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. loggingServers. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. managementDnsZoneBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. managementDnsZoneBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. managementDnsZoneBindings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. managementDnsZoneBindings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. managementDnsZoneBindings. repair</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. managementDnsZoneBindings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPeerings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPeerings. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPeerings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPeerings. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPeerings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPeerings. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPeerings. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPeerings. listPeeringRoutes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPeerings. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPeerings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPolicies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPolicies. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPolicies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPolicies. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPolicies. fetchExternalAddresses</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPolicies. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPolicies. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPolicies. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. networkPolicies. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. networkPolicies. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.nodeTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.nodeTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.nodes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.nodes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vmwareengine.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.privateClouds.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. migrateManagementVms</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. privateCloudDeletionNow</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. resetNsxCredentials</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. resetVcenterCredentials</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. showNsxCredentials</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. showVcenterCredentials</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateClouds. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateClouds. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateConnections. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateConnections. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateConnections. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateConnections. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateConnections. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateConnections. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateConnections. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateConnections. listPeeringRoutes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. privateConnections. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. privateConnections. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.projectState.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.services.use</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.services.view</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.subnets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine.subnets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine.subnets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. vmwareEngineNetworks. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. vmwareEngineNetworks. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. vmwareEngineNetworks. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. vmwareEngineNetworks. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vmwareengine. vmwareEngineNetworks. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
</tbody>
</table>
