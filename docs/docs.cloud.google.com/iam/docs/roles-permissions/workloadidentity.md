---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity
title: Workload Identity API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Workload Identity API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Workload Identity API roles

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
<td><h4 id="workloadidentity.admin" class="role-title add-link" data-text="Workload Identity API Admin" tabindex="-1">Workload Identity API Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p>
<p>Full access to Workload Identity API resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadidentity.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadidentity.locations.get</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  locations.  list</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  operations.  get</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  operations.  list</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  serviceAgents.  create</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadidentity.viewer" class="role-title add-link" data-text="Workload Identity API Viewer" tabindex="-1">Workload Identity API Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  workloadidentity.viewer</code> )</p>
<p>Readonly access to Workload Identity API resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadidentity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadidentity.locations.get</code></li>
<li><code dir="ltr" translate="no">workloadidentity.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadidentity.  operations.  get</code></p>
<p><code dir="ltr" translate="no">workloadidentity.  operations.  list</code></p></td>
</tr>
</tbody>
</table>

## Workload Identity API permissions

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
<td><h4 id="workloadidentity.locations.get" class="permission-name add-link" data-text="workloadidentity.locations.get" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadidentity.locations.list" class="permission-name add-link" data-text="workloadidentity.locations.list" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadidentity.operations.cancel" class="permission-name add-link" data-text="workloadidentity.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadidentity.operations.delete" class="permission-name add-link" data-text="workloadidentity.operations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadidentity.operations.get" class="permission-name add-link" data-text="workloadidentity.operations.get" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadidentity.operations.list" class="permission-name add-link" data-text="workloadidentity.operations.list" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.viewer">Workload Identity API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadidentity.serviceAgents.create" class="permission-name add-link" data-text="workloadidentity.serviceAgents.create" tabindex="-1"><code dir="ltr" translate="no">workloadidentity.  serviceAgents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadidentity#workloadidentity.admin">Workload Identity API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadidentity.admin</code> )</p></td>
</tr>
</tbody>
</table>
