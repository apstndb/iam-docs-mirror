---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloud
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloud
title: Google Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud roles

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
<td><h4 id="cloud.admin" class="role-title add-link" data-text="Cloud Admin Beta" tabindex="-1">Cloud Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloud.admin</code> )</p>
<p>Admin role for cloud</p></td>
<td><p><code dir="ltr" translate="no">cloud.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloud.locations.get</code></li>
<li><code dir="ltr" translate="no">cloud.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloud.viewer" class="role-title add-link" data-text="Cloud Viewer Beta" tabindex="-1">Cloud Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloud.viewer</code> )</p>
<p>Viewer role for cloud</p></td>
<td><p><code dir="ltr" translate="no">cloud.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloud.locations.get</code></li>
<li><code dir="ltr" translate="no">cloud.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloud.locationReader" class="role-title add-link" data-text="Location reader Beta" tabindex="-1">Location reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloud.locationReader</code> )</p>
<p>Read and enumerate locations available for resource creation.</p></td>
<td><p><code dir="ltr" translate="no">cloud.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloud.locations.get</code></li>
<li><code dir="ltr" translate="no">cloud.locations.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Cloud permissions

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
<td><h4 id="cloud.locations.get" class="permission-name add-link" data-text="cloud.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloud.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.locationReader">Location reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.locationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloud.locations.list" class="permission-name add-link" data-text="cloud.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloud.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin">Cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer">Cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.locationReader">Location reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloud.locationReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
