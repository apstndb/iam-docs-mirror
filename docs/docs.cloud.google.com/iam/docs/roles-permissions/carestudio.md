---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/carestudio
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio
title: Care Studio roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Care Studio. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Care Studio roles

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
<td><h4 id="carestudio.admin" class="role-title add-link" data-text="Carestudio Admin" tabindex="-1">Carestudio Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  carestudio.admin</code> )</p>
<p>Admin role for carestudio</p></td>
<td><p><code dir="ltr" translate="no">carestudio.*</code></p>
<ul>
<li><code dir="ltr" translate="no">carestudio.patients.get</code></li>
<li><code dir="ltr" translate="no">carestudio.patients.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="carestudio.viewer" class="role-title add-link" data-text="Care Studio Patients Viewer" tabindex="-1">Care Studio Patients Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  carestudio.viewer</code> )</p>
<p>This role can view all properties of Patients.</p></td>
<td><p><code dir="ltr" translate="no">carestudio.*</code></p>
<ul>
<li><code dir="ltr" translate="no">carestudio.patients.get</code></li>
<li><code dir="ltr" translate="no">carestudio.patients.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Care Studio permissions

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
<td><h4 id="carestudio.patients.get" class="permission-name add-link" data-text="carestudio.patients.get" tabindex="-1"><code dir="ltr" translate="no">carestudio.patients.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="carestudio.patients.list" class="permission-name add-link" data-text="carestudio.patients.list" tabindex="-1"><code dir="ltr" translate="no">carestudio.patients.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.admin">Carestudio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/carestudio#carestudio.viewer">Care Studio Patients Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  carestudio.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
