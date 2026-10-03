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
<td>Genomics Admin
<p>( <code>roles/ genomics.admin</code> )</p>
<p>Full access to genomics datasets and operations.</p></td>
<td><p><code>genomics.*</code></p>
<ul>
<li><code>genomics.datasets.create</code></li>
<li><code>genomics.datasets.delete</code></li>
<li><code>genomics.datasets.get</code></li>
<li><code>genomics.datasets.getIamPolicy</code></li>
<li><code>genomics.datasets.list</code></li>
<li><code>genomics.datasets.setIamPolicy</code></li>
<li><code>genomics.datasets.update</code></li>
<li><code>genomics.operations.cancel</code></li>
<li><code>genomics.operations.create</code></li>
<li><code>genomics.operations.get</code></li>
<li><code>genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Genomics Editor
<p>( <code>roles/ genomics.editor</code> )</p>
<p>Access to read and edit genomics datasets and operations.</p></td>
<td><p><code>genomics.datasets.create</code></p>
<p><code>genomics.datasets.delete</code></p>
<p><code>genomics.datasets.get</code></p>
<p><code>genomics.datasets.list</code></p>
<p><code>genomics.datasets.update</code></p>
<p><code>genomics.operations.*</code></p>
<ul>
<li><code>genomics.operations.cancel</code></li>
<li><code>genomics.operations.create</code></li>
<li><code>genomics.operations.get</code></li>
<li><code>genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Genomics Viewer
<p>( <code>roles/ genomics.viewer</code> )</p>
<p>Access to view genomics datasets and operations.</p></td>
<td><p><code>genomics.datasets.get</code></p>
<p><code>genomics.datasets.list</code></p>
<p><code>genomics.operations.get</code></p>
<p><code>genomics.operations.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Life Sciences Admin <sup>Beta</sup>
<p>( <code>roles/ lifesciences.admin</code> )</p>
<p>Full control of Cloud Life Sciences resources.</p></td>
<td><p><code>lifesciences.*</code></p>
<ul>
<li><code>lifesciences.operations.cancel</code></li>
<li><code>lifesciences.operations.get</code></li>
<li><code>lifesciences.operations.list</code></li>
<li><code>lifesciences.workflows.run</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Cloud Life Sciences Editor <sup>Beta</sup>
<p>( <code>roles/ lifesciences.editor</code> )</p>
<p>Access to read and edit Cloud Life Sciences resources.</p></td>
<td><p><code>lifesciences.*</code></p>
<ul>
<li><code>lifesciences.operations.cancel</code></li>
<li><code>lifesciences.operations.get</code></li>
<li><code>lifesciences.operations.list</code></li>
<li><code>lifesciences.workflows.run</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Life Sciences Viewer <sup>Beta</sup>
<p>( <code>roles/ lifesciences.viewer</code> )</p>
<p>Access to read Cloud Life Sciences resources.</p></td>
<td><p><code>lifesciences.operations.get</code></p>
<p><code>lifesciences.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Genomics Pipelines Runner
<p>( <code>roles/ genomics.pipelinesRunner</code> )</p>
<p>Full access to operate on genomics pipelines.</p></td>
<td><p><code>genomics.operations.*</code></p>
<ul>
<li><code>genomics.operations.cancel</code></li>
<li><code>genomics.operations.create</code></li>
<li><code>genomics.operations.get</code></li>
<li><code>genomics.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud Life Sciences Workflows Runner <sup>Beta</sup>
<p>( <code>roles/ lifesciences.workflowsRunner</code> )</p>
<p>Full access to operate on Cloud Life Sciences workflows.</p></td>
<td><p><code>lifesciences.*</code></p>
<ul>
<li><code>lifesciences.operations.cancel</code></li>
<li><code>lifesciences.operations.get</code></li>
<li><code>lifesciences.operations.list</code></li>
<li><code>lifesciences.workflows.run</code></li>
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
<td>Genomics Service Agent
<p>( <code>roles/ genomics.serviceAgent</code> )</p>
<p>Gives Genomics Service Account access to compute resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>backupdr. backupPlanAssociations. createForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr. backupPlans. useForComputeDisk</code></p>
<p><code>backupdr. backupPlans. useForComputeInstance</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.autoscalers.*</code></p>
<ul>
<li><code>compute.autoscalers.create</code></li>
<li><code>compute.autoscalers.delete</code></li>
<li><code>compute.autoscalers.get</code></li>
<li><code>compute.autoscalers.list</code></li>
<li><code>compute.autoscalers.update</code></li>
</ul>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute.diskSettings.get</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.*</code></p>
<ul>
<li><code>compute. disks. addResourcePolicies</code></li>
<li><code>compute.disks.create</code></li>
<li><code>compute.disks.createSnapshot</code></li>
<li><code>compute.disks.createTagBinding</code></li>
<li><code>compute.disks.delete</code></li>
<li><code>compute.disks.deleteTagBinding</code></li>
<li><code>compute.disks.get</code></li>
<li><code>compute.disks.getIamPolicy</code></li>
<li><code>compute.disks.list</code></li>
<li><code>compute. disks. listEffectiveTags</code></li>
<li><code>compute.disks.listTagBindings</code></li>
<li><code>compute. disks. removeResourcePolicies</code></li>
<li><code>compute.disks.resize</code></li>
<li><code>compute.disks.setIamPolicy</code></li>
<li><code>compute.disks.setLabels</code></li>
<li><code>compute. disks. startAsyncReplication</code></li>
<li><code>compute. disks. stopAsyncReplication</code></li>
<li><code>compute. disks. stopGroupAsyncReplication</code></li>
<li><code>compute.disks.update</code></li>
<li><code>compute.disks.updateKmsKey</code></li>
<li><code>compute.disks.use</code></li>
<li><code>compute.disks.useReadOnly</code></li>
</ul>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute.globalAddresses.use</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. create</code></li>
<li><code>compute. globalNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. delete</code></li>
<li><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. get</code></li>
<li><code>compute. globalNetworkEndpointGroups. list</code></li>
<li><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. globalNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. globalNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute.hosts.*</code></p>
<ul>
<li><code>compute.hosts.get</code></li>
<li><code>compute.hosts.getVersion</code></li>
<li><code>compute.hosts.list</code></li>
</ul>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute.images.*</code></p>
<ul>
<li><code>compute.images.create</code></li>
<li><code>compute. images. createTagBinding</code></li>
<li><code>compute.images.delete</code></li>
<li><code>compute. images. deleteTagBinding</code></li>
<li><code>compute.images.deprecate</code></li>
<li><code>compute.images.get</code></li>
<li><code>compute.images.getFromFamily</code></li>
<li><code>compute.images.getIamPolicy</code></li>
<li><code>compute.images.list</code></li>
<li><code>compute. images. listEffectiveTags</code></li>
<li><code>compute.images.listTagBindings</code></li>
<li><code>compute.images.setIamPolicy</code></li>
<li><code>compute.images.setLabels</code></li>
<li><code>compute.images.update</code></li>
<li><code>compute.images.useReadOnly</code></li>
</ul>
<p><code>compute. instanceGroupManagers.*</code></p>
<ul>
<li><code>compute. instanceGroupManagers. create</code></li>
<li><code>compute. instanceGroupManagers. createTagBinding</code></li>
<li><code>compute. instanceGroupManagers. delete</code></li>
<li><code>compute. instanceGroupManagers. deleteTagBinding</code></li>
<li><code>compute. instanceGroupManagers. get</code></li>
<li><code>compute. instanceGroupManagers. list</code></li>
<li><code>compute. instanceGroupManagers. listEffectiveTags</code></li>
<li><code>compute. instanceGroupManagers. listTagBindings</code></li>
<li><code>compute. instanceGroupManagers. update</code></li>
<li><code>compute. instanceGroupManagers. use</code></li>
</ul>
<p><code>compute.instanceGroups.*</code></p>
<ul>
<li><code>compute.instanceGroups.create</code></li>
<li><code>compute. instanceGroups. createTagBinding</code></li>
<li><code>compute.instanceGroups.delete</code></li>
<li><code>compute. instanceGroups. deleteTagBinding</code></li>
<li><code>compute.instanceGroups.get</code></li>
<li><code>compute.instanceGroups.list</code></li>
<li><code>compute. instanceGroups. listEffectiveTags</code></li>
<li><code>compute. instanceGroups. listTagBindings</code></li>
<li><code>compute.instanceGroups.update</code></li>
<li><code>compute.instanceGroups.use</code></li>
</ul>
<p><code>compute.instanceSettings.*</code></p>
<ul>
<li><code>compute.instanceSettings.get</code></li>
<li><code>compute. instanceSettings. update</code></li>
</ul>
<p><code>compute.instanceTemplates.*</code></p>
<ul>
<li><code>compute. instanceTemplates. create</code></li>
<li><code>compute. instanceTemplates. delete</code></li>
<li><code>compute.instanceTemplates.get</code></li>
<li><code>compute. instanceTemplates. getIamPolicy</code></li>
<li><code>compute.instanceTemplates.list</code></li>
<li><code>compute. instanceTemplates. setIamPolicy</code></li>
<li><code>compute. instanceTemplates. useReadOnly</code></li>
</ul>
<p><code>compute.instances.*</code></p>
<ul>
<li><code>compute. instances. addAccessConfig</code></li>
<li><code>compute. instances. addNetworkInterface</code></li>
<li><code>compute. instances. addResourcePolicies</code></li>
<li><code>compute.instances.attachDisk</code></li>
<li><code>compute.instances.create</code></li>
<li><code>compute. instances. createTagBinding</code></li>
<li><code>compute.instances.delete</code></li>
<li><code>compute. instances. deleteAccessConfig</code></li>
<li><code>compute. instances. deleteNetworkInterface</code></li>
<li><code>compute. instances. deleteTagBinding</code></li>
<li><code>compute.instances.detachDisk</code></li>
<li><code>compute.instances.get</code></li>
<li><code>compute. instances. getEffectiveFirewalls</code></li>
<li><code>compute. instances. getGuestAttributes</code></li>
<li><code>compute.instances.getIamPolicy</code></li>
<li><code>compute. instances. getScreenshot</code></li>
<li><code>compute. instances. getSerialPortOutput</code></li>
<li><code>compute. instances. getShieldedInstanceIdentity</code></li>
<li><code>compute. instances. getShieldedVmIdentity</code></li>
<li><code>compute. instances. getVmExtensionState</code></li>
<li><code>compute.instances.list</code></li>
<li><code>compute. instances. listEffectiveTags</code></li>
<li><code>compute. instances. listReferrers</code></li>
<li><code>compute. instances. listTagBindings</code></li>
<li><code>compute. instances. listVmExtensionStates</code></li>
<li><code>compute.instances.osAdminLogin</code></li>
<li><code>compute.instances.osLogin</code></li>
<li><code>compute. instances. pscInterfaceCreate</code></li>
<li><code>compute. instances. removeResourcePolicies</code></li>
<li><code>compute.instances.reset</code></li>
<li><code>compute.instances.resume</code></li>
<li><code>compute. instances. sendDiagnosticInterrupt</code></li>
<li><code>compute. instances. setDeletionProtection</code></li>
<li><code>compute. instances. setDiskAutoDelete</code></li>
<li><code>compute.instances.setIamPolicy</code></li>
<li><code>compute.instances.setLabels</code></li>
<li><code>compute. instances. setMachineResources</code></li>
<li><code>compute. instances. setMachineType</code></li>
<li><code>compute.instances.setMetadata</code></li>
<li><code>compute. instances. setMinCpuPlatform</code></li>
<li><code>compute.instances.setName</code></li>
<li><code>compute. instances. setScheduling</code></li>
<li><code>compute. instances. setSecurityPolicy</code></li>
<li><code>compute. instances. setServiceAccount</code></li>
<li><code>compute. instances. setShieldedInstanceIntegrityPolicy</code></li>
<li><code>compute. instances. setShieldedVmIntegrityPolicy</code></li>
<li><code>compute.instances.setTags</code></li>
<li><code>compute. instances. simulateMaintenanceEvent</code></li>
<li><code>compute.instances.start</code></li>
<li><code>compute. instances. startWithEncryptionKey</code></li>
<li><code>compute.instances.stop</code></li>
<li><code>compute.instances.suspend</code></li>
<li><code>compute.instances.troubleshoot</code></li>
<li><code>compute.instances.update</code></li>
<li><code>compute. instances. updateAccessConfig</code></li>
<li><code>compute. instances. updateDisplayDevice</code></li>
<li><code>compute. instances. updateNetworkInterface</code></li>
<li><code>compute. instances. updateSecurity</code></li>
<li><code>compute. instances. updateShieldedInstanceConfig</code></li>
<li><code>compute. instances. updateShieldedVmConfig</code></li>
<li><code>compute.instances.use</code></li>
<li><code>compute.instances.useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshotGroups.*</code></p>
<ul>
<li><code>compute. instantSnapshotGroups. create</code></li>
<li><code>compute. instantSnapshotGroups. delete</code></li>
<li><code>compute. instantSnapshotGroups. get</code></li>
<li><code>compute. instantSnapshotGroups. getIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. list</code></li>
<li><code>compute. instantSnapshotGroups. setIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshots. create</code></p>
<p><code>compute. instantSnapshots. delete</code></p>
<p><code>compute. instantSnapshots. export</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. instantSnapshots. setIamPolicy</code></p>
<p><code>compute. instantSnapshots. setLabels</code></p>
<p><code>compute. instantSnapshots. useReadOnly</code></p>
<p><code>compute. interconnectAttachmentGroups. get</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
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
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute.licenseCodes.*</code></p>
<ul>
<li><code>compute.licenseCodes.get</code></li>
<li><code>compute. licenseCodes. getIamPolicy</code></li>
<li><code>compute.licenseCodes.list</code></li>
<li><code>compute. licenseCodes. setIamPolicy</code></li>
</ul>
<p><code>compute.licenses.create</code></p>
<p><code>compute.licenses.delete</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.licenses.setIamPolicy</code></p>
<p><code>compute.licenses.update</code></p>
<p><code>compute.machineImages.create</code></p>
<p><code>compute.machineImages.delete</code></p>
<p><code>compute.machineImages.get</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. machineImages. setIamPolicy</code></p>
<p><code>compute. machineImages. setLabels</code></p>
<p><code>compute. machineImages. useReadOnly</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.multiMig.*</code></p>
<ul>
<li><code>compute.multiMig.create</code></li>
<li><code>compute.multiMig.delete</code></li>
<li><code>compute.multiMig.get</code></li>
<li><code>compute.multiMig.list</code></li>
</ul>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups.*</code></p>
<ul>
<li><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. create</code></li>
<li><code>compute. networkEndpointGroups. createTagBinding</code></li>
<li><code>compute. networkEndpointGroups. delete</code></li>
<li><code>compute. networkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. networkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. get</code></li>
<li><code>compute. networkEndpointGroups. list</code></li>
<li><code>compute. networkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. networkEndpointGroups. listTagBindings</code></li>
<li><code>compute. networkEndpointGroups. use</code></li>
</ul>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute.recoverableSnapshots.*</code></p>
<ul>
<li><code>compute. recoverableSnapshots. delete</code></li>
<li><code>compute. recoverableSnapshots. get</code></li>
<li><code>compute. recoverableSnapshots. getIamPolicy</code></li>
<li><code>compute. recoverableSnapshots. list</code></li>
<li><code>compute. recoverableSnapshots. recover</code></li>
<li><code>compute. recoverableSnapshots. setIamPolicy</code></li>
</ul>
<p><code>compute. regionBackendBuckets. get</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. get</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. regionNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. create</code></li>
<li><code>compute. regionNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. delete</code></li>
<li><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. get</code></li>
<li><code>compute. regionNetworkEndpointGroups. list</code></li>
<li><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. regionNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. regionNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute. regionNotificationEndpoints. get</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.get</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. listAvailableFeatures</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.*</code></p>
<ul>
<li><code>compute.reservationSlots.get</code></li>
<li><code>compute.reservationSlots.list</code></li>
<li><code>compute. reservationSlots. update</code></li>
</ul>
<p><code>compute. reservationSubBlocks. get</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute.resourcePolicies.*</code></p>
<ul>
<li><code>compute. resourcePolicies. create</code></li>
<li><code>compute. resourcePolicies. delete</code></li>
<li><code>compute.resourcePolicies.get</code></li>
<li><code>compute. resourcePolicies. getIamPolicy</code></li>
<li><code>compute.resourcePolicies.list</code></li>
<li><code>compute. resourcePolicies. setIamPolicy</code></li>
<li><code>compute. resourcePolicies. update</code></li>
<li><code>compute.resourcePolicies.use</code></li>
<li><code>compute. resourcePolicies. useReadOnly</code></li>
</ul>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.getRoutePolicy</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.listBgpRoutes</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listRoutePolicies</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute.snapshotGroups.*</code></p>
<ul>
<li><code>compute.snapshotGroups.create</code></li>
<li><code>compute.snapshotGroups.delete</code></li>
<li><code>compute.snapshotGroups.get</code></li>
<li><code>compute. snapshotGroups. getIamPolicy</code></li>
<li><code>compute.snapshotGroups.list</code></li>
<li><code>compute. snapshotGroups. setIamPolicy</code></li>
<li><code>compute. snapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute.snapshots.*</code></p>
<ul>
<li><code>compute.snapshots.create</code></li>
<li><code>compute. snapshots. createTagBinding</code></li>
<li><code>compute.snapshots.delete</code></li>
<li><code>compute. snapshots. deleteTagBinding</code></li>
<li><code>compute.snapshots.get</code></li>
<li><code>compute. snapshots. getEffectiveRecycleBinRule</code></li>
<li><code>compute.snapshots.getIamPolicy</code></li>
<li><code>compute.snapshots.list</code></li>
<li><code>compute. snapshots. listEffectiveTags</code></li>
<li><code>compute. snapshots. listTagBindings</code></li>
<li><code>compute.snapshots.setIamPolicy</code></li>
<li><code>compute.snapshots.setLabels</code></li>
<li><code>compute.snapshots.updateKmsKey</code></li>
<li><code>compute.snapshots.useReadOnly</code></li>
</ul>
<p><code>compute.spotAssistants.get</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. listAvailableFeatures</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute.storagePools.get</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.targetGrpcProxies.get</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Cloud Life Sciences Service Agent
<p>( <code>roles/ lifesciences.serviceAgent</code> )</p>
<p>Gives Cloud Life Sciences Service Account access to compute resources. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>backupdr. backupPlanAssociations. createForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. createForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. deleteForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. fetchForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. getForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. list</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. triggerBackupForComputeInstance</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeDisk</code></p>
<p><code>backupdr. backupPlanAssociations. updateForComputeInstance</code></p>
<p><code>backupdr.backupPlans.get</code></p>
<p><code>backupdr.backupPlans.list</code></p>
<p><code>backupdr. backupPlans. useForComputeDisk</code></p>
<p><code>backupdr. backupPlans. useForComputeInstance</code></p>
<p><code>backupdr.backupVaults.get</code></p>
<p><code>backupdr.backupVaults.list</code></p>
<p><code>backupdr.locations.list</code></p>
<p><code>backupdr.operations.get</code></p>
<p><code>backupdr.operations.list</code></p>
<p><code>backupdr. serviceConfig. initialize</code></p>
<p><code>compute.acceleratorTypes.*</code></p>
<ul>
<li><code>compute.acceleratorTypes.get</code></li>
<li><code>compute.acceleratorTypes.list</code></li>
</ul>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.autoscalers.*</code></p>
<ul>
<li><code>compute.autoscalers.create</code></li>
<li><code>compute.autoscalers.delete</code></li>
<li><code>compute.autoscalers.get</code></li>
<li><code>compute.autoscalers.list</code></li>
<li><code>compute.autoscalers.update</code></li>
</ul>
<p><code>compute.backendBuckets.get</code></p>
<p><code>compute.backendBuckets.list</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute.crossSiteNetworks.get</code></p>
<p><code>compute.crossSiteNetworks.list</code></p>
<p><code>compute.diskSettings.get</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.*</code></p>
<ul>
<li><code>compute. disks. addResourcePolicies</code></li>
<li><code>compute.disks.create</code></li>
<li><code>compute.disks.createSnapshot</code></li>
<li><code>compute.disks.createTagBinding</code></li>
<li><code>compute.disks.delete</code></li>
<li><code>compute.disks.deleteTagBinding</code></li>
<li><code>compute.disks.get</code></li>
<li><code>compute.disks.getIamPolicy</code></li>
<li><code>compute.disks.list</code></li>
<li><code>compute. disks. listEffectiveTags</code></li>
<li><code>compute.disks.listTagBindings</code></li>
<li><code>compute. disks. removeResourcePolicies</code></li>
<li><code>compute.disks.resize</code></li>
<li><code>compute.disks.setIamPolicy</code></li>
<li><code>compute.disks.setLabels</code></li>
<li><code>compute. disks. startAsyncReplication</code></li>
<li><code>compute. disks. stopAsyncReplication</code></li>
<li><code>compute. disks. stopGroupAsyncReplication</code></li>
<li><code>compute.disks.update</code></li>
<li><code>compute.disks.updateKmsKey</code></li>
<li><code>compute.disks.use</code></li>
<li><code>compute.disks.useReadOnly</code></li>
</ul>
<p><code>compute. externalVpnGateways. get</code></p>
<p><code>compute. externalVpnGateways. list</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute.globalAddresses.use</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. create</code></li>
<li><code>compute. globalNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. delete</code></li>
<li><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. globalNetworkEndpointGroups. get</code></li>
<li><code>compute. globalNetworkEndpointGroups. list</code></li>
<li><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. globalNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. globalNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute.hosts.*</code></p>
<ul>
<li><code>compute.hosts.get</code></li>
<li><code>compute.hosts.getVersion</code></li>
<li><code>compute.hosts.list</code></li>
</ul>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute.images.*</code></p>
<ul>
<li><code>compute.images.create</code></li>
<li><code>compute. images. createTagBinding</code></li>
<li><code>compute.images.delete</code></li>
<li><code>compute. images. deleteTagBinding</code></li>
<li><code>compute.images.deprecate</code></li>
<li><code>compute.images.get</code></li>
<li><code>compute.images.getFromFamily</code></li>
<li><code>compute.images.getIamPolicy</code></li>
<li><code>compute.images.list</code></li>
<li><code>compute. images. listEffectiveTags</code></li>
<li><code>compute.images.listTagBindings</code></li>
<li><code>compute.images.setIamPolicy</code></li>
<li><code>compute.images.setLabels</code></li>
<li><code>compute.images.update</code></li>
<li><code>compute.images.useReadOnly</code></li>
</ul>
<p><code>compute. instanceGroupManagers.*</code></p>
<ul>
<li><code>compute. instanceGroupManagers. create</code></li>
<li><code>compute. instanceGroupManagers. createTagBinding</code></li>
<li><code>compute. instanceGroupManagers. delete</code></li>
<li><code>compute. instanceGroupManagers. deleteTagBinding</code></li>
<li><code>compute. instanceGroupManagers. get</code></li>
<li><code>compute. instanceGroupManagers. list</code></li>
<li><code>compute. instanceGroupManagers. listEffectiveTags</code></li>
<li><code>compute. instanceGroupManagers. listTagBindings</code></li>
<li><code>compute. instanceGroupManagers. update</code></li>
<li><code>compute. instanceGroupManagers. use</code></li>
</ul>
<p><code>compute.instanceGroups.*</code></p>
<ul>
<li><code>compute.instanceGroups.create</code></li>
<li><code>compute. instanceGroups. createTagBinding</code></li>
<li><code>compute.instanceGroups.delete</code></li>
<li><code>compute. instanceGroups. deleteTagBinding</code></li>
<li><code>compute.instanceGroups.get</code></li>
<li><code>compute.instanceGroups.list</code></li>
<li><code>compute. instanceGroups. listEffectiveTags</code></li>
<li><code>compute. instanceGroups. listTagBindings</code></li>
<li><code>compute.instanceGroups.update</code></li>
<li><code>compute.instanceGroups.use</code></li>
</ul>
<p><code>compute.instanceSettings.*</code></p>
<ul>
<li><code>compute.instanceSettings.get</code></li>
<li><code>compute. instanceSettings. update</code></li>
</ul>
<p><code>compute.instanceTemplates.*</code></p>
<ul>
<li><code>compute. instanceTemplates. create</code></li>
<li><code>compute. instanceTemplates. delete</code></li>
<li><code>compute.instanceTemplates.get</code></li>
<li><code>compute. instanceTemplates. getIamPolicy</code></li>
<li><code>compute.instanceTemplates.list</code></li>
<li><code>compute. instanceTemplates. setIamPolicy</code></li>
<li><code>compute. instanceTemplates. useReadOnly</code></li>
</ul>
<p><code>compute.instances.*</code></p>
<ul>
<li><code>compute. instances. addAccessConfig</code></li>
<li><code>compute. instances. addNetworkInterface</code></li>
<li><code>compute. instances. addResourcePolicies</code></li>
<li><code>compute.instances.attachDisk</code></li>
<li><code>compute.instances.create</code></li>
<li><code>compute. instances. createTagBinding</code></li>
<li><code>compute.instances.delete</code></li>
<li><code>compute. instances. deleteAccessConfig</code></li>
<li><code>compute. instances. deleteNetworkInterface</code></li>
<li><code>compute. instances. deleteTagBinding</code></li>
<li><code>compute.instances.detachDisk</code></li>
<li><code>compute.instances.get</code></li>
<li><code>compute. instances. getEffectiveFirewalls</code></li>
<li><code>compute. instances. getGuestAttributes</code></li>
<li><code>compute.instances.getIamPolicy</code></li>
<li><code>compute. instances. getScreenshot</code></li>
<li><code>compute. instances. getSerialPortOutput</code></li>
<li><code>compute. instances. getShieldedInstanceIdentity</code></li>
<li><code>compute. instances. getShieldedVmIdentity</code></li>
<li><code>compute. instances. getVmExtensionState</code></li>
<li><code>compute.instances.list</code></li>
<li><code>compute. instances. listEffectiveTags</code></li>
<li><code>compute. instances. listReferrers</code></li>
<li><code>compute. instances. listTagBindings</code></li>
<li><code>compute. instances. listVmExtensionStates</code></li>
<li><code>compute.instances.osAdminLogin</code></li>
<li><code>compute.instances.osLogin</code></li>
<li><code>compute. instances. pscInterfaceCreate</code></li>
<li><code>compute. instances. removeResourcePolicies</code></li>
<li><code>compute.instances.reset</code></li>
<li><code>compute.instances.resume</code></li>
<li><code>compute. instances. sendDiagnosticInterrupt</code></li>
<li><code>compute. instances. setDeletionProtection</code></li>
<li><code>compute. instances. setDiskAutoDelete</code></li>
<li><code>compute.instances.setIamPolicy</code></li>
<li><code>compute.instances.setLabels</code></li>
<li><code>compute. instances. setMachineResources</code></li>
<li><code>compute. instances. setMachineType</code></li>
<li><code>compute.instances.setMetadata</code></li>
<li><code>compute. instances. setMinCpuPlatform</code></li>
<li><code>compute.instances.setName</code></li>
<li><code>compute. instances. setScheduling</code></li>
<li><code>compute. instances. setSecurityPolicy</code></li>
<li><code>compute. instances. setServiceAccount</code></li>
<li><code>compute. instances. setShieldedInstanceIntegrityPolicy</code></li>
<li><code>compute. instances. setShieldedVmIntegrityPolicy</code></li>
<li><code>compute.instances.setTags</code></li>
<li><code>compute. instances. simulateMaintenanceEvent</code></li>
<li><code>compute.instances.start</code></li>
<li><code>compute. instances. startWithEncryptionKey</code></li>
<li><code>compute.instances.stop</code></li>
<li><code>compute.instances.suspend</code></li>
<li><code>compute.instances.troubleshoot</code></li>
<li><code>compute.instances.update</code></li>
<li><code>compute. instances. updateAccessConfig</code></li>
<li><code>compute. instances. updateDisplayDevice</code></li>
<li><code>compute. instances. updateNetworkInterface</code></li>
<li><code>compute. instances. updateSecurity</code></li>
<li><code>compute. instances. updateShieldedInstanceConfig</code></li>
<li><code>compute. instances. updateShieldedVmConfig</code></li>
<li><code>compute.instances.use</code></li>
<li><code>compute.instances.useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshotGroups.*</code></p>
<ul>
<li><code>compute. instantSnapshotGroups. create</code></li>
<li><code>compute. instantSnapshotGroups. delete</code></li>
<li><code>compute. instantSnapshotGroups. get</code></li>
<li><code>compute. instantSnapshotGroups. getIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. list</code></li>
<li><code>compute. instantSnapshotGroups. setIamPolicy</code></li>
<li><code>compute. instantSnapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute. instantSnapshots. create</code></p>
<p><code>compute. instantSnapshots. delete</code></p>
<p><code>compute. instantSnapshots. export</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. instantSnapshots. setIamPolicy</code></p>
<p><code>compute. instantSnapshots. setLabels</code></p>
<p><code>compute. instantSnapshots. useReadOnly</code></p>
<p><code>compute. interconnectAttachmentGroups. get</code></p>
<p><code>compute. interconnectAttachmentGroups. list</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
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
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute.licenseCodes.*</code></p>
<ul>
<li><code>compute.licenseCodes.get</code></li>
<li><code>compute. licenseCodes. getIamPolicy</code></li>
<li><code>compute.licenseCodes.list</code></li>
<li><code>compute. licenseCodes. setIamPolicy</code></li>
</ul>
<p><code>compute.licenses.create</code></p>
<p><code>compute.licenses.delete</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.licenses.setIamPolicy</code></p>
<p><code>compute.licenses.update</code></p>
<p><code>compute.machineImages.create</code></p>
<p><code>compute.machineImages.delete</code></p>
<p><code>compute.machineImages.get</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. machineImages. setIamPolicy</code></p>
<p><code>compute. machineImages. setLabels</code></p>
<p><code>compute. machineImages. useReadOnly</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.multiMig.*</code></p>
<ul>
<li><code>compute.multiMig.create</code></li>
<li><code>compute.multiMig.delete</code></li>
<li><code>compute.multiMig.get</code></li>
<li><code>compute.multiMig.list</code></li>
</ul>
<p><code>compute.networkAttachments.get</code></p>
<p><code>compute. networkAttachments. list</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups.*</code></p>
<ul>
<li><code>compute. networkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. create</code></li>
<li><code>compute. networkEndpointGroups. createTagBinding</code></li>
<li><code>compute. networkEndpointGroups. delete</code></li>
<li><code>compute. networkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. networkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. networkEndpointGroups. get</code></li>
<li><code>compute. networkEndpointGroups. list</code></li>
<li><code>compute. networkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. networkEndpointGroups. listTagBindings</code></li>
<li><code>compute. networkEndpointGroups. use</code></li>
</ul>
<p><code>compute.networkProfiles.*</code></p>
<ul>
<li><code>compute.networkProfiles.get</code></li>
<li><code>compute.networkProfiles.list</code></li>
</ul>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute.recoverableSnapshots.*</code></p>
<ul>
<li><code>compute. recoverableSnapshots. delete</code></li>
<li><code>compute. recoverableSnapshots. get</code></li>
<li><code>compute. recoverableSnapshots. getIamPolicy</code></li>
<li><code>compute. recoverableSnapshots. list</code></li>
<li><code>compute. recoverableSnapshots. recover</code></li>
<li><code>compute. recoverableSnapshots. setIamPolicy</code></li>
</ul>
<p><code>compute. regionBackendBuckets. get</code></p>
<p><code>compute. regionBackendBuckets. list</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionCompositeHealthChecks. get</code></p>
<p><code>compute. regionCompositeHealthChecks. list</code></p>
<p><code>compute. regionHealthAggregationPolicies. get</code></p>
<p><code>compute. regionHealthAggregationPolicies. list</code></p>
<p><code>compute. regionHealthCheckServices. get</code></p>
<p><code>compute. regionHealthCheckServices. list</code></p>
<p><code>compute.regionHealthChecks.get</code></p>
<p><code>compute. regionHealthChecks. list</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionHealthSources. get</code></p>
<p><code>compute. regionHealthSources. list</code></p>
<p><code>compute. regionNetworkEndpointGroups.*</code></p>
<ul>
<li><code>compute. regionNetworkEndpointGroups. attachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. create</code></li>
<li><code>compute. regionNetworkEndpointGroups. createTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. delete</code></li>
<li><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></li>
<li><code>compute. regionNetworkEndpointGroups. detachNetworkEndpoints</code></li>
<li><code>compute. regionNetworkEndpointGroups. get</code></li>
<li><code>compute. regionNetworkEndpointGroups. list</code></li>
<li><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></li>
<li><code>compute. regionNetworkEndpointGroups. listTagBindings</code></li>
<li><code>compute. regionNetworkEndpointGroups. use</code></li>
</ul>
<p><code>compute. regionNotificationEndpoints. get</code></p>
<p><code>compute. regionNotificationEndpoints. list</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute. regionSslCertificates. get</code></p>
<p><code>compute. regionSslCertificates. list</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute.regionSslPolicies.get</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionSslPolicies. listAvailableFeatures</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. get</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. get</code></p>
<p><code>compute. regionTargetHttpsProxies. list</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute.regionUrlMaps.get</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.reservationBlocks.get</code></p>
<p><code>compute.reservationBlocks.list</code></p>
<p><code>compute. reservationConsumedInstances. list</code></p>
<p><code>compute.reservationSlots.*</code></p>
<ul>
<li><code>compute.reservationSlots.get</code></li>
<li><code>compute.reservationSlots.list</code></li>
<li><code>compute. reservationSlots. update</code></li>
</ul>
<p><code>compute. reservationSubBlocks. get</code></p>
<p><code>compute. reservationSubBlocks. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute.resourcePolicies.*</code></p>
<ul>
<li><code>compute. resourcePolicies. create</code></li>
<li><code>compute. resourcePolicies. delete</code></li>
<li><code>compute.resourcePolicies.get</code></li>
<li><code>compute. resourcePolicies. getIamPolicy</code></li>
<li><code>compute.resourcePolicies.list</code></li>
<li><code>compute. resourcePolicies. setIamPolicy</code></li>
<li><code>compute. resourcePolicies. update</code></li>
<li><code>compute.resourcePolicies.use</code></li>
<li><code>compute. resourcePolicies. useReadOnly</code></li>
</ul>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.getRoutePolicy</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.listBgpRoutes</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listRoutePolicies</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute.serviceAttachments.get</code></p>
<p><code>compute. serviceAttachments. list</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute.snapshotGroups.*</code></p>
<ul>
<li><code>compute.snapshotGroups.create</code></li>
<li><code>compute.snapshotGroups.delete</code></li>
<li><code>compute.snapshotGroups.get</code></li>
<li><code>compute. snapshotGroups. getIamPolicy</code></li>
<li><code>compute.snapshotGroups.list</code></li>
<li><code>compute. snapshotGroups. setIamPolicy</code></li>
<li><code>compute. snapshotGroups. useReadOnly</code></li>
</ul>
<p><code>compute.snapshots.*</code></p>
<ul>
<li><code>compute.snapshots.create</code></li>
<li><code>compute. snapshots. createTagBinding</code></li>
<li><code>compute.snapshots.delete</code></li>
<li><code>compute. snapshots. deleteTagBinding</code></li>
<li><code>compute.snapshots.get</code></li>
<li><code>compute. snapshots. getEffectiveRecycleBinRule</code></li>
<li><code>compute.snapshots.getIamPolicy</code></li>
<li><code>compute.snapshots.list</code></li>
<li><code>compute. snapshots. listEffectiveTags</code></li>
<li><code>compute. snapshots. listTagBindings</code></li>
<li><code>compute.snapshots.setIamPolicy</code></li>
<li><code>compute.snapshots.setLabels</code></li>
<li><code>compute.snapshots.updateKmsKey</code></li>
<li><code>compute.snapshots.useReadOnly</code></li>
</ul>
<p><code>compute.spotAssistants.get</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute.sslPolicies.get</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute. sslPolicies. listAvailableFeatures</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute.storagePools.get</code></p>
<p><code>compute.storagePools.list</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute.storagePools.use</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.targetGrpcProxies.get</code></p>
<p><code>compute.targetGrpcProxies.list</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute.targetInstances.get</code></p>
<p><code>compute.targetInstances.list</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute.targetPools.get</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute.targetSslProxies.get</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute.targetVpnGateways.get</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute.vpnGateways.get</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute.vpnTunnels.get</code></p>
<p><code>compute.vpnTunnels.list</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>compute.wireGroups.get</code></p>
<p><code>compute.wireGroups.list</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>pubsub.topics.publish</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Cloud Life Sciences permissions

