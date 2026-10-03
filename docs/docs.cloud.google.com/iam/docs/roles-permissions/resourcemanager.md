---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager
title: Resource Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Resource Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Resource Manager roles

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
<td>Resource Manager Editor
<p>( <code>roles/ resourcemanager.editor</code> )</p>
<p>Access to manage Resource Manager resources</p></td>
<td><p><code>resourcemanager.boundaries.*</code></p>
<ul>
<li><code>resourcemanager. boundaries. associateToCapabilityConfig</code></li>
<li><code>resourcemanager. boundaries. create</code></li>
<li><code>resourcemanager. boundaries. delete</code></li>
<li><code>resourcemanager.boundaries.get</code></li>
<li><code>resourcemanager. boundaries. list</code></li>
<li><code>resourcemanager. boundaries. update</code></li>
</ul>
<p><code>resourcemanager. boundaryConfigs.*</code></p>
<ul>
<li><code>resourcemanager. boundaryConfigs. get</code></li>
<li><code>resourcemanager. boundaryConfigs. update</code></li>
</ul>
<p><code>resourcemanager.capabilities.*</code></p>
<ul>
<li><code>resourcemanager. capabilities. get</code></li>
<li><code>resourcemanager. capabilities. update</code></li>
</ul>
<p><code>resourcemanager. capabilityConfigs.*</code></p>
<ul>
<li><code>resourcemanager. capabilityConfigs. create</code></li>
<li><code>resourcemanager. capabilityConfigs. delete</code></li>
<li><code>resourcemanager. capabilityConfigs. get</code></li>
<li><code>resourcemanager. capabilityConfigs. list</code></li>
<li><code>resourcemanager. capabilityConfigs. update</code></li>
</ul>
<p><code>resourcemanager.folders.create</code></p>
<p><code>resourcemanager.folders.delete</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. folders. undelete</code></p>
<p><code>resourcemanager.folders.update</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. projects. associateToCapabilityConfig</code></p>
<p><code>resourcemanager. projects. create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.projects.move</code></p>
<p><code>resourcemanager. projects. update</code></p>
<p><code>resourcemanager.tagHolds.*</code></p>
<ul>
<li><code>resourcemanager. tagHolds. create</code></li>
<li><code>resourcemanager. tagHolds. delete</code></li>
<li><code>resourcemanager.tagHolds.list</code></li>
</ul>
<p><code>resourcemanager.tagKeys.create</code></p>
<p><code>resourcemanager.tagKeys.delete</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagKeys.update</code></p>
<p><code>resourcemanager. tagValues. create</code></p>
<p><code>resourcemanager. tagValues. delete</code></p>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>resourcemanager. tagValues. update</code></p></td>
</tr>
<tr class="even">
<td>Folder Admin
<p>( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p>Provides all available permissions for working with folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>essentialcontacts.*</code></p>
<ul>
<li><code>essentialcontacts. contacts. create</code></li>
<li><code>essentialcontacts. contacts. delete</code></li>
<li><code>essentialcontacts.contacts.get</code></li>
<li><code>essentialcontacts. contacts. list</code></li>
<li><code>essentialcontacts. contacts. send</code></li>
<li><code>essentialcontacts. contacts. update</code></li>
</ul>
<p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.capabilities.*</code></p>
<ul>
<li><code>resourcemanager. capabilities. get</code></li>
<li><code>resourcemanager. capabilities. update</code></li>
</ul>
<p><code>resourcemanager.folders.*</code></p>
<ul>
<li><code>resourcemanager.folders.create</code></li>
<li><code>resourcemanager. folders. createPolicyBinding</code></li>
<li><code>resourcemanager.folders.delete</code></li>
<li><code>resourcemanager. folders. deletePolicyBinding</code></li>
<li><code>resourcemanager.folders.get</code></li>
<li><code>resourcemanager. folders. getIamPolicy</code></li>
<li><code>resourcemanager.folders.list</code></li>
<li><code>resourcemanager.folders.move</code></li>
<li><code>resourcemanager. folders. searchPolicyBindings</code></li>
<li><code>resourcemanager. folders. setIamPolicy</code></li>
<li><code>resourcemanager. folders. undelete</code></li>
<li><code>resourcemanager.folders.update</code></li>
<li><code>resourcemanager. folders. updatePolicyBinding</code></li>
</ul>
<p><code>resourcemanager. hierarchyNodes.*</code></p>
<ul>
<li><code>resourcemanager. hierarchyNodes. createTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></li>
<li><code>resourcemanager. hierarchyNodes. listTagBindings</code></li>
</ul>
<p><code>resourcemanager. projects. createPolicyBinding</code></p>
<p><code>resourcemanager. projects. deletePolicyBinding</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.projects.move</code></p>
<p><code>resourcemanager. projects. searchPolicyBindings</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>resourcemanager. projects. updatePolicyBinding</code></p></td>
</tr>
<tr class="odd">
<td>Organization Administrator
<p>( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p>Access to manage IAM policies and view organization policies for organizations, folders, and projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>essentialcontacts.*</code></p>
<ul>
<li><code>essentialcontacts. contacts. create</code></li>
<li><code>essentialcontacts. contacts. delete</code></li>
<li><code>essentialcontacts.contacts.get</code></li>
<li><code>essentialcontacts. contacts. list</code></li>
<li><code>essentialcontacts. contacts. send</code></li>
<li><code>essentialcontacts. contacts. update</code></li>
</ul>
<p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.capabilities.*</code></p>
<ul>
<li><code>resourcemanager. capabilities. get</code></li>
<li><code>resourcemanager. capabilities. update</code></li>
</ul>
<p><code>resourcemanager. folders. createPolicyBinding</code></p>
<p><code>resourcemanager. folders. deletePolicyBinding</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. folders. searchPolicyBindings</code></p>
<p><code>resourcemanager. folders. setIamPolicy</code></p>
<p><code>resourcemanager. folders. updatePolicyBinding</code></p>
<p><code>resourcemanager. organizations.*</code></p>
<ul>
<li><code>resourcemanager. organizations. createPolicyBinding</code></li>
<li><code>resourcemanager. organizations. deletePolicyBinding</code></li>
<li><code>resourcemanager. organizations. get</code></li>
<li><code>resourcemanager. organizations. getIamPolicy</code></li>
<li><code>resourcemanager. organizations. searchPolicyBindings</code></li>
<li><code>resourcemanager. organizations. setIamPolicy</code></li>
<li><code>resourcemanager. organizations. updatePolicyBinding</code></li>
</ul>
<p><code>resourcemanager. projects. createPolicyBinding</code></p>
<p><code>resourcemanager. projects. deletePolicyBinding</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. searchPolicyBindings</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>resourcemanager. projects. updatePolicyBinding</code></p></td>
</tr>
<tr class="even">
<td>Project IAM Admin
<p>( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p>Provides permissions to administer allow policies on projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>resourcemanager. projects. createPolicyBinding</code></p>
<p><code>resourcemanager. projects. deletePolicyBinding</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager. projects. searchPolicyBindings</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>resourcemanager. projects. updatePolicyBinding</code></p></td>
</tr>
<tr class="odd">
<td>Project Mover
<p>( <code>roles/ resourcemanager.projectMover</code> )</p>
<p>Provides access to update and move projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.move</code></p>
<p><code>resourcemanager. projects. update</code></p></td>
</tr>
<tr class="even">
<td>Tag Administrator
<p>( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p>Access to create, delete, update, and manage access to Tags</p></td>
<td><p><code>resourcemanager.tagHolds.*</code></p>
<ul>
<li><code>resourcemanager. tagHolds. create</code></li>
<li><code>resourcemanager. tagHolds. delete</code></li>
<li><code>resourcemanager.tagHolds.list</code></li>
</ul>
<p><code>resourcemanager.tagKeys.*</code></p>
<ul>
<li><code>resourcemanager.tagKeys.create</code></li>
<li><code>resourcemanager.tagKeys.delete</code></li>
<li><code>resourcemanager.tagKeys.get</code></li>
<li><code>resourcemanager. tagKeys. getIamPolicy</code></li>
<li><code>resourcemanager.tagKeys.list</code></li>
<li><code>resourcemanager. tagKeys. setIamPolicy</code></li>
<li><code>resourcemanager.tagKeys.update</code></li>
</ul>
<p><code>resourcemanager.tagValues.*</code></p>
<ul>
<li><code>resourcemanager. tagValues. create</code></li>
<li><code>resourcemanager. tagValues. delete</code></li>
<li><code>resourcemanager.tagValues.get</code></li>
<li><code>resourcemanager. tagValues. getIamPolicy</code></li>
<li><code>resourcemanager.tagValues.list</code></li>
<li><code>resourcemanager. tagValues. setIamPolicy</code></li>
<li><code>resourcemanager. tagValues. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Tag User
<p>( <code>roles/ resourcemanager.tagUser</code> )</p>
<p>Access to list Tags and manage their associations with resources</p></td>
<td><p><code>alloydb. backups. createTagBinding</code></p>
<p><code>alloydb. backups. deleteTagBinding</code></p>
<p><code>alloydb. backups. listEffectiveTags</code></p>
<p><code>alloydb. backups. listTagBindings</code></p>
<p><code>alloydb. clusters. createTagBinding</code></p>
<p><code>alloydb. clusters. deleteTagBinding</code></p>
<p><code>alloydb. clusters. listEffectiveTags</code></p>
<p><code>alloydb. clusters. listTagBindings</code></p>
<p><code>apigateway. apis. createTagBinding</code></p>
<p><code>apigateway. apis. deleteTagBinding</code></p>
<p><code>apigateway. apis. listEffectiveTags</code></p>
<p><code>apigateway. apis. listTagBindings</code></p>
<p><code>apigateway. gateways. createTagBinding</code></p>
<p><code>apigateway. gateways. deleteTagBinding</code></p>
<p><code>apigateway. gateways. listEffectiveTags</code></p>
<p><code>apigateway. gateways. listTagBindings</code></p>
<p><code>apihub.apis.createTagBinding</code></p>
<p><code>apihub.apis.deleteTagBinding</code></p>
<p><code>apihub.apis.listEffectiveTags</code></p>
<p><code>apihub.apis.listTagBindings</code></p>
<p><code>apihub. deployments. createTagBinding</code></p>
<p><code>apihub. deployments. deleteTagBinding</code></p>
<p><code>apihub. deployments. listEffectiveTags</code></p>
<p><code>apihub. deployments. listTagBindings</code></p>
<p><code>artifactregistry. repositories. createTagBinding</code></p>
<p><code>artifactregistry. repositories. deleteTagBinding</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>backupdr. backupVaults. createTagBinding</code></p>
<p><code>backupdr. backupVaults. deleteTagBinding</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. managementServers. createTagBinding</code></p>
<p><code>backupdr. managementServers. deleteTagBinding</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>beyondcorp. appConnections. createTagBinding</code></p>
<p><code>beyondcorp. appConnections. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnections. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnections. listTagBindings</code></p>
<p><code>beyondcorp. appConnectors. createTagBinding</code></p>
<p><code>beyondcorp. appConnectors. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnectors. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnectors. listTagBindings</code></p>
<p><code>beyondcorp. appGateways. createTagBinding</code></p>
<p><code>beyondcorp. appGateways. deleteTagBinding</code></p>
<p><code>beyondcorp. appGateways. listEffectiveTags</code></p>
<p><code>beyondcorp. appGateways. listTagBindings</code></p>
<p><code>bigquery. datasets. createTagBinding</code></p>
<p><code>bigquery. datasets. deleteTagBinding</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery. tables. createTagBinding</code></p>
<p><code>bigquery. tables. deleteTagBinding</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>bigtable. authorizedViews. createTagBinding</code></p>
<p><code>bigtable. authorizedViews. deleteTagBinding</code></p>
<p><code>bigtable. authorizedViews. listEffectiveTags</code></p>
<p><code>bigtable. authorizedViews. listTagBindings</code></p>
<p><code>bigtable. instances. createTagBinding</code></p>
<p><code>bigtable. instances. deleteTagBinding</code></p>
<p><code>bigtable. instances. listEffectiveTags</code></p>
<p><code>bigtable. instances. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. createTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. createTagBinding</code></p>
<p><code>certificatemanager. certmapentries. deleteTagBinding</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. createTagBinding</code></p>
<p><code>certificatemanager. certmaps. deleteTagBinding</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certs. createTagBinding</code></p>
<p><code>certificatemanager. certs. deleteTagBinding</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. createTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. trustconfigs. createTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>clouddeploy. deliveryPipelines. createTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. deleteTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. listEffectiveTags</code></p>
<p><code>clouddeploy. deliveryPipelines. listTagBindings</code></p>
<p><code>clouddeploy. targets. createTagBinding</code></p>
<p><code>clouddeploy. targets. deleteTagBinding</code></p>
<p><code>clouddeploy. targets. listEffectiveTags</code></p>
<p><code>clouddeploy. targets. listTagBindings</code></p>
<p><code>cloudkms. keyRings. createTagBinding</code></p>
<p><code>cloudkms. keyRings. deleteTagBinding</code></p>
<p><code>cloudkms. keyRings. listEffectiveTags</code></p>
<p><code>cloudkms. keyRings. listTagBindings</code></p>
<p><code>cloudsql. instances. createTagBinding</code></p>
<p><code>cloudsql. instances. deleteTagBinding</code></p>
<p><code>cloudsql. instances. listEffectiveTags</code></p>
<p><code>cloudsql. instances. listTagBindings</code></p>
<p><code>composer. environments. createTagBinding</code></p>
<p><code>composer. environments. deleteTagBinding</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>compute. addresses. createTagBinding</code></p>
<p><code>compute. addresses. deleteTagBinding</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute. backendBuckets. createTagBinding</code></p>
<p><code>compute. backendBuckets. deleteTagBinding</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute. backendServices. createTagBinding</code></p>
<p><code>compute. backendServices. deleteTagBinding</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute. commitments. createTagBinding</code></p>
<p><code>compute. commitments. deleteTagBinding</code></p>
<p><code>compute. commitments. listEffectiveTags</code></p>
<p><code>compute. commitments. listTagBindings</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.deleteTagBinding</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. createTagBinding</code></p>
<p><code>compute. externalVpnGateways. deleteTagBinding</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute. firewallPolicies. createTagBinding</code></p>
<p><code>compute. firewallPolicies. deleteTagBinding</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute. firewalls. createTagBinding</code></p>
<p><code>compute. firewalls. deleteTagBinding</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute. forwardingRules. createTagBinding</code></p>
<p><code>compute. forwardingRules. deleteTagBinding</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute. futureReservations. createTagBinding</code></p>
<p><code>compute. futureReservations. deleteTagBinding</code></p>
<p><code>compute. futureReservations. listEffectiveTags</code></p>
<p><code>compute. futureReservations. listTagBindings</code></p>
<p><code>compute. globalAddresses. createTagBinding</code></p>
<p><code>compute. globalAddresses. deleteTagBinding</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. createTagBinding</code></p>
<p><code>compute. globalForwardingRules. deleteTagBinding</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. globalNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. healthChecks. createTagBinding</code></p>
<p><code>compute. healthChecks. deleteTagBinding</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute. httpHealthChecks. createTagBinding</code></p>
<p><code>compute. httpHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute. httpsHealthChecks. createTagBinding</code></p>
<p><code>compute. httpsHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute. images. createTagBinding</code></p>
<p><code>compute. images. deleteTagBinding</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. createTagBinding</code></p>
<p><code>compute. instanceGroupManagers. deleteTagBinding</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute. instanceGroups. createTagBinding</code></p>
<p><code>compute. instanceGroups. deleteTagBinding</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute. instances. deleteTagBinding</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instantSnapshots. createTagBinding</code></p>
<p><code>compute. instantSnapshots. deleteTagBinding</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. interconnectAttachments. createTagBinding</code></p>
<p><code>compute. interconnectAttachments. deleteTagBinding</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute. interconnects. createTagBinding</code></p>
<p><code>compute. interconnects. deleteTagBinding</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute. licenses. createTagBinding</code></p>
<p><code>compute. licenses. deleteTagBinding</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute. machineImages. createTagBinding</code></p>
<p><code>compute. machineImages. deleteTagBinding</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. networkAttachments. createTagBinding</code></p>
<p><code>compute. networkAttachments. deleteTagBinding</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEdgeSecurityServices. createTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. deleteTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. listEffectiveTags</code></p>
<p><code>compute. networkEdgeSecurityServices. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups. createTagBinding</code></p>
<p><code>compute. networkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. networkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. networkEndpointGroups. listTagBindings</code></p>
<p><code>compute. networks. createTagBinding</code></p>
<p><code>compute. networks. deleteTagBinding</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute. packetMirrorings. createTagBinding</code></p>
<p><code>compute. packetMirrorings. deleteTagBinding</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. createTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. deleteTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. regionBackendBuckets. createTagBinding</code></p>
<p><code>compute. regionBackendBuckets. deleteTagBinding</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. createTagBinding</code></p>
<p><code>compute. regionBackendServices. deleteTagBinding</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. createTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. deleteTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionHealthChecks. createTagBinding</code></p>
<p><code>compute. regionHealthChecks. deleteTagBinding</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. regionNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. createTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSslCertificates. createTagBinding</code></p>
<p><code>compute. regionSslCertificates. deleteTagBinding</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute. regionSslPolicies. createTagBinding</code></p>
<p><code>compute. regionSslPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute. regionUrlMaps. createTagBinding</code></p>
<p><code>compute. regionUrlMaps. deleteTagBinding</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute. reservations. createTagBinding</code></p>
<p><code>compute. reservations. deleteTagBinding</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute. routers. createTagBinding</code></p>
<p><code>compute. routers. deleteTagBinding</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute. routes. createTagBinding</code></p>
<p><code>compute. routes. deleteTagBinding</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute. securityPolicies. createTagBinding</code></p>
<p><code>compute. securityPolicies. deleteTagBinding</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute. serviceAttachments. createTagBinding</code></p>
<p><code>compute. serviceAttachments. deleteTagBinding</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute. snapshots. createTagBinding</code></p>
<p><code>compute. snapshots. deleteTagBinding</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute. sslCertificates. createTagBinding</code></p>
<p><code>compute. sslCertificates. deleteTagBinding</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute. sslPolicies. createTagBinding</code></p>
<p><code>compute. sslPolicies. deleteTagBinding</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute. storagePools. createTagBinding</code></p>
<p><code>compute. storagePools. deleteTagBinding</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute. subnetworks. createTagBinding</code></p>
<p><code>compute. subnetworks. deleteTagBinding</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute. targetGrpcProxies. createTagBinding</code></p>
<p><code>compute. targetGrpcProxies. deleteTagBinding</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute. targetHttpProxies. createTagBinding</code></p>
<p><code>compute. targetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute. targetHttpsProxies. createTagBinding</code></p>
<p><code>compute. targetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute. targetInstances. createTagBinding</code></p>
<p><code>compute. targetInstances. deleteTagBinding</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute. targetPools. createTagBinding</code></p>
<p><code>compute. targetPools. deleteTagBinding</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute. targetSslProxies. createTagBinding</code></p>
<p><code>compute. targetSslProxies. deleteTagBinding</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute. targetTcpProxies. createTagBinding</code></p>
<p><code>compute. targetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute. targetVpnGateways. createTagBinding</code></p>
<p><code>compute. targetVpnGateways. deleteTagBinding</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute. urlMaps. createTagBinding</code></p>
<p><code>compute. urlMaps. deleteTagBinding</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute. vpnGateways. createTagBinding</code></p>
<p><code>compute. vpnGateways. deleteTagBinding</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute. vpnTunnels. createTagBinding</code></p>
<p><code>compute. vpnTunnels. deleteTagBinding</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>config. deploymentgroups. createTagBinding</code></p>
<p><code>config. deploymentgroups. deleteTagBinding</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config. deployments. createTagBinding</code></p>
<p><code>config. deployments. deleteTagBinding</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config. previews. createTagBinding</code></p>
<p><code>config. previews. deleteTagBinding</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>container. clusters. createTagBinding</code></p>
<p><code>container. clusters. deleteTagBinding</code></p>
<p><code>container. clusters. listEffectiveTags</code></p>
<p><code>container. clusters. listTagBindings</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>datafusion. instances. createTagBinding</code></p>
<p><code>datafusion. instances. deleteTagBinding</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datamigration. connectionprofiles. createTagBinding</code></p>
<p><code>datamigration. connectionprofiles. deleteTagBinding</code></p>
<p><code>datamigration. connectionprofiles. listEffectiveTags</code></p>
<p><code>datamigration. connectionprofiles. listTagBindings</code></p>
<p><code>datamigration. migrationjobs. createTagBinding</code></p>
<p><code>datamigration. migrationjobs. deleteTagBinding</code></p>
<p><code>datamigration. migrationjobs. listEffectiveTags</code></p>
<p><code>datamigration. migrationjobs. listTagBindings</code></p>
<p><code>datamigration. privateconnections. createTagBinding</code></p>
<p><code>datamigration. privateconnections. deleteTagBinding</code></p>
<p><code>datamigration. privateconnections. listEffectiveTags</code></p>
<p><code>datamigration. privateconnections. listTagBindings</code></p>
<p><code>dataplex. entryGroups. createTagBinding</code></p>
<p><code>dataplex. entryGroups. deleteTagBinding</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryTypes. createTagBinding</code></p>
<p><code>dataplex. entryTypes. deleteTagBinding</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.governanceRules.*</code></p>
<ul>
<li><code>dataplex. governanceRules. createTagBinding</code></li>
<li><code>dataplex. governanceRules. deleteTagBinding</code></li>
<li><code>dataplex. governanceRules. listEffectiveTags</code></li>
<li><code>dataplex. governanceRules. listTagBindings</code></li>
</ul>
<p><code>datastore. databases. createTagBinding</code></p>
<p><code>datastore. databases. deleteTagBinding</code></p>
<p><code>datastore. databases. listEffectiveTags</code></p>
<p><code>datastore. databases. listTagBindings</code></p>
<p><code>datastream. connectionProfiles. createTagBinding</code></p>
<p><code>datastream. connectionProfiles. deleteTagBinding</code></p>
<p><code>datastream. connectionProfiles. listEffectiveTags</code></p>
<p><code>datastream. connectionProfiles. listTagBindings</code></p>
<p><code>datastream. privateConnections. createTagBinding</code></p>
<p><code>datastream. privateConnections. deleteTagBinding</code></p>
<p><code>datastream. privateConnections. listEffectiveTags</code></p>
<p><code>datastream. privateConnections. listTagBindings</code></p>
<p><code>datastream. streams. createTagBinding</code></p>
<p><code>datastream. streams. deleteTagBinding</code></p>
<p><code>datastream. streams. listEffectiveTags</code></p>
<p><code>datastream. streams. listTagBindings</code></p>
<p><code>dns.policies.createTagBinding</code></p>
<p><code>dns.policies.deleteTagBinding</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>domains. registrations. createTagBinding</code></p>
<p><code>domains. registrations. deleteTagBinding</code></p>
<p><code>domains. registrations. listEffectiveTags</code></p>
<p><code>domains. registrations. listTagBindings</code></p>
<p><code>eventarc. channelConnections. createTagBinding</code></p>
<p><code>eventarc. channelConnections. deleteTagBinding</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channels. createTagBinding</code></p>
<p><code>eventarc. channels. deleteTagBinding</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc. triggers. createTagBinding</code></p>
<p><code>eventarc. triggers. deleteTagBinding</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>file.backups.createTagBinding</code></p>
<p><code>file.backups.deleteTagBinding</code></p>
<p><code>file.backups.listEffectiveTags</code></p>
<p><code>file.backups.listTagBindings</code></p>
<p><code>file. instances. createTagBinding</code></p>
<p><code>file. instances. deleteTagBinding</code></p>
<p><code>file. instances. listEffectiveTags</code></p>
<p><code>file.instances.listTagBindings</code></p>
<p><code>file.snapshots.*</code></p>
<ul>
<li><code>file. snapshots. createTagBinding</code></li>
<li><code>file. snapshots. deleteTagBinding</code></li>
<li><code>file. snapshots. listEffectiveTags</code></li>
<li><code>file.snapshots.listTagBindings</code></li>
</ul>
<p><code>financialservices. v1instances. createTagBinding</code></p>
<p><code>financialservices. v1instances. deleteTagBinding</code></p>
<p><code>financialservices. v1instances. listEffectiveTags</code></p>
<p><code>financialservices. v1instances. listTagBindings</code></p>
<p><code>gkemulticloud. attachedClusters. createTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. deleteTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareClusters. listTagBindings</code></p>
<p><code>iam.roles.createTagBinding</code></p>
<p><code>iam.roles.deleteTagBinding</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam. serviceAccounts. createTagBinding</code></p>
<p><code>iam. serviceAccounts. deleteTagBinding</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>krmapihosting. krmApiHosts. createTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. deleteTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>livestream. channels. createTagBinding</code></p>
<p><code>livestream. channels. deleteTagBinding</code></p>
<p><code>livestream. channels. listEffectiveTags</code></p>
<p><code>livestream. channels. listTagBindings</code></p>
<p><code>livestream. inputs. createTagBinding</code></p>
<p><code>livestream. inputs. deleteTagBinding</code></p>
<p><code>livestream. inputs. listEffectiveTags</code></p>
<p><code>livestream. inputs. listTagBindings</code></p>
<p><code>livestream. pools. createTagBinding</code></p>
<p><code>livestream. pools. deleteTagBinding</code></p>
<p><code>livestream. pools. listEffectiveTags</code></p>
<p><code>livestream. pools. listTagBindings</code></p>
<p><code>logging. buckets. createTagBinding</code></p>
<p><code>logging. buckets. deleteTagBinding</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>looker. instances. createTagBinding</code></p>
<p><code>looker. instances. deleteTagBinding</code></p>
<p><code>looker. instances. listEffectiveTags</code></p>
<p><code>looker. instances. listTagBindings</code></p>
<p><code>managedidentities. domains. createTagBinding</code></p>
<p><code>managedidentities. domains. deleteTagBinding</code></p>
<p><code>managedidentities. domains. listEffectiveTags</code></p>
<p><code>managedidentities. domains. listTagBindings</code></p>
<p><code>memcache. instances. createTagBinding</code></p>
<p><code>memcache. instances. deleteTagBinding</code></p>
<p><code>memcache. instances. listEffectiveTags</code></p>
<p><code>memcache. instances. listTagBindings</code></p>
<p><code>metastore. federations. createTagBinding</code></p>
<p><code>metastore. federations. deleteTagBinding</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore. services. createTagBinding</code></p>
<p><code>metastore. services. deleteTagBinding</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>monitoring. alertPolicies. createTagBinding</code></p>
<p><code>monitoring. alertPolicies. deleteTagBinding</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring. dashboards. createTagBinding</code></p>
<p><code>monitoring. dashboards. deleteTagBinding</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>networkconnectivity. hubs. createTagBinding</code></p>
<p><code>networkconnectivity. hubs. deleteTagBinding</code></p>
<p><code>networkconnectivity. hubs. listEffectiveTags</code></p>
<p><code>networkconnectivity. hubs. listTagBindings</code></p>
<p><code>networkconnectivity. spokes. createTagBinding</code></p>
<p><code>networkconnectivity. spokes. deleteTagBinding</code></p>
<p><code>networkconnectivity. spokes. listEffectiveTags</code></p>
<p><code>networkconnectivity. spokes. listTagBindings</code></p>
<p><code>networkmanagement. connectivitytests. createTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. deleteTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networksecurity. authorizationPolicies. createTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. authorizationPolicies. listTagBindings</code></p>
<p><code>networksecurity. clientTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. clientTlsPolicies. listTagBindings</code></p>
<p><code>networksecurity. serverTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. serverTlsPolicies. listTagBindings</code></p>
<p><code>networkservices. endpointConfigSelectors.*</code></p>
<ul>
<li><code>networkservices. endpointConfigSelectors. createTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. deleteTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></li>
<li><code>networkservices. endpointConfigSelectors. listTagBindings</code></li>
</ul>
<p><code>networkservices. gateways. createTagBinding</code></p>
<p><code>networkservices. gateways. deleteTagBinding</code></p>
<p><code>networkservices. gateways. listEffectiveTags</code></p>
<p><code>networkservices. gateways. listTagBindings</code></p>
<p><code>networkservices. httpFilters. createTagBinding</code></p>
<p><code>networkservices. httpFilters. deleteTagBinding</code></p>
<p><code>networkservices. httpFilters. listEffectiveTags</code></p>
<p><code>networkservices. httpFilters. listTagBindings</code></p>
<p><code>networkservices. meshes. createTagBinding</code></p>
<p><code>networkservices. meshes. deleteTagBinding</code></p>
<p><code>networkservices. meshes. listEffectiveTags</code></p>
<p><code>networkservices. meshes. listTagBindings</code></p>
<p><code>notebooks. instances. createTagBinding</code></p>
<p><code>notebooks. instances. deleteTagBinding</code></p>
<p><code>notebooks. instances. listEffectiveTags</code></p>
<p><code>notebooks. instances. listTagBindings</code></p>
<p><code>parametermanager. parameters. createTagBinding</code></p>
<p><code>parametermanager. parameters. deleteTagBinding</code></p>
<p><code>parametermanager. parameters. listEffectiveTags</code></p>
<p><code>parametermanager. parameters. listTagBindings</code></p>
<p><code>privateca. caPools. createTagBinding</code></p>
<p><code>privateca. caPools. deleteTagBinding</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. createTagBinding</code></p>
<p><code>privateca. certificateTemplates. deleteTagBinding</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>pubsub. snapshots. createTagBinding</code></p>
<p><code>pubsub. snapshots. deleteTagBinding</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub. subscriptions. createTagBinding</code></p>
<p><code>pubsub. subscriptions. deleteTagBinding</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.topics.createTagBinding</code></p>
<p><code>pubsub.topics.deleteTagBinding</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>recaptchaenterprise. keys. createTagBinding</code></p>
<p><code>recaptchaenterprise. keys. deleteTagBinding</code></p>
<p><code>recaptchaenterprise. keys. listEffectiveTags</code></p>
<p><code>recaptchaenterprise. keys. listTagBindings</code></p>
<p><code>redis. clusters. createTagBinding</code></p>
<p><code>redis. clusters. deleteTagBinding</code></p>
<p><code>redis. clusters. listEffectiveTags</code></p>
<p><code>redis.clusters.listTagBindings</code></p>
<p><code>redis. instances. createTagBinding</code></p>
<p><code>redis. instances. deleteTagBinding</code></p>
<p><code>redis. instances. listEffectiveTags</code></p>
<p><code>redis. instances. listTagBindings</code></p>
<p><code>resourcemanager. hierarchyNodes.*</code></p>
<ul>
<li><code>resourcemanager. hierarchyNodes. createTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></li>
<li><code>resourcemanager. hierarchyNodes. listTagBindings</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager. tagValueBindings.*</code></p>
<ul>
<li><code>resourcemanager. tagValueBindings. create</code></li>
<li><code>resourcemanager. tagValueBindings. delete</code></li>
</ul>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>run.jobs.createTagBinding</code></p>
<p><code>run.jobs.deleteTagBinding</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.services.createTagBinding</code></p>
<p><code>run.services.deleteTagBinding</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>secretmanager. secrets. createTagBinding</code></p>
<p><code>secretmanager. secrets. deleteTagBinding</code></p>
<p><code>secretmanager. secrets. listEffectiveTags</code></p>
<p><code>secretmanager. secrets. listTagBindings</code></p>
<p><code>spanner. instances. createTagBinding</code></p>
<p><code>spanner. instances. deleteTagBinding</code></p>
<p><code>spanner. instances. listEffectiveTags</code></p>
<p><code>spanner. instances. listTagBindings</code></p>
<p><code>storage. buckets. createTagBinding</code></p>
<p><code>storage. buckets. deleteTagBinding</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>tpu.nodes.createTagBinding</code></p>
<p><code>tpu.nodes.deleteTagBinding</code></p>
<p><code>tpu.nodes.listEffectiveTags</code></p>
<p><code>tpu.nodes.listTagBindings</code></p>
<p><code>transcoder. jobTemplates. createTagBinding</code></p>
<p><code>transcoder. jobTemplates. deleteTagBinding</code></p>
<p><code>transcoder. jobTemplates. listEffectiveTags</code></p>
<p><code>transcoder. jobTemplates. listTagBindings</code></p>
<p><code>transcoder. jobs. createTagBinding</code></p>
<p><code>transcoder. jobs. deleteTagBinding</code></p>
<p><code>transcoder. jobs. listEffectiveTags</code></p>
<p><code>transcoder. jobs. listTagBindings</code></p>
<p><code>videostitcher. cdnKeys. createTagBinding</code></p>
<p><code>videostitcher. cdnKeys. deleteTagBinding</code></p>
<p><code>videostitcher. cdnKeys. listEffectiveTags</code></p>
<p><code>videostitcher. cdnKeys. listTagBindings</code></p>
<p><code>videostitcher. liveConfigs. createTagBinding</code></p>
<p><code>videostitcher. liveConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. liveConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. liveConfigs. listTagBindings</code></p>
<p><code>videostitcher. slates. createTagBinding</code></p>
<p><code>videostitcher. slates. deleteTagBinding</code></p>
<p><code>videostitcher. slates. listEffectiveTags</code></p>
<p><code>videostitcher. slates. listTagBindings</code></p>
<p><code>videostitcher. vodConfigs. createTagBinding</code></p>
<p><code>videostitcher. vodConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. vodConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. vodConfigs. listTagBindings</code></p>
<p><code>vmmigration. groups. createTagBinding</code></p>
<p><code>vmmigration. groups. deleteTagBinding</code></p>
<p><code>vmmigration. groups. listEffectiveTags</code></p>
<p><code>vmmigration. groups. listTagBindings</code></p>
<p><code>vmmigration. sources. createTagBinding</code></p>
<p><code>vmmigration. sources. deleteTagBinding</code></p>
<p><code>vmmigration. sources. listEffectiveTags</code></p>
<p><code>vmmigration. sources. listTagBindings</code></p>
<p><code>vmwareengine. networkPeerings. createTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. createTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. createTagBinding</code></p>
<p><code>vmwareengine. privateClouds. deleteTagBinding</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. createTagBinding</code></p>
<p><code>vmwareengine. privateConnections. deleteTagBinding</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p>
<p><code>workflows. workflows. createTagBinding</code></p>
<p><code>workflows. workflows. deleteTagBinding</code></p>
<p><code>workflows. workflows. listEffectiveTags</code></p>
<p><code>workflows. workflows. listTagBindings</code></p>
<p><code>workstations. workstationClusters. createTagBinding</code></p>
<p><code>workstations. workstationClusters. deleteTagBinding</code></p>
<p><code>workstations. workstationClusters. listEffectiveTags</code></p>
<p><code>workstations. workstationClusters. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>Tag Viewer
<p>( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p>Access to list Tags and their associations with resources</p></td>
<td><p><code>alloydb. backups. listEffectiveTags</code></p>
<p><code>alloydb. backups. listTagBindings</code></p>
<p><code>alloydb. clusters. listEffectiveTags</code></p>
<p><code>alloydb. clusters. listTagBindings</code></p>
<p><code>apigateway. apis. listEffectiveTags</code></p>
<p><code>apigateway. apis. listTagBindings</code></p>
<p><code>apigateway. gateways. listEffectiveTags</code></p>
<p><code>apigateway. gateways. listTagBindings</code></p>
<p><code>apihub.apis.listEffectiveTags</code></p>
<p><code>apihub.apis.listTagBindings</code></p>
<p><code>apihub. deployments. listEffectiveTags</code></p>
<p><code>apihub. deployments. listTagBindings</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>beyondcorp. appConnections. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnections. listTagBindings</code></p>
<p><code>beyondcorp. appConnectors. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnectors. listTagBindings</code></p>
<p><code>beyondcorp. appGateways. listEffectiveTags</code></p>
<p><code>beyondcorp. appGateways. listTagBindings</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>bigtable. authorizedViews. listEffectiveTags</code></p>
<p><code>bigtable. authorizedViews. listTagBindings</code></p>
<p><code>bigtable. instances. listEffectiveTags</code></p>
<p><code>bigtable. instances. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>clouddeploy. deliveryPipelines. listEffectiveTags</code></p>
<p><code>clouddeploy. deliveryPipelines. listTagBindings</code></p>
<p><code>clouddeploy. targets. listEffectiveTags</code></p>
<p><code>clouddeploy. targets. listTagBindings</code></p>
<p><code>cloudkms. keyRings. listEffectiveTags</code></p>
<p><code>cloudkms. keyRings. listTagBindings</code></p>
<p><code>cloudsql. instances. listEffectiveTags</code></p>
<p><code>cloudsql. instances. listTagBindings</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute. commitments. listEffectiveTags</code></p>
<p><code>compute. commitments. listTagBindings</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute. futureReservations. listEffectiveTags</code></p>
<p><code>compute. futureReservations. listTagBindings</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. globalNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEdgeSecurityServices. listEffectiveTags</code></p>
<p><code>compute. networkEdgeSecurityServices. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. networkEndpointGroups. listTagBindings</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. regionNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>container. clusters. listEffectiveTags</code></p>
<p><code>container. clusters. listTagBindings</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datamigration. connectionprofiles. listEffectiveTags</code></p>
<p><code>datamigration. connectionprofiles. listTagBindings</code></p>
<p><code>datamigration. migrationjobs. listEffectiveTags</code></p>
<p><code>datamigration. migrationjobs. listTagBindings</code></p>
<p><code>datamigration. privateconnections. listEffectiveTags</code></p>
<p><code>datamigration. privateconnections. listTagBindings</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex. governanceRules. listEffectiveTags</code></p>
<p><code>dataplex. governanceRules. listTagBindings</code></p>
<p><code>datastore. databases. listEffectiveTags</code></p>
<p><code>datastore. databases. listTagBindings</code></p>
<p><code>datastream. connectionProfiles. listEffectiveTags</code></p>
<p><code>datastream. connectionProfiles. listTagBindings</code></p>
<p><code>datastream. privateConnections. listEffectiveTags</code></p>
<p><code>datastream. privateConnections. listTagBindings</code></p>
<p><code>datastream. streams. listEffectiveTags</code></p>
<p><code>datastream. streams. listTagBindings</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>domains. registrations. listEffectiveTags</code></p>
<p><code>domains. registrations. listTagBindings</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>file.backups.listEffectiveTags</code></p>
<p><code>file.backups.listTagBindings</code></p>
<p><code>file. instances. listEffectiveTags</code></p>
<p><code>file.instances.listTagBindings</code></p>
<p><code>file. snapshots. listEffectiveTags</code></p>
<p><code>file.snapshots.listTagBindings</code></p>
<p><code>financialservices. v1instances. listEffectiveTags</code></p>
<p><code>financialservices. v1instances. listTagBindings</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareClusters. listTagBindings</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>livestream. channels. listEffectiveTags</code></p>
<p><code>livestream. channels. listTagBindings</code></p>
<p><code>livestream. inputs. listEffectiveTags</code></p>
<p><code>livestream. inputs. listTagBindings</code></p>
<p><code>livestream. pools. listEffectiveTags</code></p>
<p><code>livestream. pools. listTagBindings</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>looker. instances. listEffectiveTags</code></p>
<p><code>looker. instances. listTagBindings</code></p>
<p><code>managedidentities. domains. listEffectiveTags</code></p>
<p><code>managedidentities. domains. listTagBindings</code></p>
<p><code>memcache. instances. listEffectiveTags</code></p>
<p><code>memcache. instances. listTagBindings</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>networkconnectivity. hubs. listEffectiveTags</code></p>
<p><code>networkconnectivity. hubs. listTagBindings</code></p>
<p><code>networkconnectivity. spokes. listEffectiveTags</code></p>
<p><code>networkconnectivity. spokes. listTagBindings</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networksecurity. authorizationPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. authorizationPolicies. listTagBindings</code></p>
<p><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. clientTlsPolicies. listTagBindings</code></p>
<p><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. serverTlsPolicies. listTagBindings</code></p>
<p><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></p>
<p><code>networkservices. endpointConfigSelectors. listTagBindings</code></p>
<p><code>networkservices. gateways. listEffectiveTags</code></p>
<p><code>networkservices. gateways. listTagBindings</code></p>
<p><code>networkservices. httpFilters. listEffectiveTags</code></p>
<p><code>networkservices. httpFilters. listTagBindings</code></p>
<p><code>networkservices. meshes. listEffectiveTags</code></p>
<p><code>networkservices. meshes. listTagBindings</code></p>
<p><code>notebooks. instances. listEffectiveTags</code></p>
<p><code>notebooks. instances. listTagBindings</code></p>
<p><code>parametermanager. parameters. listEffectiveTags</code></p>
<p><code>parametermanager. parameters. listTagBindings</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>recaptchaenterprise. keys. listEffectiveTags</code></p>
<p><code>recaptchaenterprise. keys. listTagBindings</code></p>
<p><code>redis. clusters. listEffectiveTags</code></p>
<p><code>redis.clusters.listTagBindings</code></p>
<p><code>redis. instances. listEffectiveTags</code></p>
<p><code>redis. instances. listTagBindings</code></p>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager. hierarchyNodes. listTagBindings</code></p>
<p><code>resourcemanager.tagHolds.list</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>secretmanager. secrets. listEffectiveTags</code></p>
<p><code>secretmanager. secrets. listTagBindings</code></p>
<p><code>spanner. instances. listEffectiveTags</code></p>
<p><code>spanner. instances. listTagBindings</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>tpu.nodes.listEffectiveTags</code></p>
<p><code>tpu.nodes.listTagBindings</code></p>
<p><code>transcoder. jobTemplates. listEffectiveTags</code></p>
<p><code>transcoder. jobTemplates. listTagBindings</code></p>
<p><code>transcoder. jobs. listEffectiveTags</code></p>
<p><code>transcoder. jobs. listTagBindings</code></p>
<p><code>videostitcher. cdnKeys. listEffectiveTags</code></p>
<p><code>videostitcher. cdnKeys. listTagBindings</code></p>
<p><code>videostitcher. liveConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. liveConfigs. listTagBindings</code></p>
<p><code>videostitcher. slates. listEffectiveTags</code></p>
<p><code>videostitcher. slates. listTagBindings</code></p>
<p><code>videostitcher. vodConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. vodConfigs. listTagBindings</code></p>
<p><code>vmmigration. groups. listEffectiveTags</code></p>
<p><code>vmmigration. groups. listTagBindings</code></p>
<p><code>vmmigration. sources. listEffectiveTags</code></p>
<p><code>vmmigration. sources. listTagBindings</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p>
<p><code>workflows. workflows. listEffectiveTags</code></p>
<p><code>workflows. workflows. listTagBindings</code></p>
<p><code>workstations. workstationClusters. listEffectiveTags</code></p>
<p><code>workstations. workstationClusters. listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td>Resource Manager Viewer
<p>( <code>roles/ resourcemanager.viewer</code> )</p>
<p>Access to view Resource Manager resources</p></td>
<td><p><code>resourcemanager.boundaries.get</code></p>
<p><code>resourcemanager. boundaries. list</code></p>
<p><code>resourcemanager. boundaryConfigs. get</code></p>
<p><code>resourcemanager. capabilities. get</code></p>
<p><code>resourcemanager. capabilityConfigs. get</code></p>
<p><code>resourcemanager. capabilityConfigs. list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagHolds.list</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p></td>
</tr>
<tr class="even">
<td>Folder Creator
<p>( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p>Provides permissions needed to browse the hierarchy and create folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>essentialcontacts.contacts.get</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager. capabilities. get</code></p>
<p><code>resourcemanager.folders.create</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Folder Editor
<p>( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p>Provides permission to modify folders as well as to view a folder's allow policy.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>essentialcontacts.contacts.get</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.capabilities.*</code></p>
<ul>
<li><code>resourcemanager. capabilities. get</code></li>
<li><code>resourcemanager. capabilities. update</code></li>
</ul>
<p><code>resourcemanager.folders.delete</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. folders. searchPolicyBindings</code></p>
<p><code>resourcemanager. folders. undelete</code></p>
<p><code>resourcemanager.folders.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Folder IAM Admin
<p>( <code>roles/ resourcemanager.folderIamAdmin</code> )</p>
<p>Provides permissions to administer allow policies on folders.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>iam.policybindings.*</code></p>
<ul>
<li><code>iam.policybindings.get</code></li>
<li><code>iam.policybindings.list</code></li>
</ul>
<p><code>resourcemanager. folders. createPolicyBinding</code></p>
<p><code>resourcemanager. folders. deletePolicyBinding</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager. folders. searchPolicyBindings</code></p>
<p><code>resourcemanager. folders. setIamPolicy</code></p>
<p><code>resourcemanager. folders. updatePolicyBinding</code></p></td>
</tr>
<tr class="odd">
<td>Folder Mover
<p>( <code>roles/ resourcemanager.folderMover</code> )</p>
<p>Provides permission to move projects and folders into and out of a parent organization or folder.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>resourcemanager.folders.move</code></p>
<p><code>resourcemanager.projects.move</code></p></td>
</tr>
<tr class="even">
<td>Folder Viewer
<p>( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p>Provides permission to get a folder and list the folders and projects below a resource.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>essentialcontacts.contacts.get</code></p>
<p><code>essentialcontacts. contacts. list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager. capabilities. get</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Project Lien Modifier
<p>( <code>roles/ resourcemanager.lienModifier</code> )</p>
<p>Provides access to modify Liens on projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager. projects. updateLiens</code></p></td>
</tr>
<tr class="even">
<td>Organization Viewer
<p>( <code>roles/ resourcemanager.organizationViewer</code> )</p>
<p>Provides access to view an organization.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>resourcemanager. organizations. get</code></p></td>
</tr>
<tr class="odd">
<td>Project Creator
<p>( <code>roles/ resourcemanager.projectCreator</code> )</p>
<p>Provides access to create new projects. Once a user creates a project, they're automatically granted the owner role for that project.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. projects. create</code></p></td>
</tr>
<tr class="even">
<td>Project Deleter
<p>( <code>roles/ resourcemanager.projectDeleter</code> )</p>
<p>Provides access to delete Google Cloud projects.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>resourcemanager. projects. delete</code></p></td>
</tr>
<tr class="odd">
<td>Tag Hold Administrator
<p>( <code>roles/ resourcemanager.tagHoldAdmin</code> )</p>
<p>Access to create, delete and list TagHolds under a TagValue</p></td>
<td><p><code>resourcemanager.tagHolds.*</code></p>
<ul>
<li><code>resourcemanager. tagHolds. create</code></li>
<li><code>resourcemanager. tagHolds. delete</code></li>
<li><code>resourcemanager.tagHolds.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Resource Manager permissions

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
<td><code>resourcemanager. boundaries. associateToCapabilityConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. boundaries. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. boundaries. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager.boundaries.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. boundaries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. boundaries. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. boundaryConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. boundaryConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. capabilities. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. capabilities. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. capabilityConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. capabilityConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. capabilityConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. capabilityConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. capabilityConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager.folders.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. folders. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager.folders.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. folders. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager.folders.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code>roles/ auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code>roles/ auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code>roles/ securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code>roles/ securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code>roles/ securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code>roles/ securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code>roles/ securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code>roles/ privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. folders. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code>roles/ privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.folders.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code>roles/ auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code>roles/ auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code>roles/ securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code>roles/ securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.folders.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderMover">Folder Mover</a> ( <code>roles/ resourcemanager.folderMover</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. folders. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. folders. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.folderServiceAgent">Privileged Access Manager Folder Service Agent</a> ( <code>roles/ privilegedaccessmanager.folderServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. folders. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.folders.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. folders. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderIamAdmin">Folder IAM Admin</a> ( <code>roles/ resourcemanager.folderIamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. hierarchyNodes. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. hierarchyNodes. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. organizations. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. organizations. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. organizations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code>roles/ advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code>roles/ advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code>roles/ auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code>roles/ axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code>roles/ beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code>roles/ beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code>roles/ chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.admin">Support Account Administrator</a> ( <code>roles/ cloudsupport.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code>roles/ commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code>roles/ dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code>roles/ dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code>roles/ policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code>roles/ securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.viewer">Security Posture Viewer</a> ( <code>roles/ securityposture.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code>roles/ assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code>roles/ auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code>roles/ auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code>roles/ auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.subscriptionAdmin">Cloud BeyondCorp Subscription Admin</a> ( <code>roles/ beyondcorp.subscriptionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.subscriptionViewer">Cloud BeyondCorp Subscription Viewer</a> ( <code>roles/ beyondcorp.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.creator">Billing Account Creator</a> ( <code>roles/ billing.creator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code>roles/ chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code>roles/ chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code>roles/ chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.supportSubscriptionEditor">Support Subscription Editor</a> ( <code>roles/ cloudsupport.supportSubscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.supportSubscriptionViewer">Support Subscription Viewer</a> ( <code>roles/ cloudsupport.supportSubscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code>roles/ commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code>roles/ commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code>roles/ compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationViewer">Organization Viewer</a> ( <code>roles/ resourcemanager.organizationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectCreator">Project Creator</a> ( <code>roles/ resourcemanager.projectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code>roles/ securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code>roles/ securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code>roles/ securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code>roles/ securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code>roles/ securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code>roles/ securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code>roles/ securitycenter.sourcesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesViewer">Security Center Sources Viewer</a> ( <code>roles/ securitycenter.sourcesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code>roles/ securityposture.postureDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeploymentsViewer">Security Posture Deployments Viewer</a> ( <code>roles/ securityposture.postureDeploymentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureViewer">Security Posture Resource Viewer</a> ( <code>roles/ securityposture.postureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ciem#ciem.serviceAgent">CIEM Service Agent</a> ( <code>roles/ ciem.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code>roles/ privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. organizations. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code>roles/ chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code>roles/ privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. organizations. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. organizations. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.organizationServiceAgent">Privileged Access Manager Organization Service Agent</a> ( <code>roles/ privilegedaccessmanager.organizationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. organizations. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. associateToCapabilityConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectCreator">Project Creator</a> ( <code>roles/ resourcemanager.projectCreator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. createBillingAssignment</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectManager">Project Billing Manager</a> ( <code>roles/ billing.projectManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. createPolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectDeleter">Project Deleter</a> ( <code>roles/ resourcemanager.projectDeleter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. deleteBillingAssignment</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.projectManager">Project Billing Manager</a> ( <code>roles/ billing.projectManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. deletePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.projects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code>roles/ actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code>roles/ actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin">Advisory Notifications Admin</a> ( <code>roles/ advisorynotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer">Advisory Notifications Viewer</a> ( <code>roles/ advisorynotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.admin">Agent Platform Administrator</a> ( <code>roles/ aiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.editor">Aiplatform Editor</a> ( <code>roles/ aiplatform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a> ( <code>roles/ aiplatform.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.viewer">Agent Platform Viewer</a> ( <code>roles/ aiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code>roles/ alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code>roles/ alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.admin">Androidmanagement Admin</a> ( <code>roles/ androidmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.viewer">Apigee Viewer</a> ( <code>roles/ apigee.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer">Apigeeconnect Viewer</a> ( <code>roles/ apigeeconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.admin">Cloud Apigee Registry Admin</a> ( <code>roles/ apigeeregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.editor">Cloud Apigee Registry Editor</a> ( <code>roles/ apigeeregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.viewer">Cloud Apigee Registry Viewer</a> ( <code>roles/ apigeeregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code>roles/ apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code>roles/ apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code>roles/ applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code>roles/ applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.admin">Artifact Registry Administrator</a> ( <code>roles/ artifactregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code>roles/ artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.repoAdmin">Artifact Registry Repository Administrator</a> ( <code>roles/ artifactregistry.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code>roles/ artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor">Assured OSS Editor</a> ( <code>roles/ assuredoss.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer">Assured OSS Viewer</a> ( <code>roles/ assuredoss.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code>roles/ auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.viewer">Auditmanager Viewer</a> ( <code>roles/ auditmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code>roles/ autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code>roles/ axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code>roles/ baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code>roles/ baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code>roles/ baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin">Batch Administrator</a> ( <code>roles/ batch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer">Batch Viewer</a> ( <code>roles/ batch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.admin">Cloud BeyondCorp Admin</a> ( <code>roles/ beyondcorp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code>roles/ beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code>roles/ beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code>roles/ biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code>roles/ biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code>roles/ biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code>roles/ bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.readSessionUser">BigQuery Read Session User</a> ( <code>roles/ bigquery.readSessionUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceAdmin">BigQuery Resource Admin</a> ( <code>roles/ bigquery.resourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceEditor">BigQuery Resource Editor</a> ( <code>roles/ bigquery.resourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceViewer">BigQuery Resource Viewer</a> ( <code>roles/ bigquery.resourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy#bigquerydatapolicy.editor">BigQuery Data Policy Editor</a> ( <code>roles/ bigquerydatapolicy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code>roles/ bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code>roles/ bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.viewer">Bigtable Viewer</a> ( <code>roles/ bigtable.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code>roles/ blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code>roles/ blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code>roles/ blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code>roles/ blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code>roles/ carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code>roles/ carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code>roles/ chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer">Chat Viewer</a> ( <code>roles/ chat.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code>roles/ chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.editor">Chronicle API Editor</a> ( <code>roles/ chronicle.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.viewer">Chronicle API Viewer</a> ( <code>roles/ chronicle.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code>roles/ chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code>roles/ cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code>roles/ cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.admin">Gemini for Google Cloud Admin</a> ( <code>roles/ cloudaicompanion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.editor">Gemini for Google Cloud Editor</a> ( <code>roles/ cloudaicompanion.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.user">Gemini for Google Cloud User</a> ( <code>roles/ cloudaicompanion.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.viewer">Gemini for Google Cloud Viewer</a> ( <code>roles/ cloudaicompanion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.admin">Cloud Asset Admin</a> ( <code>roles/ cloudasset.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.editor">Cloud Asset Editor</a> ( <code>roles/ cloudasset.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.admin">Cloud Build Admin</a> ( <code>roles/ cloudbuild.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.editor">Cloud Build Editor</a> ( <code>roles/ cloudbuild.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.viewer">Cloud Build Viewer</a> ( <code>roles/ cloudbuild.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code>roles/ cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code>roles/ cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code>roles/ cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code>roles/ clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code>roles/ clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code>roles/ clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code>roles/ cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code>roles/ cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.admin">Cloud KMS Admin</a> ( <code>roles/ cloudkms.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypter">Cloud KMS CryptoKey Encrypter/Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.viewer">Cloud KMS Viewer</a> ( <code>roles/ cloudkms.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code>roles/ cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code>roles/ cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Cloudprivatecatalog Admin</a> ( <code>roles/ cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Cloudprivatecatalog Viewer</a> ( <code>roles/ cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code>roles/ cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer">Cloud Profiler Viewer</a> ( <code>roles/ cloudprofiler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code>roles/ cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.viewer">Cloud Quotas Viewer</a> ( <code>roles/ cloudquotas.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code>roles/ cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code>roles/ cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code>roles/ cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code>roles/ cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code>roles/ cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code>roles/ cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code>roles/ cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code>roles/ cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code>roles/ cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code>roles/ cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code>roles/ cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code>roles/ commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code>roles/ commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code>roles/ commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code>roles/ commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code>roles/ commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code>roles/ commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.admin">Commerce Producer Admin</a> ( <code>roles/ commerceproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.viewer">Commerce Producer Viewer</a> ( <code>roles/ commerceproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code>roles/ confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code>roles/ confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code>roles/ config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code>roles/ config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code>roles/ config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code>roles/ configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code>roles/ configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code>roles/ contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code>roles/ contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterViewer">Kubernetes Engine Cluster Viewer</a> ( <code>roles/ container.clusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.developer">Kubernetes Engine Developer</a> ( <code>roles/ container.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.editor">Kubernetes Engine Editor</a> ( <code>roles/ container.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.viewer">Kubernetes Engine Viewer</a> ( <code>roles/ container.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code>roles/ containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code>roles/ containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code>roles/ containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code>roles/ containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code>roles/ containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code>roles/ contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.admin">Database Center Admin</a> ( <code>roles/ databasecenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.viewer">Database Center Viewer</a> ( <code>roles/ databasecenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code>roles/ databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.editor">Databasesconsole Editor</a> ( <code>roles/ databasesconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.viewer">Databasesconsole Viewer</a> ( <code>roles/ databasesconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code>roles/ dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code>roles/ dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code>roles/ dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code>roles/ datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code>roles/ datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code>roles/ datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code>roles/ datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code>roles/ datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code>roles/ datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code>roles/ datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.admin">Data pipelines Admin</a> ( <code>roles/ datapipelines.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.viewer">Data pipelines Viewer</a> ( <code>roles/ datapipelines.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.viewer">Dataproc Viewer</a> ( <code>roles/ dataproc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code>roles/ dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code>roles/ dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.admin">Dataproc Resource Manager Admin</a> ( <code>roles/ dataprocrm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.viewer">Dataproc Resource Manager Viewer</a> ( <code>roles/ dataprocrm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code>roles/ datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code>roles/ datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code>roles/ datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code>roles/ datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code>roles/ datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code>roles/ datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code>roles/ datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code>roles/ datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.viewer">Data Studio Asset Viewer</a> ( <code>roles/ datastudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code>roles/ dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code>roles/ dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code>roles/ devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code>roles/ devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code>roles/ devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code>roles/ devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.admin">Dialogflow API Admin</a> ( <code>roles/ dialogflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.editor">Discovery Engine Editor</a> ( <code>roles/ discoveryengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code>roles/ discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.viewer">Discovery Engine Viewer</a> ( <code>roles/ discoveryengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code>roles/ domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code>roles/ domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code>roles/ domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.admin">Earth Admin</a> ( <code>roles/ earth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.viewer">Earth Viewer</a> ( <code>roles/ earth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code>roles/ earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.editor">Earthengine Editor</a> ( <code>roles/ earthengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code>roles/ earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code>roles/ edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code>roles/ edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code>roles/ edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code>roles/ edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code>roles/ edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code>roles/ edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code>roles/ enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code>roles/ enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code>roles/ enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.admin">Enterprise Purchasing Admin</a> ( <code>roles/ enterprisepurchasing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.editor">Enterprise Purchasing Editor</a> ( <code>roles/ enterprisepurchasing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.viewer">Enterprise Purchasing Viewer</a> ( <code>roles/ enterprisepurchasing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code>roles/ errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code>roles/ errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code>roles/ errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.admin">Eventarc Admin</a> ( <code>roles/ eventarc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.editor">Eventarc Editor</a> ( <code>roles/ eventarc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.viewer">Eventarc Viewer</a> ( <code>roles/ eventarc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code>roles/ externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code>roles/ externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code>roles/ faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code>roles/ financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code>roles/ financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code>roles/ firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code>roles/ firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code>roles/ firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code>roles/ firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.admin">Firebase App Hosting Admin</a> ( <code>roles/ firebaseapphosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.viewer">Firebase App Hosting Viewer</a> ( <code>roles/ firebaseapphosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code>roles/ firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code>roles/ firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code>roles/ firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code>roles/ firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code>roles/ firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code>roles/ firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code>roles/ firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.admin">Firebase SQL Connect API Admin</a> ( <code>roles/ firebasedataconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.viewer">Firebase SQL Connect API Viewer</a> ( <code>roles/ firebasedataconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code>roles/ firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code>roles/ firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code>roles/ firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code>roles/ firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code>roles/ firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code>roles/ firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code>roles/ firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code>roles/ firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code>roles/ firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code>roles/ firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code>roles/ firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code>roles/ firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code>roles/ firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.admin">Firebase Rules Admin</a> ( <code>roles/ firebaserules.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.viewer">Firebase Rules Viewer</a> ( <code>roles/ firebaserules.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code>roles/ firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.viewer">Cloud Storage for Firebase Viewer</a> ( <code>roles/ firebasestorage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.admin">Firebase AI Logic Admin</a> ( <code>roles/ firebasevertexai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.viewer">Firebase AI Logic Viewer</a> ( <code>roles/ firebasevertexai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.viewer">Fleetengine Viewer</a> ( <code>roles/ fleetengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#flow.admin">Flow Admin</a> ( <code>roles/ flow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#flow.editor">Flow Editor</a> ( <code>roles/ flow.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code>roles/ ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code>roles/ ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code>roles/ gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code>roles/ gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code>roles/ gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code>roles/ gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code>roles/ gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code>roles/ gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code>roles/ gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code>roles/ gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code>roles/ gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code>roles/ gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code>roles/ iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code>roles/ iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code>roles/ iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code>roles/ ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code>roles/ ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code>roles/ ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code>roles/ issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code>roles/ issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code>roles/ krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code>roles/ krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code>roles/ krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code>roles/ kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code>roles/ licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code>roles/ licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code>roles/ lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code>roles/ livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code>roles/ livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code>roles/ livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code>roles/ logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.privateLogViewer">Private Logs Viewer</a> ( <code>roles/ logging.privateLogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.viewer">Logs Viewer</a> ( <code>roles/ logging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code>roles/ looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code>roles/ looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.admin">Google Cloud Managed Lustre Admin</a> ( <code>roles/ lustre.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.viewer">Google Cloud Managed Lustre Viewer</a> ( <code>roles/ lustre.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code>roles/ maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code>roles/ maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code>roles/ managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code>roles/ managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code>roles/ managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code>roles/ managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code>roles/ managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.admin">Mandiant Admin</a> ( <code>roles/ mandiant.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.viewer">Mandiant Viewer</a> ( <code>roles/ mandiant.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code>roles/ mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code>roles/ mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code>roles/ mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code>roles/ mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code>roles/ mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code>roles/ marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code>roles/ marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code>roles/ marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code>roles/ mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code>roles/ mcp.toolUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code>roles/ memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code>roles/ memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code>roles/ memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.viewer">Memorystore Viewer</a> ( <code>roles/ memorystore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code>roles/ migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code>roles/ migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.admin">AI Platform Admin</a> ( <code>roles/ ml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.viewer">AI Platform Viewer</a> ( <code>roles/ ml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin">Navigation Connect Admin</a> ( <code>roles/ navigationconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.viewer">Navigation Connect Viewer</a> ( <code>roles/ navigationconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code>roles/ nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code>roles/ nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code>roles/ nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code>roles/ netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code>roles/ netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code>roles/ netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.editor">Network Connectivity Editor</a> ( <code>roles/ networkconnectivity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.admin">Networksecurity Admin</a> ( <code>roles/ networksecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.editor">Networksecurity Editor</a> ( <code>roles/ networksecurity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.viewer">Networksecurity Viewer</a> ( <code>roles/ networksecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.admin">Network Services Admin</a> ( <code>roles/ networkservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.editor">Network Services Editor</a> ( <code>roles/ networkservices.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.viewer">Network Services Viewer</a> ( <code>roles/ networkservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code>roles/ oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ondemandscanning#ondemandscanning.viewer">On-Demand Scanning Viewer</a> ( <code>roles/ ondemandscanning.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code>roles/ opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.viewer">Opsconfigmonitoring Viewer</a> ( <code>roles/ opsconfigmonitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code>roles/ parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code>roles/ parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code>roles/ parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code>roles/ parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code>roles/ parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code>roles/ paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code>roles/ paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code>roles/ policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code>roles/ policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code>roles/ policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code>roles/ policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code>roles/ policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.admin">Privileged Access Manager Admin</a> ( <code>roles/ privilegedaccessmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code>roles/ privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.viewer">Privileged Access Manager Viewer</a> ( <code>roles/ privilegedaccessmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code>roles/ proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code>roles/ proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code>roles/ proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin">Publicca Admin</a> ( <code>roles/ publicca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.admin">Pub/Sub Admin</a> ( <code>roles/ pubsub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.editor">Pub/Sub Editor</a> ( <code>roles/ pubsub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.viewer">Pub/Sub Viewer</a> ( <code>roles/ pubsub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code>roles/ readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code>roles/ readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code>roles/ recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code>roles/ recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code>roles/ recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.admin">Recommender Admin</a> ( <code>roles/ recommender.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.editor">Recommender Editor</a> ( <code>roles/ recommender.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.viewer">Recommender Viewer</a> ( <code>roles/ recommender.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.editor">Cloud Memorystore Redis Editor</a> ( <code>roles/ redis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.viewer">Cloud Memorystore Redis Viewer</a> ( <code>roles/ redis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code>roles/ redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code>roles/ redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code>roles/ resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code>roles/ retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code>roles/ retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code>roles/ retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code>roles/ riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code>roles/ riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code>roles/ riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code>roles/ rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code>roles/ rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code>roles/ routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code>roles/ routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer">Route Optimization Viewer</a> ( <code>roles/ routeoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code>roles/ run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code>roles/ run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code>roles/ run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code>roles/ run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code>roles/ runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code>roles/ runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code>roles/ runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code>roles/ runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer">SaaS Config Viewer</a> ( <code>roles/ saasconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code>roles/ saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code>roles/ saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.editor">Secretmanager Editor</a> ( <code>roles/ secretmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretAccessor">Secret Manager Secret Accessor</a> ( <code>roles/ secretmanager.secretAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code>roles/ secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin">Secured Landing Zone Admin</a> ( <code>roles/ securedlandingzone.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.viewer">Secured Landing Zone Viewer</a> ( <code>roles/ securedlandingzone.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code>roles/ serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code>roles/ serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code>roles/ serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.admin">Servicehealth Admin</a> ( <code>roles/ servicehealth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.viewer">Personalized Service Health Viewer</a> ( <code>roles/ servicehealth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code>roles/ servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code>roles/ servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code>roles/ servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code>roles/ servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code>roles/ servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code>roles/ source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code>roles/ spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code>roles/ spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code>roles/ stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.admin">Storage Batch Operations Admin</a> ( <code>roles/ storagebatchoperations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.viewer">Storage Batch Operations Viewer</a> ( <code>roles/ storagebatchoperations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code>roles/ storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code>roles/ storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code>roles/ storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code>roles/ storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code>roles/ stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code>roles/ stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.admin">Subscribewithgoogledeveloper Admin</a> ( <code>roles/ subscribewithgoogledeveloper.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.viewer">Subscribewithgoogledeveloper Viewer</a> ( <code>roles/ subscribewithgoogledeveloper.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code>roles/ telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code>roles/ telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code>roles/ telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.admin">TPU Admin</a> ( <code>roles/ tpu.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.editor">TPU Editor</a> ( <code>roles/ tpu.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.viewer">TPU Viewer</a> ( <code>roles/ tpu.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code>roles/ trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code>roles/ trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code>roles/ transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code>roles/ transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code>roles/ transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code>roles/ transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code>roles/ transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code>roles/ translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code>roles/ translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code>roles/ videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code>roles/ videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin">Visual Inspection AI Admin</a> ( <code>roles/ visualinspection.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code>roles/ vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code>roles/ workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code>roles/ workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code>roles/ workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code>roles/ workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code>roles/ workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code>roles/ workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code>roles/ accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.entityTypeOwner">Agent Platform Feature Store EntityType owner</a> ( <code>roles/ aiplatform.entityTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreAdmin">Agent Platform Feature Store Admin</a> ( <code>roles/ aiplatform.featurestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataViewer">Agent Platform Feature Store Data Viewer</a> ( <code>roles/ aiplatform.featurestoreDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataWriter">Agent Platform Feature Store Data Writer</a> ( <code>roles/ aiplatform.featurestoreDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreResourceViewer">Agent Platform Feature Store Resource Viewer</a> ( <code>roles/ aiplatform.featurestoreResourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreUser">Agent Platform Feature Store User</a> ( <code>roles/ aiplatform.featurestoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code>roles/ alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code>roles/ alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsEditor">Apigee Analytics Editor</a> ( <code>roles/ apigee.analyticsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsViewer">Apigee Analytics Viewer</a> ( <code>roles/ apigee.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code>roles/ apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code>roles/ apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.monetizationAdmin">Apigee Monetization Admin</a> ( <code>roles/ apigee.monetizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.portalAdmin">Apigee Portal Admin</a> ( <code>roles/ apigee.portalAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code>roles/ apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code>roles/ apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code>roles/ apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.spaceConsoleUser">Apigee Space Console User</a> ( <code>roles/ apigee.spaceConsoleUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.worker">Cloud Apigee Registry Worker</a> ( <code>roles/ apigeeregistry.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code>roles/ apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code>roles/ appengine.appCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code>roles/ applianceactivation.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code>roles/ applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code>roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushRepoAdmin">Artifact Registry Create-on-Push Repository Administrator</a> ( <code>roles/ artifactregistry.createOnPushRepoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.createOnPushWriter">Artifact Registry Create-on-Push Writer</a> ( <code>roles/ artifactregistry.createOnPushWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.reader">Artifact Registry Reader</a> ( <code>roles/ artifactregistry.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.writer">Artifact Registry Writer</a> ( <code>roles/ artifactregistry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code>roles/ assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code>roles/ auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.predictor">AutoML Predictor</a> ( <code>roles/ automl.predictor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code>roles/ baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code>roles/ baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code>roles/ baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor">Batch Job Editor</a> ( <code>roles/ batch.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer">Batch Job Viewer</a> ( <code>roles/ batch.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor">Batch ResourceAllowance Editor</a> ( <code>roles/ batch.resourceAllowancesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer">Batch ResourceAllowance Viewer</a> ( <code>roles/ batch.resourceAllowancesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code>roles/ biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code>roles/ bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code>roles/ binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.dataGovernor">Chronicle API Data Governor</a> ( <code>roles/ chronicle.dataGovernor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationAdmin">Chronicle API Federation Admin</a> ( <code>roles/ chronicle.federationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationViewer">Chronicle API Federation Viewer</a> ( <code>roles/ chronicle.federationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.limitedViewer">Chronicle API Limited Viewer</a> ( <code>roles/ chronicle.limitedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.restrictedDataAccessViewer">Chronicle API Restricted Data Access Viewer</a> ( <code>roles/ chronicle.restrictedDataAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code>roles/ chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarRemoteAgent">Chronicle SOAR Remote Agent</a> ( <code>roles/ chronicle.soarRemoteAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code>roles/ chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code>roles/ chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesAdmin">Code Repository Indexes Admin</a> ( <code>roles/ cloudaicompanion.codeRepositoryIndexesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesViewer">Code Repository Indexes Viewer</a> ( <code>roles/ cloudaicompanion.codeRepositoryIndexesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code>roles/ cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code>roles/ cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code>roles/ cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionAdmin">Cloud Build Connection Admin</a> ( <code>roles/ cloudbuild.connectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionViewer">Cloud Build Connection Viewer</a> ( <code>roles/ cloudbuild.connectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsEditor">Cloud Build Integrations Editor</a> ( <code>roles/ cloudbuild.integrationsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsOwner">Cloud Build Integrations Owner</a> ( <code>roles/ cloudbuild.integrationsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsViewer">Cloud Build Integrations Viewer</a> ( <code>roles/ cloudbuild.integrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolEditor">Cloud Build WorkerPool Editor</a> ( <code>roles/ cloudbuild.workerPoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolOwner">Cloud Build WorkerPool Owner</a> ( <code>roles/ cloudbuild.workerPoolOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolViewer">Cloud Build WorkerPool Viewer</a> ( <code>roles/ cloudbuild.workerPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code>roles/ clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code>roles/ clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code>roles/ clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code>roles/ clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code>roles/ clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code>roles/ clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code>roles/ clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code>roles/ cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code>roles/ cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code>roles/ cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code>roles/ cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypter">Cloud KMS CryptoKey Decrypter</a> ( <code>roles/ cloudkms.cryptoKeyDecrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypter">Cloud KMS CryptoKey Encrypter</a> ( <code>roles/ cloudkms.cryptoKeyEncrypter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoOperator">Cloud KMS Crypto Operator</a> ( <code>roles/ cloudkms.cryptoOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.decapsulator">Cloud KMS CryptoKey Decapsulator</a> ( <code>roles/ cloudkms.decapsulator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code>roles/ cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code>roles/ cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.importer">Cloud KMS Importer</a> ( <code>roles/ cloudkms.importer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.publicKeyViewer">Cloud KMS CryptoKey Public Key Viewer</a> ( <code>roles/ cloudkms.publicKeyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signer">Cloud KMS CryptoKey Signer</a> ( <code>roles/ cloudkms.signer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.signerVerifier">Cloud KMS CryptoKey Signer/Verifier</a> ( <code>roles/ cloudkms.signerVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.verifier">Cloud KMS CryptoKey Verifier</a> ( <code>roles/ cloudkms.verifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager">Velostrata Manager</a> ( <code>roles/ cloudmigration.inframanager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code>roles/ cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code>roles/ cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code>roles/ cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportEditor">Advisory Support Editor</a> ( <code>roles/ cloudsupport.advisorySupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportViewer">Advisory Support Viewer</a> ( <code>roles/ cloudsupport.advisorySupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code>roles/ cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code>roles/ cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code>roles/ cloudtasks.enqueuer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code>roles/ cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskDeleter">Cloud Tasks Task Deleter</a> ( <code>roles/ cloudtasks.taskDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code>roles/ cloudtasks.taskRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code>roles/ cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code>roles/ cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code>roles/ commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code>roles/ commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code>roles/ commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code>roles/ commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code>roles/ commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code>roles/ commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.publicIpAdmin">Compute Public IP Admin</a> ( <code>roles/ compute.publicIpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyAdmin">Compute VM extension policy admin</a> ( <code>roles/ compute.vmExtensionPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyViewer">Compute VM extension policy viewer</a> ( <code>roles/ compute.vmExtensionPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code>roles/ compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code>roles/ configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code>roles/ configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code>roles/ configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.cloudKmsKeyUser">Kubernetes Engine KMS Crypto Key User</a> ( <code>roles/ container.cloudKmsKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code>roles/ containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code>roles/ containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code>roles/ containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code>roles/ containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code>roles/ contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code>roles/ contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code>roles/ contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code>roles/ contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code>roles/ contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryAdmin">Studio Query Admin</a> ( <code>roles/ databasesconsole.studioQueryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryUser">Studio Query User</a> ( <code>roles/ databasesconsole.studioQueryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code>roles/ dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code>roles/ datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code>roles/ datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code>roles/ datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.invoker">Data pipelines Invoker</a> ( <code>roles/ datapipelines.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code>roles/ dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code>roles/ dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.projects.user">Dataprep User</a> ( <code>roles/ dataprep.projects.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessViewer">Dataproc Serverless Viewer</a> ( <code>roles/ dataproc.serverlessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code>roles/ datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code>roles/ datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code>roles/ datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code>roles/ datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code>roles/ datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code>roles/ datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code>roles/ datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.workspaceViewer">Data Studio Workspace Viewer</a> ( <code>roles/ datastudio.workspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code>roles/ dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleAgentEditor">Dialogflow Console Agent Editor</a> ( <code>roles/ dialogflow.consoleAgentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.reader">Dialogflow API Reader</a> ( <code>roles/ dialogflow.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceEditor">Gemini Enterprise Editor</a> ( <code>roles/ discoveryengine.agentspaceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceRestrictedUser">Gemini Enterprise Restricted User</a> ( <code>roles/ discoveryengine.agentspaceRestrictedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code>roles/ discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceViewer">Gemini Enterprise Viewer</a> ( <code>roles/ discoveryengine.agentspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmOwner">Cloud NotebookLM Admin</a> ( <code>roles/ discoveryengine.notebookLmOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmUser">Cloud NotebookLM User</a> ( <code>roles/ discoveryengine.notebookLmUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code>roles/ discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsAdmin">Earth Subscriptions Administrator</a> ( <code>roles/ earth.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsViewer">Earth Subscriptions Viewer</a> ( <code>roles/ earth.subscriptionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.appsPublisher">Earth Engine Apps Publisher</a> ( <code>roles/ earthengine.appsPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code>roles/ earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code>roles/ edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.offlineCredentialUser">Edge Container Cluster offline Credential User</a> ( <code>roles/ edgecontainer.offlineCredentialUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.connectionPublisher">Eventarc Connection Publisher</a> ( <code>roles/ eventarc.connectionPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.developer">Eventarc Developer</a> ( <code>roles/ eventarc.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.publisher">Eventarc Publisher</a> ( <code>roles/ eventarc.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code>roles/ faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.developer">Firebase App Hosting Developer</a> ( <code>roles/ firebaseapphosting.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrash.symbolMappingsAdmin">Firebase Crash Symbol Uploader</a> ( <code>roles/ firebasecrash.symbolMappingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code>roles/ firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code>roles/ fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code>roles/ fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code>roles/ fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code>roles/ fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code>roles/ gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code>roles/ gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code>roles/ gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code>roles/ gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code>roles/ gsuiteaddons.tester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code>roles/ healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code>roles/ healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code>roles/ healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code>roles/ healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code>roles/ healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code>roles/ healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code>roles/ healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code>roles/ healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code>roles/ healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code>roles/ healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code>roles/ healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code>roles/ healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code>roles/ healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code>roles/ healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code>roles/ healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code>roles/ healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code>roles/ healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code>roles/ healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code>roles/ healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code>roles/ healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code>roles/ healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code>roles/ healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code>roles/ healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code>roles/ healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code>roles/ healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code>roles/ healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code>roles/ healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code>roles/ healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code>roles/ healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code>roles/ healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code>roles/ healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.certificateViewer">Certificate Viewer</a> ( <code>roles/ integrations.certificateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code>roles/ issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code>roles/ issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code>roles/ issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code>roles/ issuerswitch.issuerParticipantsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code>roles/ issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code>roles/ issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code>roles/ issuerswitch.rulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code>roles/ issuerswitch.transactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code>roles/ logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code>roles/ looker.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code>roles/ lookerstudio.lookerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code>roles/ lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code>roles/ managedflink.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code>roles/ managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code>roles/ managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code>roles/ managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code>roles/ managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code>roles/ managedidentities.peeringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementEditor">Mandiant Attack Surface Management Editor</a> ( <code>roles/ mandiant.attackSurfaceManagementEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementViewer">Mandiant Attack Surface Management Viewer</a> ( <code>roles/ mandiant.attackSurfaceManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringEditor">Mandiant Digital Threat Monitoring Editor</a> ( <code>roles/ mandiant.digitalThreatMonitoringEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringViewer">Mandiant Digital Threat Monitoring Viewer</a> ( <code>roles/ mandiant.digitalThreatMonitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandEditor">Mandiant Expertise On Demand Editor</a> ( <code>roles/ mandiant.expertiseOnDemandEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandViewer">Mandiant Expertise On Demand Viewer</a> ( <code>roles/ mandiant.expertiseOnDemandViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelEditor">Mandiant Threat Intel Editor</a> ( <code>roles/ mandiant.threatIntelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelViewer">Mandiant Threat Intel Viewer</a> ( <code>roles/ mandiant.threatIntelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationEditor">Mandiant Validation Editor</a> ( <code>roles/ mandiant.validationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationViewer">Mandiant Validation Viewer</a> ( <code>roles/ mandiant.validationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code>roles/ migrationcenter.discoveryClientRegistrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.developer">AI Platform Developer</a> ( <code>roles/ ml.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code>roles/ modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesAdmin">Monitoring Metrics Scopes Admin</a> ( <code>roles/ monitoring.metricsScopesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesViewer">Monitoring Metrics Scopes Viewer</a> ( <code>roles/ monitoring.metricsScopesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code>roles/ nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code>roles/ nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code>roles/ nestconsole.homeDeveloperViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.consumerNetworkAdmin">Service Automation Consumer Network Admin</a> ( <code>roles/ networkconnectivity.consumerNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.groupAdmin">Group Admin</a> ( <code>roles/ networkconnectivity.groupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubAdmin">Hub &amp; Spoke Admin</a> ( <code>roles/ networkconnectivity.hubAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubViewer">Hub &amp; Spoke Viewer</a> ( <code>roles/ networkconnectivity.hubViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigAdmin">Multicloud Data Transfer Config Admin</a> ( <code>roles/ networkconnectivity.multicloudDataTransferConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigViewer">Multicloud Data Transfer Config Viewer</a> ( <code>roles/ networkconnectivity.multicloudDataTransferConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationAdmin">Destination Admin</a> ( <code>roles/ networkconnectivity.multicloudDataTransferDestinationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationViewer">Destination Viewer</a> ( <code>roles/ networkconnectivity.multicloudDataTransferDestinationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointAdmin">Regional Endpoint Admin</a> ( <code>roles/ networkconnectivity.regionalEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointViewer">Regional Endpoint Viewer</a> ( <code>roles/ networkconnectivity.regionalEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceClassUser">Service Class User</a> ( <code>roles/ networkconnectivity.serviceClassUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceProducerAdmin">Service Automation Service Producer Admin</a> ( <code>roles/ networkconnectivity.serviceProducerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.spokeAdmin">Spoke Admin</a> ( <code>roles/ networkconnectivity.spokeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportAdmin">Transport Admin</a> ( <code>roles/ networkconnectivity.transportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportViewer">Transport Viewer</a> ( <code>roles/ networkconnectivity.transportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorAdmin">DNS Threat Detector Admin</a> ( <code>roles/ networksecurity.dnsThreatDetectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorViewer">DNS Threat Detector Viewer</a> ( <code>roles/ networksecurity.dnsThreatDetectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.firewallEndpointAdmin">Firewall Endpoint Admin</a> ( <code>roles/ networksecurity.firewallEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentAdmin">Intercept Deployment Admin</a> ( <code>roles/ networksecurity.interceptDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentViewer">Intercept Deployment Viewer</a> ( <code>roles/ networksecurity.interceptDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointAdmin">Intercept Endpoint Admin</a> ( <code>roles/ networksecurity.interceptEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointViewer">Intercept Endpoint Viewer</a> ( <code>roles/ networksecurity.interceptEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentAdmin">Mirroring Deployment Admin</a> ( <code>roles/ networksecurity.mirroringDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentViewer">Mirroring Deployment Viewer</a> ( <code>roles/ networksecurity.mirroringDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointAdmin">Mirroring Endpoint Admin</a> ( <code>roles/ networksecurity.mirroringEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointViewer">Mirroring Endpoint Viewer</a> ( <code>roles/ networksecurity.mirroringEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.securityProfileAdmin">Security Profile Admin</a> ( <code>roles/ networksecurity.securityProfileAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.GoogleTagGatewayPolicyAdmin">Google Tag Gateway Admin</a> ( <code>roles/ networkservices.GoogleTagGatewayPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code>roles/ networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code>roles/ networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code>roles/ osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code>roles/ osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code>roles/ osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code>roles/ osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code>roles/ osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code>roles/ osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code>roles/ osconfig.projectFeatureSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code>roles/ osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code>roles/ parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code>roles/ parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code>roles/ parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code>roles/ parametermanager.parameterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.templateVersionManager">Parameter Manager Template Version Manager</a> ( <code>roles/ parametermanager.templateVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.templateViewer">Parameter Manager Template Viewer</a> ( <code>roles/ parametermanager.templateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code>roles/ paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code>roles/ paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.productViewer">Payments Reseller Products Viewer</a> ( <code>roles/ paymentsresellersubscription.productViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.promotionViewer">Payments Reseller Promotions Viewer</a> ( <code>roles/ paymentsresellersubscription.promotionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code>roles/ paymentsresellersubscription.subscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionViewer">Payments Reseller Subscriptions Viewer</a> ( <code>roles/ paymentsresellersubscription.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code>roles/ proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code>roles/ proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code>roles/ proximitybeacon.attachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code>roles/ proximitybeacon.beaconEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator">External Account Key Creator</a> ( <code>roles/ publicca.externalAccountKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code>roles/ recaptchaenterprise.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbAdmin">AlloyDB Recommender Admin</a> ( <code>roles/ recommender.alloydbAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbViewer">AlloyDB Recommender Viewer</a> ( <code>roles/ recommender.alloydbViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostAdmin">App Engine Version Cost Recommender Admin</a> ( <code>roles/ recommender.appengineversioncostAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostViewer">App Engine Version Cost Recommender Viewer</a> ( <code>roles/ recommender.appengineversioncostViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsAdmin">BigQuery Slot Recommender Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectAdmin">BigQuery Recommender Project Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectViewer">BigQuery Recommender Project Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsViewer">BigQuery Slot Recommender Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewAdmin">BigQuery Materialized View Recommender Admin</a> ( <code>roles/ recommender.bigqueryMaterializedViewAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewViewer">BigQuery Materialized View Recommender Viewer</a> ( <code>roles/ recommender.bigqueryMaterializedViewViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterAdmin">BigQuery Partitioning Clustering Recommender Admin</a> ( <code>roles/ recommender.bigqueryPartitionClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterViewer">BigQuery Partitioning Clustering Recommender Viewer</a> ( <code>roles/ recommender.bigqueryPartitionClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceAdmin">Bigtable Cluster Performance Recommender Admin</a> ( <code>roles/ recommender.bigtableClusterPerformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceViewer">Bigtable Cluster Performance Recommender Viewer</a> ( <code>roles/ recommender.bigtableClusterPerformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsAdmin">Cloud Asset Insights Admin</a> ( <code>roles/ recommender.cloudAssetInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsViewer">Cloud Asset Insights Viewer</a> ( <code>roles/ recommender.cloudAssetInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationAdmin">Cloud Cost General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudCostRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationViewer">Cloud Cost General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudCostRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationAdmin">Cloud Deprecation General Recommender Admin</a> ( <code>roles/ recommender.cloudDeprecationRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationViewer">Cloud Deprecation General Recommender Viewer</a> ( <code>roles/ recommender.cloudDeprecationRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationAdmin">Cloud Manageability General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudManageabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationViewer">Cloud Manageability General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudManageabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationAdmin">Cloud Performance General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudPerformanceRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationViewer">Cloud Performance General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudPerformanceRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationAdmin">Cloud Reliability General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudReliabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationViewer">Cloud Reliability General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudReliabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationAdmin">Cloud Security General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudSecurityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationViewer">Cloud Security General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudSecurityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlAdmin">Cloud SQL Recommender Admin</a> ( <code>roles/ recommender.cloudsqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlViewer">Cloud SQL Recommender Viewer</a> ( <code>roles/ recommender.cloudsqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeAdmin">Compute Recommender Admin</a> ( <code>roles/ recommender.computeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeViewer">Compute Recommender Viewer</a> ( <code>roles/ recommender.computeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisAdmin">GKE Diagnosis Recommender Admin</a> ( <code>roles/ recommender.containerDiagnosisAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisViewer">GKE Diagnosis Recommender Viewer</a> ( <code>roles/ recommender.containerDiagnosisViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsAdmin">Dataflow Diagnostics Admin</a> ( <code>roles/ recommender.dataflowDiagnosticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsViewer">Dataflow Diagnostics Viewer</a> ( <code>roles/ recommender.dataflowDiagnosticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingAdmin">Error Reporting Recommender Admin</a> ( <code>roles/ recommender.errorReportingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingViewer">Error Reporting Recommender Viewer</a> ( <code>roles/ recommender.errorReportingViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesAdmin">Firestore Database Firebase rules Recommender Admin</a> ( <code>roles/ recommender.firestoredatabasefirebaserulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesViewer">Firestore Database Firebase rules Recommender Viewer</a> ( <code>roles/ recommender.firestoredatabasefirebaserulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityAdmin">Firestore Database Reliability Recommender Admin</a> ( <code>roles/ recommender.firestoredatabasereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityViewer">Firestore Database Reliability Recommender Viewer</a> ( <code>roles/ recommender.firestoredatabasereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallAdmin">Firewall Recommender Admin</a> ( <code>roles/ recommender.firewallAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallViewer">Firewall Recommender Viewer</a> ( <code>roles/ recommender.firewallViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpAdmin">Google Maps Platform Insights/Recommendations Admin</a> ( <code>roles/ recommender.gmpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpViewer">Google Maps Platform Insights/Recommendations Viewer</a> ( <code>roles/ recommender.gmpViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code>roles/ recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code>roles/ recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskAdmin">IAM Policy Change Risk Recommender Admin</a> ( <code>roles/ recommender.iampolicychangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskViewer">IAM Policy Change Risk Recommender Viewer</a> ( <code>roles/ recommender.iampolicychangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityAdmin">Memorystore Manageability Recommender Admin</a> ( <code>roles/ recommender.memorystoremanageabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityViewer">Memorystore Manageability Recommender Viewer</a> ( <code>roles/ recommender.memorystoremanageabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceAdmin">Memorystore Performance Recommender Admin</a> ( <code>roles/ recommender.memorystoreperformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceViewer">Memorystore Performance Recommender Viewer</a> ( <code>roles/ recommender.memorystoreperformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityAdmin">Memorystore Reliability Recommender Admin</a> ( <code>roles/ recommender.memorystorereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityViewer">Memorystore Reliability Recommender Viewer</a> ( <code>roles/ recommender.memorystorereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerAdmin">Network Analyzer Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlAdmin">Network Analyzer Cloud SQL Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerCloudSqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlViewer">Network Analyzer Cloud SQL Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerCloudSqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteAdmin">Network Analyzer Dynamic Route Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerDynamicRouteAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteViewer">Network Analyzer Dynamic Route Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerDynamicRouteViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityAdmin">Network Analyzer GKE Connectivity Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityViewer">Network Analyzer GKE Connectivity Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressAdmin">Network Analyzer GKE IP Address Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressViewer">Network Analyzer GKE IP Address Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountAdmin">Network Analyzer GKE Service Account Insights Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeServiceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountViewer">Network Analyzer GKE Service Account Insights Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeServiceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressAdmin">Network Analyzer IP Address Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressViewer">Network Analyzer IP Address Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerAdmin">Network Analyzer Load Balancer Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerLoadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerViewer">Network Analyzer Load Balancer Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerLoadBalancerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerViewer">Network Analyzer Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityAdmin">Network Analyzer VPC Connectivity Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerVpcConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityViewer">Network Analyzer VPC Connectivity Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerVpcConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyAdmin">Org Policy Recommender Admin</a> ( <code>roles/ recommender.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyViewer">Org Policy Recommender Viewer</a> ( <code>roles/ recommender.orgPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionAdmin">Product Suggestion Recommenders Admin</a> ( <code>roles/ recommender.productSuggestionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionViewer">Product Suggestion Recommenders Viewer</a> ( <code>roles/ recommender.productSuggestionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudAdmin">Project Usage Commitment Recommender Admin</a> ( <code>roles/ recommender.projectCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudViewer">Project Usage Commitment Recommender Viewer</a> ( <code>roles/ recommender.projectCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilAdmin">Project Utilization Recommender Admin</a> ( <code>roles/ recommender.projectUtilAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilViewer">Project Utilization Recommender Viewer</a> ( <code>roles/ recommender.projectUtilViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentChangeConfigAdmin">RecentChange RecommenderConfig Admin</a> ( <code>roles/ recommender.recentChangeConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskAdmin">Recent Change Risk Recommender Admin</a> ( <code>roles/ recommender.recentchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskViewer">Recent Change Risk Recommender Viewer</a> ( <code>roles/ recommender.recentchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitAdmin">Service Limit Recommender Admin</a> ( <code>roles/ recommender.serviceLimitAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitViewer">Service Limit Recommender Viewer</a> ( <code>roles/ recommender.serviceLimitViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskAdmin">Service Account Change Risk Recommender Admin</a> ( <code>roles/ recommender.serviceaccntchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskViewer">Service Account Change Risk Recommender Viewer</a> ( <code>roles/ recommender.serviceaccntchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerAdmin">Spanner Project Reliability Recommender Admin</a> ( <code>roles/ recommender.spannerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerViewer">Spanner Project Reliability Recommender Viewer</a> ( <code>roles/ recommender.spannerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code>roles/ retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code>roles/ retail.merchantCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code>roles/ riskmanager.reviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code>roles/ rma.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code>roles/ roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code>roles/ roads.roadsSelectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code>roles/ runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code>roles/ runapps.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionAdder">Secret Manager Secret Version Adder</a> ( <code>roles/ secretmanager.secretVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code>roles/ secretmanager.secretVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code>roles/ securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code>roles/ securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code>roles/ securedlandingzone.overwatchViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code>roles/ securesourcemanager.repoCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code>roles/ securesourcemanager.repoPullRequestApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code>roles/ securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code>roles/ securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code>roles/ securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code>roles/ securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code>roles/ securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code>roles/ servicedirectory.networkAttacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code>roles/ servicedirectory.pscAuthorizedService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code>roles/ spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code>roles/ spanner.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.viewer">Stackdriver Accounts Viewer</a> ( <code>roles/ stackdriver.accounts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code>roles/ storage.insightsCollectorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code>roles/ storageinsights.analyst</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code>roles/ storagetransfer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code>roles/ stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code>roles/ stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code>roles/ stream.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.developer">Subscribe with Google Developer</a> ( <code>roles/ subscribewithgoogledeveloper.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier1">Telco Automation Tier 1 Operations Admin</a> ( <code>roles/ telcoautomation.opsAdminTier1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.opsAdminTier4">Telco Automation Tier 4 Operations Admin</a> ( <code>roles/ telcoautomation.opsAdminTier4</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code>roles/ threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code>roles/ threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code>roles/ threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code>roles/ threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code>roles/ threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code>roles/ threatintelligence.ctemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code>roles/ translationhub.portalUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code>roles/ videostitcher.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code>roles/ workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code>roles/ workloadcertificate.registrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code>roles/ workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code>roles/ workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code>roles/ workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code>roles/ workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code>roles/ workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code>roles/ workstations.workstationLimitExemptedCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.tuningServiceAgent">Vertex AI Tuning Service Agent</a> ( <code>roles/ aiplatform.tuningServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.serviceAgent">Analytics Hub Service Agent</a> ( <code>roles/ analyticshub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.serviceAgent">Bare Metal Solution Service Agent</a> ( <code>roles/ baremetalsolution.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.serviceAgent">BigQuery Migration Service Agent</a> ( <code>roles/ bigquerymigration.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code>roles/ compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code>roles/ containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a> ( <code>roles/ containerthreatdetection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code>roles/ dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code>roles/ gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code>roles/ gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement#gkedataplanemanagement.warpRunServiceAgent">Warp Run Service Agent</a> ( <code>roles/ gkedataplanemanagement.warpRunServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code>roles/ krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsControlPlaneServiceAgent">KubeRun Events Control Plane Service Agent</a> ( <code>roles/ kuberun.eventsControlPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsDataPlaneServiceAgent">KubeRun Events Data Plane Service Agent</a> ( <code>roles/ kuberun.eventsDataPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a> ( <code>roles/ looker.restrictedServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.serviceAgent">(Legacy) Looker Service Agent</a> ( <code>roles/ looker.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code>roles/ osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a> ( <code>roles/ parallelstore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code>roles/ privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code>roles/ rapidmigrationassessment.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code>roles/ securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackSurfaceManagementScannerServiceAgent">Attack Surface Management Scanner Service Agent</a> ( <code>roles/ securitycenter.attackSurfaceManagementScannerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spectrumsas#spectrumsas.serviceAgent">Spectrum SAS Service Agent</a> ( <code>roles/ spectrumsas.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.serviceAgent">Serverless VPC Access Service Agent</a> ( <code>roles/ vpcaccess.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.editor">Data Studio Asset Editor</a> ( <code>roles/ datastudio.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleAdmin">Role Administrator</a> ( <code>roles/ iam.roleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.roleViewer">Role Viewer</a> ( <code>roles/ iam.roleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code>roles/ apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code>roles/ apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code>roles/ apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.containerRegistryMigrationAdmin">Container Registry -&gt; Artifact Registry Migration Admin</a> ( <code>roles/ artifactregistry.containerRegistryMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code>roles/ compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contentManager">Data Studio Workspace Content Manager</a> ( <code>roles/ datastudio.contentManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.contributor">Data Studio Workspace Contributor</a> ( <code>roles/ datastudio.contributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.manager">Data Studio Workspace Manager</a> ( <code>roles/ datastudio.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.lookerAdmin">Looker Admin</a> ( <code>roles/ lookerstudio.lookerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.crossProjectServiceAgent">GKE Hub Cross Project Service Agent</a> ( <code>roles/ gkehub.crossProjectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code>roles/ privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.projects.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.admin">Access Approval Admin</a> ( <code>roles/ accessapproval.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.editor">Access Approval Editor</a> ( <code>roles/ accessapproval.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.viewer">Access Approval Viewer</a> ( <code>roles/ accessapproval.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code>roles/ accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code>roles/ accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code>roles/ accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code>roles/ accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Admin">Actions Admin</a> ( <code>roles/ actions.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/actions#actions.Viewer">Actions Viewer</a> ( <code>roles/ actions.Viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.admin">Agent Platform Administrator</a> ( <code>roles/ aiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.editor">Aiplatform Editor</a> ( <code>roles/ aiplatform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.user">Agent Platform User</a> ( <code>roles/ aiplatform.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.viewer">Agent Platform Viewer</a> ( <code>roles/ aiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.admin">AlloyDB Admin</a> ( <code>roles/ alloydb.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.editor">AlloyDB Editor</a> ( <code>roles/ alloydb.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.viewer">AlloyDB Viewer</a> ( <code>roles/ alloydb.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.admin">Analytics Hub Admin</a> ( <code>roles/ analyticshub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.editor">Analytics Hub Editor</a> ( <code>roles/ analyticshub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.viewer">Analytics Hub Viewer</a> ( <code>roles/ analyticshub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/androidmanagement#androidmanagement.admin">Androidmanagement Admin</a> ( <code>roles/ androidmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.editor">Apigee Editor</a> ( <code>roles/ apigee.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.viewer">Apigee Viewer</a> ( <code>roles/ apigee.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer">Apigeeconnect Viewer</a> ( <code>roles/ apigeeconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.admin">Cloud Apigee Registry Admin</a> ( <code>roles/ apigeeregistry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.editor">Cloud Apigee Registry Editor</a> ( <code>roles/ apigeeregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.viewer">Cloud Apigee Registry Viewer</a> ( <code>roles/ apigeeregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code>roles/ apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code>roles/ apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.admin">Appengine Admin</a> ( <code>roles/ appengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appAdmin">App Engine Admin</a> ( <code>roles/ appengine.appAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.editor">Appengine Editor</a> ( <code>roles/ appengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.viewer">Appengine Viewer</a> ( <code>roles/ appengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code>roles/ applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code>roles/ applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.editor">Artifactregistry Editor</a> ( <code>roles/ artifactregistry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/artifactregistry#artifactregistry.viewer">Artifactregistry Viewer</a> ( <code>roles/ artifactregistry.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.admin">Assured OSS Admin</a> ( <code>roles/ assuredoss.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.editor">Assured OSS Editor</a> ( <code>roles/ assuredoss.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.viewer">Assured OSS Viewer</a> ( <code>roles/ assuredoss.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assuredworkloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code>roles/ auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.viewer">Auditmanager Viewer</a> ( <code>roles/ auditmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.admin">AutoML Admin</a> ( <code>roles/ automl.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.editor">AutoML Editor</a> ( <code>roles/ automl.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.viewer">AutoML Viewer</a> ( <code>roles/ automl.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code>roles/ automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code>roles/ automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code>roles/ automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.admin">Autoscaling Admin</a> ( <code>roles/ autoscaling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.editor">Autoscaling Editor</a> ( <code>roles/ autoscaling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.viewer">Autoscaling Viewer</a> ( <code>roles/ autoscaling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/axt#axt.admin">Access Transparency Admin</a> ( <code>roles/ axt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.admin">Backup and DR Admin</a> ( <code>roles/ backupdr.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.editor">Backupdr Editor</a> ( <code>roles/ backupdr.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.viewer">Backup and DR Viewer</a> ( <code>roles/ backupdr.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code>roles/ baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code>roles/ baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code>roles/ baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin">Batch Administrator</a> ( <code>roles/ batch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer">Batch Viewer</a> ( <code>roles/ batch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.admin">Cloud BeyondCorp Admin</a> ( <code>roles/ beyondcorp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.editor">Cloud BeyondCorp Editor</a> ( <code>roles/ beyondcorp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/beyondcorp#beyondcorp.viewer">Cloud BeyondCorp Viewer</a> ( <code>roles/ beyondcorp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code>roles/ biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code>roles/ biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code>roles/ biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataEditor">BigQuery Data Editor</a> ( <code>roles/ bigquery.dataEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataOwner">BigQuery Data Owner</a> ( <code>roles/ bigquery.dataOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.dataViewer">BigQuery Data Viewer</a> ( <code>roles/ bigquery.dataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.jobUser">BigQuery Job User</a> ( <code>roles/ bigquery.jobUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.metadataViewer">BigQuery Metadata Viewer</a> ( <code>roles/ bigquery.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.readSessionUser">BigQuery Read Session User</a> ( <code>roles/ bigquery.readSessionUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceAdmin">BigQuery Resource Admin</a> ( <code>roles/ bigquery.resourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceEditor">BigQuery Resource Editor</a> ( <code>roles/ bigquery.resourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.resourceViewer">BigQuery Resource Viewer</a> ( <code>roles/ bigquery.resourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatapolicy#bigquerydatapolicy.editor">BigQuery Data Policy Editor</a> ( <code>roles/ bigquerydatapolicy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code>roles/ bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code>roles/ billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.admin">Binary Authorization Admin</a> ( <code>roles/ binaryauthorization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.editor">Binary Authorization Editor</a> ( <code>roles/ binaryauthorization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.viewer">Binary Authorization Viewer</a> ( <code>roles/ binaryauthorization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code>roles/ blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code>roles/ blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code>roles/ blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code>roles/ blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code>roles/ carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code>roles/ carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.admin">Certificatemanager Admin</a> ( <code>roles/ certificatemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.editor">Certificate Manager Editor</a> ( <code>roles/ certificatemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.viewer">Certificate Manager Viewer</a> ( <code>roles/ certificatemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.admin">Gemini Enterprise for Customer Experience Admin</a> ( <code>roles/ ces.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.viewer">Gemini Enterprise for Customer Experience Viewer</a> ( <code>roles/ ces.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code>roles/ chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer">Chat Viewer</a> ( <code>roles/ chat.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code>roles/ chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.editor">Chronicle API Editor</a> ( <code>roles/ chronicle.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.viewer">Chronicle API Viewer</a> ( <code>roles/ chronicle.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chroniclesm#chroniclesm.editor">Chroniclesm Editor</a> ( <code>roles/ chroniclesm.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code>roles/ cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code>roles/ cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.admin">Gemini for Google Cloud Admin</a> ( <code>roles/ cloudaicompanion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.editor">Gemini for Google Cloud Editor</a> ( <code>roles/ cloudaicompanion.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.user">Gemini for Google Cloud User</a> ( <code>roles/ cloudaicompanion.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.viewer">Gemini for Google Cloud Viewer</a> ( <code>roles/ cloudaicompanion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.admin">Cloud Asset Admin</a> ( <code>roles/ cloudasset.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudasset#cloudasset.editor">Cloud Asset Editor</a> ( <code>roles/ cloudasset.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.admin">Cloud Build Admin</a> ( <code>roles/ cloudbuild.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.builder">Cloud Build Service Account</a> ( <code>roles/ cloudbuild.builds.builder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.editor">Cloud Build Editor</a> ( <code>roles/ cloudbuild.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.viewer">Cloud Build Viewer</a> ( <code>roles/ cloudbuild.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.admin">Firebase Remote Config Admin</a> ( <code>roles/ cloudconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudconfig#cloudconfig.viewer">Firebase Remote Config Viewer</a> ( <code>roles/ cloudconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code>roles/ cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.admin">Cloud Deploy Admin</a> ( <code>roles/ clouddeploy.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.editor">Cloud Deploy Editor</a> ( <code>roles/ clouddeploy.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.viewer">Cloud Deploy Viewer</a> ( <code>roles/ clouddeploy.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.admin">Cloud Functions Admin</a> ( <code>roles/ cloudfunctions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.editor">Cloud Functions Editor</a> ( <code>roles/ cloudfunctions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.viewer">Cloud Functions Viewer</a> ( <code>roles/ cloudfunctions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.admin">Cloud Talent Solution Admin</a> ( <code>roles/ cloudjobdiscovery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.viewer">Cloud Talent Solution Viewer</a> ( <code>roles/ cloudjobdiscovery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code>roles/ cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code>roles/ cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.admin">Cloudprivatecatalog Admin</a> ( <code>roles/ cloudprivatecatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.viewer">Cloudprivatecatalog Viewer</a> ( <code>roles/ cloudprivatecatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.admin">Catalog Admin</a> ( <code>roles/ cloudprivatecatalogproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.editor">Catalog Editor</a> ( <code>roles/ cloudprivatecatalogproducer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.viewer">Catalog Viewer</a> ( <code>roles/ cloudprivatecatalogproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.admin">Cloud Profiler Admin</a> ( <code>roles/ cloudprofiler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.viewer">Cloud Profiler Viewer</a> ( <code>roles/ cloudprofiler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code>roles/ cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.viewer">Cloud Quotas Viewer</a> ( <code>roles/ cloudquotas.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.admin">Cloud Scheduler Admin</a> ( <code>roles/ cloudscheduler.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.viewer">Cloud Scheduler Viewer</a> ( <code>roles/ cloudscheduler.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code>roles/ cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code>roles/ cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.admin">Web Security Scanner Admin</a> ( <code>roles/ cloudsecurityscanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecurityscanner#cloudsecurityscanner.editor">Web Security Scanner Editor</a> ( <code>roles/ cloudsecurityscanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code>roles/ cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code>roles/ cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code>roles/ cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code>roles/ cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code>roles/ cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.admin">Cloud Trace Admin</a> ( <code>roles/ cloudtrace.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtrace#cloudtrace.user">Cloud Trace User</a> ( <code>roles/ cloudtrace.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.admin">Cloud Translation API Admin</a> ( <code>roles/ cloudtranslate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.editor">Cloud Translation API Editor</a> ( <code>roles/ cloudtranslate.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.user">Cloud Translation API User</a> ( <code>roles/ cloudtranslate.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtranslate#cloudtranslate.viewer">Cloud Translation API Viewer</a> ( <code>roles/ cloudtranslate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.admin">Commerce Agreement Publishing Admin</a> ( <code>roles/ commerceagreementpublishing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceagreementpublishing#commerceagreementpublishing.viewer">Commerce Agreement Publishing Viewer</a> ( <code>roles/ commerceagreementpublishing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.admin">Commerce Business Enablement Configuration Admin</a> ( <code>roles/ commercebusinessenablement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.viewer">Commerce Business Enablement Configuration Viewer</a> ( <code>roles/ commercebusinessenablement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceoffercatalog#commerceoffercatalog.admin">Commerce Offer Catalog Admin</a> ( <code>roles/ commerceoffercatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.admin">Commerce Organization Governance Admin</a> ( <code>roles/ commerceorggovernance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.viewer">Commerce Organization Governance Viewer</a> ( <code>roles/ commerceorggovernance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.editor">Commercepricemanagement Editor</a> ( <code>roles/ commercepricemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.viewer">Commerce Price Management Viewer</a> ( <code>roles/ commercepricemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.admin">Commerce Producer Admin</a> ( <code>roles/ commerceproducer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceproducer#commerceproducer.viewer">Commerce Producer Viewer</a> ( <code>roles/ commerceproducer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.editor">Composer Editor</a> ( <code>roles/ composer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.viewer">Composer Viewer</a> ( <code>roles/ composer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.admin">Compute Admin</a> ( <code>roles/ compute.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.editor">Compute Editor</a> ( <code>roles/ compute.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin">Compute Instance Admin (beta)</a> ( <code>roles/ compute.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceAdmin.v1">Compute Instance Admin (v1)</a> ( <code>roles/ compute.instanceAdmin.v1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerAdmin">Compute Load Balancer Admin</a> ( <code>roles/ compute.loadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code>roles/ compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code>roles/ compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osAdminLogin">Compute OS Admin Login</a> ( <code>roles/ compute.osAdminLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.osLogin">Compute OS Login</a> ( <code>roles/ compute.osLogin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.securityAdmin">Compute Security Admin</a> ( <code>roles/ compute.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.storageAdmin">Compute Storage Admin</a> ( <code>roles/ compute.storageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.viewer">Compute Viewer</a> ( <code>roles/ compute.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin">Confidentialcomputing Admin</a> ( <code>roles/ confidentialcomputing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer">Confidentialcomputing Viewer</a> ( <code>roles/ confidentialcomputing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.admin">Cloud Infrastructure Manager Admin</a> ( <code>roles/ config.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.editor">Cloud Infrastructure Manager Editor</a> ( <code>roles/ config.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.viewer">Cloud Infrastructure Manager Viewer</a> ( <code>roles/ config.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.admin">Configdelivery Admin</a> ( <code>roles/ configdelivery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.viewer">Configdelivery Viewer</a> ( <code>roles/ configdelivery.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.admin">Connector Admin</a> ( <code>roles/ connectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.editor">Connectors Editor</a> ( <code>roles/ connectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.viewer">Connectors Viewer</a> ( <code>roles/ connectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code>roles/ contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code>roles/ contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.admin">Kubernetes Engine Admin</a> ( <code>roles/ container.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterAdmin">Kubernetes Engine Cluster Admin</a> ( <code>roles/ container.clusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.clusterViewer">Kubernetes Engine Cluster Viewer</a> ( <code>roles/ container.clusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.developer">Kubernetes Engine Developer</a> ( <code>roles/ container.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.editor">Kubernetes Engine Editor</a> ( <code>roles/ container.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.viewer">Kubernetes Engine Viewer</a> ( <code>roles/ container.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.admin">Container Analysis Admin</a> ( <code>roles/ containeranalysis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.editor">Container Analysis Editor</a> ( <code>roles/ containeranalysis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.viewer">Container Analysis Viewer</a> ( <code>roles/ containeranalysis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin">Containersecurity Admin</a> ( <code>roles/ containersecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer">GKE Security Posture Viewer</a> ( <code>roles/ containersecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.admin">Content Warehouse Admin</a> ( <code>roles/ contentwarehouse.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.admin">Database Center Admin</a> ( <code>roles/ databasecenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasecenter#databasecenter.viewer">Database Center Viewer</a> ( <code>roles/ databasecenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code>roles/ databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.editor">Databasesconsole Editor</a> ( <code>roles/ databasesconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.viewer">Databasesconsole Viewer</a> ( <code>roles/ databasesconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.admin">Data Catalog Admin</a> ( <code>roles/ datacatalog.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.editor">Data Catalog Editor</a> ( <code>roles/ datacatalog.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.viewer">Data Catalog Viewer</a> ( <code>roles/ datacatalog.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code>roles/ dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code>roles/ dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code>roles/ dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.admin">Dataflow Admin</a> ( <code>roles/ dataflow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.viewer">Dataflow Viewer</a> ( <code>roles/ dataflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.admin">Dataform Admin</a> ( <code>roles/ dataform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.editor">Dataform Editor</a> ( <code>roles/ dataform.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.viewer">Dataform Viewer</a> ( <code>roles/ dataform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.admin">Cloud Data Fusion Admin</a> ( <code>roles/ datafusion.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.viewer">Cloud Data Fusion Viewer</a> ( <code>roles/ datafusion.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.admin">Data Labeling Service Admin</a> ( <code>roles/ datalabeling.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.editor">Data Labeling Service Editor</a> ( <code>roles/ datalabeling.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.viewer">Data Labeling Service Viewer</a> ( <code>roles/ datalabeling.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.admin">Database Migration Admin</a> ( <code>roles/ datamigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datamigration#datamigration.editor">Datamigration Editor</a> ( <code>roles/ datamigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.admin">Data pipelines Admin</a> ( <code>roles/ datapipelines.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.viewer">Data pipelines Viewer</a> ( <code>roles/ datapipelines.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.admin">Dataplex Administrator</a> ( <code>roles/ dataplex.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.admin">Dataprep Admin</a> ( <code>roles/ dataprep.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.admin">Dataproc Administrator</a> ( <code>roles/ dataproc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.editor">Dataproc Editor</a> ( <code>roles/ dataproc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.viewer">Dataproc Viewer</a> ( <code>roles/ dataproc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code>roles/ dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code>roles/ dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.admin">Dataproc Resource Manager Admin</a> ( <code>roles/ dataprocrm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.viewer">Dataproc Resource Manager Viewer</a> ( <code>roles/ dataprocrm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.admin">Cloud Datastore Admin</a> ( <code>roles/ datastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.editor">Cloud Datastore Editor</a> ( <code>roles/ datastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.owner">Cloud Datastore Owner</a> ( <code>roles/ datastore.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.user">Cloud Datastore User</a> ( <code>roles/ datastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.viewer">Cloud Datastore Viewer</a> ( <code>roles/ datastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.admin">Datastream Admin</a> ( <code>roles/ datastream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.viewer">Datastream Viewer</a> ( <code>roles/ datastream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#datastudio.admin">Data Studio Admin</a> ( <code>roles/ datastudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.admin">Dell EMC Cloud OneFS Admin</a> ( <code>roles/ dellemccloudonefs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.viewer">Dell EMC Cloud OneFS Viewer</a> ( <code>roles/ dellemccloudonefs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.admin">Deployment Manager Admin</a> ( <code>roles/ deploymentmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.editor">Deployment Manager Editor</a> ( <code>roles/ deploymentmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.viewer">Deployment Manager Viewer</a> ( <code>roles/ deploymentmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.editor">Designcenter Editor</a> ( <code>roles/ designcenter.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.viewer">Application Design Center Viewer</a> ( <code>roles/ designcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.admin">Developer Connect Admin</a> ( <code>roles/ developerconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.viewer">Developer Connect Viewer</a> ( <code>roles/ developerconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code>roles/ devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code>roles/ devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code>roles/ devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code>roles/ devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.viewer">Dialogflow Viewer</a> ( <code>roles/ dialogflow.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.editor">Discovery Engine Editor</a> ( <code>roles/ discoveryengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code>roles/ discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.viewer">Discovery Engine Viewer</a> ( <code>roles/ discoveryengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.admin">Document AI Administrator</a> ( <code>roles/ documentai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.editor">Document AI Editor</a> ( <code>roles/ documentai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddocumentai#documentai.viewer">Document AI Viewer</a> ( <code>roles/ documentai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.admin">Cloud Domains Admin</a> ( <code>roles/ domains.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.editor">Cloud Domains Editor</a> ( <code>roles/ domains.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/domains#domains.viewer">Cloud Domains Viewer</a> ( <code>roles/ domains.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.admin">Earth Admin</a> ( <code>roles/ earth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.viewer">Earth Viewer</a> ( <code>roles/ earth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code>roles/ earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.editor">Earthengine Editor</a> ( <code>roles/ earthengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code>roles/ earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.admin">Edge Container Admin</a> ( <code>roles/ edgecontainer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.editor">Edgecontainer Editor</a> ( <code>roles/ edgecontainer.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.viewer">Edge Container Viewer</a> ( <code>roles/ edgecontainer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code>roles/ edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code>roles/ edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code>roles/ edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code>roles/ enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code>roles/ enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code>roles/ enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.admin">Enterprise Purchasing Admin</a> ( <code>roles/ enterprisepurchasing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.editor">Enterprise Purchasing Editor</a> ( <code>roles/ enterprisepurchasing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterprisepurchasing#enterprisepurchasing.viewer">Enterprise Purchasing Viewer</a> ( <code>roles/ enterprisepurchasing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code>roles/ errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code>roles/ errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code>roles/ errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.admin">Eventarc Admin</a> ( <code>roles/ eventarc.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.editor">Eventarc Editor</a> ( <code>roles/ eventarc.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.viewer">Eventarc Viewer</a> ( <code>roles/ eventarc.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.admin">External Exposure Admin</a> ( <code>roles/ externalexposure.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/externalexposure#externalexposure.viewer">External Exposure Viewer</a> ( <code>roles/ externalexposure.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code>roles/ faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.admin">File Admin</a> ( <code>roles/ file.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code>roles/ financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code>roles/ financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code>roles/ firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code>roles/ firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.admin">Firebase App Distribution Admin</a> ( <code>roles/ firebaseappdistro.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseappdistro#firebaseappdistro.viewer">Firebase App Distribution Viewer</a> ( <code>roles/ firebaseappdistro.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.admin">Firebase App Hosting Admin</a> ( <code>roles/ firebaseapphosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.viewer">Firebase App Hosting Viewer</a> ( <code>roles/ firebaseapphosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code>roles/ firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code>roles/ firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code>roles/ firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.admin">Firebase Crashlytics Admin</a> ( <code>roles/ firebasecrashlytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecrash#firebasecrashlytics.viewer">Firebase Crashlytics Viewer</a> ( <code>roles/ firebasecrashlytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.admin">Firebase Realtime Database Admin</a> ( <code>roles/ firebasedatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedatabase#firebasedatabase.viewer">Firebase Realtime Database Viewer</a> ( <code>roles/ firebasedatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.admin">Firebase SQL Connect API Admin</a> ( <code>roles/ firebasedataconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedataconnect#firebasedataconnect.viewer">Firebase SQL Connect API Viewer</a> ( <code>roles/ firebasedataconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code>roles/ firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code>roles/ firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code>roles/ firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.editor">Firebaseextensions Editor</a> ( <code>roles/ firebaseextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.viewer">Firebase Extensions Viewer</a> ( <code>roles/ firebaseextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code>roles/ firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code>roles/ firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.admin">Firebase Hosting Admin</a> ( <code>roles/ firebasehosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasehosting#firebasehosting.viewer">Firebase Hosting Viewer</a> ( <code>roles/ firebasehosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.admin">Firebase In-App Messaging Admin</a> ( <code>roles/ firebaseinappmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseinappmessaging#firebaseinappmessaging.viewer">Firebase In-App Messaging Viewer</a> ( <code>roles/ firebaseinappmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.admin">Firebase ML Kit Admin</a> ( <code>roles/ firebaseml.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseml#firebaseml.viewer">Firebase ML Kit Viewer</a> ( <code>roles/ firebaseml.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.admin">Firebase Performance Reporting Admin</a> ( <code>roles/ firebaseperformance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseperformance#firebaseperformance.viewer">Firebase Performance Reporting Viewer</a> ( <code>roles/ firebaseperformance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.admin">Firebase Rules Admin</a> ( <code>roles/ firebaserules.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.system">Firebase Rules System</a> ( <code>roles/ firebaserules.system</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaserules#firebaserules.viewer">Firebase Rules Viewer</a> ( <code>roles/ firebaserules.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.admin">Cloud Storage for Firebase Admin</a> ( <code>roles/ firebasestorage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasestorage#firebasestorage.viewer">Cloud Storage for Firebase Viewer</a> ( <code>roles/ firebasestorage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.admin">Firebase AI Logic Admin</a> ( <code>roles/ firebasevertexai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasevertexai#firebasevertexai.viewer">Firebase AI Logic Viewer</a> ( <code>roles/ firebasevertexai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.viewer">Fleetengine Viewer</a> ( <code>roles/ fleetengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#flow.admin">Flow Admin</a> ( <code>roles/ flow.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/flow#flow.editor">Flow Editor</a> ( <code>roles/ flow.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.admin">Cloud FTP Admin</a> ( <code>roles/ ftp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ftp#ftp.viewer">Cloud FTP Viewer</a> ( <code>roles/ ftp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code>roles/ gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code>roles/ gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.admin">Gemini Data Analytics Admin</a> ( <code>roles/ geminidataanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminidataanalytics#geminidataanalytics.viewer">Gemini Data Analytics Viewer</a> ( <code>roles/ geminidataanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.admin">Backup for GKE Admin</a> ( <code>roles/ gkebackup.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.editor">Gkebackup Editor</a> ( <code>roles/ gkebackup.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.viewer">Backup for GKE Viewer</a> ( <code>roles/ gkebackup.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.admin">Fleet Admin (formerly GKE Hub Admin)</a> ( <code>roles/ gkehub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.editor">Fleet Editor (formerly GKE Hub Editor)</a> ( <code>roles/ gkehub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.viewer">Fleet Viewer (formerly GKE Hub Viewer)</a> ( <code>roles/ gkehub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.admin">GKE on-prem Admin</a> ( <code>roles/ gkeonprem.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.editor">Gkeonprem Editor</a> ( <code>roles/ gkeonprem.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkeonprem#gkeonprem.viewer">GKE on-prem Viewer</a> ( <code>roles/ gkeonprem.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code>roles/ gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code>roles/ gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.editor">Cluster Director Editor</a> ( <code>roles/ hypercomputecluster.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.admin">Iam Admin</a> ( <code>roles/ iam.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.editor">Iam Editor</a> ( <code>roles/ iam.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountAdmin">Service Account Admin</a> ( <code>roles/ iam.serviceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountCreator">Create Service Accounts</a> ( <code>roles/ iam.serviceAccountCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountKeyAdmin">Service Account Key Admin</a> ( <code>roles/ iam.serviceAccountKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountTokenCreator">Service Account Token Creator</a> ( <code>roles/ iam.serviceAccountTokenCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountUser">Service Account User</a> ( <code>roles/ iam.serviceAccountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountViewer">View Service Accounts</a> ( <code>roles/ iam.serviceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.viewer">Iam Viewer</a> ( <code>roles/ iam.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.editor">IAP Policy Editor</a> ( <code>roles/ iap.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iap#iap.viewer">IAP Policy Viewer</a> ( <code>roles/ iap.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code>roles/ ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code>roles/ ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code>roles/ ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.admin">Integrations Admin</a> ( <code>roles/ integrations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.viewer">Integrations Viewer</a> ( <code>roles/ integrations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.admin">Issuerswitch Admin</a> ( <code>roles/ issuerswitch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.viewer">Issuerswitch Viewer</a> ( <code>roles/ issuerswitch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code>roles/ krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code>roles/ krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code>roles/ krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.admin">Kubernetesmetadata Admin</a> ( <code>roles/ kubernetesmetadata.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kubernetesmetadata#kubernetesmetadata.viewer">Kubernetesmetadata Viewer</a> ( <code>roles/ kubernetesmetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code>roles/ licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code>roles/ licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code>roles/ lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.admin">Live Stream Admin</a> ( <code>roles/ livestream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.editor">Live Stream Editor</a> ( <code>roles/ livestream.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/livestream#livestream.viewer">Live Stream Viewer</a> ( <code>roles/ livestream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.admin">Logging Admin</a> ( <code>roles/ logging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code>roles/ looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code>roles/ looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.admin">Google Cloud Managed Lustre Admin</a> ( <code>roles/ lustre.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lustre#lustre.viewer">Google Cloud Managed Lustre Viewer</a> ( <code>roles/ lustre.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code>roles/ maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code>roles/ maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code>roles/ managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code>roles/ managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.admin">Google Cloud Managed Identities Admin</a> ( <code>roles/ managedidentities.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.editor">Google Cloud Managed Identities Editor</a> ( <code>roles/ managedidentities.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.viewer">Google Cloud Managed Identities Viewer</a> ( <code>roles/ managedidentities.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.admin">Managed Kafka Admin</a> ( <code>roles/ managedkafka.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.viewer">Managed Kafka Viewer</a> ( <code>roles/ managedkafka.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.admin">Mandiant Admin</a> ( <code>roles/ mandiant.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.viewer">Mandiant Viewer</a> ( <code>roles/ mandiant.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code>roles/ mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code>roles/ mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code>roles/ mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code>roles/ mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code>roles/ mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code>roles/ mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code>roles/ marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code>roles/ marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code>roles/ marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.admin">MCP Admin</a> ( <code>roles/ mcp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mcp#mcp.toolUser">MCP Tool User</a> ( <code>roles/ mcp.toolUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code>roles/ memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code>roles/ memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code>roles/ memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.admin">Memorystore Admin</a> ( <code>roles/ memorystore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.viewer">Memorystore Viewer</a> ( <code>roles/ memorystore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.admin">Dataproc Metastore Admin</a> ( <code>roles/ metastore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.editor">Dataproc Metastore Editor</a> ( <code>roles/ metastore.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.viewer">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.admin">Migration Center Admin</a> ( <code>roles/ migrationcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.viewer">Migration Center Viewer</a> ( <code>roles/ migrationcenter.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.editor">AI Platform Editor</a> ( <code>roles/ ml.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.admin">Model Armor Admin</a> ( <code>roles/ modelarmor.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.editor">Model Armor Editor</a> ( <code>roles/ modelarmor.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.viewer">Model Armor Viewer</a> ( <code>roles/ modelarmor.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin">Navigation Connect Admin</a> ( <code>roles/ navigationconnect.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.viewer">Navigation Connect Viewer</a> ( <code>roles/ navigationconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin">Nestconsole Admin</a> ( <code>roles/ nestconsole.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor">Nestconsole Editor</a> ( <code>roles/ nestconsole.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer">Nestconsole Viewer</a> ( <code>roles/ nestconsole.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code>roles/ netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code>roles/ netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code>roles/ netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code>roles/ netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.editor">Network Connectivity Editor</a> ( <code>roles/ networkconnectivity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.admin">Network Management Admin</a> ( <code>roles/ networkmanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.editor">Networkmanagement Editor</a> ( <code>roles/ networkmanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.viewer">Network Management Viewer</a> ( <code>roles/ networkmanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.admin">Networksecurity Admin</a> ( <code>roles/ networksecurity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.editor">Networksecurity Editor</a> ( <code>roles/ networksecurity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.viewer">Networksecurity Viewer</a> ( <code>roles/ networksecurity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.admin">Network Services Admin</a> ( <code>roles/ networkservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.editor">Network Services Editor</a> ( <code>roles/ networkservices.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.viewer">Network Services Viewer</a> ( <code>roles/ networkservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.admin">Notebooks Admin</a> ( <code>roles/ notebooks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.editor">Notebooks Editor</a> ( <code>roles/ notebooks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.viewer">Notebooks Viewer</a> ( <code>roles/ notebooks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code>roles/ oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code>roles/ oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ondemandscanning#ondemandscanning.viewer">On-Demand Scanning Viewer</a> ( <code>roles/ ondemandscanning.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code>roles/ opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.viewer">Opsconfigmonitoring Viewer</a> ( <code>roles/ opsconfigmonitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.admin">Oracle Database@Google Cloud admin</a> ( <code>roles/ oracledatabase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.viewer">Oracle Database@Google Cloud viewer</a> ( <code>roles/ oracledatabase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code>roles/ parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code>roles/ parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code>roles/ parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code>roles/ parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code>roles/ parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.admin">Paymentsresellersubscription Admin</a> ( <code>roles/ paymentsresellersubscription.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.viewer">Paymentsresellersubscription Viewer</a> ( <code>roles/ paymentsresellersubscription.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin">Policyanalyzer Admin</a> ( <code>roles/ policyanalyzer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer">Policyanalyzer Viewer</a> ( <code>roles/ policyanalyzer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code>roles/ policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code>roles/ policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code>roles/ policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.admin">CA Service Admin</a> ( <code>roles/ privateca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.editor">CA Service Editor</a> ( <code>roles/ privateca.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.viewer">CA Service Viewer</a> ( <code>roles/ privateca.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.editor">Privilegedaccessmanager Editor</a> ( <code>roles/ privilegedaccessmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.admin">Proximitybeacon Admin</a> ( <code>roles/ proximitybeacon.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.editor">Proximitybeacon Editor</a> ( <code>roles/ proximitybeacon.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.viewer">Proximitybeacon Viewer</a> ( <code>roles/ proximitybeacon.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.admin">Publicca Admin</a> ( <code>roles/ publicca.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.admin">Subscription Linking Admin</a> ( <code>roles/ readerrevenuesubscriptionlinking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/readerrevenuesubscriptionlinking#readerrevenuesubscriptionlinking.viewer">Subscription Linking Viewer</a> ( <code>roles/ readerrevenuesubscriptionlinking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code>roles/ recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code>roles/ recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code>roles/ recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.admin">Recommender Admin</a> ( <code>roles/ recommender.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.editor">Recommender Editor</a> ( <code>roles/ recommender.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.admin">Cloud Memorystore Redis Admin</a> ( <code>roles/ redis.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.editor">Cloud Memorystore Redis Editor</a> ( <code>roles/ redis.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.viewer">Cloud Memorystore Redis Viewer</a> ( <code>roles/ redis.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.admin">Redis Enterprise Cloud Admin</a> ( <code>roles/ redisenterprisecloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redisenterprisecloud#redisenterprisecloud.viewer">Redis Enterprise Cloud Viewer</a> ( <code>roles/ redisenterprisecloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.admin">Remotebuildexecution Admin</a> ( <code>roles/ remotebuildexecution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.editor">Remotebuildexecution Editor</a> ( <code>roles/ remotebuildexecution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/remotebuildexecution#remotebuildexecution.viewer">Remotebuildexecution Viewer</a> ( <code>roles/ remotebuildexecution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code>roles/ retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code>roles/ retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code>roles/ riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code>roles/ riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code>roles/ riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.admin">Rapid Migration Assessment Admin</a> ( <code>roles/ rma.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.viewer">Rapid Migration Assessment Viewer</a> ( <code>roles/ rma.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code>roles/ routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code>roles/ routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer">Route Optimization Viewer</a> ( <code>roles/ routeoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.admin">Cloud Run Admin</a> ( <code>roles/ run.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.developer">Cloud Run Developer</a> ( <code>roles/ run.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.editor">Cloud Run Editor</a> ( <code>roles/ run.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.viewer">Cloud Run Viewer</a> ( <code>roles/ run.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code>roles/ runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code>roles/ runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code>roles/ runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code>roles/ runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasconfig#saasconfig.viewer">SaaS Config Viewer</a> ( <code>roles/ saasconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.admin">SaaS Service Management Admin</a> ( <code>roles/ saasservicemgmt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.viewer">SaaS Service Management Viewer</a> ( <code>roles/ saasservicemgmt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.admin">Secret Manager Admin</a> ( <code>roles/ secretmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.editor">Secretmanager Editor</a> ( <code>roles/ secretmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretAccessor">Secret Manager Secret Accessor</a> ( <code>roles/ secretmanager.secretAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.viewer">Secret Manager Viewer</a> ( <code>roles/ secretmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.admin">Secured Landing Zone Admin</a> ( <code>roles/ securedlandingzone.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.viewer">Secured Landing Zone Viewer</a> ( <code>roles/ securedlandingzone.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.admin">Secure Source Manager Admin</a> ( <code>roles/ securesourcemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.editor">Securesourcemanager Editor</a> ( <code>roles/ securesourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.viewer">Securesourcemanager Viewer</a> ( <code>roles/ securesourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code>roles/ securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Security Center Management Editor</a> ( <code>roles/ securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code>roles/ securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code>roles/ serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code>roles/ serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code>roles/ serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.admin">Servicehealth Admin</a> ( <code>roles/ servicehealth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicehealth#servicehealth.viewer">Personalized Service Health Viewer</a> ( <code>roles/ servicehealth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.editor">Service Management Editor</a> ( <code>roles/ servicemanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.viewer">Service Management Viewer</a> ( <code>roles/ servicemanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code>roles/ servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code>roles/ servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code>roles/ servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.editor">Source Editor</a> ( <code>roles/ source.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/source#source.viewer">Source Viewer</a> ( <code>roles/ source.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code>roles/ spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code>roles/ spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code>roles/ stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.editor">Storage Editor</a> ( <code>roles/ storage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.folderAdmin">Storage Folder Admin</a> ( <code>roles/ storage.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectCreator">Storage Object Creator</a> ( <code>roles/ storage.objectCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectViewer">Storage Object Viewer</a> ( <code>roles/ storage.objectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.viewer">Storage Viewer</a> ( <code>roles/ storage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.admin">Storage Batch Operations Admin</a> ( <code>roles/ storagebatchoperations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagebatchoperations#storagebatchoperations.viewer">Storage Batch Operations Viewer</a> ( <code>roles/ storagebatchoperations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code>roles/ storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code>roles/ storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.admin">Storage Transfer Admin</a> ( <code>roles/ storagetransfer.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.viewer">Storage Transfer Viewer</a> ( <code>roles/ storagetransfer.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.admin">Stream Admin</a> ( <code>roles/ stream.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.viewer">Stream Viewer</a> ( <code>roles/ stream.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.admin">Subscribewithgoogledeveloper Admin</a> ( <code>roles/ subscribewithgoogledeveloper.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.viewer">Subscribewithgoogledeveloper Viewer</a> ( <code>roles/ subscribewithgoogledeveloper.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.editor">Telcoautomation Editor</a> ( <code>roles/ telcoautomation.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.viewer">Telcoautomation Viewer</a> ( <code>roles/ telcoautomation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.admin">Telemetry Admin</a> ( <code>roles/ telemetry.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.editor">Telemetry Editor</a> ( <code>roles/ telemetry.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.admin">TPU Admin</a> ( <code>roles/ tpu.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.editor">TPU Editor</a> ( <code>roles/ tpu.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.viewer">TPU Viewer</a> ( <code>roles/ tpu.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.admin">Trafficdirector Admin</a> ( <code>roles/ trafficdirector.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#trafficdirector.viewer">Trafficdirector Viewer</a> ( <code>roles/ trafficdirector.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.admin">Transcoder Admin</a> ( <code>roles/ transcoder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.editor">Transcoder Editor</a> ( <code>roles/ transcoder.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transcoder#transcoder.viewer">Transcoder Viewer</a> ( <code>roles/ transcoder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code>roles/ transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code>roles/ transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin">Translation Hub Admin</a> ( <code>roles/ translationhub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer">Translation Hub Viewer</a> ( <code>roles/ translationhub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.admin">Vector Search Admin</a> ( <code>roles/ vectorsearch.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.viewer">Vector Search Viewer</a> ( <code>roles/ vectorsearch.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.admin">Video Stitcher Admin</a> ( <code>roles/ videostitcher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.viewer">Video Stitcher Viewer</a> ( <code>roles/ videostitcher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.admin">VisionAI Admin</a> ( <code>roles/ visionai.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.editor">VisionAI Editor</a> ( <code>roles/ visionai.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.viewer">VisionAI Viewer</a> ( <code>roles/ visionai.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.admin">Visual Inspection AI Admin</a> ( <code>roles/ visualinspection.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code>roles/ vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code>roles/ vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code>roles/ vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code>roles/ vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code>roles/ vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.admin">Workflows Admin</a> ( <code>roles/ workflows.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.editor">Workflows Editor</a> ( <code>roles/ workflows.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.viewer">Workflows Viewer</a> ( <code>roles/ workflows.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code>roles/ workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code>roles/ workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code>roles/ workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code>roles/ workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.viewer">Workload Manager Viewer</a> ( <code>roles/ workloadmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code>roles/ workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code>roles/ workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.approver">Access Approval Approver</a> ( <code>roles/ accessapproval.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.configEditor">Access Approval Config Editor</a> ( <code>roles/ accessapproval.configEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accessapproval#accessapproval.invalidator">Access Approval Invalidator</a> ( <code>roles/ accessapproval.invalidator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code>roles/ accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code>roles/ accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code>roles/ accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseAdmin">Colab Enterprise Admin</a> ( <code>roles/ aiplatform.colabEnterpriseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.colabEnterpriseUser">Colab Enterprise User</a> ( <code>roles/ aiplatform.colabEnterpriseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.entityTypeOwner">Agent Platform Feature Store EntityType owner</a> ( <code>roles/ aiplatform.entityTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreAdmin">Agent Platform Feature Store Admin</a> ( <code>roles/ aiplatform.featurestoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataViewer">Agent Platform Feature Store Data Viewer</a> ( <code>roles/ aiplatform.featurestoreDataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreDataWriter">Agent Platform Feature Store Data Writer</a> ( <code>roles/ aiplatform.featurestoreDataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreResourceViewer">Agent Platform Feature Store Resource Viewer</a> ( <code>roles/ aiplatform.featurestoreResourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.featurestoreUser">Agent Platform Feature Store User</a> ( <code>roles/ aiplatform.featurestoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code>roles/ alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.databaseUser">AlloyDB Database User</a> ( <code>roles/ alloydb.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.listingAdmin">Analytics Hub Listing Admin</a> ( <code>roles/ analyticshub.listingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.publisher">Analytics Hub Publisher</a> ( <code>roles/ analyticshub.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriber">Analytics Hub Subscriber</a> ( <code>roles/ analyticshub.subscriber</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.subscriptionOwner">Analytics Hub Subscription Owner</a> ( <code>roles/ analyticshub.subscriptionOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsEditor">Apigee Analytics Editor</a> ( <code>roles/ apigee.analyticsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.analyticsViewer">Apigee Analytics Viewer</a> ( <code>roles/ apigee.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.developerAdmin">Apigee Developer Admin</a> ( <code>roles/ apigee.developerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.environmentAdmin">Apigee Environment Admin</a> ( <code>roles/ apigee.environmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.monetizationAdmin">Apigee Monetization Admin</a> ( <code>roles/ apigee.monetizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.portalAdmin">Apigee Portal Admin</a> ( <code>roles/ apigee.portalAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code>roles/ apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code>roles/ apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code>roles/ apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.spaceConsoleUser">Apigee Space Console User</a> ( <code>roles/ apigee.spaceConsoleUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeregistry#apigeeregistry.worker">Cloud Apigee Registry Worker</a> ( <code>roles/ apigeeregistry.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code>roles/ apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appCreator">App Engine Creator</a> ( <code>roles/ appengine.appCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.appViewer">App Engine Viewer</a> ( <code>roles/ appengine.appViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.codeViewer">App Engine Code Viewer</a> ( <code>roles/ appengine.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.debugger">App Engine Managed VM Debug Access</a> ( <code>roles/ appengine.debugger</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.deployer">App Engine Deployer</a> ( <code>roles/ appengine.deployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.memcacheDataAdmin">App Engine Memcache Data Admin</a> ( <code>roles/ appengine.memcacheDataAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengine#appengine.serviceAdmin">App Engine Service Admin</a> ( <code>roles/ appengine.serviceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code>roles/ applianceactivation.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code>roles/ applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.projectAdmin">Assured OSS Project Admin</a> ( <code>roles/ assuredoss.projectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.reader">Assured OSS Reader</a> ( <code>roles/ assuredoss.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredoss#assuredoss.user">Assured OSS User</a> ( <code>roles/ assuredoss.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code>roles/ auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automl#automl.predictor">AutoML Predictor</a> ( <code>roles/ automl.predictor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code>roles/ automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/autoscaling#autoscaling.sitesAdmin">Autoscaling Site Admin</a> ( <code>roles/ autoscaling.sitesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.backupUser">Backup and DR Backup User</a> ( <code>roles/ backupdr.backupUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.computeEngineOperator">Backup and DR Compute Engine Operator</a> ( <code>roles/ backupdr.computeEngineOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.mountUser">Backup and DR Mount User</a> ( <code>roles/ backupdr.mountUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.restoreUser">Backup and DR Restore User</a> ( <code>roles/ backupdr.restoreUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.user">Backup and DR User</a> ( <code>roles/ backupdr.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.userv2">Backup and DR User V2</a> ( <code>roles/ backupdr.userv2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code>roles/ baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code>roles/ baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code>roles/ baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor">Batch Job Editor</a> ( <code>roles/ batch.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer">Batch Job Viewer</a> ( <code>roles/ batch.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor">Batch ResourceAllowance Editor</a> ( <code>roles/ batch.resourceAllowancesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer">Batch ResourceAllowance Viewer</a> ( <code>roles/ batch.resourceAllowancesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code>roles/ biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsAdmin">Binary Authorization Attestor Admin</a> ( <code>roles/ binaryauthorization.attestorsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsEditor">Binary Authorization Attestor Editor</a> ( <code>roles/ binaryauthorization.attestorsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsVerifier">Binary Authorization Attestor Image Verifier</a> ( <code>roles/ binaryauthorization.attestorsVerifier</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.attestorsViewer">Binary Authorization Attestor Viewer</a> ( <code>roles/ binaryauthorization.attestorsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyAdmin">Binary Authorization Policy Administrator</a> ( <code>roles/ binaryauthorization.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEditor">Binary Authorization Policy Editor</a> ( <code>roles/ binaryauthorization.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyEvaluator">Binary Authorization Policy Evaluator</a> ( <code>roles/ binaryauthorization.policyEvaluator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.policyViewer">Binary Authorization Policy Viewer</a> ( <code>roles/ binaryauthorization.policyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/browser#browser">Browser</a> ( <code>roles/ browser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/certificatemanager#certificatemanager.owner">Certificate Manager Owner</a> ( <code>roles/ certificatemanager.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.agentEditor">Gemini Enterprise for Customer Experience Agent Editor</a> ( <code>roles/ ces.agentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.appEditor">Gemini Enterprise for Customer Experience App Editor</a> ( <code>roles/ ces.appEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.deploymentEditor">Gemini Enterprise for Customer Experience Deployment Editor</a> ( <code>roles/ ces.deploymentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.evalsEditor">Gemini Enterprise for Customer Experience Evals Editor</a> ( <code>roles/ ces.evalsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.guardrailsEditor">Gemini Enterprise for Customer Experience Guardrails Editor</a> ( <code>roles/ ces.guardrailsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.securitySettingsEditor">Gemini Enterprise for Customer Experience Security Settings Editor</a> ( <code>roles/ ces.securitySettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.toolsEditor">Gemini Enterprise for Customer Experience Tools Editor</a> ( <code>roles/ ces.toolsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.dataGovernor">Chronicle API Data Governor</a> ( <code>roles/ chronicle.dataGovernor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationAdmin">Chronicle API Federation Admin</a> ( <code>roles/ chronicle.federationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.federationViewer">Chronicle API Federation Viewer</a> ( <code>roles/ chronicle.federationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.limitedViewer">Chronicle API Limited Viewer</a> ( <code>roles/ chronicle.limitedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.restrictedDataAccessViewer">Chronicle API Restricted Data Access Viewer</a> ( <code>roles/ chronicle.restrictedDataAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code>roles/ chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarRemoteAgent">Chronicle SOAR Remote Agent</a> ( <code>roles/ chronicle.soarRemoteAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code>roles/ chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code>roles/ chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesAdmin">Code Repository Indexes Admin</a> ( <code>roles/ cloudaicompanion.codeRepositoryIndexesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeRepositoryIndexesViewer">Code Repository Indexes Viewer</a> ( <code>roles/ cloudaicompanion.codeRepositoryIndexesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsAdmin">Gemini Code Assist Tools Admin</a> ( <code>roles/ cloudaicompanion.codeToolsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.approver">Cloud Build Approver</a> ( <code>roles/ cloudbuild.builds.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.editor">Cloud Build Editor</a> ( <code>roles/ cloudbuild.builds.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.builds.viewer">Cloud Build Viewer</a> ( <code>roles/ cloudbuild.builds.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionAdmin">Cloud Build Connection Admin</a> ( <code>roles/ cloudbuild.connectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.connectionViewer">Cloud Build Connection Viewer</a> ( <code>roles/ cloudbuild.connectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsEditor">Cloud Build Integrations Editor</a> ( <code>roles/ cloudbuild.integrationsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsOwner">Cloud Build Integrations Owner</a> ( <code>roles/ cloudbuild.integrationsOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.integrationsViewer">Cloud Build Integrations Viewer</a> ( <code>roles/ cloudbuild.integrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolEditor">Cloud Build WorkerPool Editor</a> ( <code>roles/ cloudbuild.workerPoolEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolOwner">Cloud Build WorkerPool Owner</a> ( <code>roles/ cloudbuild.workerPoolOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.workerPoolViewer">Cloud Build WorkerPool Viewer</a> ( <code>roles/ cloudbuild.workerPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.approver">Cloud Deploy Approver</a> ( <code>roles/ clouddeploy.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.customTargetTypeAdmin">Cloud Deploy Custom Target Type Admin</a> ( <code>roles/ clouddeploy.customTargetTypeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.developer">Cloud Deploy Developer</a> ( <code>roles/ clouddeploy.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.operator">Cloud Deploy Operator</a> ( <code>roles/ clouddeploy.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyAdmin">Cloud Deploy Policy Admin</a> ( <code>roles/ clouddeploy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.policyOverrider">Cloud Deploy Policy Overrider</a> ( <code>roles/ clouddeploy.policyOverrider</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/clouddeploy#clouddeploy.releaser">Cloud Deploy Releaser</a> ( <code>roles/ clouddeploy.releaser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.developer">Cloud Functions Developer</a> ( <code>roles/ cloudfunctions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsEditor">Cloud Talent Solution Job Editor</a> ( <code>roles/ cloudjobdiscovery.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.jobsViewer">Cloud Talent Solution Job Viewer</a> ( <code>roles/ cloudjobdiscovery.jobsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesEditor">Cloud Talent Solution Profile Editor</a> ( <code>roles/ cloudjobdiscovery.profilesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudjobdiscovery#cloudjobdiscovery.profilesViewer">Cloud Talent Solution Profile Viewer</a> ( <code>roles/ cloudjobdiscovery.profilesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyDecrypterViaDelegation">Cloud KMS CryptoKey Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterDecrypterViaDelegation">Cloud KMS CryptoKey Encrypter/Decrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterDecrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.cryptoKeyEncrypterViaDelegation">Cloud KMS CryptoKey Encrypter Via Delegation</a> ( <code>roles/ cloudkms.cryptoKeyEncrypterViaDelegation</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.ekmConnectionsAdmin">Cloud KMS EkmConnections Admin</a> ( <code>roles/ cloudkms.ekmConnectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertPqcSigner">Cloud KMS Expert PQ Asymmetric Signing Key Manager</a> ( <code>roles/ cloudkms.expertPqcSigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCbc">Cloud KMS Expert Raw AES-CBC Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCbc</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawAesCtr">Cloud KMS Expert Raw AES-CTR Key Manager</a> ( <code>roles/ cloudkms.expertRawAesCtr</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudkms#cloudkms.expertRawPKCS1">Cloud KMS Expert Raw PKCS#1 Key Manager</a> ( <code>roles/ cloudkms.expertRawPKCS1</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code>roles/ cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code>roles/ cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalog.consumer">Catalog Consumer</a> ( <code>roles/ cloudprivatecatalog.consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.manager">Catalog Manager</a> ( <code>roles/ cloudprivatecatalogproducer.manager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprivatecatalog#cloudprivatecatalogproducer.orgAdmin">Catalog Org Admin</a> ( <code>roles/ cloudprivatecatalogproducer.orgAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudprofiler#cloudprofiler.user">Cloud Profiler User</a> ( <code>roles/ cloudprofiler.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudscheduler#cloudscheduler.jobRunner">Cloud Scheduler Job Runner</a> ( <code>roles/ cloudscheduler.jobRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportEditor">Advisory Support Editor</a> ( <code>roles/ cloudsupport.advisorySupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.advisorySupportViewer">Advisory Support Viewer</a> ( <code>roles/ cloudsupport.advisorySupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportEditor">Tech Support Editor</a> ( <code>roles/ cloudsupport.techSupportEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsupport#cloudsupport.techSupportViewer">Tech Support Viewer</a> ( <code>roles/ cloudsupport.techSupportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.enqueuer">Cloud Tasks Enqueuer</a> ( <code>roles/ cloudtasks.enqueuer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.queueAdmin">Cloud Tasks Queue Admin</a> ( <code>roles/ cloudtasks.queueAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskDeleter">Cloud Tasks Task Deleter</a> ( <code>roles/ cloudtasks.taskDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.taskRunner">Cloud Tasks Task Runner</a> ( <code>roles/ cloudtasks.taskRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code>roles/ cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code>roles/ cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code>roles/ cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code>roles/ cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigAdmin">Commerce Business Enablement PaymentConfig Admin</a> ( <code>roles/ commercebusinessenablement.paymentConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.paymentConfigViewer">Commerce Business Enablement PaymentConfig Viewer</a> ( <code>roles/ commercebusinessenablement.paymentConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountAdmin">Commerce Business Enablement Reseller Discount Admin</a> ( <code>roles/ commercebusinessenablement.resellerDiscountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercebusinessenablement#commercebusinessenablement.resellerDiscountViewer">Commerce Business Enablement Reseller Discount Viewer</a> ( <code>roles/ commercebusinessenablement.resellerDiscountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commerceorggovernance#commerceorggovernance.user">Governed Marketplace User</a> ( <code>roles/ commerceorggovernance.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.eventsViewer">Commerce Price Management Events Viewer</a> ( <code>roles/ commercepricemanagement.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/commercepricemanagement#commercepricemanagement.privateOffersAdmin">Commerce Price Management Private Offers Admin</a> ( <code>roles/ commercepricemanagement.privateOffersAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectUser">Environment and Storage Object User</a> ( <code>roles/ composer.environmentAndStorageObjectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectViewer">Environment and Storage Object Viewer</a> ( <code>roles/ composer.environmentAndStorageObjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.imageUser">Compute Image User</a> ( <code>roles/ compute.imageUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.loadBalancerServiceUser">Compute Load Balancer Services User</a> ( <code>roles/ compute.loadBalancerServiceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyAdmin">Compute Organization Firewall Policy Admin</a> ( <code>roles/ compute.orgFirewallPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgFirewallPolicyUser">Compute Organization Firewall Policy User</a> ( <code>roles/ compute.orgFirewallPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyAdmin">Compute Organization Security Policy Admin</a> ( <code>roles/ compute.orgSecurityPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityPolicyUser">Compute Organization Security Policy User</a> ( <code>roles/ compute.orgSecurityPolicyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.orgSecurityResourceAdmin">Compute Organization Resource Admin</a> ( <code>roles/ compute.orgSecurityResourceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringAdmin">Compute packet mirroring admin</a> ( <code>roles/ compute.packetMirroringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.packetMirroringUser">Compute packet mirroring user</a> ( <code>roles/ compute.packetMirroringUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.publicIpAdmin">Compute Public IP Admin</a> ( <code>roles/ compute.publicIpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyAdmin">Compute VM extension policy admin</a> ( <code>roles/ compute.vmExtensionPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.vmExtensionPolicyViewer">Compute VM extension policy viewer</a> ( <code>roles/ compute.vmExtensionPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.xpnAdmin">Compute Shared VPC Admin</a> ( <code>roles/ compute.xpnAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryAdmin">ConfigDelivery Admin</a> ( <code>roles/ configdelivery.configDeliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.configDeliveryViewer">ConfigDelivery Viewer</a> ( <code>roles/ configdelivery.configDeliveryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/configdelivery#configdelivery.resourceBundlePublisher">Config Delivery Resource Bundle Publisher</a> ( <code>roles/ configdelivery.resourceBundlePublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementManager">Consumer Procurement Entitlement Manager</a> ( <code>roles/ consumerprocurement.entitlementManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.entitlementViewer">Consumer Procurement Entitlement Viewer</a> ( <code>roles/ consumerprocurement.entitlementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementAdmin">Consumer Procurement Administrator</a> ( <code>roles/ consumerprocurement.procurementAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/consumerprocurement#consumerprocurement.procurementViewer">Consumer Procurement Viewer</a> ( <code>roles/ consumerprocurement.procurementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.editor">Container Analysis Notes Editor</a> ( <code>roles/ containeranalysis.notes.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.notes.viewer">Container Analysis Notes Viewer</a> ( <code>roles/ containeranalysis.notes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.editor">Container Analysis Occurrences Editor</a> ( <code>roles/ containeranalysis.occurrences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.occurrences.viewer">Container Analysis Occurrences Viewer</a> ( <code>roles/ containeranalysis.occurrences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentAdmin">Content Warehouse Document Admin</a> ( <code>roles/ contentwarehouse.documentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentCreator">Content Warehouse document creator</a> ( <code>roles/ contentwarehouse.documentCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentEditor">Content Warehouse Document Editor</a> ( <code>roles/ contentwarehouse.documentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentSchemaViewer">Content Warehouse document schema viewer</a> ( <code>roles/ contentwarehouse.documentSchemaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contentwarehouse#contentwarehouse.documentViewer">Content Warehouse Viewer</a> ( <code>roles/ contentwarehouse.documentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryAdmin">Studio Query Admin</a> ( <code>roles/ databasesconsole.studioQueryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databasesconsole#databasesconsole.studioQueryUser">Studio Query User</a> ( <code>roles/ databasesconsole.studioQueryUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.categoryAdmin">Policy Tag Admin</a> ( <code>roles/ datacatalog.categoryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.dataSteward">DataCatalog Data Steward</a> ( <code>roles/ datacatalog.dataSteward</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupCreator">DataCatalog EntryGroup Creator</a> ( <code>roles/ datacatalog.entryGroupCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryGroupOwner">DataCatalog EntryGroup Owner</a> ( <code>roles/ datacatalog.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryOwner">DataCatalog Entry Owner</a> ( <code>roles/ datacatalog.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.entryViewer">DataCatalog Entry Viewer</a> ( <code>roles/ datacatalog.entryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.migrationConfigAdmin">DataCatalog Migration Config Admin</a> ( <code>roles/ datacatalog.migrationConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.searchAdmin">DataCatalog Search Admin</a> ( <code>roles/ datacatalog.searchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateOwner">Data Catalog TagTemplate Owner</a> ( <code>roles/ datacatalog.tagTemplateOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateUser">Data Catalog TagTemplate User</a> ( <code>roles/ datacatalog.tagTemplateUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datacatalog#datacatalog.tagTemplateViewer">Data Catalog TagTemplate Viewer</a> ( <code>roles/ datacatalog.tagTemplateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code>roles/ dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.developer">Dataflow Developer</a> ( <code>roles/ dataflow.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCommenter">Code Commenter</a> ( <code>roles/ dataform.codeCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeCreator">Code Creator</a> ( <code>roles/ dataform.codeCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeEditor">Code Editor</a> ( <code>roles/ dataform.codeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeOwner">Code Owner</a> ( <code>roles/ dataform.codeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.codeViewer">Code Viewer</a> ( <code>roles/ dataform.codeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderCommenter">Team Folder Commenter</a> ( <code>roles/ dataform.teamFolderCommenter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderContributor">Team Folder Contributor</a> ( <code>roles/ dataform.teamFolderContributor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderOwner">Team Folder Owner</a> ( <code>roles/ dataform.teamFolderOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.teamFolderViewer">Team Folder Viewer</a> ( <code>roles/ dataform.teamFolderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.accessor">Cloud Data Fusion Accessor</a> ( <code>roles/ datafusion.accessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.developer">Cloud Data Fusion Developer</a> ( <code>roles/ datafusion.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.operator">Cloud Data Fusion Operator</a> ( <code>roles/ datafusion.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.invoker">Data pipelines Invoker</a> ( <code>roles/ datapipelines.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeOwner">Dataplex Aspect Type Owner</a> ( <code>roles/ dataplex.aspectTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.aspectTypeUser">Dataplex Aspect Type User</a> ( <code>roles/ dataplex.aspectTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogAdmin">Dataplex Catalog Admin</a> ( <code>roles/ dataplex.catalogAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogEditor">Dataplex Catalog Editor</a> ( <code>roles/ dataplex.catalogEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.catalogViewer">Dataplex Catalog Viewer</a> ( <code>roles/ dataplex.catalogViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainAdmin">Dataplex Data Domain Admin</a> ( <code>roles/ dataplex.dataDomainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainEditor">Dataplex Data Domain Configuration Editor</a> ( <code>roles/ dataplex.dataDomainEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataDomainViewer">Dataplex Data Domain Configuration Viewer</a> ( <code>roles/ dataplex.dataDomainViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsAdmin">Dataplex Data Products Admin</a> ( <code>roles/ dataplex.dataProductsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsConsumer">Dataplex Data Products Consumer</a> ( <code>roles/ dataplex.dataProductsConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsEditor">Dataplex Data Products Editor</a> ( <code>roles/ dataplex.dataProductsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.dataProductsViewer">Dataplex Data Products Viewer</a> ( <code>roles/ dataplex.dataProductsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupExporter">Dataplex Entry Group Exporter</a> ( <code>roles/ dataplex.entryGroupExporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupImporter">Dataplex Entry Group Importer</a> ( <code>roles/ dataplex.entryGroupImporter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryGroupOwner">Dataplex Entry Group Owner</a> ( <code>roles/ dataplex.entryGroupOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeOwner">Dataplex Entry Link Type Owner</a> ( <code>roles/ dataplex.entryLinkTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryLinkTypeUser">Dataplex Entry Link Type User</a> ( <code>roles/ dataplex.entryLinkTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryOwner">Dataplex Entry and EntryLink Owner</a> ( <code>roles/ dataplex.entryOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeOwner">Dataplex Entry Type Owner</a> ( <code>roles/ dataplex.entryTypeOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.entryTypeUser">Dataplex Entry Type User</a> ( <code>roles/ dataplex.entryTypeUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedOwner">Dataplex Metadata Feed Owner</a> ( <code>roles/ dataplex.metadataFeedOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataFeedViewer">Dataplex Metadata Feed Viewer</a> ( <code>roles/ dataplex.metadataFeedViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobOwner">Dataplex Metadata Job Owner</a> ( <code>roles/ dataplex.metadataJobOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataJobViewer">Dataplex Metadata Job Viewer</a> ( <code>roles/ dataplex.metadataJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataReader">Dataplex Metadata Reader</a> ( <code>roles/ dataplex.metadataReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.metadataWriter">Dataplex Metadata Writer</a> ( <code>roles/ dataplex.metadataWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.hubAgent">Dataproc Hub Agent</a> ( <code>roles/ dataproc.hubAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessEditor">Dataproc Serverless Editor</a> ( <code>roles/ dataproc.serverlessEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serverlessViewer">Dataproc Serverless Viewer</a> ( <code>roles/ dataproc.serverlessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.bulkAdmin">Cloud Datastore Bulk Admin</a> ( <code>roles/ datastore.bulkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.importExportAdmin">Cloud Datastore Import Export Admin</a> ( <code>roles/ datastore.importExportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.indexAdmin">Cloud Datastore Index Admin</a> ( <code>roles/ datastore.indexAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firestore#datastore.keyVisualizerViewer">Cloud Datastore Key Visualizer Viewer</a> ( <code>roles/ datastore.keyVisualizerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dellemccloudonefs#dellemccloudonefs.user">Dell EMC Cloud OneFS User</a> ( <code>roles/ dellemccloudonefs.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeEditor">Deployment Manager Type Editor</a> ( <code>roles/ deploymentmanager.typeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#deploymentmanager.typeViewer">Deployment Manager Type Viewer</a> ( <code>roles/ deploymentmanager.typeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsAdmin">Developer Connect Insights Admin</a> ( <code>roles/ developerconnect.insightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.insightsViewer">Developer Connect Insights Viewer</a> ( <code>roles/ developerconnect.insightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthAdmin">Developer Connect OAuth Admin</a> ( <code>roles/ developerconnect.oauthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.oauthUser">Developer Connect OAuth User</a> ( <code>roles/ developerconnect.oauthUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.user">Developer Connect User</a> ( <code>roles/ developerconnect.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamAdmin">CX Premium Admin</a> ( <code>roles/ dialogflow.aamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamConversationalArchitect">CX Premium Conversational Architect</a> ( <code>roles/ dialogflow.aamConversationalArchitect</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamDialogDesigner">CX Premium Dialog Designer</a> ( <code>roles/ dialogflow.aamDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamLeadDialogDesigner">CX Premium Lead Dialog Designer</a> ( <code>roles/ dialogflow.aamLeadDialogDesigner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.aamViewer">CX Premium Viewer</a> ( <code>roles/ dialogflow.aamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSimulatorUser">Dialogflow Console Simulator User</a> ( <code>roles/ dialogflow.consoleSimulatorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.consoleSmartMessagingAllowlistEditor">Dialogflow Console Smart Messaging Allowlist Editor</a> ( <code>roles/ dialogflow.consoleSmartMessagingAllowlistEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceEditor">Gemini Enterprise Editor</a> ( <code>roles/ discoveryengine.agentspaceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceRestrictedUser">Gemini Enterprise Restricted User</a> ( <code>roles/ discoveryengine.agentspaceRestrictedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code>roles/ discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceViewer">Gemini Enterprise Viewer</a> ( <code>roles/ discoveryengine.agentspaceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmOwner">Cloud NotebookLM Admin</a> ( <code>roles/ discoveryengine.notebookLmOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.notebookLmUser">Cloud NotebookLM User</a> ( <code>roles/ discoveryengine.notebookLmUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code>roles/ discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsAdmin">Earth Subscriptions Administrator</a> ( <code>roles/ earth.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earth#earth.subscriptionsViewer">Earth Subscriptions Viewer</a> ( <code>roles/ earth.subscriptionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code>roles/ earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.machineUser">Edge Container Machine User</a> ( <code>roles/ edgecontainer.machineUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.offlineCredentialUser">Edge Container Cluster offline Credential User</a> ( <code>roles/ edgecontainer.offlineCredentialUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.connectionPublisher">Eventarc Connection Publisher</a> ( <code>roles/ eventarc.connectionPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.developer">Eventarc Developer</a> ( <code>roles/ eventarc.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.publisher">Eventarc Publisher</a> ( <code>roles/ eventarc.publisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code>roles/ faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsAdmin">Firebase Analytics Admin</a> ( <code>roles/ firebase.analyticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.analyticsViewer">Firebase Analytics Viewer</a> ( <code>roles/ firebase.analyticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.developer">Firebase App Hosting Developer</a> ( <code>roles/ firebaseapphosting.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensions#firebaseextensions.developer">Firebase Extensions Developer</a> ( <code>roles/ firebaseextensions.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code>roles/ firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code>roles/ firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliveryAdmin">Fleet Engine Delivery Admin</a> ( <code>roles/ fleetengine.deliveryAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.deliverySuperUser">Fleet Engine Delivery Super User</a> ( <code>roles/ fleetengine.deliverySuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.ondemandAdmin">Fleet Engine On-Demand Admin</a> ( <code>roles/ fleetengine.ondemandAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceSuperUser">Fleet Engine Service Super User</a> ( <code>roles/ fleetengine.serviceSuperUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code>roles/ gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code>roles/ gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.backupAdmin">Backup for GKE Backup Admin</a> ( <code>roles/ gkebackup.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.restoreAdmin">Backup for GKE Restore Admin</a> ( <code>roles/ gkebackup.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code>roles/ gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code>roles/ gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code>roles/ gsuiteaddons.tester</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationEditor">Healthcare Annotation Editor</a> ( <code>roles/ healthcare.annotationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationReader">Healthcare Annotation Reader</a> ( <code>roles/ healthcare.annotationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreAdmin">Healthcare Annotation Administrator</a> ( <code>roles/ healthcare.annotationStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.annotationStoreViewer">Healthcare Annotation Store Viewer</a> ( <code>roles/ healthcare.annotationStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionEditor">Healthcare Attribute Definition Editor</a> ( <code>roles/ healthcare.attributeDefinitionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.attributeDefinitionReader">Healthcare Attribute Definition Reader</a> ( <code>roles/ healthcare.attributeDefinitionReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactAdmin">Healthcare Consent Artifact Administrator</a> ( <code>roles/ healthcare.consentArtifactAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactEditor">Healthcare Consent Artifact Editor</a> ( <code>roles/ healthcare.consentArtifactEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentArtifactReader">Healthcare Consent Artifact Reader</a> ( <code>roles/ healthcare.consentArtifactReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentEditor">Healthcare Consent Editor</a> ( <code>roles/ healthcare.consentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentReader">Healthcare Consent Reader</a> ( <code>roles/ healthcare.consentReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreAdmin">Healthcare Consent Store Administrator</a> ( <code>roles/ healthcare.consentStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.consentStoreViewer">Healthcare Consent Store Viewer</a> ( <code>roles/ healthcare.consentStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetAdmin">Healthcare Dataset Administrator</a> ( <code>roles/ healthcare.datasetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.datasetViewer">Healthcare Dataset Viewer</a> ( <code>roles/ healthcare.datasetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomEditor">Healthcare DICOM Editor</a> ( <code>roles/ healthcare.dicomEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreAdmin">Healthcare DICOM Store Administrator</a> ( <code>roles/ healthcare.dicomStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomStoreViewer">Healthcare DICOM Store Viewer</a> ( <code>roles/ healthcare.dicomStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.dicomViewer">Healthcare DICOM Viewer</a> ( <code>roles/ healthcare.dicomViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceEditor">Healthcare FHIR Resource Editor</a> ( <code>roles/ healthcare.fhirResourceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirResourceReader">Healthcare FHIR Resource Reader</a> ( <code>roles/ healthcare.fhirResourceReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreAdmin">Healthcare FHIR Store Administrator</a> ( <code>roles/ healthcare.fhirStoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.fhirStoreViewer">Healthcare FHIR Store Viewer</a> ( <code>roles/ healthcare.fhirStoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Consumer">Healthcare HL7v2 Message Consumer</a> ( <code>roles/ healthcare.hl7V2Consumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Editor">Healthcare HL7v2 Message Editor</a> ( <code>roles/ healthcare.hl7V2Editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2Ingest">Healthcare HL7v2 Message Ingest</a> ( <code>roles/ healthcare.hl7V2Ingest</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreAdmin">Healthcare HL7v2 Store Administrator</a> ( <code>roles/ healthcare.hl7V2StoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.hl7V2StoreViewer">Healthcare HL7v2 Store Viewer</a> ( <code>roles/ healthcare.hl7V2StoreViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.nlpServiceViewer">Healthcare NLP Service Viewer</a> ( <code>roles/ healthcare.nlpServiceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingEditor">Healthcare User Data Mapping Editor</a> ( <code>roles/ healthcare.userDataMappingEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.userDataMappingReader">Healthcare User Data Mapping Reader</a> ( <code>roles/ healthcare.userDataMappingReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientAdmin">IAM OAuth Client Admin</a> ( <code>roles/ iam.oauthClientAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.oauthClientViewer">IAM OAuth Client Viewer</a> ( <code>roles/ iam.oauthClientViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleAdmin">Organization Role Administrator</a> ( <code>roles/ iam.organizationRoleAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.organizationRoleViewer">Organization Role Viewer</a> ( <code>roles/ iam.organizationRoleViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.serviceAccountDeleter">Delete Service Accounts</a> ( <code>roles/ iam.serviceAccountDeleter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolAdmin">IAM Workload Identity Pool Admin</a> ( <code>roles/ iam.workloadIdentityPoolAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.workloadIdentityPoolViewer">IAM Workload Identity Pool Viewer</a> ( <code>roles/ iam.workloadIdentityPoolViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationAdminRole">Apigee Integration Admin</a> ( <code>roles/ integrations.apigeeIntegrationAdminRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationDeployerRole">Apigee Integration Deployer</a> ( <code>roles/ integrations.apigeeIntegrationDeployerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationEditorRole">Apigee Integration Editor</a> ( <code>roles/ integrations.apigeeIntegrationEditorRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationInvokerRole">Apigee Integration Invoker</a> ( <code>roles/ integrations.apigeeIntegrationInvokerRole</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeIntegrationsViewer">Apigee Integration Viewer</a> ( <code>roles/ integrations.apigeeIntegrationsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.apigeeSuspensionResolver">Apigee Integration Approver</a> ( <code>roles/ integrations.apigeeSuspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.certificateViewer">Certificate Viewer</a> ( <code>roles/ integrations.certificateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationAdmin">Application Integration Admin</a> ( <code>roles/ integrations.integrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationDeployer">Application Integration Deployer</a> ( <code>roles/ integrations.integrationDeployer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationEditor">Application Integration Editor</a> ( <code>roles/ integrations.integrationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationInvoker">Application Integration Invoker</a> ( <code>roles/ integrations.integrationInvoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.integrationViewer">Application Integration Viewer</a> ( <code>roles/ integrations.integrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceAdmin">Application Integration SFDC Instance Admin</a> ( <code>roles/ integrations.sfdcInstanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceEditor">Application Integration SFDC Instance Editor</a> ( <code>roles/ integrations.sfdcInstanceEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.sfdcInstanceViewer">Application Integration SFDC Instance Viewer</a> ( <code>roles/ integrations.sfdcInstanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.suspensionResolver">Application Integration Approver</a> ( <code>roles/ integrations.suspensionResolver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerAdmin">Issuerswitch Account Manager Admin</a> ( <code>roles/ issuerswitch.accountManagerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsAdmin">Issuerswitch Account Manager Transactions Admin</a> ( <code>roles/ issuerswitch.accountManagerTransactionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.accountManagerTransactionsViewer">Issuerswitch Account Manager Transactions Viewer</a> ( <code>roles/ issuerswitch.accountManagerTransactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.issuerParticipantsAdmin">Issuerswitch Participants Admin</a> ( <code>roles/ issuerswitch.issuerParticipantsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.resolutionsAdmin">Issuerswitch Resolutions Admin</a> ( <code>roles/ issuerswitch.resolutionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesAdmin">Issuerswitch Rules Admin</a> ( <code>roles/ issuerswitch.rulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.rulesViewer">Issuerswitch Rules Viewer</a> ( <code>roles/ issuerswitch.rulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/issuerswitch#issuerswitch.transactionsViewer">Issuerswitch Transactions Viewer</a> ( <code>roles/ issuerswitch.transactionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/logging#logging.configWriter">Logs Configuration Writer</a> ( <code>roles/ logging.configWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code>roles/ looker.instanceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code>roles/ lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code>roles/ managedflink.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupAdmin">Google Cloud Managed Identities Backup Admin</a> ( <code>roles/ managedidentities.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.backupViewer">Google Cloud Managed Identities Backup Viewer</a> ( <code>roles/ managedidentities.backupViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.domainAdmin">Google Cloud Managed Identities Domain Admin</a> ( <code>roles/ managedidentities.domainAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringAdmin">Google Cloud Managed Identities Peering Admin</a> ( <code>roles/ managedidentities.peeringAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.peeringViewer">Google Cloud Managed Identities Peering Viewer</a> ( <code>roles/ managedidentities.peeringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.client">Managed Kafka Client</a> ( <code>roles/ managedkafka.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.clusterEditor">Managed Kafka Cluster Editor</a> ( <code>roles/ managedkafka.clusterEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.connectorEditor">Managed Kafka Connector Editor</a> ( <code>roles/ managedkafka.connectorEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.consumerGroupEditor">Managed Kafka Consumer Group Editor</a> ( <code>roles/ managedkafka.consumerGroupEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.topicEditor">Managed Kafka Topic Editor</a> ( <code>roles/ managedkafka.topicEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementEditor">Mandiant Attack Surface Management Editor</a> ( <code>roles/ mandiant.attackSurfaceManagementEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.attackSurfaceManagementViewer">Mandiant Attack Surface Management Viewer</a> ( <code>roles/ mandiant.attackSurfaceManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringEditor">Mandiant Digital Threat Monitoring Editor</a> ( <code>roles/ mandiant.digitalThreatMonitoringEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.digitalThreatMonitoringViewer">Mandiant Digital Threat Monitoring Viewer</a> ( <code>roles/ mandiant.digitalThreatMonitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandEditor">Mandiant Expertise On Demand Editor</a> ( <code>roles/ mandiant.expertiseOnDemandEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.expertiseOnDemandViewer">Mandiant Expertise On Demand Viewer</a> ( <code>roles/ mandiant.expertiseOnDemandViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelEditor">Mandiant Threat Intel Editor</a> ( <code>roles/ mandiant.threatIntelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.threatIntelViewer">Mandiant Threat Intel Viewer</a> ( <code>roles/ mandiant.threatIntelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationEditor">Mandiant Validation Editor</a> ( <code>roles/ mandiant.validationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mandiant#mandiant.validationViewer">Mandiant Validation Viewer</a> ( <code>roles/ mandiant.validationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.metadataOperator">Dataproc Metastore Metadata Operator</a> ( <code>roles/ metastore.metadataOperator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.user">Dataproc Metastore Viewer</a> ( <code>roles/ metastore.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.discoveryClientRegistrator">Migration Center Discovery Client Registrator</a> ( <code>roles/ migrationcenter.discoveryClientRegistrator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.calloutUser">Model Armor Callout User</a> ( <code>roles/ modelarmor.calloutUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsAdmin">Model Armor Floor Setting Admin</a> ( <code>roles/ modelarmor.floorSettingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.floorSettingsViewer">Model Armor Floor Setting Viewer</a> ( <code>roles/ modelarmor.floorSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.user">Model Armor User</a> ( <code>roles/ modelarmor.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesAdmin">Monitoring Metrics Scopes Admin</a> ( <code>roles/ monitoring.metricsScopesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesViewer">Monitoring Metrics Scopes Viewer</a> ( <code>roles/ monitoring.metricsScopesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin">Google Home Developer Console Admin</a> ( <code>roles/ nestconsole.homeDeveloperAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor">Google Home Developer Console Editor</a> ( <code>roles/ nestconsole.homeDeveloperEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer">Google Home Developer Console Reader</a> ( <code>roles/ nestconsole.homeDeveloperViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.consumerNetworkAdmin">Service Automation Consumer Network Admin</a> ( <code>roles/ networkconnectivity.consumerNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.groupAdmin">Group Admin</a> ( <code>roles/ networkconnectivity.groupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubAdmin">Hub &amp; Spoke Admin</a> ( <code>roles/ networkconnectivity.hubAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.hubViewer">Hub &amp; Spoke Viewer</a> ( <code>roles/ networkconnectivity.hubViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigAdmin">Multicloud Data Transfer Config Admin</a> ( <code>roles/ networkconnectivity.multicloudDataTransferConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferConfigViewer">Multicloud Data Transfer Config Viewer</a> ( <code>roles/ networkconnectivity.multicloudDataTransferConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationAdmin">Destination Admin</a> ( <code>roles/ networkconnectivity.multicloudDataTransferDestinationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.multicloudDataTransferDestinationViewer">Destination Viewer</a> ( <code>roles/ networkconnectivity.multicloudDataTransferDestinationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointAdmin">Regional Endpoint Admin</a> ( <code>roles/ networkconnectivity.regionalEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.regionalEndpointViewer">Regional Endpoint Viewer</a> ( <code>roles/ networkconnectivity.regionalEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceClassUser">Service Class User</a> ( <code>roles/ networkconnectivity.serviceClassUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceProducerAdmin">Service Automation Service Producer Admin</a> ( <code>roles/ networkconnectivity.serviceProducerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.spokeAdmin">Spoke Admin</a> ( <code>roles/ networkconnectivity.spokeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportAdmin">Transport Admin</a> ( <code>roles/ networkconnectivity.transportAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.transportViewer">Transport Viewer</a> ( <code>roles/ networkconnectivity.transportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsAdmin">Cloud Network Insights Admin</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsEditor">Cloud Network Insights Editor</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkmanagement#networkmanagement.CloudNetworkInsightsViewer">Cloud Network Insights Viewer</a> ( <code>roles/ networkmanagement.CloudNetworkInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorAdmin">DNS Threat Detector Admin</a> ( <code>roles/ networksecurity.dnsThreatDetectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.dnsThreatDetectorViewer">DNS Threat Detector Viewer</a> ( <code>roles/ networksecurity.dnsThreatDetectorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.firewallEndpointAdmin">Firewall Endpoint Admin</a> ( <code>roles/ networksecurity.firewallEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentAdmin">Intercept Deployment Admin</a> ( <code>roles/ networksecurity.interceptDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptDeploymentViewer">Intercept Deployment Viewer</a> ( <code>roles/ networksecurity.interceptDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointAdmin">Intercept Endpoint Admin</a> ( <code>roles/ networksecurity.interceptEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.interceptEndpointViewer">Intercept Endpoint Viewer</a> ( <code>roles/ networksecurity.interceptEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentAdmin">Mirroring Deployment Admin</a> ( <code>roles/ networksecurity.mirroringDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringDeploymentViewer">Mirroring Deployment Viewer</a> ( <code>roles/ networksecurity.mirroringDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointAdmin">Mirroring Endpoint Admin</a> ( <code>roles/ networksecurity.mirroringEndpointAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.mirroringEndpointViewer">Mirroring Endpoint Viewer</a> ( <code>roles/ networksecurity.mirroringEndpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networksecurity#networksecurity.securityProfileAdmin">Security Profile Admin</a> ( <code>roles/ networksecurity.securityProfileAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.GoogleTagGatewayPolicyAdmin">Google Tag Gateway Admin</a> ( <code>roles/ networkservices.GoogleTagGatewayPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code>roles/ networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code>roles/ networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyAdmin">Notebooks Legacy Admin</a> ( <code>roles/ notebooks.legacyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.legacyViewer">Notebooks Legacy Viewer</a> ( <code>roles/ notebooks.legacyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.runner">Notebooks Runner</a> ( <code>roles/ notebooks.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseAdmin">Oracle Database@Google Cloud Autonomous Database Admin</a> ( <code>roles/ oracledatabase.autonomousDatabaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.autonomousDatabaseViewer">Oracle Database@Google Cloud Autonomous Database Viewer</a> ( <code>roles/ oracledatabase.autonomousDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureAdmin">Oracle Database@Google Cloud Exadata Infrastructure Admin</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureUser">Oracle Database@Google Cloud Exadata Infrastructure User</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudExadataInfrastructureViewer">Oracle Database@Google Cloud Exadata Infrastructure Viewer</a> ( <code>roles/ oracledatabase.cloudExadataInfrastructureViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterAdmin">Oracle Database@Google Cloud VM Cluster Admin</a> ( <code>roles/ oracledatabase.cloudVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.cloudVmClusterViewer">Oracle Database@Google Cloud VM Cluster Viewer</a> ( <code>roles/ oracledatabase.cloudVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.databaseViewer">Oracle Database@Google Cloud Container Database Viewer</a> ( <code>roles/ oracledatabase.databaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemAdmin">Oracle Database@Google Cloud DB System Admin</a> ( <code>roles/ oracledatabase.dbSystemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.dbSystemViewer">Oracle Database@Google Cloud DB System Viewer</a> ( <code>roles/ oracledatabase.dbSystemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Admin</a> ( <code>roles/ oracledatabase.exadbVmClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exadbVmClusterViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure VM Cluster Viewer</a> ( <code>roles/ oracledatabase.exadbVmClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultAdmin">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Admin</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultUser">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault User</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.exascaleDbStorageVaultViewer">Oracle Database@Google Cloud Exadata Database Service on Exascale Infrastructure Storage Vault Viewer</a> ( <code>roles/ oracledatabase.exascaleDbStorageVaultViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAdmin">Oracle Database@Google Cloud GoldenGate Connection Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentAdmin">Oracle Database@Google Cloud GoldenGate Connection Assignment Admin</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionAssignmentViewer">Oracle Database@Google Cloud GoldenGate Connection Assignment Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionViewer">Oracle Database@Google Cloud GoldenGate Connection Viewer</a> ( <code>roles/ oracledatabase.goldenGateConnectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateConnectionsUser">Oracle Database@Google GoldenGate Connections User</a> ( <code>roles/ oracledatabase.goldenGateConnectionsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentAdmin">Oracle Database@Google Cloud GoldenGate Deployment Admin</a> ( <code>roles/ oracledatabase.goldenGateDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentViewer">Oracle Database@Google Cloud GoldenGate Deployment Viewer</a> ( <code>roles/ oracledatabase.goldenGateDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.goldenGateDeploymentsUser">Oracle Database@Google GoldenGate Deployments User</a> ( <code>roles/ oracledatabase.goldenGateDeploymentsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.networkAdmin">Oracle Database@Google Network Admin</a> ( <code>roles/ oracledatabase.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkAdmin">Oracle Database@Google ODB Network Admin</a> ( <code>roles/ oracledatabase.odbNetworkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbNetworkViewer">Oracle Database@Google ODB Network Viewer</a> ( <code>roles/ oracledatabase.odbNetworkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetAdmin">Oracle Database@Google ODB Subnet Admin</a> ( <code>roles/ oracledatabase.odbSubnetAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetUser">Oracle Database@Google ODB Subnet User</a> ( <code>roles/ oracledatabase.odbSubnetUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.odbSubnetViewer">Oracle Database@Google ODB Subnet Viewer</a> ( <code>roles/ oracledatabase.odbSubnetViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oracledatabase#oracledatabase.pluggableDatabaseViewer">Oracle Database@Google Cloud Pluggable Database Viewer</a> ( <code>roles/ oracledatabase.pluggableDatabaseViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code>roles/ osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code>roles/ osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code>roles/ osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code>roles/ osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code>roles/ osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code>roles/ osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code>roles/ osconfig.projectFeatureSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code>roles/ osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code>roles/ parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code>roles/ parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code>roles/ parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code>roles/ parametermanager.parameterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.templateVersionManager">Parameter Manager Template Version Manager</a> ( <code>roles/ parametermanager.templateVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.templateViewer">Parameter Manager Template Viewer</a> ( <code>roles/ parametermanager.templateViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerAdmin">Payments Reseller Admin</a> ( <code>roles/ paymentsresellersubscription.partnerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.partnerViewer">Payments Reseller Viewer</a> ( <code>roles/ paymentsresellersubscription.partnerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.productViewer">Payments Reseller Products Viewer</a> ( <code>roles/ paymentsresellersubscription.productViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.promotionViewer">Payments Reseller Promotions Viewer</a> ( <code>roles/ paymentsresellersubscription.promotionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionEditor">Payments Reseller Subscriptions Editor</a> ( <code>roles/ paymentsresellersubscription.subscriptionEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/paymentsresellersubscription#paymentsresellersubscription.subscriptionViewer">Payments Reseller Subscriptions Viewer</a> ( <code>roles/ paymentsresellersubscription.subscriptionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.auditor">CA Service Auditor</a> ( <code>roles/ privateca.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.caManager">CA Service Operation Manager</a> ( <code>roles/ privateca.caManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privateca#privateca.certificateManager">CA Service Certificate Manager</a> ( <code>roles/ privateca.certificateManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentEditor">Beacon Attachment Editor</a> ( <code>roles/ proximitybeacon.attachmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentPublisher">Beacon Attachment Publisher</a> ( <code>roles/ proximitybeacon.attachmentPublisher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.attachmentViewer">Beacon Attachment Viewer</a> ( <code>roles/ proximitybeacon.attachmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/proximitybeacon#proximitybeacon.beaconEditor">Beacon Editor</a> ( <code>roles/ proximitybeacon.beaconEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/publicca#publicca.externalAccountKeyCreator">External Account Key Creator</a> ( <code>roles/ publicca.externalAccountKeyCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.agent">reCAPTCHA Enterprise Agent</a> ( <code>roles/ recaptchaenterprise.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbAdmin">AlloyDB Recommender Admin</a> ( <code>roles/ recommender.alloydbAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.alloydbViewer">AlloyDB Recommender Viewer</a> ( <code>roles/ recommender.alloydbViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostAdmin">App Engine Version Cost Recommender Admin</a> ( <code>roles/ recommender.appengineversioncostAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.appengineversioncostViewer">App Engine Version Cost Recommender Viewer</a> ( <code>roles/ recommender.appengineversioncostViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsAdmin">BigQuery Slot Recommender Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectAdmin">BigQuery Recommender Project Admin</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsProjectViewer">BigQuery Recommender Project Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsProjectViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigQueryCapacityCommitmentsViewer">BigQuery Slot Recommender Viewer</a> ( <code>roles/ recommender.bigQueryCapacityCommitmentsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewAdmin">BigQuery Materialized View Recommender Admin</a> ( <code>roles/ recommender.bigqueryMaterializedViewAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryMaterializedViewViewer">BigQuery Materialized View Recommender Viewer</a> ( <code>roles/ recommender.bigqueryMaterializedViewViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterAdmin">BigQuery Partitioning Clustering Recommender Admin</a> ( <code>roles/ recommender.bigqueryPartitionClusterAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigqueryPartitionClusterViewer">BigQuery Partitioning Clustering Recommender Viewer</a> ( <code>roles/ recommender.bigqueryPartitionClusterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceAdmin">Bigtable Cluster Performance Recommender Admin</a> ( <code>roles/ recommender.bigtableClusterPerformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.bigtableClusterPerformanceViewer">Bigtable Cluster Performance Recommender Viewer</a> ( <code>roles/ recommender.bigtableClusterPerformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsAdmin">Cloud Asset Insights Admin</a> ( <code>roles/ recommender.cloudAssetInsightsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudAssetInsightsViewer">Cloud Asset Insights Viewer</a> ( <code>roles/ recommender.cloudAssetInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationAdmin">Cloud Cost General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudCostRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudCostRecommendationViewer">Cloud Cost General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudCostRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationAdmin">Cloud Deprecation General Recommender Admin</a> ( <code>roles/ recommender.cloudDeprecationRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudDeprecationRecommendationViewer">Cloud Deprecation General Recommender Viewer</a> ( <code>roles/ recommender.cloudDeprecationRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationAdmin">Cloud Manageability General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudManageabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudManageabilityRecommendationViewer">Cloud Manageability General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudManageabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationAdmin">Cloud Performance General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudPerformanceRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudPerformanceRecommendationViewer">Cloud Performance General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudPerformanceRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationAdmin">Cloud Reliability General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudReliabilityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudReliabilityRecommendationViewer">Cloud Reliability General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudReliabilityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationAdmin">Cloud Security General Recommendations Recommender Admin</a> ( <code>roles/ recommender.cloudSecurityRecommendationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudSecurityRecommendationViewer">Cloud Security General Recommendations Recommender Viewer</a> ( <code>roles/ recommender.cloudSecurityRecommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlAdmin">Cloud SQL Recommender Admin</a> ( <code>roles/ recommender.cloudsqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.cloudsqlViewer">Cloud SQL Recommender Viewer</a> ( <code>roles/ recommender.cloudsqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeAdmin">Compute Recommender Admin</a> ( <code>roles/ recommender.computeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.computeViewer">Compute Recommender Viewer</a> ( <code>roles/ recommender.computeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisAdmin">GKE Diagnosis Recommender Admin</a> ( <code>roles/ recommender.containerDiagnosisAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.containerDiagnosisViewer">GKE Diagnosis Recommender Viewer</a> ( <code>roles/ recommender.containerDiagnosisViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsAdmin">Dataflow Diagnostics Admin</a> ( <code>roles/ recommender.dataflowDiagnosticsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.dataflowDiagnosticsViewer">Dataflow Diagnostics Viewer</a> ( <code>roles/ recommender.dataflowDiagnosticsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingAdmin">Error Reporting Recommender Admin</a> ( <code>roles/ recommender.errorReportingAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.errorReportingViewer">Error Reporting Recommender Viewer</a> ( <code>roles/ recommender.errorReportingViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesAdmin">Firestore Database Firebase rules Recommender Admin</a> ( <code>roles/ recommender.firestoredatabasefirebaserulesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasefirebaserulesViewer">Firestore Database Firebase rules Recommender Viewer</a> ( <code>roles/ recommender.firestoredatabasefirebaserulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityAdmin">Firestore Database Reliability Recommender Admin</a> ( <code>roles/ recommender.firestoredatabasereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firestoredatabasereliabilityViewer">Firestore Database Reliability Recommender Viewer</a> ( <code>roles/ recommender.firestoredatabasereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallAdmin">Firewall Recommender Admin</a> ( <code>roles/ recommender.firewallAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallViewer">Firewall Recommender Viewer</a> ( <code>roles/ recommender.firewallViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpAdmin">Google Maps Platform Insights/Recommendations Admin</a> ( <code>roles/ recommender.gmpAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.gmpViewer">Google Maps Platform Insights/Recommendations Viewer</a> ( <code>roles/ recommender.gmpViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code>roles/ recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code>roles/ recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskAdmin">IAM Policy Change Risk Recommender Admin</a> ( <code>roles/ recommender.iampolicychangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iampolicychangeriskViewer">IAM Policy Change Risk Recommender Viewer</a> ( <code>roles/ recommender.iampolicychangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityAdmin">Memorystore Manageability Recommender Admin</a> ( <code>roles/ recommender.memorystoremanageabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoremanageabilityViewer">Memorystore Manageability Recommender Viewer</a> ( <code>roles/ recommender.memorystoremanageabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceAdmin">Memorystore Performance Recommender Admin</a> ( <code>roles/ recommender.memorystoreperformanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystoreperformanceViewer">Memorystore Performance Recommender Viewer</a> ( <code>roles/ recommender.memorystoreperformanceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityAdmin">Memorystore Reliability Recommender Admin</a> ( <code>roles/ recommender.memorystorereliabilityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.memorystorereliabilityViewer">Memorystore Reliability Recommender Viewer</a> ( <code>roles/ recommender.memorystorereliabilityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerAdmin">Network Analyzer Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlAdmin">Network Analyzer Cloud SQL Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerCloudSqlAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerCloudSqlViewer">Network Analyzer Cloud SQL Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerCloudSqlViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteAdmin">Network Analyzer Dynamic Route Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerDynamicRouteAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerDynamicRouteViewer">Network Analyzer Dynamic Route Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerDynamicRouteViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityAdmin">Network Analyzer GKE Connectivity Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeConnectivityViewer">Network Analyzer GKE Connectivity Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressAdmin">Network Analyzer GKE IP Address Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeIpAddressViewer">Network Analyzer GKE IP Address Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountAdmin">Network Analyzer GKE Service Account Insights Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerGkeServiceAccountAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerGkeServiceAccountViewer">Network Analyzer GKE Service Account Insights Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerGkeServiceAccountViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressAdmin">Network Analyzer IP Address Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerIpAddressAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerIpAddressViewer">Network Analyzer IP Address Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerIpAddressViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerAdmin">Network Analyzer Load Balancer Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerLoadBalancerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerLoadBalancerViewer">Network Analyzer Load Balancer Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerLoadBalancerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerViewer">Network Analyzer Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityAdmin">Network Analyzer VPC Connectivity Recommender Admin</a> ( <code>roles/ recommender.networkAnalyzerVpcConnectivityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.networkAnalyzerVpcConnectivityViewer">Network Analyzer VPC Connectivity Recommender Viewer</a> ( <code>roles/ recommender.networkAnalyzerVpcConnectivityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyAdmin">Org Policy Recommender Admin</a> ( <code>roles/ recommender.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.orgPolicyViewer">Org Policy Recommender Viewer</a> ( <code>roles/ recommender.orgPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionAdmin">Product Suggestion Recommenders Admin</a> ( <code>roles/ recommender.productSuggestionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.productSuggestionViewer">Product Suggestion Recommenders Viewer</a> ( <code>roles/ recommender.productSuggestionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudAdmin">Project Usage Commitment Recommender Admin</a> ( <code>roles/ recommender.projectCudAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectCudViewer">Project Usage Commitment Recommender Viewer</a> ( <code>roles/ recommender.projectCudViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilAdmin">Project Utilization Recommender Admin</a> ( <code>roles/ recommender.projectUtilAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.projectUtilViewer">Project Utilization Recommender Viewer</a> ( <code>roles/ recommender.projectUtilViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentChangeConfigAdmin">RecentChange RecommenderConfig Admin</a> ( <code>roles/ recommender.recentChangeConfigAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskAdmin">Recent Change Risk Recommender Admin</a> ( <code>roles/ recommender.recentchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.recentchangeriskViewer">Recent Change Risk Recommender Viewer</a> ( <code>roles/ recommender.recentchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitAdmin">Service Limit Recommender Admin</a> ( <code>roles/ recommender.serviceLimitAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceLimitViewer">Service Limit Recommender Viewer</a> ( <code>roles/ recommender.serviceLimitViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskAdmin">Service Account Change Risk Recommender Admin</a> ( <code>roles/ recommender.serviceaccntchangeriskAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.serviceaccntchangeriskViewer">Service Account Change Risk Recommender Viewer</a> ( <code>roles/ recommender.serviceaccntchangeriskViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerAdmin">Spanner Project Reliability Recommender Admin</a> ( <code>roles/ recommender.spannerAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.spannerViewer">Spanner Project Reliability Recommender Viewer</a> ( <code>roles/ recommender.spannerViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderCreator">Folder Creator</a> ( <code>roles/ resourcemanager.folderCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderEditor">Folder Editor</a> ( <code>roles/ resourcemanager.folderEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderViewer">Folder Viewer</a> ( <code>roles/ resourcemanager.folderViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code>roles/ retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code>roles/ retail.merchantCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code>roles/ riskmanager.reviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rma.runner">Rapid Migration Assessment Runner</a> ( <code>roles/ rma.runner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code>roles/ roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code>roles/ roads.roadsSelectionViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceDeveloper">Cloud Run Source Developer</a> ( <code>roles/ run.sourceDeveloper</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.sourceViewer">Cloud Run Source Viewer</a> ( <code>roles/ run.sourceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code>roles/ runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code>roles/ runapps.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionAdder">Secret Manager Secret Version Adder</a> ( <code>roles/ secretmanager.secretVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/secretmanager#secretmanager.secretVersionManager">Secret Manager Secret Version Manager</a> ( <code>roles/ secretmanager.secretVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchActivator">Overwatch Activator</a> ( <code>roles/ securedlandingzone.overwatchActivator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchAdmin">Overwatch Admin</a> ( <code>roles/ securedlandingzone.overwatchAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.overwatchViewer">Overwatch Viewer</a> ( <code>roles/ securedlandingzone.overwatchViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.developerConnectLinker">Secure Source Manager Developer Connect Linker</a> ( <code>roles/ securesourcemanager.developerConnectLinker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceAccessor">Secure Source Manager Instance Accessor</a> ( <code>roles/ securesourcemanager.instanceAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceManager">Secure Source Manager Instance Manager</a> ( <code>roles/ securesourcemanager.instanceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceOwner">Secure Source Manager Instance Owner</a> ( <code>roles/ securesourcemanager.instanceOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.instanceRepositoryCreator">Secure Source Manager Instance Repository Creator</a> ( <code>roles/ securesourcemanager.instanceRepositoryCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoAdmin">Secure Source Manager Repository Admin</a> ( <code>roles/ securesourcemanager.repoAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoCreator">Secure Source Manager Repository Creator</a> ( <code>roles/ securesourcemanager.repoCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoPullRequestApprover">Secure Source Manager Repository Pull Request Approver</a> ( <code>roles/ securesourcemanager.repoPullRequestApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoReader">Secure Source Manager Repository Reader</a> ( <code>roles/ securesourcemanager.repoReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.repoWriter">Secure Source Manager Repository Writer</a> ( <code>roles/ securesourcemanager.repoWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securesourcemanager#securesourcemanager.sshKeyUser">Secure Source Manager SSH Key User</a> ( <code>roles/ securesourcemanager.sshKeyUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code>roles/ securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code>roles/ securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code>roles/ securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code>roles/ securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code>roles/ securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesEditor">Security Center Management Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.customModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.customModulesViewer">Security Center Management Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.customModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesEditor">Security Center Management Custom ETD Modules Editor</a> ( <code>roles/ securitycentermanagement.etdCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.etdCustomModulesViewer">Security Center Management ETD Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.etdCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code>roles/ securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code>roles/ securitycentermanagement.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesEditor">Security Center Management SHA Custom Modules Editor</a> ( <code>roles/ securitycentermanagement.shaCustomModulesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.shaCustomModulesViewer">Security Center Management SHA Custom Modules Viewer</a> ( <code>roles/ securitycentermanagement.shaCustomModulesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code>roles/ servicedirectory.networkAttacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code>roles/ servicedirectory.pscAuthorizedService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code>roles/ spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code>roles/ spanner.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.viewer">Stackdriver Accounts Viewer</a> ( <code>roles/ stackdriver.accounts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.hmacKeyAdmin">Storage HMAC Key Admin</a> ( <code>roles/ storage.hmacKeyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.insightsCollectorService">Storage Insights Collector Service</a> ( <code>roles/ storage.insightsCollectorService</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code>roles/ storageinsights.analyst</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.user">Storage Transfer User</a> ( <code>roles/ storagetransfer.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentAdmin">Stream Content Admin</a> ( <code>roles/ stream.contentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.contentBuilder">Stream Content Builder</a> ( <code>roles/ stream.contentBuilder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.instanceAdmin">Stream Instance Admin</a> ( <code>roles/ stream.instanceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/subscribewithgoogledeveloper#subscribewithgoogledeveloper.developer">Subscribe with Google Developer</a> ( <code>roles/ subscribewithgoogledeveloper.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code>roles/ threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code>roles/ threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code>roles/ threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code>roles/ threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code>roles/ threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code>roles/ threatintelligence.ctemViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser">Translation Hub Portal User</a> ( <code>roles/ translationhub.portalUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.collectionWriter">Vector Search Collection Writer</a> ( <code>roles/ vectorsearch.collectionWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.dataObjectWriter">Vector Search DataObject Writer</a> ( <code>roles/ vectorsearch.dataObjectWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vectorsearch#vectorsearch.indexWriter">Vector Search Index Writer</a> ( <code>roles/ vectorsearch.indexWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/videostitcher#videostitcher.user">Video Stitcher User</a> ( <code>roles/ videostitcher.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code>roles/ vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code>roles/ vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code>roles/ vmwareengine.vmwareengineViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workflows#workflows.invoker">Workflows Invoker</a> ( <code>roles/ workflows.invoker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code>roles/ workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code>roles/ workloadcertificate.registrationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentViewer">Workload Manager Deployment Viewer</a> ( <code>roles/ workloadmanager.deploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationAdmin">Workload Manager Evaluation Admin</a> ( <code>roles/ workloadmanager.evaluationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.evaluationViewer">Workload Manager Evaluation Viewer</a> ( <code>roles/ workloadmanager.evaluationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.worker">Workload Manager Worker</a> ( <code>roles/ workloadmanager.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.workloadViewer">Workload Manager Workload Viewer</a> ( <code>roles/ workloadmanager.workloadViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code>roles/ workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code>roles/ workstations.workstationLimitExemptedCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/analyticshub#analyticshub.serviceAgent">Analytics Hub Service Agent</a> ( <code>roles/ analyticshub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthossupport#anthossupport.serviceAgent">Anthos Support Service Agent</a> ( <code>roles/ anthossupport.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code>roles/ backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.serviceAgent">Google Batch Service Agent</a> ( <code>roles/ batch.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/binaryauthorization#binaryauthorization.serviceAgent">Binary Authorization Service Agent</a> ( <code>roles/ binaryauthorization.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compliancescanning#compliancescanning.serviceAgent">Compliance Scanning Service Agent</a> ( <code>roles/ compliancescanning.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containeranalysis#containeranalysis.ServiceAgent">Container Analysis Service Agent</a> ( <code>roles/ containeranalysis.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerscanning#containerscanning.ServiceAgent">Container Scanner Service Agent</a> ( <code>roles/ containerscanning.ServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection#containerthreatdetection.serviceAgent">Container Threat Detection Service Agent</a> ( <code>roles/ containerthreatdetection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataform#dataform.serviceAgent">Dataform Service Agent</a> ( <code>roles/ dataform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalabeling#datalabeling.serviceAgent">Data Labeling Service Agent</a> ( <code>roles/ datalabeling.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.serviceAgent">Enterprise Knowledge Graph Service Agent</a> ( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/fleetengine#fleetengine.serviceAgent">FleetEngine Service Agent</a> ( <code>roles/ fleetengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gameservices#gameservices.serviceAgent">Game Services Service Agent</a> ( <code>roles/ gameservices.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.serviceAgent">Genomics Service Agent</a> ( <code>roles/ genomics.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code>roles/ gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement#gkedataplanemanagement.warpRunServiceAgent">Warp Run Service Agent</a> ( <code>roles/ gkedataplanemanagement.warpRunServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/integrations#integrations.serviceAgent">Application Integration Service Agent</a> ( <code>roles/ integrations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.serviceAgent">KRM API Hosting Service Agent</a> ( <code>roles/ krmapihosting.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.serviceAgent">Cloud Life Sciences Service Agent</a> ( <code>roles/ lifesciences.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/notebooks#notebooks.serviceAgent">AI Platform Notebooks Service Agent</a> ( <code>roles/ notebooks.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code>roles/ osconfig.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.serviceAgent">Parallelstore Service Agent</a> ( <code>roles/ parallelstore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/pubsub#pubsub.serviceAgent">Cloud Pub/Sub Service Agent</a> ( <code>roles/ pubsub.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code>roles/ riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.automationServiceAgent">Security Center Automation Service Agent</a> ( <code>roles/ securitycenter.automationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/stream#stream.serviceAgent">Stream Service Agent</a> ( <code>roles/ stream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.projects.move</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code>roles/ resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderMover">Folder Mover</a> ( <code>roles/ resourcemanager.folderMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. searchPolicyBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex#appengineflex.serviceAgent">App Engine flexible environment Service Agent</a> ( <code>roles/ appengineflex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.crossProjectServiceAgent">GKE Hub Cross Project Service Agent</a> ( <code>roles/ gkehub.crossProjectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.anthosApiEndpointServiceAgent">KRM API Hosting AnthosApiEndpoint Service Agent</a> ( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.projectServiceAgent">Privileged Access Manager Project Service Agent</a> ( <code>roles/ privilegedaccessmanager.projectServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/privilegedaccessmanager#privilegedaccessmanager.serviceAgent">Privileged Access Manager Service Agent</a> ( <code>roles/ privilegedaccessmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectMover">Project Mover</a> ( <code>roles/ resourcemanager.projectMover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwProjectRemediator">SLZ BQDW Blueprint Project Level Remediator</a> ( <code>roles/ securedlandingzone.bqdwProjectRemediator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code>roles/ firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. projects. updateLiens</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastudio#lookerstudio.proManager">Looker Studio Pro Manager</a> ( <code>roles/ lookerstudio.proManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.lienModifier">Project Lien Modifier</a> ( <code>roles/ resourcemanager.lienModifier</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasemods#firebasemods.serviceAgent">Firebase Extensions API Service Agent</a> ( <code>roles/ firebasemods.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkebackup#gkebackup.serviceAgent">Backup for GKE Service Agent</a> ( <code>roles/ gkebackup.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. projects. updatePolicyBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.folderAdmin">Folder Admin</a> ( <code>roles/ resourcemanager.folderAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.organizationAdmin">Organization Administrator</a> ( <code>roles/ resourcemanager.organizationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.projectIamAdmin">Project IAM Admin</a> ( <code>roles/ resourcemanager.projectIamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagHolds. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code>roles/ resourcemanager.tagHoldAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. tagHolds. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code>roles/ resourcemanager.tagHoldAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.tagHolds.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagHoldAdmin">Tag Hold Administrator</a> ( <code>roles/ resourcemanager.tagHoldAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.tagKeys.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.tagKeys.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.tagKeys.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagKeys. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.tagKeys.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagKeys. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager.tagKeys.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagValueBindings. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code>roles/ compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. tagValueBindings. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code>roles/ compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagValues. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. tagValues. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.tagValues.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code>roles/ securitycenter.resourceValueConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsViewer">Security Center Resource Value Configurations Viewer</a> ( <code>roles/ securitycenter.resourceValueConfigsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.instanceGroupManagerServiceAgent">Instance Group Manager Service Agent</a> ( <code>roles/ compute.instanceGroupManagerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. tagValues. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
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
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>resourcemanager.tagValues.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.viewer">Resource Manager Viewer</a> ( <code>roles/ resourcemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>resourcemanager. tagValues. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>resourcemanager. tagValues. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.editor">Resource Manager Editor</a> ( <code>roles/ resourcemanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagAdmin">Tag Administrator</a> ( <code>roles/ resourcemanager.tagAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code>roles/ dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
