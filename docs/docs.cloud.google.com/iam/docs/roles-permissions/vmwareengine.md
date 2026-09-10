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
<td><h4 id="vmwareengine.admin" class="role-title add-link" data-text="Vmwareengine Admin" tabindex="-1">Vmwareengine Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p>Admin role for vmwareengine</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.clusters.create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.clusters.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.clusters.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.clusters.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  clusters.  mountDatastore</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  clusters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  clusters.  unmountDatastore</code></li>
<li><code dir="ltr" translate="no">vmwareengine.clusters.update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  datastores.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  grant</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  revoke</code></li>
<li><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsForwarding.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  repair</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  migrateManagementVms</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  privateCloudDeletionNow</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetNsxCredentials</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetVcenterCredentials</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showNsxCredentials</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showVcenterCredentials</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  undelete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateClouds.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.projectState.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.services.use</code></li>
<li><code dir="ltr" translate="no">vmwareengine.services.view</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.update</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.editor" class="role-title add-link" data-text="Vmwareengine Editor" tabindex="-1">Vmwareengine Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p>Editor role for vmwareengine</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  mountDatastore</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  unmountDatastore</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  grant</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  revoke</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.dnsForwarding.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsForwarding.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.loggingServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  repair</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.operations.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  migrateManagementVms</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  privateCloudDeletionNow</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetNsxCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetVcenterCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showNsxCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showVcenterCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  undelete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.projectState.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.services.use</code></li>
<li><code dir="ltr" translate="no">vmwareengine.services.view</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.subnets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.subnets.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.viewer" class="role-title add-link" data-text="Vmwareengine Viewer" tabindex="-1">Vmwareengine Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p>Viewer role for vmwareengine</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.operations.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.operations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.projectState.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.services.view</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareengineAdmin" class="role-title add-link" data-text="VMware Engine Service Admin" tabindex="-1">VMware Engine Service Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p>Admin has full access to VMware Engine Service</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  mountDatastore</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  unmountDatastore</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.datastores.create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  datastores.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.datastores.update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  grant</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  revoke</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.dnsForwarding.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  dnsForwarding.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.loggingServers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  loggingServers.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  repair</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.networkPeerings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.networkPolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.operations.delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  create</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  migrateManagementVms</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetNsxCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetVcenterCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showNsxCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showVcenterCredentials</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  undelete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  update</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  privateConnections.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.projectState.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.services.use</code></li>
<li><code dir="ltr" translate="no">vmwareengine.services.view</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.subnets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.subnets.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.subnets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  create</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  delete</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareenginePrivilegedUser" class="role-title add-link" data-text="VMware Engine Service Privileged User" tabindex="-1">VMware Engine Service Privileged User</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p>Privileged User has access to VMWare Engine Service Privileged API, including accelerating private cloud deletion.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.delete</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.operations.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.operations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  privateCloudDeletionNow</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.projectState.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.services.use</code></li>
<li><code dir="ltr" translate="no">vmwareengine.services.view</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.subnets.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareengineViewer" class="role-title add-link" data-text="VMware Engine Service Viewer" tabindex="-1">VMware Engine Service Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p>Viewer has read-only access to VMware Engine Service</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.clusters.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.datastores.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.locations.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodeTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmwareengine.operations.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.operations.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.projectState.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.services.view</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.subnets.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p></td>
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
<td><h4 id="vmwareengine.serviceAgent" class="role-title add-link" data-text="VMware Engine Service Agent" tabindex="-1">VMware Engine Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</p>
<p>Gives permission to manage network configuration, such as establishing network peering, necessary for GCVE</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">dns.changes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.changes.create</code></li>
<li><code dir="ltr" translate="no">dns.changes.get</code></li>
<li><code dir="ltr" translate="no">dns.changes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.dnsKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.dnsKeys.get</code></li>
<li><code dir="ltr" translate="no">dns.dnsKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.gkeClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.  gkeClusters.  bindDNSResponsePolicy</code></li>
<li><code dir="ltr" translate="no">dns.  gkeClusters.  bindPrivateDNSZone</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZoneOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.get</code></li>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.update</code></p>
<p><code dir="ltr" translate="no">dns.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.  networks.  bindDNSResponsePolicy</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSPolicy</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></li>
<li><code dir="ltr" translate="no">dns.networks.useHealthSignals</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.policies.create</code></p>
<p><code dir="ltr" translate="no">dns.policies.delete</code></p>
<p><code dir="ltr" translate="no">dns.policies.get</code></p>
<p><code dir="ltr" translate="no">dns.policies.list</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">dns.policies.update</code></p>
<p><code dir="ltr" translate="no">dns.projects.get</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.get</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicies.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicyRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">file.instances.get</code></p>
<p><code dir="ltr" translate="no">file.instances.list</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.get</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></p>
<p><code dir="ltr" translate="no">vmwareengine.nodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmwareengine.nodes.get</code></li>
<li><code dir="ltr" translate="no">vmwareengine.nodes.list</code></li>
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
<td><h4 id="vmwareengine.clusters.create" class="permission-name add-link" data-text="vmwareengine.clusters.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.clusters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.clusters.delete" class="permission-name add-link" data-text="vmwareengine.clusters.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.clusters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.clusters.get" class="permission-name add-link" data-text="vmwareengine.clusters.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.clusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.clusters.getIamPolicy" class="permission-name add-link" data-text="vmwareengine.clusters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  clusters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.clusters.list" class="permission-name add-link" data-text="vmwareengine.clusters.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.clusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.clusters.mountDatastore" class="permission-name add-link" data-text="vmwareengine.clusters.mountDatastore" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  clusters.  mountDatastore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.clusters.setIamPolicy" class="permission-name add-link" data-text="vmwareengine.clusters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  clusters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.clusters.unmountDatastore" class="permission-name add-link" data-text="vmwareengine.clusters.unmountDatastore" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  clusters.  unmountDatastore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.clusters.update" class="permission-name add-link" data-text="vmwareengine.clusters.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.clusters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.datastores.create" class="permission-name add-link" data-text="vmwareengine.datastores.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.datastores.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.datastores.delete" class="permission-name add-link" data-text="vmwareengine.datastores.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.datastores.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.datastores.get" class="permission-name add-link" data-text="vmwareengine.datastores.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.datastores.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.datastores.getIamPolicy" class="permission-name add-link" data-text="vmwareengine.datastores.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  datastores.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.datastores.list" class="permission-name add-link" data-text="vmwareengine.datastores.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.datastores.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.datastores.setIamPolicy" class="permission-name add-link" data-text="vmwareengine.datastores.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  datastores.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.datastores.update" class="permission-name add-link" data-text="vmwareengine.datastores.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.datastores.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.dnsBindPermission.get" class="permission-name add-link" data-text="vmwareengine.dnsBindPermission.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.dnsBindPermission.grant" class="permission-name add-link" data-text="vmwareengine.dnsBindPermission.grant" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  grant</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.dnsBindPermission.revoke" class="permission-name add-link" data-text="vmwareengine.dnsBindPermission.revoke" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  dnsBindPermission.  revoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.dnsForwarding.get" class="permission-name add-link" data-text="vmwareengine.dnsForwarding.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.dnsForwarding.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.dnsForwarding.update" class="permission-name add-link" data-text="vmwareengine.dnsForwarding.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  dnsForwarding.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.externalAccessRules.create" class="permission-name add-link" data-text="vmwareengine.externalAccessRules.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.externalAccessRules.delete" class="permission-name add-link" data-text="vmwareengine.externalAccessRules.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.externalAccessRules.get" class="permission-name add-link" data-text="vmwareengine.externalAccessRules.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.externalAccessRules.list" class="permission-name add-link" data-text="vmwareengine.externalAccessRules.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.externalAccessRules.update" class="permission-name add-link" data-text="vmwareengine.externalAccessRules.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAccessRules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.externalAddresses.create" class="permission-name add-link" data-text="vmwareengine.externalAddresses.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.externalAddresses.delete" class="permission-name add-link" data-text="vmwareengine.externalAddresses.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.externalAddresses.get" class="permission-name add-link" data-text="vmwareengine.externalAddresses.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.externalAddresses.list" class="permission-name add-link" data-text="vmwareengine.externalAddresses.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.externalAddresses.update" class="permission-name add-link" data-text="vmwareengine.externalAddresses.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  externalAddresses.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.hcxActivationKeys.create" class="permission-name add-link" data-text="vmwareengine.hcxActivationKeys.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.hcxActivationKeys.get" class="permission-name add-link" data-text="vmwareengine.hcxActivationKeys.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.hcxActivationKeys.getIamPolicy" class="permission-name add-link" data-text="vmwareengine.hcxActivationKeys.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.hcxActivationKeys.list" class="permission-name add-link" data-text="vmwareengine.hcxActivationKeys.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.hcxActivationKeys.setIamPolicy" class="permission-name add-link" data-text="vmwareengine.hcxActivationKeys.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  hcxActivationKeys.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.locations.get" class="permission-name add-link" data-text="vmwareengine.locations.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.locations.list" class="permission-name add-link" data-text="vmwareengine.locations.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.loggingServers.create" class="permission-name add-link" data-text="vmwareengine.loggingServers.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  loggingServers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.loggingServers.delete" class="permission-name add-link" data-text="vmwareengine.loggingServers.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  loggingServers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.loggingServers.get" class="permission-name add-link" data-text="vmwareengine.loggingServers.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  loggingServers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.loggingServers.list" class="permission-name add-link" data-text="vmwareengine.loggingServers.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  loggingServers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.loggingServers.update" class="permission-name add-link" data-text="vmwareengine.loggingServers.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  loggingServers.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.managementDnsZoneBindings.create" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.managementDnsZoneBindings.delete" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.managementDnsZoneBindings.get" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.managementDnsZoneBindings.list" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.managementDnsZoneBindings.repair" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.repair" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  repair</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.managementDnsZoneBindings.update" class="permission-name add-link" data-text="vmwareengine.managementDnsZoneBindings.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  managementDnsZoneBindings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPeerings.create" class="permission-name add-link" data-text="vmwareengine.networkPeerings.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPeerings.createTagBinding" class="permission-name add-link" data-text="vmwareengine.networkPeerings.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPeerings.delete" class="permission-name add-link" data-text="vmwareengine.networkPeerings.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPeerings.deleteTagBinding" class="permission-name add-link" data-text="vmwareengine.networkPeerings.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPeerings.get" class="permission-name add-link" data-text="vmwareengine.networkPeerings.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPeerings.list" class="permission-name add-link" data-text="vmwareengine.networkPeerings.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPeerings.listEffectiveTags" class="permission-name add-link" data-text="vmwareengine.networkPeerings.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPeerings.listPeeringRoutes" class="permission-name add-link" data-text="vmwareengine.networkPeerings.listPeeringRoutes" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listPeeringRoutes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPeerings.listTagBindings" class="permission-name add-link" data-text="vmwareengine.networkPeerings.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPeerings.update" class="permission-name add-link" data-text="vmwareengine.networkPeerings.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPolicies.create" class="permission-name add-link" data-text="vmwareengine.networkPolicies.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPolicies.createTagBinding" class="permission-name add-link" data-text="vmwareengine.networkPolicies.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPolicies.delete" class="permission-name add-link" data-text="vmwareengine.networkPolicies.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPolicies.deleteTagBinding" class="permission-name add-link" data-text="vmwareengine.networkPolicies.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPolicies.fetchExternalAddresses" class="permission-name add-link" data-text="vmwareengine.networkPolicies.fetchExternalAddresses" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  fetchExternalAddresses</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPolicies.get" class="permission-name add-link" data-text="vmwareengine.networkPolicies.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPolicies.list" class="permission-name add-link" data-text="vmwareengine.networkPolicies.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPolicies.listEffectiveTags" class="permission-name add-link" data-text="vmwareengine.networkPolicies.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.networkPolicies.listTagBindings" class="permission-name add-link" data-text="vmwareengine.networkPolicies.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.networkPolicies.update" class="permission-name add-link" data-text="vmwareengine.networkPolicies.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.nodeTypes.get" class="permission-name add-link" data-text="vmwareengine.nodeTypes.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.nodeTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.nodeTypes.list" class="permission-name add-link" data-text="vmwareengine.nodeTypes.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.nodeTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.nodes.get" class="permission-name add-link" data-text="vmwareengine.nodes.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.nodes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.nodes.list" class="permission-name add-link" data-text="vmwareengine.nodes.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.nodes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.operations.delete" class="permission-name add-link" data-text="vmwareengine.operations.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.operations.get" class="permission-name add-link" data-text="vmwareengine.operations.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.operations.list" class="permission-name add-link" data-text="vmwareengine.operations.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.create" class="permission-name add-link" data-text="vmwareengine.privateClouds.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.createTagBinding" class="permission-name add-link" data-text="vmwareengine.privateClouds.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.delete" class="permission-name add-link" data-text="vmwareengine.privateClouds.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.deleteTagBinding" class="permission-name add-link" data-text="vmwareengine.privateClouds.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.get" class="permission-name add-link" data-text="vmwareengine.privateClouds.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.privateClouds.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.getIamPolicy" class="permission-name add-link" data-text="vmwareengine.privateClouds.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.list" class="permission-name add-link" data-text="vmwareengine.privateClouds.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.listEffectiveTags" class="permission-name add-link" data-text="vmwareengine.privateClouds.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.listTagBindings" class="permission-name add-link" data-text="vmwareengine.privateClouds.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.migrateManagementVms" class="permission-name add-link" data-text="vmwareengine.privateClouds.migrateManagementVms" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  migrateManagementVms</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.privateCloudDeletionNow" class="permission-name add-link" data-text="vmwareengine.privateClouds.privateCloudDeletionNow" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  privateCloudDeletionNow</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.resetNsxCredentials" class="permission-name add-link" data-text="vmwareengine.privateClouds.resetNsxCredentials" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetNsxCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.resetVcenterCredentials" class="permission-name add-link" data-text="vmwareengine.privateClouds.resetVcenterCredentials" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  resetVcenterCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.setIamPolicy" class="permission-name add-link" data-text="vmwareengine.privateClouds.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.showNsxCredentials" class="permission-name add-link" data-text="vmwareengine.privateClouds.showNsxCredentials" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showNsxCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.showVcenterCredentials" class="permission-name add-link" data-text="vmwareengine.privateClouds.showVcenterCredentials" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  showVcenterCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateClouds.undelete" class="permission-name add-link" data-text="vmwareengine.privateClouds.undelete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateClouds.update" class="permission-name add-link" data-text="vmwareengine.privateClouds.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateClouds.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateConnections.create" class="permission-name add-link" data-text="vmwareengine.privateConnections.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateConnections.createTagBinding" class="permission-name add-link" data-text="vmwareengine.privateConnections.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateConnections.delete" class="permission-name add-link" data-text="vmwareengine.privateConnections.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateConnections.deleteTagBinding" class="permission-name add-link" data-text="vmwareengine.privateConnections.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateConnections.get" class="permission-name add-link" data-text="vmwareengine.privateConnections.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateConnections.list" class="permission-name add-link" data-text="vmwareengine.privateConnections.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateConnections.listEffectiveTags" class="permission-name add-link" data-text="vmwareengine.privateConnections.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateConnections.listPeeringRoutes" class="permission-name add-link" data-text="vmwareengine.privateConnections.listPeeringRoutes" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listPeeringRoutes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.privateConnections.listTagBindings" class="permission-name add-link" data-text="vmwareengine.privateConnections.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.privateConnections.update" class="permission-name add-link" data-text="vmwareengine.privateConnections.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  privateConnections.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.projectState.get" class="permission-name add-link" data-text="vmwareengine.projectState.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.projectState.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.services.use" class="permission-name add-link" data-text="vmwareengine.services.use" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.services.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.services.view" class="permission-name add-link" data-text="vmwareengine.services.view" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.services.view</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.subnets.get" class="permission-name add-link" data-text="vmwareengine.subnets.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.subnets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.subnets.list" class="permission-name add-link" data-text="vmwareengine.subnets.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.subnets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.subnets.update" class="permission-name add-link" data-text="vmwareengine.subnets.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.subnets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareEngineNetworks.create" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.create" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareEngineNetworks.createTagBinding" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareEngineNetworks.delete" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.delete" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareEngineNetworks.deleteTagBinding" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareEngineNetworks.get" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.get" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareEngineNetworks.list" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.list" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareEngineNetworks.listEffectiveTags" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmwareengine.vmwareEngineNetworks.listTagBindings" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.viewer">Vmwareengine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareenginePrivilegedUser">VMware Engine Service Privileged User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareenginePrivilegedUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineViewer">VMware Engine Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmwareengine.vmwareEngineNetworks.update" class="permission-name add-link" data-text="vmwareengine.vmwareEngineNetworks.update" tabindex="-1"><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.admin">Vmwareengine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.editor">Vmwareengine Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.vmwareengineAdmin">VMware Engine Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.vmwareengineAdmin</code> )</p></td>
</tr>
</tbody>
</table>
