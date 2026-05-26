---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/memcache
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/memcache
title: Memorystore for Memcached roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Memorystore for Memcached. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Memorystore for Memcached roles

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
<td><h4 id="memcache.admin" class="role-title add-link" data-text="Cloud Memorystore Memcached Admin" tabindex="-1">Cloud Memorystore Memcached Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p>Full access to Memcached instances and related resources.</p></td>
<td><p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">memcache.*</code></p>
<ul>
<li><code dir="ltr" translate="no">memcache.  instances.  applyParameters</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  applySoftwareUpdate</code></li>
<li><code dir="ltr" translate="no">memcache.instances.create</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">memcache.instances.delete</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">memcache.instances.get</code></li>
<li><code dir="ltr" translate="no">memcache.instances.list</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  rescheduleMaintenance</code></li>
<li><code dir="ltr" translate="no">memcache.instances.update</code></li>
<li><code dir="ltr" translate="no">memcache.  instances.  updateParameters</code></li>
<li><code dir="ltr" translate="no">memcache.instances.upgrade</code></li>
<li><code dir="ltr" translate="no">memcache.locations.get</code></li>
<li><code dir="ltr" translate="no">memcache.locations.list</code></li>
<li><code dir="ltr" translate="no">memcache.operations.cancel</code></li>
<li><code dir="ltr" translate="no">memcache.operations.delete</code></li>
<li><code dir="ltr" translate="no">memcache.operations.get</code></li>
<li><code dir="ltr" translate="no">memcache.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.editor" class="role-title add-link" data-text="Cloud Memorystore Memcached Editor" tabindex="-1">Cloud Memorystore Memcached Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p>Read-Write access to Memcached instances and related resources.</p></td>
<td><p><code dir="ltr" translate="no">memcache.  instances.  applyParameters</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.instances.get</code></p>
<p><code dir="ltr" translate="no">memcache.instances.list</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">memcache.instances.update</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  updateParameters</code></p>
<p><code dir="ltr" translate="no">memcache.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">memcache.locations.get</code></li>
<li><code dir="ltr" translate="no">memcache.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">memcache.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">memcache.operations.cancel</code></li>
<li><code dir="ltr" translate="no">memcache.operations.delete</code></li>
<li><code dir="ltr" translate="no">memcache.operations.get</code></li>
<li><code dir="ltr" translate="no">memcache.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.viewer" class="role-title add-link" data-text="Cloud Memorystore Memcached Viewer" tabindex="-1">Cloud Memorystore Memcached Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p>Read-only access to Memcached instances and related resources.</p></td>
<td><p><code dir="ltr" translate="no">memcache.instances.get</code></p>
<p><code dir="ltr" translate="no">memcache.instances.list</code></p>
<p><code dir="ltr" translate="no">memcache.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">memcache.locations.get</code></li>
<li><code dir="ltr" translate="no">memcache.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">memcache.operations.get</code></p>
<p><code dir="ltr" translate="no">memcache.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="memcache.serviceAgent" class="role-title add-link" data-text="Cloud Memorystore Memcached Service Agent" tabindex="-1">Cloud Memorystore Memcached Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  memcache.serviceAgent</code> )</p>
<p>Gives Cloud Memorystore Memcached service account access to managed resource</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Memorystore for Memcached permissions

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
<td><h4 id="memcache.instances.applyParameters" class="permission-name add-link" data-text="memcache.instances.applyParameters" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  applyParameters</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.applySoftwareUpdate" class="permission-name add-link" data-text="memcache.instances.applySoftwareUpdate" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  applySoftwareUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.create" class="permission-name add-link" data-text="memcache.instances.create" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.createTagBinding" class="permission-name add-link" data-text="memcache.instances.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.delete" class="permission-name add-link" data-text="memcache.instances.delete" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.deleteTagBinding" class="permission-name add-link" data-text="memcache.instances.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.get" class="permission-name add-link" data-text="memcache.instances.get" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.list" class="permission-name add-link" data-text="memcache.instances.list" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.listEffectiveTags" class="permission-name add-link" data-text="memcache.instances.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.listTagBindings" class="permission-name add-link" data-text="memcache.instances.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.rescheduleMaintenance" class="permission-name add-link" data-text="memcache.instances.rescheduleMaintenance" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  rescheduleMaintenance</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.update" class="permission-name add-link" data-text="memcache.instances.update" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.instances.updateParameters" class="permission-name add-link" data-text="memcache.instances.updateParameters" tabindex="-1"><code dir="ltr" translate="no">memcache.  instances.  updateParameters</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.instances.upgrade" class="permission-name add-link" data-text="memcache.instances.upgrade" tabindex="-1"><code dir="ltr" translate="no">memcache.instances.upgrade</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.locations.get" class="permission-name add-link" data-text="memcache.locations.get" tabindex="-1"><code dir="ltr" translate="no">memcache.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.locations.list" class="permission-name add-link" data-text="memcache.locations.list" tabindex="-1"><code dir="ltr" translate="no">memcache.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.operations.cancel" class="permission-name add-link" data-text="memcache.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">memcache.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.operations.delete" class="permission-name add-link" data-text="memcache.operations.delete" tabindex="-1"><code dir="ltr" translate="no">memcache.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="memcache.operations.get" class="permission-name add-link" data-text="memcache.operations.get" tabindex="-1"><code dir="ltr" translate="no">memcache.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="memcache.operations.list" class="permission-name add-link" data-text="memcache.operations.list" tabindex="-1"><code dir="ltr" translate="no">memcache.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.admin">Cloud Memorystore Memcached Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.editor">Cloud Memorystore Memcached Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.viewer">Cloud Memorystore Memcached Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  memcache.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
