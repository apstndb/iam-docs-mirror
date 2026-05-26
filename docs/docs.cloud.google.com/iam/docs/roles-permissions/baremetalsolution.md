---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution
title: Bare Metal Solution roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Bare Metal Solution. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Bare Metal Solution roles

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
<td><h4 id="baremetalsolution.admin" class="role-title add-link" data-text="Bare Metal Solution Admin" tabindex="-1">Bare Metal Solution Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p>Administrator of Bare Metal Solution resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachLun</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  disableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  enableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  reset</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  start</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  stop</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.luns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.luns.create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  addProposal</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  approve</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.networks.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.nfsshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.sshKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  restore</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.editor" class="role-title add-link" data-text="Bare Metal Solution Editor" tabindex="-1">Bare Metal Solution Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p>Editor of Bare Metal Solution resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachLun</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  disableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  enableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  reset</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  start</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  stop</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.luns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.luns.create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  addProposal</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  approve</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.networks.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.nfsshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.sshKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  restore</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.viewer" class="role-title add-link" data-text="Bare Metal Solution Viewer" tabindex="-1">Bare Metal Solution Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p>Viewer of Bare Metal Solution resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.networks.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instancesadmin" class="role-title add-link" data-text="Bare Metal Solution Instances Admin" tabindex="-1">Bare Metal Solution Instances Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p>Admin of Bare Metal Solution Instance resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  attachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachLun</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachNetwork</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  detachVolume</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  disableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  enableInteractiveSerialConsole</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  reset</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  start</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  stop</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  instances.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instancesviewer" class="role-title add-link" data-text="Bare Metal Solution Instances Viewer" tabindex="-1">Bare Metal Solution Instances Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p>Viewer of Bare Metal Solution Instance resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.lunsadmin" class="role-title add-link" data-text="Luns Admin" tabindex="-1">Luns Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.lunsadmin</code> )</p>
<p>Administrator of Bare Metal Solution Lun resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.luns.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.lunsviewer" class="role-title add-link" data-text="Luns Viewer" tabindex="-1">Luns Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.lunsviewer</code> )</p>
<p>Viewer of Bare Metal Solution Lun resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.luns.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.luns.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.maintenanceeventsadmin" class="role-title add-link" data-text="Maintenance Events Admin" tabindex="-1">Maintenance Events Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsadmin</code> )</p>
<p>Administrator of Bare Metal Solution maintenance events resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  addProposal</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  approve</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.maintenanceeventseditor" class="role-title add-link" data-text="Maintenance Events Editor" tabindex="-1">Maintenance Events Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventseditor</code> )</p>
<p>Editor of Bare Metal Solution maintenance events resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  addProposal</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  approve</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.maintenanceeventsviewer" class="role-title add-link" data-text="Maintenance Events Viewer" tabindex="-1">Maintenance Events Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsviewer</code> )</p>
<p>Viewer of Bare Metal Solution maintenance events resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.networksadmin" class="role-title add-link" data-text="Networks Admin" tabindex="-1">Networks Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p>Admin of Bare Metal Solution networks resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.networks.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  networks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.nfssharesadmin" class="role-title add-link" data-text="NFS Shares Admin" tabindex="-1">NFS Shares Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p>Administrator of Bare Metal Solution NFS Share resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.nfsshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.nfsshareseditor" class="role-title add-link" data-text="NFS Shares Editor" tabindex="-1">NFS Shares Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p>Editor of Bare Metal Solution NFS Share resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.nfsshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.nfssharesviewer" class="role-title add-link" data-text="NFS Shares Viewer" tabindex="-1">NFS Shares Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.nfssharesviewer</code> )</p>
<p>Viewer of Bare Metal Solution NFS Share resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.osimagesviewer" class="role-title add-link" data-text="OS Images Viewer" tabindex="-1">OS Images Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.osimagesviewer</code> )</p>
<p>Viewer of Bare Metal Solution OS images resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.procurementsadmin" class="role-title add-link" data-text="Bare Metal Solution Procurements Admin" tabindex="-1">Bare Metal Solution Procurements Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p>Administrator of Bare Metal Solution Procurements</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.procurementseditor" class="role-title add-link" data-text="Bare Metal Solution Procurements Editor" tabindex="-1">Bare Metal Solution Procurements Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p>
<p>Editor of Bare Metal Solution Procurements</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.procurementsviewer" class="role-title add-link" data-text="Bare Metal Solution Procurements Viewer" tabindex="-1">Bare Metal Solution Procurements Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.procurementsviewer</code> )</p>
<p>Viewer of Bare Metal Solution Procurements</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.skus.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.storageadmin" class="role-title add-link" data-text="Bare Metal Solution Storage Admin" tabindex="-1">Bare Metal Solution Storage Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p>Administrator of Bare Metal Solution storage resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.luns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.luns.create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.luns.update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.nfsshares.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  restore</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumesadmin" class="role-title add-link" data-text="Volume Admin" tabindex="-1">Volume Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p>Administrator of Bare Metal Solution volume resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  evict</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumeseditor" class="role-title add-link" data-text="Volumes Editor" tabindex="-1">Volumes Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p>Editor of Bare Metal Solution volumes resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.pods.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumesnapshotsadmin" class="role-title add-link" data-text="Snapshots Admin" tabindex="-1">Snapshots Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p>Administrator of Bare Metal Solution snapshots resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></li>
<li><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  restore</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumesnapshotseditor" class="role-title add-link" data-text="Snapshots Editor" tabindex="-1">Snapshots Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p>
<p>Editor of Bare Metal Solution snapshots resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumesnapshotsviewer" class="role-title add-link" data-text="Snapshots Viewer" tabindex="-1">Snapshots Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsviewer</code> )</p>
<p>Viewer of Bare Metal Solution snapshots resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumessviewer" class="role-title add-link" data-text="Volumes Viewer" tabindex="-1">Volumes Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.volumessviewer</code> )</p>
<p>Viewer of Bare Metal Solution volumes resources</p></td>
<td><p><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></p>
<p><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></p></td>
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
<td><h4 id="baremetalsolution.serviceAgent" class="role-title add-link" data-text="Bare Metal Solution Service Agent" tabindex="-1">Bare Metal Solution Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  baremetalsolution.serviceAgent</code> )</p>
<p>Gives permission to manage network resources such as interconnect pairing keys, required for Bare Metal Solution.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.get</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Bare Metal Solution permissions

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
<td><h4 id="baremetalsolution.instancequotas.list" class="permission-name add-link" data-text="baremetalsolution.instancequotas.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instancequotas.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.attachNetwork" class="permission-name add-link" data-text="baremetalsolution.instances.attachNetwork" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  attachNetwork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.attachVolume" class="permission-name add-link" data-text="baremetalsolution.instances.attachVolume" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  attachVolume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.create" class="permission-name add-link" data-text="baremetalsolution.instances.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.detachLun" class="permission-name add-link" data-text="baremetalsolution.instances.detachLun" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  detachLun</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.detachNetwork" class="permission-name add-link" data-text="baremetalsolution.instances.detachNetwork" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  detachNetwork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.detachVolume" class="permission-name add-link" data-text="baremetalsolution.instances.detachVolume" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  detachVolume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.disableInteractiveSerialConsole" class="permission-name add-link" data-text="baremetalsolution.instances.disableInteractiveSerialConsole" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  disableInteractiveSerialConsole</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.enableInteractiveSerialConsole" class="permission-name add-link" data-text="baremetalsolution.instances.enableInteractiveSerialConsole" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  enableInteractiveSerialConsole</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.get" class="permission-name add-link" data-text="baremetalsolution.instances.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.list" class="permission-name add-link" data-text="baremetalsolution.instances.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.rename" class="permission-name add-link" data-text="baremetalsolution.instances.rename" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  rename</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.reset" class="permission-name add-link" data-text="baremetalsolution.instances.reset" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  reset</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.start" class="permission-name add-link" data-text="baremetalsolution.instances.start" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  start</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.instances.stop" class="permission-name add-link" data-text="baremetalsolution.instances.stop" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.instances.update" class="permission-name add-link" data-text="baremetalsolution.instances.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  instances.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.luns.create" class="permission-name add-link" data-text="baremetalsolution.luns.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.luns.delete" class="permission-name add-link" data-text="baremetalsolution.luns.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.luns.evict" class="permission-name add-link" data-text="baremetalsolution.luns.evict" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.evict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.luns.get" class="permission-name add-link" data-text="baremetalsolution.luns.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsadmin">Luns Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsviewer">Luns Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.luns.list" class="permission-name add-link" data-text="baremetalsolution.luns.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsadmin">Luns Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsviewer">Luns Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.luns.update" class="permission-name add-link" data-text="baremetalsolution.luns.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.luns.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.maintenanceevents.addProposal" class="permission-name add-link" data-text="baremetalsolution.maintenanceevents.addProposal" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  addProposal</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsadmin">Maintenance Events Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventseditor">Maintenance Events Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventseditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.maintenanceevents.approve" class="permission-name add-link" data-text="baremetalsolution.maintenanceevents.approve" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsadmin">Maintenance Events Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventseditor">Maintenance Events Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventseditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.maintenanceevents.get" class="permission-name add-link" data-text="baremetalsolution.maintenanceevents.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsadmin">Maintenance Events Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventseditor">Maintenance Events Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsviewer">Maintenance Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.maintenanceevents.list" class="permission-name add-link" data-text="baremetalsolution.maintenanceevents.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  maintenanceevents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsadmin">Maintenance Events Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventseditor">Maintenance Events Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.maintenanceeventsviewer">Maintenance Events Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.maintenanceeventsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.networkquotas.list" class="permission-name add-link" data-text="baremetalsolution.networkquotas.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networkquotas.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.networks.create" class="permission-name add-link" data-text="baremetalsolution.networks.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.networks.delete" class="permission-name add-link" data-text="baremetalsolution.networks.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.networks.get" class="permission-name add-link" data-text="baremetalsolution.networks.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.networks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.networks.list" class="permission-name add-link" data-text="baremetalsolution.networks.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.networks.rename" class="permission-name add-link" data-text="baremetalsolution.networks.rename" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networks.  rename</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.networks.update" class="permission-name add-link" data-text="baremetalsolution.networks.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  networks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.nfsshares.create" class="permission-name add-link" data-text="baremetalsolution.nfsshares.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.nfsshares.delete" class="permission-name add-link" data-text="baremetalsolution.nfsshares.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.nfsshares.get" class="permission-name add-link" data-text="baremetalsolution.nfsshares.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesviewer">NFS Shares Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.nfsshares.list" class="permission-name add-link" data-text="baremetalsolution.nfsshares.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesviewer">NFS Shares Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.nfsshares.rename" class="permission-name add-link" data-text="baremetalsolution.nfsshares.rename" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  rename</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.nfsshares.update" class="permission-name add-link" data-text="baremetalsolution.nfsshares.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  nfsshares.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.operations.get" class="permission-name add-link" data-text="baremetalsolution.operations.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesviewer">Bare Metal Solution Instances Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsadmin">Luns Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.lunsviewer">Luns Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.lunsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesviewer">NFS Shares Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotseditor">Snapshots Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsviewer">Snapshots Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumessviewer">Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumessviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.osimages.list" class="permission-name add-link" data-text="baremetalsolution.osimages.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  osimages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.osimagesviewer">OS Images Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.osimagesviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.pods.list" class="permission-name add-link" data-text="baremetalsolution.pods.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.pods.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.instancesadmin">Bare Metal Solution Instances Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.instancesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.networksadmin">Networks Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.networksadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfssharesadmin">NFS Shares Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfssharesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.nfsshareseditor">NFS Shares Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.nfsshareseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsadmin">Bare Metal Solution Procurements Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementseditor">Bare Metal Solution Procurements Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.procurements.create" class="permission-name add-link" data-text="baremetalsolution.procurements.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  procurements.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsadmin">Bare Metal Solution Procurements Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementseditor">Bare Metal Solution Procurements Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.procurements.get" class="permission-name add-link" data-text="baremetalsolution.procurements.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  procurements.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsadmin">Bare Metal Solution Procurements Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementseditor">Bare Metal Solution Procurements Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsviewer">Bare Metal Solution Procurements Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.procurements.list" class="permission-name add-link" data-text="baremetalsolution.procurements.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  procurements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsadmin">Bare Metal Solution Procurements Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementseditor">Bare Metal Solution Procurements Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsviewer">Bare Metal Solution Procurements Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.skus.list" class="permission-name add-link" data-text="baremetalsolution.skus.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.skus.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsadmin">Bare Metal Solution Procurements Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementseditor">Bare Metal Solution Procurements Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.procurementsviewer">Bare Metal Solution Procurements Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.procurementsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.snapshotschedulepolicies.create" class="permission-name add-link" data-text="baremetalsolution.snapshotschedulepolicies.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.snapshotschedulepolicies.delete" class="permission-name add-link" data-text="baremetalsolution.snapshotschedulepolicies.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.snapshotschedulepolicies.get" class="permission-name add-link" data-text="baremetalsolution.snapshotschedulepolicies.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.snapshotschedulepolicies.list" class="permission-name add-link" data-text="baremetalsolution.snapshotschedulepolicies.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.snapshotschedulepolicies.update" class="permission-name add-link" data-text="baremetalsolution.snapshotschedulepolicies.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  snapshotschedulepolicies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.sshKeys.create" class="permission-name add-link" data-text="baremetalsolution.sshKeys.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.sshKeys.delete" class="permission-name add-link" data-text="baremetalsolution.sshKeys.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  sshKeys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.sshKeys.list" class="permission-name add-link" data-text="baremetalsolution.sshKeys.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.sshKeys.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.storageaggregatepools.list" class="permission-name add-link" data-text="baremetalsolution.storageaggregatepools.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  storageaggregatepools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumequotas.list" class="permission-name add-link" data-text="baremetalsolution.volumequotas.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumequotas.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumes.create" class="permission-name add-link" data-text="baremetalsolution.volumes.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumes.delete" class="permission-name add-link" data-text="baremetalsolution.volumes.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumes.evict" class="permission-name add-link" data-text="baremetalsolution.volumes.evict" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  evict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumes.get" class="permission-name add-link" data-text="baremetalsolution.volumes.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.volumes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumessviewer">Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumessviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumes.list" class="permission-name add-link" data-text="baremetalsolution.volumes.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.volumes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumessviewer">Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumessviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumes.rename" class="permission-name add-link" data-text="baremetalsolution.volumes.rename" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  rename</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumes.resize" class="permission-name add-link" data-text="baremetalsolution.volumes.resize" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  resize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumes.update" class="permission-name add-link" data-text="baremetalsolution.volumes.update" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesadmin">Volume Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumeseditor">Volumes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumeseditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumesnapshots.create" class="permission-name add-link" data-text="baremetalsolution.volumesnapshots.create" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotseditor">Snapshots Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumesnapshots.delete" class="permission-name add-link" data-text="baremetalsolution.volumesnapshots.delete" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotseditor">Snapshots Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumesnapshots.get" class="permission-name add-link" data-text="baremetalsolution.volumesnapshots.get" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotseditor">Snapshots Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsviewer">Snapshots Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="baremetalsolution.volumesnapshots.list" class="permission-name add-link" data-text="baremetalsolution.volumesnapshots.list" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.viewer">Bare Metal Solution Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotseditor">Snapshots Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotseditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsviewer">Snapshots Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="baremetalsolution.volumesnapshots.restore" class="permission-name add-link" data-text="baremetalsolution.volumesnapshots.restore" tabindex="-1"><code dir="ltr" translate="no">baremetalsolution.  volumesnapshots.  restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.admin">Bare Metal Solution Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.editor">Bare Metal Solution Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.storageadmin">Bare Metal Solution Storage Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.storageadmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/baremetalsolution#baremetalsolution.volumesnapshotsadmin">Snapshots Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  baremetalsolution.volumesnapshotsadmin</code> )</p></td>
</tr>
</tbody>
</table>
