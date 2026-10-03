---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration
title: Migrate to Virtual Machines roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Migrate to Virtual Machines. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Migrate to Virtual Machines roles

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
<td>Velostrata Manager <sup>Beta</sup>
<p>( <code>roles/ cloudmigration.inframanager</code> )</p>
<p>Ability to create and manage Compute VMs to run Velostrata Infrastructure</p></td>
<td><p><code>cloudmigration. velostrataendpoints. connect</code></p>
<p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.setLabels</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.diskTypes.*</code></p>
<ul>
<li><code>compute.diskTypes.get</code></li>
<li><code>compute.diskTypes.list</code></li>
</ul>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.createSnapshot</code></p>
<p><code>compute.disks.delete</code></p>
<p><code>compute.disks.get</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.disks.setLabels</code></p>
<p><code>compute.disks.update</code></p>
<p><code>compute.disks.use</code></p>
<p><code>compute.disks.useReadOnly</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.list</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute.instances.attachDisk</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.detachDisk</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.instances.reset</code></p>
<p><code>compute. instances. setDiskAutoDelete</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute. instances. setMachineType</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute. instances. setMinCpuPlatform</code></p>
<p><code>compute. instances. setScheduling</code></p>
<p><code>compute. instances. setServiceAccount</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute. instances. startWithEncryptionKey</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute.instances.update</code></p>
<p><code>compute. instances. updateNetworkInterface</code></p>
<p><code>compute. instances. updateShieldedInstanceConfig</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute.licenseCodes.get</code></p>
<p><code>compute.licenseCodes.list</code></p>
<p><code>compute.licenses.get</code></p>
<p><code>compute.licenses.list</code></p>
<p><code>compute.machineTypes.*</code></p>
<ul>
<li><code>compute.machineTypes.get</code></li>
<li><code>compute.machineTypes.list</code></li>
</ul>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.nodeGroups.get</code></p>
<p><code>compute.nodeGroups.list</code></p>
<p><code>compute.nodeTemplates.list</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.snapshots.create</code></p>
<p><code>compute.snapshots.delete</code></p>
<p><code>compute.snapshots.get</code></p>
<p><code>compute.snapshots.setLabels</code></p>
<p><code>compute.snapshots.useReadOnly</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>gkehub.endpoints.connect</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam.serviceAccounts.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.buckets.update</code></p></td>
</tr>
<tr class="even">
<td>Velostrata Storage Access <sup>Beta</sup>
<p>( <code>roles/ cloudmigration.storageaccess</code> )</p>
<p>Ability to access migration storage</p></td>
<td><p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
<tr class="odd">
<td>Velostrata Manager Connection Agent <sup>Beta</sup>
<p>( <code>roles/ cloudmigration.velostrataconnect</code> )</p>
<p>Ability to set up connection between Velostrata Manager and Google</p></td>
<td><p><code>cloudmigration. velostrataendpoints. connect</code></p>
<p><code>gkehub.endpoints.connect</code></p></td>
</tr>
</tbody>
</table>

## Migrate to Virtual Machines permissions

| Permission                                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cloudmigration. velostrataendpoints. connect` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Velostrata Manager](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.inframanager) ( `roles/ cloudmigration.inframanager` ) [Velostrata Manager Connection Agent](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudmigration#cloudmigration.velostrataconnect) ( `roles/ cloudmigration.velostrataconnect` ) |
