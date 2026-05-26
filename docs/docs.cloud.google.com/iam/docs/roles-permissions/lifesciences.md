---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/lifesciences
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences
title: Cloud Life Sciences roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Life Sciences. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Life Sciences roles

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
<td><h4 id="genomics.admin" class="role-title add-link" data-text="Genomics Admin" tabindex="-1">Genomics Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p>Full access to genomics datasets and operations.</p></td>
<td><p><code dir="ltr" translate="no">genomics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">genomics.datasets.create</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.delete</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.get</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.list</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">genomics.datasets.update</code></li>
<li><code dir="ltr" translate="no">genomics.operations.cancel</code></li>
<li><code dir="ltr" translate="no">genomics.operations.create</code></li>
<li><code dir="ltr" translate="no">genomics.operations.get</code></li>
<li><code dir="ltr" translate="no">genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="genomics.editor" class="role-title add-link" data-text="Genomics Editor" tabindex="-1">Genomics Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p>Access to read and edit genomics datasets and operations.</p></td>
<td><p><code dir="ltr" translate="no">genomics.datasets.create</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.delete</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.get</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.list</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.update</code></p>
<p><code dir="ltr" translate="no">genomics.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">genomics.operations.cancel</code></li>
<li><code dir="ltr" translate="no">genomics.operations.create</code></li>
<li><code dir="ltr" translate="no">genomics.operations.get</code></li>
<li><code dir="ltr" translate="no">genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.viewer" class="role-title add-link" data-text="Genomics Viewer" tabindex="-1">Genomics Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  genomics.viewer</code> )</p>
<p>Access to view genomics datasets and operations.</p></td>
<td><p><code dir="ltr" translate="no">genomics.datasets.get</code></p>
<p><code dir="ltr" translate="no">genomics.datasets.list</code></p>
<p><code dir="ltr" translate="no">genomics.operations.get</code></p>
<p><code dir="ltr" translate="no">genomics.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.admin" class="role-title add-link" data-text="Cloud Life Sciences Admin Beta" tabindex="-1">Cloud Life Sciences Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lifesciences.admin</code> )</p>
<p>Full control of Cloud Life Sciences resources.</p></td>
<td><p><code dir="ltr" translate="no">lifesciences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">lifesciences.operations.cancel</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.get</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.list</code></li>
<li><code dir="ltr" translate="no">lifesciences.workflows.run</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="lifesciences.editor" class="role-title add-link" data-text="Cloud Life Sciences Editor Beta" tabindex="-1">Cloud Life Sciences Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lifesciences.editor</code> )</p>
<p>Access to read and edit Cloud Life Sciences resources.</p></td>
<td><p><code dir="ltr" translate="no">lifesciences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">lifesciences.operations.cancel</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.get</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.list</code></li>
<li><code dir="ltr" translate="no">lifesciences.workflows.run</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.viewer" class="role-title add-link" data-text="Cloud Life Sciences Viewer Beta" tabindex="-1">Cloud Life Sciences Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lifesciences.viewer</code> )</p>
<p>Access to read Cloud Life Sciences resources.</p></td>
<td><p><code dir="ltr" translate="no">lifesciences.operations.get</code></p>
<p><code dir="ltr" translate="no">lifesciences.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.pipelinesRunner" class="role-title add-link" data-text="Genomics Pipelines Runner" tabindex="-1">Genomics Pipelines Runner</h4>
<p>( <code dir="ltr" translate="no">roles/  genomics.pipelinesRunner</code> )</p>
<p>Full access to operate on genomics pipelines.</p></td>
<td><p><code dir="ltr" translate="no">genomics.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">genomics.operations.cancel</code></li>
<li><code dir="ltr" translate="no">genomics.operations.create</code></li>
<li><code dir="ltr" translate="no">genomics.operations.get</code></li>
<li><code dir="ltr" translate="no">genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.workflowsRunner" class="role-title add-link" data-text="Cloud Life Sciences Workflows Runner Beta" tabindex="-1">Cloud Life Sciences Workflows Runner <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  lifesciences.workflowsRunner</code> )</p>
<p>Full access to operate on Cloud Life Sciences workflows.</p></td>
<td><p><code dir="ltr" translate="no">lifesciences.*</code></p>
<ul>
<li><code dir="ltr" translate="no">lifesciences.operations.cancel</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.get</code></li>
<li><code dir="ltr" translate="no">lifesciences.operations.list</code></li>
<li><code dir="ltr" translate="no">lifesciences.workflows.run</code></li>
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
<td><h4 id="genomics.serviceAgent" class="role-title add-link" data-text="Genomics Service Agent" tabindex="-1">Genomics Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  genomics.serviceAgent</code> )</p>
<p>Gives Genomics Service Account access to compute resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.autoscalers.create</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.delete</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.get</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.list</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.diskSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  disks.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.create</code></li>
<li><code dir="ltr" translate="no">compute.disks.createSnapshot</code></li>
<li><code dir="ltr" translate="no">compute.disks.createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.delete</code></li>
<li><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.get</code></li>
<li><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.list</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.disks.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.resize</code></li>
<li><code dir="ltr" translate="no">compute.disks.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  startAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopGroupAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.disks.update</code></li>
<li><code dir="ltr" translate="no">compute.disks.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.disks.use</code></li>
<li><code dir="ltr" translate="no">compute.disks.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.use</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.images.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.images.create</code></li>
<li><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.delete</code></li>
<li><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.deprecate</code></li>
<li><code dir="ltr" translate="no">compute.images.get</code></li>
<li><code dir="ltr" translate="no">compute.images.getFromFamily</code></li>
<li><code dir="ltr" translate="no">compute.images.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.list</code></li>
<li><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.images.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.images.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.images.update</code></li>
<li><code dir="ltr" translate="no">compute.images.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.update</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceSettings.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instances.  addAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.attachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.create</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.detachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.get</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></li>
<li><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedInstanceIdentity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedVmIdentity</code></li>
<li><code dir="ltr" translate="no">compute.instances.list</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instances.osAdminLogin</code></li>
<li><code dir="ltr" translate="no">compute.instances.osLogin</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.reset</code></li>
<li><code dir="ltr" translate="no">compute.instances.resume</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  sendDiagnosticInterrupt</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></li>
<li><code dir="ltr" translate="no">compute.instances.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineResources</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineType</code></li>
<li><code dir="ltr" translate="no">compute.instances.setMetadata</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMinCpuPlatform</code></li>
<li><code dir="ltr" translate="no">compute.instances.setName</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setScheduling</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedInstanceIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedVmIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  simulateMaintenanceEvent</code></li>
<li><code dir="ltr" translate="no">compute.instances.start</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  startWithEncryptionKey</code></li>
<li><code dir="ltr" translate="no">compute.instances.stop</code></li>
<li><code dir="ltr" translate="no">compute.instances.suspend</code></li>
<li><code dir="ltr" translate="no">compute.instances.update</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateSecurity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedInstanceConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedVmConfig</code></li>
<li><code dir="ltr" translate="no">compute.instances.use</code></li>
<li><code dir="ltr" translate="no">compute.instances.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  export</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
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
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.licenseCodes.get</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.licenseCodes.list</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenses.create</code></p>
<p><code dir="ltr" translate="no">compute.licenses.delete</code></p>
<p><code dir="ltr" translate="no">compute.licenses.get</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.update</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.create</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.delete</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.get</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMig.create</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.delete</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.use</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshotGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshots.create</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.get</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.spotAssistants.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.serviceAgent" class="role-title add-link" data-text="Cloud Life Sciences Service Agent" tabindex="-1">Cloud Life Sciences Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  lifesciences.serviceAgent</code> )</p>
<p>Gives Cloud Life Sciences Service Account access to compute resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  createForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  deleteForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  fetchForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  getForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  triggerBackupForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlanAssociations.  updateForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeDisk</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupPlans.  useForComputeInstance</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.autoscalers.create</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.delete</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.get</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.list</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.backendBuckets.get</code></p>
<p><code dir="ltr" translate="no">compute.backendBuckets.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.crossSiteNetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.diskSettings.get</code></p>
<p><code dir="ltr" translate="no">compute.diskTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.diskTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.diskTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  disks.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.create</code></li>
<li><code dir="ltr" translate="no">compute.disks.createSnapshot</code></li>
<li><code dir="ltr" translate="no">compute.disks.createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.delete</code></li>
<li><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.disks.get</code></li>
<li><code dir="ltr" translate="no">compute.disks.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.list</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.disks.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.disks.resize</code></li>
<li><code dir="ltr" translate="no">compute.disks.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.disks.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  startAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.  disks.  stopGroupAsyncReplication</code></li>
<li><code dir="ltr" translate="no">compute.disks.update</code></li>
<li><code dir="ltr" translate="no">compute.disks.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.disks.use</code></li>
<li><code dir="ltr" translate="no">compute.disks.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  get</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  list</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.use</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.images.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.images.create</code></li>
<li><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.delete</code></li>
<li><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.images.deprecate</code></li>
<li><code dir="ltr" translate="no">compute.images.get</code></li>
<li><code dir="ltr" translate="no">compute.images.getFromFamily</code></li>
<li><code dir="ltr" translate="no">compute.images.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.list</code></li>
<li><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.images.listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.images.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.images.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.images.update</code></li>
<li><code dir="ltr" translate="no">compute.images.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.update</code></li>
<li><code dir="ltr" translate="no">compute.instanceGroups.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.instanceSettings.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instanceTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.get</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instanceTemplates.list</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instances.  addAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  addResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.attachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.create</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.delete</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.instances.detachDisk</code></li>
<li><code dir="ltr" translate="no">compute.instances.get</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getEffectiveFirewalls</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></li>
<li><code dir="ltr" translate="no">compute.instances.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getScreenshot</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedInstanceIdentity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  getShieldedVmIdentity</code></li>
<li><code dir="ltr" translate="no">compute.instances.list</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listReferrers</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.instances.osAdminLogin</code></li>
<li><code dir="ltr" translate="no">compute.instances.osLogin</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  pscInterfaceCreate</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  removeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">compute.instances.reset</code></li>
<li><code dir="ltr" translate="no">compute.instances.resume</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  sendDiagnosticInterrupt</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDeletionProtection</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setDiskAutoDelete</code></li>
<li><code dir="ltr" translate="no">compute.instances.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineResources</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMachineType</code></li>
<li><code dir="ltr" translate="no">compute.instances.setMetadata</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setMinCpuPlatform</code></li>
<li><code dir="ltr" translate="no">compute.instances.setName</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setScheduling</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedInstanceIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  setShieldedVmIntegrityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.instances.setTags</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  simulateMaintenanceEvent</code></li>
<li><code dir="ltr" translate="no">compute.instances.start</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  startWithEncryptionKey</code></li>
<li><code dir="ltr" translate="no">compute.instances.stop</code></li>
<li><code dir="ltr" translate="no">compute.instances.suspend</code></li>
<li><code dir="ltr" translate="no">compute.instances.update</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateAccessConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateDisplayDevice</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateNetworkInterface</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateSecurity</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedInstanceConfig</code></li>
<li><code dir="ltr" translate="no">compute.  instances.  updateShieldedVmConfig</code></li>
<li><code dir="ltr" translate="no">compute.instances.use</code></li>
<li><code dir="ltr" translate="no">compute.instances.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  instantSnapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  export</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.instantSnapshots.list</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachmentGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
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
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenseCodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.licenseCodes.get</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.licenseCodes.list</code></li>
<li><code dir="ltr" translate="no">compute.  licenseCodes.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.licenses.create</code></p>
<p><code dir="ltr" translate="no">compute.licenses.delete</code></p>
<p><code dir="ltr" translate="no">compute.licenses.get</code></p>
<p><code dir="ltr" translate="no">compute.licenses.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.list</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.licenses.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.licenses.update</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.create</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.delete</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.get</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.list</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.multiMig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.multiMig.create</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.delete</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.get</code></li>
<li><code dir="ltr" translate="no">compute.multiMig.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networkProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.networkProfiles.get</code></li>
<li><code dir="ltr" translate="no">compute.networkProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionCompositeHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthAggregationPolicies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthCheckServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthSources.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNotificationEndpoints.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.reservationBlocks.get</code></p>
<p><code dir="ltr" translate="no">compute.reservationBlocks.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  get</code></p>
<p><code dir="ltr" translate="no">compute.  reservationSubBlocks.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.resourcePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.get</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.list</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  update</code></li>
<li><code dir="ltr" translate="no">compute.resourcePolicies.use</code></li>
<li><code dir="ltr" translate="no">compute.  resourcePolicies.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.getRoutePolicy</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.listBgpRoutes</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listRoutePolicies</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.serviceAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.snapshotGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshotGroups.create</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.delete</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.get</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshotGroups.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  snapshotGroups.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.snapshots.create</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.get</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.list</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.setLabels</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.updateKmsKey</code></li>
<li><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.spotAssistants.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.get</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listAvailableFeatures</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.list</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetGrpcProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.get</code></p>
<p><code dir="ltr" translate="no">compute.targetInstances.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.get</code></p>
<p><code dir="ltr" translate="no">compute.targetPools.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.targetVpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.get</code></p>
<p><code dir="ltr" translate="no">compute.vpnTunnels.list</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.wireGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Cloud Life Sciences permissions

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
<td><h4 id="genomics.datasets.create" class="permission-name add-link" data-text="genomics.datasets.create" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="genomics.datasets.delete" class="permission-name add-link" data-text="genomics.datasets.delete" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.datasets.get" class="permission-name add-link" data-text="genomics.datasets.get" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer">Genomics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="genomics.datasets.getIamPolicy" class="permission-name add-link" data-text="genomics.datasets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.datasets.list" class="permission-name add-link" data-text="genomics.datasets.list" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer">Genomics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="genomics.datasets.setIamPolicy" class="permission-name add-link" data-text="genomics.datasets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.datasets.update" class="permission-name add-link" data-text="genomics.datasets.update" tabindex="-1"><code dir="ltr" translate="no">genomics.datasets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="genomics.operations.cancel" class="permission-name add-link" data-text="genomics.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">genomics.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner">Genomics Pipelines Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.pipelinesRunner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.operations.create" class="permission-name add-link" data-text="genomics.operations.create" tabindex="-1"><code dir="ltr" translate="no">genomics.operations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner">Genomics Pipelines Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.pipelinesRunner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="genomics.operations.get" class="permission-name add-link" data-text="genomics.operations.get" tabindex="-1"><code dir="ltr" translate="no">genomics.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer">Genomics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner">Genomics Pipelines Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.pipelinesRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="genomics.operations.list" class="permission-name add-link" data-text="genomics.operations.list" tabindex="-1"><code dir="ltr" translate="no">genomics.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin">Genomics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor">Genomics Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer">Genomics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner">Genomics Pipelines Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  genomics.pipelinesRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.operations.cancel" class="permission-name add-link" data-text="lifesciences.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">lifesciences.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin">Cloud Life Sciences Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor">Cloud Life Sciences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner">Cloud Life Sciences Workflows Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.workflowsRunner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="lifesciences.operations.get" class="permission-name add-link" data-text="lifesciences.operations.get" tabindex="-1"><code dir="ltr" translate="no">lifesciences.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin">Cloud Life Sciences Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor">Cloud Life Sciences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner">Cloud Life Sciences Workflows Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.workflowsRunner</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="lifesciences.operations.list" class="permission-name add-link" data-text="lifesciences.operations.list" tabindex="-1"><code dir="ltr" translate="no">lifesciences.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin">Cloud Life Sciences Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor">Cloud Life Sciences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer">Cloud Life Sciences Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner">Cloud Life Sciences Workflows Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.workflowsRunner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="lifesciences.workflows.run" class="permission-name add-link" data-text="lifesciences.workflows.run" tabindex="-1"><code dir="ltr" translate="no">lifesciences.workflows.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin">Cloud Life Sciences Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor">Cloud Life Sciences Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner">Cloud Life Sciences Workflows Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  lifesciences.workflowsRunner</code> )</p></td>
</tr>
</tbody>
</table>
