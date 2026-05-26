---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder
title: Cloud Location Finder roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Location Finder. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Location Finder roles

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
<td><h4 id="cloudlocationfinder.admin" class="role-title add-link" data-text="Cloud Location Finder Admin Beta" tabindex="-1">Cloud Location Finder Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p>Full access to Cloud Location Finder resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudlocationfinder.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  create</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  get</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  list</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  search</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  update</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  locations.  get</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudlocationfinder.viewer" class="role-title add-link" data-text="Cloud Location Finder Viewer Beta" tabindex="-1">Cloud Location Finder Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p>Readonly access to Cloud Location Finder resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  get</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  list</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  search</code></p>
<p><code dir="ltr" translate="no">cloudlocationfinder.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudlocationfinder.  locations.  get</code></li>
<li><code dir="ltr" translate="no">cloudlocationfinder.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Location Finder permissions

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
<td><h4 id="cloudlocationfinder.cloudLocations.create" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.create" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudlocationfinder.cloudLocations.delete" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.delete" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudlocationfinder.cloudLocations.get" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.get" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudlocationfinder.cloudLocations.list" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.list" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudlocationfinder.cloudLocations.search" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.search" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudlocationfinder.cloudLocations.update" class="permission-name add-link" data-text="cloudlocationfinder.cloudLocations.update" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  cloudLocations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudlocationfinder.locations.get" class="permission-name add-link" data-text="cloudlocationfinder.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudlocationfinder.locations.list" class="permission-name add-link" data-text="cloudlocationfinder.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudlocationfinder.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.admin">Cloud Location Finder Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudlocationfinder#cloudlocationfinder.viewer">Cloud Location Finder Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudlocationfinder.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
