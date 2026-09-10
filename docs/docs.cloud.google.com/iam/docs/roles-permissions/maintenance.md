---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/maintenance
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance
title: Maintenance API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Maintenance API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Maintenance API roles

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
<td><h4 id="maintenance.admin" class="role-title add-link" data-text="Maintenance Admin" tabindex="-1">Maintenance Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p>Admin role for maintenance</p></td>
<td><p><code dir="ltr" translate="no">maintenance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">maintenance.locations.get</code></li>
<li><code dir="ltr" translate="no">maintenance.locations.list</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  get</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="maintenance.viewer" class="role-title add-link" data-text="Maintenance API Viewer" tabindex="-1">Maintenance API Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p>Readonly access to Maintenance API resources.</p></td>
<td><p><code dir="ltr" translate="no">maintenance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">maintenance.locations.get</code></li>
<li><code dir="ltr" translate="no">maintenance.locations.list</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  get</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Maintenance API permissions

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
<td><h4 id="maintenance.locations.get" class="permission-name add-link" data-text="maintenance.locations.get" tabindex="-1"><code dir="ltr" translate="no">maintenance.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="maintenance.locations.list" class="permission-name add-link" data-text="maintenance.locations.list" tabindex="-1"><code dir="ltr" translate="no">maintenance.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="maintenance.resourceMaintenances.get" class="permission-name add-link" data-text="maintenance.resourceMaintenances.get" tabindex="-1"><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="maintenance.resourceMaintenances.list" class="permission-name add-link" data-text="maintenance.resourceMaintenances.list" tabindex="-1"><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin">Maintenance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer">Maintenance API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  maintenance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
