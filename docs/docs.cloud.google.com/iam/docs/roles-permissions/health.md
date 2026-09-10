---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/health
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/health
title: Google Health roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Health. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Health roles

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
<td><h4 id="health.admin" class="role-title add-link" data-text="Google Health API Admin" tabindex="-1">Google Health API Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p>Admin access to Google Health API resources.</p></td>
<td><p><code dir="ltr" translate="no">health.*</code></p>
<ul>
<li><code dir="ltr" translate="no">health.subscribers.create</code></li>
<li><code dir="ltr" translate="no">health.subscribers.delete</code></li>
<li><code dir="ltr" translate="no">health.subscribers.list</code></li>
<li><code dir="ltr" translate="no">health.subscribers.update</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.delete</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="health.editor" class="role-title add-link" data-text="Google Health API Editor" tabindex="-1">Google Health API Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  health.editor</code> )</p>
<p>Edit access to Google Health API resources.</p></td>
<td><p><code dir="ltr" translate="no">health.*</code></p>
<ul>
<li><code dir="ltr" translate="no">health.subscribers.create</code></li>
<li><code dir="ltr" translate="no">health.subscribers.delete</code></li>
<li><code dir="ltr" translate="no">health.subscribers.list</code></li>
<li><code dir="ltr" translate="no">health.subscribers.update</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.delete</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">health.subscriptions.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="health.viewer" class="role-title add-link" data-text="Google Health API Viewer" tabindex="-1">Google Health API Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  health.viewer</code> )</p>
<p>Read-only access to Google Health API resources.</p></td>
<td><p><code dir="ltr" translate="no">health.subscribers.list</code></p>
<p><code dir="ltr" translate="no">health.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">health.subscriptions.list</code></p></td>
</tr>
</tbody>
</table>

## Google Health permissions

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
<td><h4 id="health.subscribers.create" class="permission-name add-link" data-text="health.subscribers.create" tabindex="-1"><code dir="ltr" translate="no">health.subscribers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="health.subscribers.delete" class="permission-name add-link" data-text="health.subscribers.delete" tabindex="-1"><code dir="ltr" translate="no">health.subscribers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="health.subscribers.list" class="permission-name add-link" data-text="health.subscribers.list" tabindex="-1"><code dir="ltr" translate="no">health.subscribers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.viewer">Google Health API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="health.subscribers.update" class="permission-name add-link" data-text="health.subscribers.update" tabindex="-1"><code dir="ltr" translate="no">health.subscribers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="health.subscriptions.create" class="permission-name add-link" data-text="health.subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">health.subscriptions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="health.subscriptions.delete" class="permission-name add-link" data-text="health.subscriptions.delete" tabindex="-1"><code dir="ltr" translate="no">health.subscriptions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="health.subscriptions.get" class="permission-name add-link" data-text="health.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">health.subscriptions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.viewer">Google Health API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="health.subscriptions.list" class="permission-name add-link" data-text="health.subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">health.subscriptions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.viewer">Google Health API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="health.subscriptions.update" class="permission-name add-link" data-text="health.subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">health.subscriptions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.admin">Google Health API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/health#health.editor">Google Health API Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  health.editor</code> )</p></td>
</tr>
</tbody>
</table>
