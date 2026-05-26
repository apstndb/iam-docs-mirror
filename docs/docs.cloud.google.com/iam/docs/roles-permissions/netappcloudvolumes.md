---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes
title: NetApp Cloud Volumes Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for NetApp Cloud Volumes Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## NetApp Cloud Volumes Service roles

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
<td><h4 id="netappcloudvolumes.admin" class="role-title add-link" data-text="NetApp Cloud Volumes Admin Beta" tabindex="-1">NetApp Cloud Volumes Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p>This role is managed by NetApp, not Google.</p></td>
<td><p><code dir="ltr" translate="no">cloudvolumesgcp-api.  netapp.com/*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  create</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  delete</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  update</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/ipRanges.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/regions.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/serviceLevels.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  create</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  delete</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  update</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  authorize</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  break</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  create</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  delete</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  release</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  resync</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  update</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  create</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  delete</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  list</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="netappcloudvolumes.viewer" class="role-title add-link" data-text="NetApp Cloud Volumes Viewer Beta" tabindex="-1">NetApp Cloud Volumes Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p>This role is managed by NetApp, not Google.</p></td>
<td><p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  get</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/ipRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  get</code></li>
<li><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/regions.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/serviceLevels.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  get</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  list</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  get</code></p>
<p><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## NetApp Cloud Volumes Service permissions

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
<td><h4 id="cloudvolumesgcp_api.netapp.com_activeDirectories.create" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/activeDirectories.create" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_activeDirectories.delete" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/activeDirectories.delete" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_activeDirectories.get" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/activeDirectories.get" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_activeDirectories.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/activeDirectories.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_activeDirectories.update" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/activeDirectories.update" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/activeDirectories.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_ipRanges.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/ipRanges.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/ipRanges.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_jobs.get" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/jobs.get" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_jobs.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/jobs.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/jobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_regions.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/regions.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/regions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_serviceLevels.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/serviceLevels.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/serviceLevels.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_snapshots.create" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/snapshots.create" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_snapshots.delete" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/snapshots.delete" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_snapshots.get" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/snapshots.get" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_snapshots.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/snapshots.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_snapshots.update" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/snapshots.update" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/snapshots.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.authorize" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.authorize" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  authorize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.break" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.break" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  break</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.create" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.create" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.delete" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.delete" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.get" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.get" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.release" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.release" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  release</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.resync" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.resync" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  resync</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumereplication.update" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumereplication.update" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumereplication.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumes.create" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumes.create" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumes.delete" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumes.delete" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumes.get" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumes.get" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumes.list" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumes.list" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.viewer">NetApp Cloud Volumes Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudvolumesgcp_api.netapp.com_volumes.update" class="permission-name add-link" data-text="cloudvolumesgcp-api.netapp.com/volumes.update" tabindex="-1"><code dir="ltr" translate="no">cloudvolumesgcp-api.netapp.  com/volumes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/netappcloudvolumes#netappcloudvolumes.admin">NetApp Cloud Volumes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  netappcloudvolumes.admin</code> )</p></td>
</tr>
</tbody>
</table>