| Permission                       | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `genomics.datasets.create`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `genomics.datasets.delete`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `genomics.datasets.get`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Genomics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer) ( `roles/ genomics.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `genomics.datasets.getIamPolicy` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `genomics.datasets.list`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Genomics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer) ( `roles/ genomics.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                               |
| `genomics.datasets.setIamPolicy` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `genomics.datasets.update`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `genomics.operations.cancel`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Genomics Pipelines Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner) ( `roles/ genomics.pipelinesRunner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `genomics.operations.create`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Genomics Pipelines Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner) ( `roles/ genomics.pipelinesRunner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `genomics.operations.get`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Genomics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer) ( `roles/ genomics.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Genomics Pipelines Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner) ( `roles/ genomics.pipelinesRunner` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `genomics.operations.list`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Genomics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.admin) ( `roles/ genomics.admin` ) [Genomics Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.editor) ( `roles/ genomics.editor` ) [Genomics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.viewer) ( `roles/ genomics.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Genomics Pipelines Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#genomics.pipelinesRunner) ( `roles/ genomics.pipelinesRunner` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                             |
| `lifesciences.operations.cancel` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Life Sciences Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin) ( `roles/ lifesciences.admin` ) [Cloud Life Sciences Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor) ( `roles/ lifesciences.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Life Sciences Workflows Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner) ( `roles/ lifesciences.workflowsRunner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `lifesciences.operations.get`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Life Sciences Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin) ( `roles/ lifesciences.admin` ) [Cloud Life Sciences Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor) ( `roles/ lifesciences.editor` ) [Cloud Life Sciences Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer) ( `roles/ lifesciences.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Cloud Life Sciences Workflows Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner) ( `roles/ lifesciences.workflowsRunner` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `lifesciences.operations.list`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Cloud Life Sciences Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin) ( `roles/ lifesciences.admin` ) [Cloud Life Sciences Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor) ( `roles/ lifesciences.editor` ) [Cloud Life Sciences Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.viewer) ( `roles/ lifesciences.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Cloud Life Sciences Workflows Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner) ( `roles/ lifesciences.workflowsRunner` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `lifesciences.workflows.run`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Cloud Life Sciences Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.admin) ( `roles/ lifesciences.admin` ) [Cloud Life Sciences Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.editor) ( `roles/ lifesciences.editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Life Sciences Workflows Runner](https://docs.cloud.google.com/iam/docs/roles-permissions/lifesciences#lifesciences.workflowsRunner) ( `roles/ lifesciences.workflowsRunner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
