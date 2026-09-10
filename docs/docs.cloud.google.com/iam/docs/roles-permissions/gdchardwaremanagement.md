---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement
title: GDC Hardware Management API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for GDC Hardware Management API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## GDC Hardware Management API roles

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
<td><h4 id="gdchardwaremanagement.admin" class="role-title add-link" data-text="GDC Hardware Management Admin Beta" tabindex="-1">GDC Hardware Management Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p>Full access to GDC Hardware Management resources.</p></td>
<td><p><code dir="ltr" translate="no">gdchardwaremanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  update</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  update</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  submit</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  update</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  update</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.skus.get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.viewer" class="role-title add-link" data-text="Gdchardwaremanagement Viewer Beta" tabindex="-1">Gdchardwaremanagement Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p>Viewer role for gdchardwaremanagement</p></td>
<td><p><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.skus.get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.operator" class="role-title add-link" data-text="GDC Hardware Management Operator Beta" tabindex="-1">GDC Hardware Management Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p>Create, read, and update access to GDC Hardware Management resources that support those operations. Also grants delete access to HardwareGroup resource.</p></td>
<td><p><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  create</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  update</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  create</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  update</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.skus.get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  create</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  delete</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.reader" class="role-title add-link" data-text="GDC Hardware Management Reader Beta" tabindex="-1">GDC Hardware Management Reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p>Readonly access to GDC Hardware Management resources.</p></td>
<td><p><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.skus.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gdchardwaremanagement.skus.get</code></li>
<li><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  get</code></p>
<p><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## GDC Hardware Management API permissions

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
<td><h4 id="gdchardwaremanagement.changeLogEntries.get" class="permission-name add-link" data-text="gdchardwaremanagement.changeLogEntries.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.changeLogEntries.list" class="permission-name add-link" data-text="gdchardwaremanagement.changeLogEntries.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  changeLogEntries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.comments.create" class="permission-name add-link" data-text="gdchardwaremanagement.comments.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.comments.get" class="permission-name add-link" data-text="gdchardwaremanagement.comments.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.comments.list" class="permission-name add-link" data-text="gdchardwaremanagement.comments.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  comments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.hardware.create" class="permission-name add-link" data-text="gdchardwaremanagement.hardware.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.hardware.delete" class="permission-name add-link" data-text="gdchardwaremanagement.hardware.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.hardware.get" class="permission-name add-link" data-text="gdchardwaremanagement.hardware.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.hardware.list" class="permission-name add-link" data-text="gdchardwaremanagement.hardware.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.hardware.update" class="permission-name add-link" data-text="gdchardwaremanagement.hardware.update" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardware.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.hardwareGroups.create" class="permission-name add-link" data-text="gdchardwaremanagement.hardwareGroups.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.hardwareGroups.delete" class="permission-name add-link" data-text="gdchardwaremanagement.hardwareGroups.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.hardwareGroups.get" class="permission-name add-link" data-text="gdchardwaremanagement.hardwareGroups.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.hardwareGroups.list" class="permission-name add-link" data-text="gdchardwaremanagement.hardwareGroups.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.hardwareGroups.update" class="permission-name add-link" data-text="gdchardwaremanagement.hardwareGroups.update" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  hardwareGroups.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.locations.get" class="permission-name add-link" data-text="gdchardwaremanagement.locations.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.locations.list" class="permission-name add-link" data-text="gdchardwaremanagement.locations.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.operations.cancel" class="permission-name add-link" data-text="gdchardwaremanagement.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.operations.delete" class="permission-name add-link" data-text="gdchardwaremanagement.operations.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.operations.get" class="permission-name add-link" data-text="gdchardwaremanagement.operations.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.operations.list" class="permission-name add-link" data-text="gdchardwaremanagement.operations.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.orders.create" class="permission-name add-link" data-text="gdchardwaremanagement.orders.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.orders.delete" class="permission-name add-link" data-text="gdchardwaremanagement.orders.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.orders.get" class="permission-name add-link" data-text="gdchardwaremanagement.orders.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.orders.list" class="permission-name add-link" data-text="gdchardwaremanagement.orders.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.orders.submit" class="permission-name add-link" data-text="gdchardwaremanagement.orders.submit" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  submit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.orders.update" class="permission-name add-link" data-text="gdchardwaremanagement.orders.update" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  orders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.sites.create" class="permission-name add-link" data-text="gdchardwaremanagement.sites.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.sites.delete" class="permission-name add-link" data-text="gdchardwaremanagement.sites.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.sites.get" class="permission-name add-link" data-text="gdchardwaremanagement.sites.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.sites.list" class="permission-name add-link" data-text="gdchardwaremanagement.sites.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.sites.update" class="permission-name add-link" data-text="gdchardwaremanagement.sites.update" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  sites.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.skus.get" class="permission-name add-link" data-text="gdchardwaremanagement.skus.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.skus.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.skus.list" class="permission-name add-link" data-text="gdchardwaremanagement.skus.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  skus.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.zones.create" class="permission-name add-link" data-text="gdchardwaremanagement.zones.create" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.zones.delete" class="permission-name add-link" data-text="gdchardwaremanagement.zones.delete" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.zones.get" class="permission-name add-link" data-text="gdchardwaremanagement.zones.get" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gdchardwaremanagement.zones.list" class="permission-name add-link" data-text="gdchardwaremanagement.zones.list" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.viewer">Gdchardwaremanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.reader">GDC Hardware Management Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gdchardwaremanagement.zones.update" class="permission-name add-link" data-text="gdchardwaremanagement.zones.update" tabindex="-1"><code dir="ltr" translate="no">gdchardwaremanagement.  zones.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.admin">GDC Hardware Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gdchardwaremanagement#gdchardwaremanagement.operator">GDC Hardware Management Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gdchardwaremanagement.operator</code> )</p></td>
</tr>
</tbody>
</table>
