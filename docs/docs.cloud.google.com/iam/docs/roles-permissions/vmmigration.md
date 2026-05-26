---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/vmmigration
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration
title: VM Migration roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for VM Migration. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## VM Migration roles

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
<td><h4 id="vmmigration.admin" class="role-title add-link" data-text="VM Migration Administrator" tabindex="-1">VM Migration Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p>Ability to view and edit all VM Migration objects</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmmigration.cloneJobs.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.cloneJobs.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.cloneJobs.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.cloneJobs.update</code></li>
<li><code dir="ltr" translate="no">vmmigration.cutoverJobs.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.cutoverJobs.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.cutoverJobs.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.cutoverJobs.update</code></li>
<li><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  create</code></li>
<li><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  get</code></li>
<li><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  list</code></li>
<li><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  update</code></li>
<li><code dir="ltr" translate="no">vmmigration.deployments.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.deployments.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.deployments.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.groups.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.groups.delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.groups.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.groups.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.groups.update</code></li>
<li><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  cancel</code></li>
<li><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  get</code></li>
<li><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  list</code></li>
<li><code dir="ltr" translate="no">vmmigration.  imageImports.  create</code></li>
<li><code dir="ltr" translate="no">vmmigration.  imageImports.  delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.imageImports.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.imageImports.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.locations.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.locations.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.  migratingVms.  create</code></li>
<li><code dir="ltr" translate="no">vmmigration.  migratingVms.  delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.migratingVms.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.migratingVms.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.  migratingVms.  update</code></li>
<li><code dir="ltr" translate="no">vmmigration.operations.cancel</code></li>
<li><code dir="ltr" translate="no">vmmigration.operations.delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.operations.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.operations.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.  replicationCycles.  get</code></li>
<li><code dir="ltr" translate="no">vmmigration.  replicationCycles.  list</code></li>
<li><code dir="ltr" translate="no">vmmigration.sources.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.sources.delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.sources.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.sources.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.sources.update</code></li>
<li><code dir="ltr" translate="no">vmmigration.targets.create</code></li>
<li><code dir="ltr" translate="no">vmmigration.targets.delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.targets.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.targets.list</code></li>
<li><code dir="ltr" translate="no">vmmigration.targets.update</code></li>
<li><code dir="ltr" translate="no">vmmigration.  utilizationReports.  create</code></li>
<li><code dir="ltr" translate="no">vmmigration.  utilizationReports.  delete</code></li>
<li><code dir="ltr" translate="no">vmmigration.  utilizationReports.  get</code></li>
<li><code dir="ltr" translate="no">vmmigration.  utilizationReports.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.viewer" class="role-title add-link" data-text="VM Migration Viewer" tabindex="-1">VM Migration Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p>Ability to view all VM Migration objects</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cloneJobs.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.cloneJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.cutoverJobs.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.cutoverJobs.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  get</code></p>
<p><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.deployments.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.deployments.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.groups.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.groups.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  get</code></p>
<p><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  list</code></p>
<p><code dir="ltr" translate="no">vmmigration.imageImports.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.imageImports.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmmigration.locations.get</code></li>
<li><code dir="ltr" translate="no">vmmigration.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmmigration.migratingVms.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.migratingVms.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.operations.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.operations.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  replicationCycles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vmmigration.  replicationCycles.  get</code></li>
<li><code dir="ltr" translate="no">vmmigration.  replicationCycles.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">vmmigration.sources.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.sources.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.targets.get</code></p>
<p><code dir="ltr" translate="no">vmmigration.targets.list</code></p>
<p><code dir="ltr" translate="no">vmmigration.  utilizationReports.  get</code></p>
<p><code dir="ltr" translate="no">vmmigration.  utilizationReports.  list</code></p></td>
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
<td><h4 id="vmmigration.serviceAgent" class="role-title add-link" data-text="VM Migration Service Agent" tabindex="-1">VM Migration Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  vmmigration.serviceAgent</code> )</p>
<p>Grants VM Migration Service Account access to create migrated VMs, disks and images in the user project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.createSnapshot</code></p>
<p><code dir="ltr" translate="no">compute.disks.delete</code></p>
<p><code dir="ltr" translate="no">compute.disks.get</code></p>
<p><code dir="ltr" translate="no">compute.disks.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.disks.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.images.create</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  setServiceAccount</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.instances.update</code></p>
<p><code dir="ltr" translate="no">compute.instances.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.create</code></p>
<p><code dir="ltr" translate="no">compute.machineImages.get</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.get</code></p>
<p><code dir="ltr" translate="no">compute.storagePools.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p></td>
</tr>
</tbody>
</table>

