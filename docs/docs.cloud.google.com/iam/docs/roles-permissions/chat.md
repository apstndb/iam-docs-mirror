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
<td>Chat Admin
<p>( <code>roles/ chat.admin</code> )</p>
<p>Admin role for chat</p></td>
<td><p><code>chat.*</code></p>
<ul>
<li><code>chat.bots.get</code></li>
<li><code>chat.bots.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Chat Viewer
<p>( <code>roles/ chat.viewer</code> )</p>
<p>Viewer role for chat</p></td>
<td><p><code>chat.bots.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Chat Apps Owner
<p>( <code>roles/ chat.owner</code> )</p>
<p>Can view and modify app configurations</p></td>
<td><p><code>chat.*</code></p>
<ul>
<li><code>chat.bots.get</code></li>
<li><code>chat.bots.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Chat Apps Viewer
<p>( <code>roles/ chat.reader</code> )</p>
<p>Can view app configurations</p></td>
<td><p><code>chat.bots.get</code></p></td>
</tr>
</tbody>
</table>

## Hangouts Chat permissions

| Permission         | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `chat.bots.get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Chat Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin) ( `roles/ chat.admin` ) [Chat Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.viewer) ( `roles/ chat.viewer` ) [Google Workspace Add-ons Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin) ( `roles/ gsuiteaddons.admin` ) [Google Workspace Add-ons Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer) ( `roles/ gsuiteaddons.viewer` ) [Workspace Marketplace App Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin) ( `roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin` ) [Chat Apps Owner](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.owner) ( `roles/ chat.owner` ) [Chat Apps Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.reader) ( `roles/ chat.reader` ) [Google Workspace Add-ons Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer) ( `roles/ gsuiteaddons.developer` ) [Google Workspace Add-ons Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader) ( `roles/ gsuiteaddons.reader` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `chat.bots.update` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Chat Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.admin) ( `roles/ chat.admin` ) [Chat Apps Owner](https://docs.cloud.google.com/iam/docs/roles-permissions/chat#chat.owner) ( `roles/ chat.owner` ) [Google Workspace Add-ons Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer) ( `roles/ gsuiteaddons.developer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
