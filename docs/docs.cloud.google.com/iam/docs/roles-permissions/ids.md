---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/ids
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/ids
title: Cloud Intrusion Detection System roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Intrusion Detection System. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Intrusion Detection System roles

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
<td><h4 id="ids.admin" class="role-title add-link" data-text="Cloud IDS Admin Beta" tabindex="-1">Cloud IDS Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p>Full access to Cloud IDS all resources.</p></td>
<td><p><code dir="ltr" translate="no">ids.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ids.endpoints.create</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.get</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.list</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">ids.endpoints.update</code></li>
<li><code dir="ltr" translate="no">ids.locations.get</code></li>
<li><code dir="ltr" translate="no">ids.locations.list</code></li>
<li><code dir="ltr" translate="no">ids.operations.cancel</code></li>
<li><code dir="ltr" translate="no">ids.operations.delete</code></li>
<li><code dir="ltr" translate="no">ids.operations.get</code></li>
<li><code dir="ltr" translate="no">ids.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="ids.editor" class="role-title add-link" data-text="Cloud IDS Editor Beta" tabindex="-1">Cloud IDS Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p>Editor role for Cloud IDS</p></td>
<td><p><code dir="ltr" translate="no">ids.endpoints.create</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.delete</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.get</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.list</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.update</code></p>
<p><code dir="ltr" translate="no">ids.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ids.locations.get</code></li>
<li><code dir="ltr" translate="no">ids.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ids.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ids.operations.cancel</code></li>
<li><code dir="ltr" translate="no">ids.operations.delete</code></li>
<li><code dir="ltr" translate="no">ids.operations.get</code></li>
<li><code dir="ltr" translate="no">ids.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.viewer" class="role-title add-link" data-text="Cloud IDS Viewer Beta" tabindex="-1">Cloud IDS Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p>Read-only access to Cloud IDS all resources.</p></td>
<td><p><code dir="ltr" translate="no">ids.endpoints.get</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">ids.endpoints.list</code></p>
<p><code dir="ltr" translate="no">ids.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">ids.locations.get</code></li>
<li><code dir="ltr" translate="no">ids.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">ids.operations.get</code></p>
<p><code dir="ltr" translate="no">ids.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Intrusion Detection System permissions

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
<td><h4 id="ids.endpoints.create" class="permission-name add-link" data-text="ids.endpoints.create" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.endpoints.delete" class="permission-name add-link" data-text="ids.endpoints.delete" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.endpoints.get" class="permission-name add-link" data-text="ids.endpoints.get" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.endpoints.getIamPolicy" class="permission-name add-link" data-text="ids.endpoints.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.endpoints.list" class="permission-name add-link" data-text="ids.endpoints.list" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.endpoints.setIamPolicy" class="permission-name add-link" data-text="ids.endpoints.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.endpoints.update" class="permission-name add-link" data-text="ids.endpoints.update" tabindex="-1"><code dir="ltr" translate="no">ids.endpoints.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.locations.get" class="permission-name add-link" data-text="ids.locations.get" tabindex="-1"><code dir="ltr" translate="no">ids.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.locations.list" class="permission-name add-link" data-text="ids.locations.list" tabindex="-1"><code dir="ltr" translate="no">ids.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.operations.cancel" class="permission-name add-link" data-text="ids.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">ids.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.operations.delete" class="permission-name add-link" data-text="ids.operations.delete" tabindex="-1"><code dir="ltr" translate="no">ids.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="ids.operations.get" class="permission-name add-link" data-text="ids.operations.get" tabindex="-1"><code dir="ltr" translate="no">ids.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="ids.operations.list" class="permission-name add-link" data-text="ids.operations.list" tabindex="-1"><code dir="ltr" translate="no">ids.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.admin">Cloud IDS Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.editor">Cloud IDS Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ids#ids.viewer">Cloud IDS Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ids.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
