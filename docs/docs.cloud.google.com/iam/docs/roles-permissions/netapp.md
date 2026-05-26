---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/netapp
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/netapp
title: Google Cloud NetApp Volumes roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud NetApp Volumes. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud NetApp Volumes roles

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
<td><h4 id="netapp.admin" class="role-title add-link" data-text="Google Cloud NetApp Volumes Admin Beta" tabindex="-1">Google Cloud NetApp Volumes Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p>Full access to Google Cloud NetApp Volumes resources.</p></td>
<td><p><code dir="ltr" translate="no">backupdr.backupPlans.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupPlans.list</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">backupdr.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">backupdr.locations.list</code></p>
<p><code dir="ltr" translate="no">backupdr.operations.get</code></p>
<p><code dir="ltr" translate="no">backupdr.  serviceConfig.  initialize</code></p>
<p><code dir="ltr" translate="no">netapp.*</code></p>
<ul>
<li><code dir="ltr" translate="no">netapp.  activeDirectories.  create</code></li>
<li><code dir="ltr" translate="no">netapp.  activeDirectories.  delete</code></li>
<li><code dir="ltr" translate="no">netapp.activeDirectories.get</code></li>
<li><code dir="ltr" translate="no">netapp.activeDirectories.list</code></li>
<li><code dir="ltr" translate="no">netapp.  activeDirectories.  update</code></li>
<li><code dir="ltr" translate="no">netapp.backupPolicies.create</code></li>
<li><code dir="ltr" translate="no">netapp.backupPolicies.delete</code></li>
<li><code dir="ltr" translate="no">netapp.backupPolicies.get</code></li>
<li><code dir="ltr" translate="no">netapp.backupPolicies.list</code></li>
<li><code dir="ltr" translate="no">netapp.backupPolicies.update</code></li>
<li><code dir="ltr" translate="no">netapp.backupVaults.create</code></li>
<li><code dir="ltr" translate="no">netapp.backupVaults.delete</code></li>
<li><code dir="ltr" translate="no">netapp.backupVaults.get</code></li>
<li><code dir="ltr" translate="no">netapp.backupVaults.list</code></li>
<li><code dir="ltr" translate="no">netapp.backupVaults.update</code></li>
<li><code dir="ltr" translate="no">netapp.backups.create</code></li>
<li><code dir="ltr" translate="no">netapp.backups.delete</code></li>
<li><code dir="ltr" translate="no">netapp.backups.get</code></li>
<li><code dir="ltr" translate="no">netapp.backups.list</code></li>
<li><code dir="ltr" translate="no">netapp.backups.update</code></li>
<li><code dir="ltr" translate="no">netapp.hostGroups.create</code></li>
<li><code dir="ltr" translate="no">netapp.hostGroups.delete</code></li>
<li><code dir="ltr" translate="no">netapp.hostGroups.get</code></li>
<li><code dir="ltr" translate="no">netapp.hostGroups.list</code></li>
<li><code dir="ltr" translate="no">netapp.hostGroups.update</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.create</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.delete</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.encrypt</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.get</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.list</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.update</code></li>
<li><code dir="ltr" translate="no">netapp.kmsConfigs.verify</code></li>
<li><code dir="ltr" translate="no">netapp.locations.get</code></li>
<li><code dir="ltr" translate="no">netapp.locations.list</code></li>
<li><code dir="ltr" translate="no">netapp.ontap.delete</code></li>
<li><code dir="ltr" translate="no">netapp.ontap.patch</code></li>
<li><code dir="ltr" translate="no">netapp.ontap.post</code></li>
<li><code dir="ltr" translate="no">netapp.operations.cancel</code></li>
<li><code dir="ltr" translate="no">netapp.operations.delete</code></li>
<li><code dir="ltr" translate="no">netapp.operations.get</code></li>
<li><code dir="ltr" translate="no">netapp.operations.list</code></li>
<li><code dir="ltr" translate="no">netapp.quotaRules.create</code></li>
<li><code dir="ltr" translate="no">netapp.quotaRules.delete</code></li>
<li><code dir="ltr" translate="no">netapp.quotaRules.get</code></li>
<li><code dir="ltr" translate="no">netapp.quotaRules.list</code></li>
<li><code dir="ltr" translate="no">netapp.quotaRules.update</code></li>
<li><code dir="ltr" translate="no">netapp.replications.create</code></li>
<li><code dir="ltr" translate="no">netapp.replications.delete</code></li>
<li><code dir="ltr" translate="no">netapp.  replications.  establishPeering</code></li>
<li><code dir="ltr" translate="no">netapp.replications.get</code></li>
<li><code dir="ltr" translate="no">netapp.replications.list</code></li>
<li><code dir="ltr" translate="no">netapp.replications.resume</code></li>
<li><code dir="ltr" translate="no">netapp.replications.reverse</code></li>
<li><code dir="ltr" translate="no">netapp.replications.stop</code></li>
<li><code dir="ltr" translate="no">netapp.replications.sync</code></li>
<li><code dir="ltr" translate="no">netapp.replications.update</code></li>
<li><code dir="ltr" translate="no">netapp.snapshots.create</code></li>
<li><code dir="ltr" translate="no">netapp.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">netapp.snapshots.get</code></li>
<li><code dir="ltr" translate="no">netapp.snapshots.list</code></li>
<li><code dir="ltr" translate="no">netapp.snapshots.update</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.create</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.delete</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.get</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.list</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.switch</code></li>
<li><code dir="ltr" translate="no">netapp.storagePools.update</code></li>
<li><code dir="ltr" translate="no">netapp.  storagePools.  validateDirectoryService</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.create</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.delete</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.export</code></li>
<li><code dir="ltr" translate="no">netapp.  volumes.  findValidCRRRegions</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.get</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.list</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.restore</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.revert</code></li>
<li><code dir="ltr" translate="no">netapp.volumes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.viewer" class="role-title add-link" data-text="Google Cloud NetApp Volumes Viewer Beta" tabindex="-1">Google Cloud NetApp Volumes Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p>Readonly access to Google Cloud NetApp Volumes resources.</p></td>
<td><p><code dir="ltr" translate="no">netapp.activeDirectories.get</code></p>
<p><code dir="ltr" translate="no">netapp.activeDirectories.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupPolicies.get</code></p>
<p><code dir="ltr" translate="no">netapp.backupPolicies.list</code></p>
<p><code dir="ltr" translate="no">netapp.backupVaults.get</code></p>
<p><code dir="ltr" translate="no">netapp.backupVaults.list</code></p>
<p><code dir="ltr" translate="no">netapp.backups.get</code></p>
<p><code dir="ltr" translate="no">netapp.backups.list</code></p>
<p><code dir="ltr" translate="no">netapp.hostGroups.get</code></p>
<p><code dir="ltr" translate="no">netapp.hostGroups.list</code></p>
<p><code dir="ltr" translate="no">netapp.kmsConfigs.get</code></p>
<p><code dir="ltr" translate="no">netapp.kmsConfigs.list</code></p>
<p><code dir="ltr" translate="no">netapp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">netapp.locations.get</code></li>
<li><code dir="ltr" translate="no">netapp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">netapp.operations.get</code></p>
<p><code dir="ltr" translate="no">netapp.operations.list</code></p>
<p><code dir="ltr" translate="no">netapp.quotaRules.get</code></p>
<p><code dir="ltr" translate="no">netapp.quotaRules.list</code></p>
<p><code dir="ltr" translate="no">netapp.replications.get</code></p>
<p><code dir="ltr" translate="no">netapp.replications.list</code></p>
<p><code dir="ltr" translate="no">netapp.snapshots.get</code></p>
<p><code dir="ltr" translate="no">netapp.snapshots.list</code></p>
<p><code dir="ltr" translate="no">netapp.storagePools.get</code></p>
<p><code dir="ltr" translate="no">netapp.storagePools.list</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.get</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.dataExporter" class="role-title add-link" data-text="Google Cloud NetApp Volumes Data Exporter Beta" tabindex="-1">Google Cloud NetApp Volumes Data Exporter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  netapp.dataExporter</code> )</p>
<p>Access to export data from Google Cloud NetApp Volumes.</p></td>
<td><p><code dir="ltr" translate="no">netapp.operations.get</code></p>
<p><code dir="ltr" translate="no">netapp.volumes.export</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud NetApp Volumes permissions

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
<td><h4 id="netapp.activeDirectories.create" class="permission-name add-link" data-text="netapp.activeDirectories.create" tabindex="-1"><code dir="ltr" translate="no">netapp.  activeDirectories.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.activeDirectories.delete" class="permission-name add-link" data-text="netapp.activeDirectories.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.  activeDirectories.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.activeDirectories.get" class="permission-name add-link" data-text="netapp.activeDirectories.get" tabindex="-1"><code dir="ltr" translate="no">netapp.activeDirectories.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.activeDirectories.list" class="permission-name add-link" data-text="netapp.activeDirectories.list" tabindex="-1"><code dir="ltr" translate="no">netapp.activeDirectories.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.activeDirectories.update" class="permission-name add-link" data-text="netapp.activeDirectories.update" tabindex="-1"><code dir="ltr" translate="no">netapp.  activeDirectories.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backupPolicies.create" class="permission-name add-link" data-text="netapp.backupPolicies.create" tabindex="-1"><code dir="ltr" translate="no">netapp.backupPolicies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backupPolicies.delete" class="permission-name add-link" data-text="netapp.backupPolicies.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.backupPolicies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backupPolicies.get" class="permission-name add-link" data-text="netapp.backupPolicies.get" tabindex="-1"><code dir="ltr" translate="no">netapp.backupPolicies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backupPolicies.list" class="permission-name add-link" data-text="netapp.backupPolicies.list" tabindex="-1"><code dir="ltr" translate="no">netapp.backupPolicies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backupPolicies.update" class="permission-name add-link" data-text="netapp.backupPolicies.update" tabindex="-1"><code dir="ltr" translate="no">netapp.backupPolicies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backupVaults.create" class="permission-name add-link" data-text="netapp.backupVaults.create" tabindex="-1"><code dir="ltr" translate="no">netapp.backupVaults.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backupVaults.delete" class="permission-name add-link" data-text="netapp.backupVaults.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.backupVaults.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backupVaults.get" class="permission-name add-link" data-text="netapp.backupVaults.get" tabindex="-1"><code dir="ltr" translate="no">netapp.backupVaults.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backupVaults.list" class="permission-name add-link" data-text="netapp.backupVaults.list" tabindex="-1"><code dir="ltr" translate="no">netapp.backupVaults.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backupVaults.update" class="permission-name add-link" data-text="netapp.backupVaults.update" tabindex="-1"><code dir="ltr" translate="no">netapp.backupVaults.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backups.create" class="permission-name add-link" data-text="netapp.backups.create" tabindex="-1"><code dir="ltr" translate="no">netapp.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backups.delete" class="permission-name add-link" data-text="netapp.backups.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backups.get" class="permission-name add-link" data-text="netapp.backups.get" tabindex="-1"><code dir="ltr" translate="no">netapp.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.backups.list" class="permission-name add-link" data-text="netapp.backups.list" tabindex="-1"><code dir="ltr" translate="no">netapp.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.backups.update" class="permission-name add-link" data-text="netapp.backups.update" tabindex="-1"><code dir="ltr" translate="no">netapp.backups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.hostGroups.create" class="permission-name add-link" data-text="netapp.hostGroups.create" tabindex="-1"><code dir="ltr" translate="no">netapp.hostGroups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.hostGroups.delete" class="permission-name add-link" data-text="netapp.hostGroups.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.hostGroups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.hostGroups.get" class="permission-name add-link" data-text="netapp.hostGroups.get" tabindex="-1"><code dir="ltr" translate="no">netapp.hostGroups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.hostGroups.list" class="permission-name add-link" data-text="netapp.hostGroups.list" tabindex="-1"><code dir="ltr" translate="no">netapp.hostGroups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.hostGroups.update" class="permission-name add-link" data-text="netapp.hostGroups.update" tabindex="-1"><code dir="ltr" translate="no">netapp.hostGroups.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.kmsConfigs.create" class="permission-name add-link" data-text="netapp.kmsConfigs.create" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.kmsConfigs.delete" class="permission-name add-link" data-text="netapp.kmsConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.kmsConfigs.encrypt" class="permission-name add-link" data-text="netapp.kmsConfigs.encrypt" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.encrypt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.kmsConfigs.get" class="permission-name add-link" data-text="netapp.kmsConfigs.get" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.kmsConfigs.list" class="permission-name add-link" data-text="netapp.kmsConfigs.list" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.kmsConfigs.update" class="permission-name add-link" data-text="netapp.kmsConfigs.update" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.kmsConfigs.verify" class="permission-name add-link" data-text="netapp.kmsConfigs.verify" tabindex="-1"><code dir="ltr" translate="no">netapp.kmsConfigs.verify</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.locations.get" class="permission-name add-link" data-text="netapp.locations.get" tabindex="-1"><code dir="ltr" translate="no">netapp.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.locations.list" class="permission-name add-link" data-text="netapp.locations.list" tabindex="-1"><code dir="ltr" translate="no">netapp.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.ontap.delete" class="permission-name add-link" data-text="netapp.ontap.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.ontap.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.ontap.patch" class="permission-name add-link" data-text="netapp.ontap.patch" tabindex="-1"><code dir="ltr" translate="no">netapp.ontap.patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.ontap.post" class="permission-name add-link" data-text="netapp.ontap.post" tabindex="-1"><code dir="ltr" translate="no">netapp.ontap.post</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.operations.cancel" class="permission-name add-link" data-text="netapp.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">netapp.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.operations.delete" class="permission-name add-link" data-text="netapp.operations.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.operations.get" class="permission-name add-link" data-text="netapp.operations.get" tabindex="-1"><code dir="ltr" translate="no">netapp.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.dataExporter">Google Cloud NetApp Volumes Data Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.dataExporter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.operations.list" class="permission-name add-link" data-text="netapp.operations.list" tabindex="-1"><code dir="ltr" translate="no">netapp.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.quotaRules.create" class="permission-name add-link" data-text="netapp.quotaRules.create" tabindex="-1"><code dir="ltr" translate="no">netapp.quotaRules.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.quotaRules.delete" class="permission-name add-link" data-text="netapp.quotaRules.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.quotaRules.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.quotaRules.get" class="permission-name add-link" data-text="netapp.quotaRules.get" tabindex="-1"><code dir="ltr" translate="no">netapp.quotaRules.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.quotaRules.list" class="permission-name add-link" data-text="netapp.quotaRules.list" tabindex="-1"><code dir="ltr" translate="no">netapp.quotaRules.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.quotaRules.update" class="permission-name add-link" data-text="netapp.quotaRules.update" tabindex="-1"><code dir="ltr" translate="no">netapp.quotaRules.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.replications.create" class="permission-name add-link" data-text="netapp.replications.create" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.replications.delete" class="permission-name add-link" data-text="netapp.replications.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.replications.establishPeering" class="permission-name add-link" data-text="netapp.replications.establishPeering" tabindex="-1"><code dir="ltr" translate="no">netapp.  replications.  establishPeering</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.replications.get" class="permission-name add-link" data-text="netapp.replications.get" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.replications.list" class="permission-name add-link" data-text="netapp.replications.list" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.replications.resume" class="permission-name add-link" data-text="netapp.replications.resume" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.replications.reverse" class="permission-name add-link" data-text="netapp.replications.reverse" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.reverse</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.replications.stop" class="permission-name add-link" data-text="netapp.replications.stop" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.stop</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.replications.sync" class="permission-name add-link" data-text="netapp.replications.sync" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.sync</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.replications.update" class="permission-name add-link" data-text="netapp.replications.update" tabindex="-1"><code dir="ltr" translate="no">netapp.replications.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.snapshots.create" class="permission-name add-link" data-text="netapp.snapshots.create" tabindex="-1"><code dir="ltr" translate="no">netapp.snapshots.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.snapshots.delete" class="permission-name add-link" data-text="netapp.snapshots.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.snapshots.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.snapshots.get" class="permission-name add-link" data-text="netapp.snapshots.get" tabindex="-1"><code dir="ltr" translate="no">netapp.snapshots.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.snapshots.list" class="permission-name add-link" data-text="netapp.snapshots.list" tabindex="-1"><code dir="ltr" translate="no">netapp.snapshots.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.snapshots.update" class="permission-name add-link" data-text="netapp.snapshots.update" tabindex="-1"><code dir="ltr" translate="no">netapp.snapshots.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.storagePools.create" class="permission-name add-link" data-text="netapp.storagePools.create" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.storagePools.delete" class="permission-name add-link" data-text="netapp.storagePools.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.storagePools.get" class="permission-name add-link" data-text="netapp.storagePools.get" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.storagePools.list" class="permission-name add-link" data-text="netapp.storagePools.list" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.storagePools.switch" class="permission-name add-link" data-text="netapp.storagePools.switch" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.switch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.storagePools.update" class="permission-name add-link" data-text="netapp.storagePools.update" tabindex="-1"><code dir="ltr" translate="no">netapp.storagePools.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.storagePools.validateDirectoryService" class="permission-name add-link" data-text="netapp.storagePools.validateDirectoryService" tabindex="-1"><code dir="ltr" translate="no">netapp.  storagePools.  validateDirectoryService</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.volumes.create" class="permission-name add-link" data-text="netapp.volumes.create" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.volumes.delete" class="permission-name add-link" data-text="netapp.volumes.delete" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.volumes.export" class="permission-name add-link" data-text="netapp.volumes.export" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.dataExporter">Google Cloud NetApp Volumes Data Exporter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.dataExporter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.volumes.findValidCRRRegions" class="permission-name add-link" data-text="netapp.volumes.findValidCRRRegions" tabindex="-1"><code dir="ltr" translate="no">netapp.  volumes.  findValidCRRRegions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.volumes.get" class="permission-name add-link" data-text="netapp.volumes.get" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/backupdr#backupdr.serviceAgent">Backup and DR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  backupdr.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="netapp.volumes.list" class="permission-name add-link" data-text="netapp.volumes.list" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.viewer">Google Cloud NetApp Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.volumes.restore" class="permission-name add-link" data-text="netapp.volumes.restore" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.restore</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="netapp.volumes.revert" class="permission-name add-link" data-text="netapp.volumes.revert" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.revert</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="netapp.volumes.update" class="permission-name add-link" data-text="netapp.volumes.update" tabindex="-1"><code dir="ltr" translate="no">netapp.volumes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netapp#netapp.admin">Google Cloud NetApp Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netapp.admin</code> )</p></td>
</tr>
</tbody>
</table>
