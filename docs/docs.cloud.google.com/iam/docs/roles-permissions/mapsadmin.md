---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin
title: Maps Admin roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Maps Admin. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Maps Admin roles

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
<td><h4 id="mapsadmin.admin" class="role-title add-link" data-text="Maps API Admin" tabindex="-1">Maps API Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p>Read and Write all Maps Management and Maps Styles Resources.</p></td>
<td><p><code dir="ltr" translate="no">mapsadmin.*</code></p>
<ul>
<li><code dir="ltr" translate="no">mapsadmin.clientMaps.create</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientMaps.delete</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientMaps.get</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientMaps.list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientMaps.update</code></li>
<li><code dir="ltr" translate="no">mapsadmin.  clientStyleActivationRules.  update</code></li>
<li><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.create</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.delete</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.get</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.clientStyles.update</code></li>
<li><code dir="ltr" translate="no">mapsadmin.mapViews.create</code></li>
<li><code dir="ltr" translate="no">mapsadmin.mapViews.delete</code></li>
<li><code dir="ltr" translate="no">mapsadmin.mapViews.get</code></li>
<li><code dir="ltr" translate="no">mapsadmin.mapViews.list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.mapViews.update</code></li>
<li><code dir="ltr" translate="no">mapsadmin.  styleEditorConfigs.  get</code></li>
<li><code dir="ltr" translate="no">mapsadmin.styleSnapshots.list</code></li>
<li><code dir="ltr" translate="no">mapsadmin.  styleSnapshots.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.viewer" class="role-title add-link" data-text="Maps API Viewer" tabindex="-1">Maps API Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p>Read all Maps Management and Maps Styles Resources.</p></td>
<td><p><code dir="ltr" translate="no">mapsadmin.clientMaps.get</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientMaps.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientStyles.get</code></p>
<p><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.mapViews.get</code></p>
<p><code dir="ltr" translate="no">mapsadmin.mapViews.list</code></p>
<p><code dir="ltr" translate="no">mapsadmin.  styleEditorConfigs.  get</code></p>
<p><code dir="ltr" translate="no">mapsadmin.styleSnapshots.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Maps Admin permissions

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
<td><h4 id="mapsadmin.clientMaps.create" class="permission-name add-link" data-text="mapsadmin.clientMaps.create" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientMaps.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientMaps.delete" class="permission-name add-link" data-text="mapsadmin.clientMaps.delete" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientMaps.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientMaps.get" class="permission-name add-link" data-text="mapsadmin.clientMaps.get" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientMaps.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientMaps.list" class="permission-name add-link" data-text="mapsadmin.clientMaps.list" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientMaps.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientMaps.update" class="permission-name add-link" data-text="mapsadmin.clientMaps.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientMaps.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientStyleActivationRules.update" class="permission-name add-link" data-text="mapsadmin.clientStyleActivationRules.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.  clientStyleActivationRules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientStyleSheetSnapshots.list" class="permission-name add-link" data-text="mapsadmin.clientStyleSheetSnapshots.list" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientStyleSheetSnapshots.update" class="permission-name add-link" data-text="mapsadmin.clientStyleSheetSnapshots.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.  clientStyleSheetSnapshots.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientStyles.create" class="permission-name add-link" data-text="mapsadmin.clientStyles.create" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientStyles.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientStyles.delete" class="permission-name add-link" data-text="mapsadmin.clientStyles.delete" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientStyles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientStyles.get" class="permission-name add-link" data-text="mapsadmin.clientStyles.get" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientStyles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.clientStyles.list" class="permission-name add-link" data-text="mapsadmin.clientStyles.list" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientStyles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.viewer">Maps Platform Datasets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.clientStyles.update" class="permission-name add-link" data-text="mapsadmin.clientStyles.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.clientStyles.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsplatformdatasets#mapsplatformdatasets.admin">Maps Platform Datasets Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsplatformdatasets.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.mapViews.create" class="permission-name add-link" data-text="mapsadmin.mapViews.create" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.mapViews.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.mapViews.delete" class="permission-name add-link" data-text="mapsadmin.mapViews.delete" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.mapViews.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.mapViews.get" class="permission-name add-link" data-text="mapsadmin.mapViews.get" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.mapViews.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.mapViews.list" class="permission-name add-link" data-text="mapsadmin.mapViews.list" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.mapViews.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.mapViews.update" class="permission-name add-link" data-text="mapsadmin.mapViews.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.mapViews.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.styleEditorConfigs.get" class="permission-name add-link" data-text="mapsadmin.styleEditorConfigs.get" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.  styleEditorConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsadmin.styleSnapshots.list" class="permission-name add-link" data-text="mapsadmin.styleSnapshots.list" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.styleSnapshots.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.viewer">Maps API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsadmin.styleSnapshots.update" class="permission-name add-link" data-text="mapsadmin.styleSnapshots.update" tabindex="-1"><code dir="ltr" translate="no">mapsadmin.  styleSnapshots.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsadmin#mapsadmin.admin">Maps API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsadmin.admin</code> )</p></td>
</tr>
</tbody>
</table>