## VM Migration permissions

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
<td><h4 id="vmmigration.cloneJobs.create" class="permission-name add-link" data-text="vmmigration.cloneJobs.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cloneJobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.cloneJobs.get" class="permission-name add-link" data-text="vmmigration.cloneJobs.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cloneJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.cloneJobs.list" class="permission-name add-link" data-text="vmmigration.cloneJobs.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cloneJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.cloneJobs.update" class="permission-name add-link" data-text="vmmigration.cloneJobs.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cloneJobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.cutoverJobs.create" class="permission-name add-link" data-text="vmmigration.cutoverJobs.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cutoverJobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.cutoverJobs.get" class="permission-name add-link" data-text="vmmigration.cutoverJobs.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cutoverJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.cutoverJobs.list" class="permission-name add-link" data-text="vmmigration.cutoverJobs.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cutoverJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.cutoverJobs.update" class="permission-name add-link" data-text="vmmigration.cutoverJobs.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.cutoverJobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.datacenterConnectors.create" class="permission-name add-link" data-text="vmmigration.datacenterConnectors.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.datacenterConnectors.delete" class="permission-name add-link" data-text="vmmigration.datacenterConnectors.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.datacenterConnectors.get" class="permission-name add-link" data-text="vmmigration.datacenterConnectors.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.datacenterConnectors.list" class="permission-name add-link" data-text="vmmigration.datacenterConnectors.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.datacenterConnectors.update" class="permission-name add-link" data-text="vmmigration.datacenterConnectors.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  datacenterConnectors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.deployments.create" class="permission-name add-link" data-text="vmmigration.deployments.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.deployments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.deployments.get" class="permission-name add-link" data-text="vmmigration.deployments.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.deployments.list" class="permission-name add-link" data-text="vmmigration.deployments.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.groups.create" class="permission-name add-link" data-text="vmmigration.groups.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.groups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.groups.delete" class="permission-name add-link" data-text="vmmigration.groups.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.groups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.groups.get" class="permission-name add-link" data-text="vmmigration.groups.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.groups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.groups.list" class="permission-name add-link" data-text="vmmigration.groups.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.groups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.groups.update" class="permission-name add-link" data-text="vmmigration.groups.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.groups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.imageImportJobs.cancel" class="permission-name add-link" data-text="vmmigration.imageImportJobs.cancel" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.imageImportJobs.get" class="permission-name add-link" data-text="vmmigration.imageImportJobs.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.imageImportJobs.list" class="permission-name add-link" data-text="vmmigration.imageImportJobs.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  imageImportJobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.imageImports.create" class="permission-name add-link" data-text="vmmigration.imageImports.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  imageImports.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.imageImports.delete" class="permission-name add-link" data-text="vmmigration.imageImports.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  imageImports.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.imageImports.get" class="permission-name add-link" data-text="vmmigration.imageImports.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.imageImports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.imageImports.list" class="permission-name add-link" data-text="vmmigration.imageImports.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.imageImports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.locations.get" class="permission-name add-link" data-text="vmmigration.locations.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.locations.list" class="permission-name add-link" data-text="vmmigration.locations.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.migratingVms.create" class="permission-name add-link" data-text="vmmigration.migratingVms.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  migratingVms.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/migrationcenter#migrationcenter.serviceAgent">Migration Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  migrationcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.migratingVms.delete" class="permission-name add-link" data-text="vmmigration.migratingVms.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  migratingVms.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.migratingVms.get" class="permission-name add-link" data-text="vmmigration.migratingVms.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.migratingVms.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.migratingVms.list" class="permission-name add-link" data-text="vmmigration.migratingVms.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.migratingVms.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.migratingVms.update" class="permission-name add-link" data-text="vmmigration.migratingVms.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  migratingVms.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.operations.cancel" class="permission-name add-link" data-text="vmmigration.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">vmmigration.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.operations.delete" class="permission-name add-link" data-text="vmmigration.operations.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.operations.get" class="permission-name add-link" data-text="vmmigration.operations.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.operations.list" class="permission-name add-link" data-text="vmmigration.operations.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.replicationCycles.get" class="permission-name add-link" data-text="vmmigration.replicationCycles.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  replicationCycles.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.replicationCycles.list" class="permission-name add-link" data-text="vmmigration.replicationCycles.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  replicationCycles.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.sources.create" class="permission-name add-link" data-text="vmmigration.sources.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.sources.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.sources.delete" class="permission-name add-link" data-text="vmmigration.sources.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.sources.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.sources.get" class="permission-name add-link" data-text="vmmigration.sources.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.sources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.sources.list" class="permission-name add-link" data-text="vmmigration.sources.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.sources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.sources.update" class="permission-name add-link" data-text="vmmigration.sources.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.sources.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.targets.create" class="permission-name add-link" data-text="vmmigration.targets.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.targets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.targets.delete" class="permission-name add-link" data-text="vmmigration.targets.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.targets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.targets.get" class="permission-name add-link" data-text="vmmigration.targets.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.targets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.targets.list" class="permission-name add-link" data-text="vmmigration.targets.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.targets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.targets.update" class="permission-name add-link" data-text="vmmigration.targets.update" tabindex="-1"><code dir="ltr" translate="no">vmmigration.targets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.utilizationReports.create" class="permission-name add-link" data-text="vmmigration.utilizationReports.create" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  utilizationReports.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.utilizationReports.delete" class="permission-name add-link" data-text="vmmigration.utilizationReports.delete" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  utilizationReports.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vmmigration.utilizationReports.get" class="permission-name add-link" data-text="vmmigration.utilizationReports.get" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  utilizationReports.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="vmmigration.utilizationReports.list" class="permission-name add-link" data-text="vmmigration.utilizationReports.list" tabindex="-1"><code dir="ltr" translate="no">vmmigration.  utilizationReports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.admin">VM Migration Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmmigration#vmmigration.viewer">VM Migration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmmigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
