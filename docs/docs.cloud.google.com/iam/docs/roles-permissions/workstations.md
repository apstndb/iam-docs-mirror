---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workstations
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workstations
title: Cloud Workstations roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Workstations. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Workstations roles

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
<td><h4 id="workstations.admin" class="role-title add-link" data-text="Cloud Workstations Admin" tabindex="-1">Cloud Workstations Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p>Grants CRUD access to all Workstation resources.</p></td>
<td><p><code dir="ltr" translate="no">compute.acceleratorTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.acceleratorTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.machineTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.machineTypes.get</code></li>
<li><code dir="ltr" translate="no">compute.machineTypes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.operations.get</code></li>
<li><code dir="ltr" translate="no">workstations.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  create</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  delete</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  get</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationClusters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  create</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  get</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  list</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">workstations.  workstationConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstations.  create</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  delete</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  start</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.stop</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.editor" class="role-title add-link" data-text="Cloud Workstations Editor" tabindex="-1">Cloud Workstations Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p>Editor role for Cloud Workstations</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.operations.get</code></li>
<li><code dir="ltr" translate="no">workstations.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  create</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  delete</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  update</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  create</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  delete</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  update</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  create</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  delete</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  start</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.stop</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  update</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.networkAdmin" class="role-title add-link" data-text="Cloud Workstations Network Admin" tabindex="-1">Cloud Workstations Network Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.networkAdmin</code> )</p>
<p>Grants ability to connect a Workstation Cluster to a shared VPC network.</p></td>
<td><p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.operationViewer" class="role-title add-link" data-text="Cloud Workstations Operation Viewer" tabindex="-1">Cloud Workstations Operation Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.operationViewer</code> )</p>
<p>Grants ability to view Cloud Workstations API operations.</p></td>
<td><p><code dir="ltr" translate="no">workstations.operations.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.policyAdmin" class="role-title add-link" data-text="Cloud Workstations Policy Admin" tabindex="-1">Cloud Workstations Policy Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.policyAdmin</code> )</p>
<p>Grants permission to set IAM policy on workstation.</p></td>
<td><p><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  setIamPolicy</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.user" class="role-title add-link" data-text="Cloud Workstations User" tabindex="-1">Cloud Workstations User</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.user</code> )</p>
<p>Grants runtime access to Workstation resources.</p></td>
<td><p><code dir="ltr" translate="no">workstations.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.operations.get</code></li>
<li><code dir="ltr" translate="no">workstations.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstations.  delete</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  start</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.stop</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  update</code></p>
<p><code dir="ltr" translate="no">workstations.workstations.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationCreator" class="role-title add-link" data-text="Cloud Workstations Creator" tabindex="-1">Cloud Workstations Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p>Grants ability to create Workstation resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.operations.get</code></li>
<li><code dir="ltr" translate="no">workstations.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  create</code></p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationLimitExemptedCreator" class="role-title add-link" data-text="Cloud Workstations Limit Exempted Creator" tabindex="-1">Cloud Workstations Limit Exempted Creator</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p>
<p>Grants ability to create workstations with exemption from max_usable_workstations Limit.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workstations.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workstations.operations.get</code></li>
<li><code dir="ltr" translate="no">workstations.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">workstations.  workstationConfigs.  get</code></p>
<p><code dir="ltr" translate="no">workstations.  workstations.  create</code></p></td>
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
<td><h4 id="workstations.serviceAgent" class="role-title add-link" data-text="Workstations Service Agent" tabindex="-1">Workstations Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</p>
<p>Grants the Workstations Service Account access to manage resources in consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.resize</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.attachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.instances.detachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></p>
<p><code dir="ltr" translate="no">compute.instances.resume</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.suspend</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.create</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.delete</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.get</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.snapshots.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Workstations permissions

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
<td><h4 id="workstations.operations.get" class="permission-name add-link" data-text="workstations.operations.get" tabindex="-1"><code dir="ltr" translate="no">workstations.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.operationViewer">Cloud Workstations Operation Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.operationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.operations.list" class="permission-name add-link" data-text="workstations.operations.list" tabindex="-1"><code dir="ltr" translate="no">workstations.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationClusters.create" class="permission-name add-link" data-text="workstations.workstationClusters.create" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationClusters.createTagBinding" class="permission-name add-link" data-text="workstations.workstationClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationClusters.delete" class="permission-name add-link" data-text="workstations.workstationClusters.delete" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationClusters.deleteTagBinding" class="permission-name add-link" data-text="workstations.workstationClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationClusters.get" class="permission-name add-link" data-text="workstations.workstationClusters.get" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationClusters.list" class="permission-name add-link" data-text="workstations.workstationClusters.list" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationClusters.listEffectiveTags" class="permission-name add-link" data-text="workstations.workstationClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationClusters.listTagBindings" class="permission-name add-link" data-text="workstations.workstationClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationClusters.update" class="permission-name add-link" data-text="workstations.workstationClusters.update" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationConfigs.create" class="permission-name add-link" data-text="workstations.workstationConfigs.create" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationConfigs.delete" class="permission-name add-link" data-text="workstations.workstationConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationConfigs.get" class="permission-name add-link" data-text="workstations.workstationConfigs.get" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationConfigs.getIamPolicy" class="permission-name add-link" data-text="workstations.workstationConfigs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationConfigs.list" class="permission-name add-link" data-text="workstations.workstationConfigs.list" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstationConfigs.setIamPolicy" class="permission-name add-link" data-text="workstations.workstationConfigs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstationConfigs.update" class="permission-name add-link" data-text="workstations.workstationConfigs.update" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstationConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstations.create" class="permission-name add-link" data-text="workstations.workstations.create" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationCreator">Cloud Workstations Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.workstationLimitExemptedCreator">Cloud Workstations Limit Exempted Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.workstationLimitExemptedCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstations.delete" class="permission-name add-link" data-text="workstations.workstations.delete" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstations.get" class="permission-name add-link" data-text="workstations.workstations.get" tabindex="-1"><code dir="ltr" translate="no">workstations.workstations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstations.getIamPolicy" class="permission-name add-link" data-text="workstations.workstations.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.policyAdmin">Cloud Workstations Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.policyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstations.list" class="permission-name add-link" data-text="workstations.workstations.list" tabindex="-1"><code dir="ltr" translate="no">workstations.workstations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstations.setIamPolicy" class="permission-name add-link" data-text="workstations.workstations.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.policyAdmin">Cloud Workstations Policy Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.policyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstations.start" class="permission-name add-link" data-text="workstations.workstations.start" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstations.stop" class="permission-name add-link" data-text="workstations.workstations.stop" tabindex="-1"><code dir="ltr" translate="no">workstations.workstations.stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workstations.workstations.update" class="permission-name add-link" data-text="workstations.workstations.update" tabindex="-1"><code dir="ltr" translate="no">workstations.  workstations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.admin">Cloud Workstations Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workstations.workstations.use" class="permission-name add-link" data-text="workstations.workstations.use" tabindex="-1"><code dir="ltr" translate="no">workstations.workstations.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.editor">Cloud Workstations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.user">Cloud Workstations User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.user</code> )</p></td>
</tr>
</tbody>
</table>
