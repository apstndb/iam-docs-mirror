---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/roads
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/roads
title: Roads Management Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Roads Management Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Roads Management Insights roles

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
<td><h4 id="roads.roadsSelectionAdmin" class="role-title add-link" data-text="Roads Selection Admin" tabindex="-1">Roads Selection Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p>
<p>Full access to SelectedRoutes</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">roads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">roads.  selectedRoutes.  batchCreate</code></li>
<li><code dir="ltr" translate="no">roads.selectedRoutes.create</code></li>
<li><code dir="ltr" translate="no">roads.selectedRoutes.delete</code></li>
<li><code dir="ltr" translate="no">roads.selectedRoutes.get</code></li>
<li><code dir="ltr" translate="no">roads.selectedRoutes.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="roads.roadsSelectionViewer" class="role-title add-link" data-text="Roads Selection Viewer" tabindex="-1">Roads Selection Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  roads.roadsSelectionViewer</code> )</p>
<p>Read access to SelectedRoutes</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">roads.selectedRoutes.get</code></p>
<p><code dir="ltr" translate="no">roads.selectedRoutes.list</code></p></td>
</tr>
</tbody>
</table>

## Roads Management Insights permissions

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
<td><h4 id="roads.selectedRoutes.batchCreate" class="permission-name add-link" data-text="roads.selectedRoutes.batchCreate" tabindex="-1"><code dir="ltr" translate="no">roads.  selectedRoutes.  batchCreate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="roads.selectedRoutes.create" class="permission-name add-link" data-text="roads.selectedRoutes.create" tabindex="-1"><code dir="ltr" translate="no">roads.selectedRoutes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="roads.selectedRoutes.delete" class="permission-name add-link" data-text="roads.selectedRoutes.delete" tabindex="-1"><code dir="ltr" translate="no">roads.selectedRoutes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="roads.selectedRoutes.get" class="permission-name add-link" data-text="roads.selectedRoutes.get" tabindex="-1"><code dir="ltr" translate="no">roads.selectedRoutes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="roads.selectedRoutes.list" class="permission-name add-link" data-text="roads.selectedRoutes.list" tabindex="-1"><code dir="ltr" translate="no">roads.selectedRoutes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionAdmin">Roads Selection Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/roads#roads.roadsSelectionViewer">Roads Selection Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  roads.roadsSelectionViewer</code> )</p></td>
</tr>
</tbody>
</table>
