---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/chat
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/chat
title: Hangouts Chat roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Hangouts Chat. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Hangouts Chat roles

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
<td><h4 id="chat.admin" class="role-title add-link" data-text="Chat Admin" tabindex="-1">Chat Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  chat.admin</code> )</p>
<p>Admin role for chat</p></td>
<td><p><code dir="ltr" translate="no">chat.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chat.bots.get</code></li>
<li><code dir="ltr" translate="no">chat.bots.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="chat.viewer" class="role-title add-link" data-text="Chat Viewer" tabindex="-1">Chat Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  chat.viewer</code> )</p>
<p>Viewer role for chat</p></td>
<td><p><code dir="ltr" translate="no">chat.bots.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="chat.owner" class="role-title add-link" data-text="Chat Apps Owner" tabindex="-1">Chat Apps Owner</h4>
<p>( <code dir="ltr" translate="no">roles/  chat.owner</code> )</p>
<p>Can view and modify app configurations</p></td>
<td><p><code dir="ltr" translate="no">chat.*</code></p>
<ul>
<li><code dir="ltr" translate="no">chat.bots.get</code></li>
<li><code dir="ltr" translate="no">chat.bots.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="chat.reader" class="role-title add-link" data-text="Chat Apps Viewer" tabindex="-1">Chat Apps Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  chat.reader</code> )</p>
<p>Can view app configurations</p></td>
<td><p><code dir="ltr" translate="no">chat.bots.get</code></p></td>
</tr>
</tbody>
</table>

## Hangouts Chat permissions

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
<td><h4 id="chat.bots.get" class="permission-name add-link" data-text="chat.bots.get" tabindex="-1"><code dir="ltr" translate="no">chat.bots.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer">Chat Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.owner">Chat Apps Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.reader">Chat Apps Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="chat.bots.update" class="permission-name add-link" data-text="chat.bots.update" tabindex="-1"><code dir="ltr" translate="no">chat.bots.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin">Chat Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.owner">Chat Apps Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chat.owner</code> )</p></td>
</tr>
</tbody>
</table>
