---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/earthengine
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine
title: Google Earth Engine roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Earth Engine. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Earth Engine roles

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
<td><h4 id="earthengine.admin" class="role-title add-link" data-text="Earth Engine Resource Admin Beta" tabindex="-1">Earth Engine Resource Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p>Full access to all Earth Engine resource features</p></td>
<td><p><code dir="ltr" translate="no">earthengine.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.assets.create</code></li>
<li><code dir="ltr" translate="no">earthengine.assets.delete</code></li>
<li><code dir="ltr" translate="no">earthengine.assets.get</code></li>
<li><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">earthengine.assets.list</code></li>
<li><code dir="ltr" translate="no">earthengine.  assets.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">earthengine.assets.update</code></li>
<li><code dir="ltr" translate="no">earthengine.  computations.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.config.get</code></li>
<li><code dir="ltr" translate="no">earthengine.config.update</code></li>
<li><code dir="ltr" translate="no">earthengine.exports.create</code></li>
<li><code dir="ltr" translate="no">earthengine.  featureviews.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  get</code></li>
<li><code dir="ltr" translate="no">earthengine.imports.create</code></li>
<li><code dir="ltr" translate="no">earthengine.maps.create</code></li>
<li><code dir="ltr" translate="no">earthengine.maps.get</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.delete</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.get</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.list</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.update</code></li>
<li><code dir="ltr" translate="no">earthengine.tables.create</code></li>
<li><code dir="ltr" translate="no">earthengine.tables.get</code></li>
<li><code dir="ltr" translate="no">earthengine.thumbnails.create</code></li>
<li><code dir="ltr" translate="no">earthengine.thumbnails.get</code></li>
<li><code dir="ltr" translate="no">earthengine.  videothumbnails.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.  videothumbnails.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.viewer" class="role-title add-link" data-text="Earth Engine Resource Viewer Beta" tabindex="-1">Earth Engine Resource Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p>Viewer of all Earth Engine resources</p></td>
<td><p><code dir="ltr" translate="no">earthengine.assets.get</code></p>
<p><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.list</code></p>
<p><code dir="ltr" translate="no">earthengine.  computations.  create</code></p>
<p><code dir="ltr" translate="no">earthengine.config.get</code></p>
<p><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  get</code></p>
<p><code dir="ltr" translate="no">earthengine.maps.get</code></p>
<p><code dir="ltr" translate="no">earthengine.operations.get</code></p>
<p><code dir="ltr" translate="no">earthengine.operations.list</code></p>
<p><code dir="ltr" translate="no">earthengine.tables.get</code></p>
<p><code dir="ltr" translate="no">earthengine.thumbnails.get</code></p>
<p><code dir="ltr" translate="no">earthengine.  videothumbnails.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.appsPublisher" class="role-title add-link" data-text="Earth Engine Apps Publisher Beta" tabindex="-1">Earth Engine Apps Publisher <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  earthengine.appsPublisher</code> )</p>
<p>Publisher of Earth Engine Apps</p></td>
<td><p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.disable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.enable</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.writer" class="role-title add-link" data-text="Earth Engine Resource Writer Beta" tabindex="-1">Earth Engine Resource Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p>Writer of all Earth Engine resources</p></td>
<td><p><code dir="ltr" translate="no">earthengine.assets.create</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.delete</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.get</code></p>
<p><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.list</code></p>
<p><code dir="ltr" translate="no">earthengine.assets.update</code></p>
<p><code dir="ltr" translate="no">earthengine.  computations.  create</code></p>
<p><code dir="ltr" translate="no">earthengine.config.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.config.get</code></li>
<li><code dir="ltr" translate="no">earthengine.config.update</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.exports.create</code></p>
<p><code dir="ltr" translate="no">earthengine.  featureviews.  create</code></p>
<p><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.imports.create</code></p>
<p><code dir="ltr" translate="no">earthengine.maps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.maps.create</code></li>
<li><code dir="ltr" translate="no">earthengine.maps.get</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.operations.delete</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.get</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.list</code></li>
<li><code dir="ltr" translate="no">earthengine.operations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.tables.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.tables.create</code></li>
<li><code dir="ltr" translate="no">earthengine.tables.get</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.thumbnails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.thumbnails.create</code></li>
<li><code dir="ltr" translate="no">earthengine.thumbnails.get</code></li>
</ul>
<p><code dir="ltr" translate="no">earthengine.videothumbnails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">earthengine.  videothumbnails.  create</code></li>
<li><code dir="ltr" translate="no">earthengine.  videothumbnails.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Google Earth Engine permissions

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
<td><h4 id="earthengine.assets.create" class="permission-name add-link" data-text="earthengine.assets.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.assets.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.assets.delete" class="permission-name add-link" data-text="earthengine.assets.delete" tabindex="-1"><code dir="ltr" translate="no">earthengine.assets.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.assets.get" class="permission-name add-link" data-text="earthengine.assets.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.assets.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.assets.getIamPolicy" class="permission-name add-link" data-text="earthengine.assets.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">earthengine.  assets.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.assets.list" class="permission-name add-link" data-text="earthengine.assets.list" tabindex="-1"><code dir="ltr" translate="no">earthengine.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.assets.setIamPolicy" class="permission-name add-link" data-text="earthengine.assets.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">earthengine.  assets.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.assets.update" class="permission-name add-link" data-text="earthengine.assets.update" tabindex="-1"><code dir="ltr" translate="no">earthengine.assets.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.computations.create" class="permission-name add-link" data-text="earthengine.computations.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.  computations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.config.get" class="permission-name add-link" data-text="earthengine.config.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.config.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.config.update" class="permission-name add-link" data-text="earthengine.config.update" tabindex="-1"><code dir="ltr" translate="no">earthengine.config.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.exports.create" class="permission-name add-link" data-text="earthengine.exports.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.exports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.featureviews.create" class="permission-name add-link" data-text="earthengine.featureviews.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.  featureviews.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.filmstripthumbnails.create" class="permission-name add-link" data-text="earthengine.filmstripthumbnails.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.filmstripthumbnails.get" class="permission-name add-link" data-text="earthengine.filmstripthumbnails.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.  filmstripthumbnails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.imports.create" class="permission-name add-link" data-text="earthengine.imports.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.imports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.maps.create" class="permission-name add-link" data-text="earthengine.maps.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.maps.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.maps.get" class="permission-name add-link" data-text="earthengine.maps.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.maps.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.operations.delete" class="permission-name add-link" data-text="earthengine.operations.delete" tabindex="-1"><code dir="ltr" translate="no">earthengine.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.operations.get" class="permission-name add-link" data-text="earthengine.operations.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.operations.list" class="permission-name add-link" data-text="earthengine.operations.list" tabindex="-1"><code dir="ltr" translate="no">earthengine.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.operations.update" class="permission-name add-link" data-text="earthengine.operations.update" tabindex="-1"><code dir="ltr" translate="no">earthengine.operations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.tables.create" class="permission-name add-link" data-text="earthengine.tables.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.tables.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.tables.get" class="permission-name add-link" data-text="earthengine.tables.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.tables.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.thumbnails.create" class="permission-name add-link" data-text="earthengine.thumbnails.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.thumbnails.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.thumbnails.get" class="permission-name add-link" data-text="earthengine.thumbnails.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.thumbnails.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="earthengine.videothumbnails.create" class="permission-name add-link" data-text="earthengine.videothumbnails.create" tabindex="-1"><code dir="ltr" translate="no">earthengine.  videothumbnails.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="earthengine.videothumbnails.get" class="permission-name add-link" data-text="earthengine.videothumbnails.get" tabindex="-1"><code dir="ltr" translate="no">earthengine.  videothumbnails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.admin">Earth Engine Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.viewer">Earth Engine Resource Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/earthengine#earthengine.writer">Earth Engine Resource Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  earthengine.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
