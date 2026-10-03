---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/batch
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/batch
title: Batch roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Batch. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Batch roles

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
<td>Batch Administrator
<p>( <code>roles/ batch.admin</code> )</p>
<p>Administrator of Batch resources</p></td>
<td><p><code>batch.jobs.*</code></p>
<ul>
<li><code>batch.jobs.create</code></li>
<li><code>batch.jobs.delete</code></li>
<li><code>batch.jobs.get</code></li>
<li><code>batch.jobs.list</code></li>
</ul>
<p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.resourceAllowances.*</code></p>
<ul>
<li><code>batch. resourceAllowances. create</code></li>
<li><code>batch. resourceAllowances. delete</code></li>
<li><code>batch.resourceAllowances.get</code></li>
<li><code>batch.resourceAllowances.list</code></li>
<li><code>batch. resourceAllowances. update</code></li>
</ul>
<p><code>batch.tasks.*</code></p>
<ul>
<li><code>batch.tasks.get</code></li>
<li><code>batch.tasks.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Batch Viewer
<p>( <code>roles/ batch.viewer</code> )</p>
<p>Viewer role for Batch resources</p></td>
<td><p><code>batch.jobs.get</code></p>
<p><code>batch.jobs.list</code></p>
<p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.resourceAllowances.get</code></p>
<p><code>batch.resourceAllowances.list</code></p>
<p><code>batch.tasks.*</code></p>
<ul>
<li><code>batch.tasks.get</code></li>
<li><code>batch.tasks.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Batch Agent Reporter
<p>( <code>roles/ batch.agentReporter</code> )</p>
<p>Reporter of Batch agent states.</p></td>
<td><p><code>batch.states.report</code></p></td>
</tr>
<tr class="even">
<td>Batch Job Editor
<p>( <code>roles/ batch.jobsEditor</code> )</p>
<p>Editor of Batch Jobs</p></td>
<td><p><code>batch.jobs.*</code></p>
<ul>
<li><code>batch.jobs.create</code></li>
<li><code>batch.jobs.delete</code></li>
<li><code>batch.jobs.get</code></li>
<li><code>batch.jobs.list</code></li>
</ul>
<p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.tasks.*</code></p>
<ul>
<li><code>batch.tasks.get</code></li>
<li><code>batch.tasks.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Batch Job Viewer
<p>( <code>roles/ batch.jobsViewer</code> )</p>
<p>Viewer of Batch Jobs, Task Groups and Tasks</p></td>
<td><p><code>batch.jobs.get</code></p>
<p><code>batch.jobs.list</code></p>
<p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.tasks.*</code></p>
<ul>
<li><code>batch.tasks.get</code></li>
<li><code>batch.tasks.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Batch ResourceAllowance Editor
<p>( <code>roles/ batch.resourceAllowancesEditor</code> )</p>
<p>Editor of Batch ResourceAllowances</p></td>
<td><p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.resourceAllowances.*</code></p>
<ul>
<li><code>batch. resourceAllowances. create</code></li>
<li><code>batch. resourceAllowances. delete</code></li>
<li><code>batch.resourceAllowances.get</code></li>
<li><code>batch.resourceAllowances.list</code></li>
<li><code>batch. resourceAllowances. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Batch ResourceAllowance Viewer
<p>( <code>roles/ batch.resourceAllowancesViewer</code> )</p>
<p>Viewer of Batch ResourceAllowances</p></td>
<td><p><code>batch.locations.*</code></p>
<ul>
<li><code>batch.locations.get</code></li>
<li><code>batch.locations.list</code></li>
</ul>
<p><code>batch.operations.*</code></p>
<ul>
<li><code>batch.operations.get</code></li>
<li><code>batch.operations.list</code></li>
</ul>
<p><code>batch.resourceAllowances.get</code></p>
<p><code>batch.resourceAllowances.list</code></p>
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
<td>Google Batch Service Agent
<p>( <code>roles/ batch.serviceAgent</code> )</p>
<p>Gives Google Batch account access to manage customer resources.</p>
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
<p><code>compute. disks. addResourcePolicies</code></p>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.deleteTagBinding</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.getIamPolicy</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. disks. removeResourcePolicies</code></p>
<p><code>compute.disks.resize</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute. disks. startAsyncReplication</code></p>
<p><code>compute. disks. stopAsyncReplication</code></p>
<p><code>compute. disks. stopGroupAsyncReplication</code></p>
<p><code>compute.disks.update</code></p>
<p><code>compute.disks.updateKmsKey</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute.disks.useReadOnly</code></p>
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
<p><code>compute.images.create</code></p>
<p><code>compute. images. createTagBinding</code></p>
<p><code>compute.images.delete</code></p>
<p><code>compute. images. deleteTagBinding</code></p>
<p><code>compute.images.deprecate</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.getFromFamily</code></p>
<p><code>compute.images.getIamPolicy</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute.images.setLabels</code></p>
<p><code>compute.images.update</code></p>
<p><code>compute.images.useReadOnly</code></p>
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
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. getIamPolicy</code></p>
<p><code>compute.instanceTemplates.list</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute. instances. addAccessConfig</code></p>
<p><code>compute. instances. addNetworkInterface</code></p>
<p><code>compute. instances. addResourcePolicies</code></p>
<p><code>compute.instances.attachDisk</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute. instances. deleteAccessConfig</code></p>
<p><code>compute. instances. deleteNetworkInterface</code></p>
<p><code>compute. instances. deleteTagBinding</code></p>
<p><code>compute.instances.detachDisk</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getEffectiveFirewalls</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute.instances.getIamPolicy</code></p>
<p><code>compute. instances. getScreenshot</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute. instances. getShieldedInstanceIdentity</code></p>
<p><code>compute. instances. getShieldedVmIdentity</code></p>
<p><code>compute. instances. getVmExtensionState</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listReferrers</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instances. listVmExtensionStates</code></p>
<p><code>compute.instances.osAdminLogin</code></p>
<p><code>compute.instances.osLogin</code></p>
<p><code>compute. instances. pscInterfaceCreate</code></p>
<p><code>compute. instances. removeResourcePolicies</code></p>
<p><code>compute.instances.reset</code></p>
<p><code>compute.instances.resume</code></p>
<p><code>compute. instances. sendDiagnosticInterrupt</code></p>
<p><code>compute. instances. setDeletionProtection</code></p>
<p><code>compute. instances. setDiskAutoDelete</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute. instances. setMachineResources</code></p>
<p><code>compute. instances. setMachineType</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setMinCpuPlatform</code></p>
<p><code>compute.instances.setName</code></p>
<p><code>compute. instances. setScheduling</code></p>
<p><code>compute. instances. setSecurityPolicy</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute. instances. setShieldedInstanceIntegrityPolicy</code></p>
<p><code>compute. instances. setShieldedVmIntegrityPolicy</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute. instances. simulateMaintenanceEvent</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute. instances. startWithEncryptionKey</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute.instances.suspend</code></p>
<p><code>compute.instances.troubleshoot</code></p>
<p><code>compute.instances.update</code></p>
<p><code>compute. instances. updateAccessConfig</code></p>
<p><code>compute. instances. updateDisplayDevice</code></p>
<p><code>compute. instances. updateNetworkInterface</code></p>
<p><code>compute. instances. updateSecurity</code></p>
<p><code>compute. instances. updateShieldedInstanceConfig</code></p>
<p><code>compute. instances. updateShieldedVmConfig</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute.instances.useReadOnly</code></p>
<p><code>compute. instantSnapshotGroups. create</code></p>
<p><code>compute. instantSnapshotGroups. delete</code></p>
<p><code>compute. instantSnapshotGroups. get</code></p>
<p><code>compute. instantSnapshotGroups. getIamPolicy</code></p>
<p><code>compute. instantSnapshotGroups. list</code></p>
<p><code>compute. instantSnapshotGroups. useReadOnly</code></p>
<p><code>compute. instantSnapshots. create</code></p>
<p><code>compute. instantSnapshots. delete</code></p>
<p><code>compute. instantSnapshots. export</code></p>
<p><code>compute.instantSnapshots.get</code></p>
<p><code>compute. instantSnapshots. getIamPolicy</code></p>
<p><code>compute.instantSnapshots.list</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
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
<p><code>compute.licenseCodes.get</code></p>
<p><code>compute. licenseCodes. getIamPolicy</code></p>
<p><code>compute.licenseCodes.list</code></p>
<p><code>compute.licenses.create</code></p>
<p><code>compute.licenses.delete</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.getIamPolicy</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute.licenses.update</code></p>
<p><code>compute.machineImages.create</code></p>
<p><code>compute.machineImages.delete</code></p>
<p><code>compute.machineImages.get</code></p>
<p><code>compute. machineImages. getIamPolicy</code></p>
<p><code>compute.machineImages.list</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
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
<p><code>compute.multiMigMembers.*</code></p>
<ul>
<li><code>compute.multiMigMembers.get</code></li>
<li><code>compute.multiMigMembers.list</code></li>
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
<p><code>compute.networks.create</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute. recoverableSnapshots. delete</code></p>
<p><code>compute. recoverableSnapshots. get</code></p>
<p><code>compute. recoverableSnapshots. getIamPolicy</code></p>
<p><code>compute. recoverableSnapshots. list</code></p>
<p><code>compute. recoverableSnapshots. recover</code></p>
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
<p><code>compute.reservationSubBlocks.*</code></p>
<ul>
<li><code>compute. reservationSubBlocks. get</code></li>
<li><code>compute. reservationSubBlocks. list</code></li>
<li><code>compute. reservationSubBlocks. performMaintenance</code></li>
<li><code>compute. reservationSubBlocks. reportFaulty</code></li>
</ul>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute. resourcePolicies. create</code></p>
<p><code>compute. resourcePolicies. delete</code></p>
<p><code>compute.resourcePolicies.get</code></p>
<p><code>compute. resourcePolicies. getIamPolicy</code></p>
<p><code>compute.resourcePolicies.list</code></p>
<p><code>compute. resourcePolicies. update</code></p>
<p><code>compute.resourcePolicies.use</code></p>
<p><code>compute. resourcePolicies. useReadOnly</code></p>
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
<p><code>compute.snapshotGroups.create</code></p>
<p><code>compute.snapshotGroups.delete</code></p>
<p><code>compute.snapshotGroups.get</code></p>
<p><code>compute. snapshotGroups. getIamPolicy</code></p>
<p><code>compute.snapshotGroups.list</code></p>
<p><code>compute. snapshotGroups. useReadOnly</code></p>
<p><code>compute.snapshots.create</code></p>
<p><code>compute. snapshots. createTagBinding</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute. snapshots. deleteTagBinding</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute. snapshots. getEffectiveRecycleBinRule</code></p>
<p><code>compute.snapshots.getIamPolicy</code></p>
<p><code>compute.snapshots.list</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.updateKmsKey</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
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
<p><code>compute.subnetworks.create</code></p>
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

## Batch permissions

| Permission                          | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `batch.jobs.create`                 | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `batch.jobs.delete`                 | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `batch.jobs.get`                    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `batch.jobs.list`                   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                         |
| `batch.locations.get`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `batch.locations.list`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `batch.operations.get`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `batch.operations.list`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `batch. resourceAllowances. create` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `batch. resourceAllowances. delete` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `batch.resourceAllowances.get`      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `batch.resourceAllowances.list`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Batch ResourceAllowance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesViewer) ( `roles/ batch.resourceAllowancesViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                     |
| `batch. resourceAllowances. update` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch ResourceAllowance Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.resourceAllowancesEditor) ( `roles/ batch.resourceAllowancesEditor` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `batch.states.report`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Agent Reporter](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.agentReporter) ( `roles/ batch.agentReporter` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `batch.tasks.get`                   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `batch.tasks.list`                  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Batch Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.admin) ( `roles/ batch.admin` ) [Batch Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.viewer) ( `roles/ batch.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Batch Job Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsEditor) ( `roles/ batch.jobsEditor` ) [Batch Job Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/batch#batch.jobsViewer) ( `roles/ batch.jobsViewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                         |
