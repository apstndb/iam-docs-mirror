---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace
title: Google Workspace Marketplace roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Workspace Marketplace. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Workspace Marketplace roles

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
<td>Workspace Marketplace App Configuration Admin
<p>( <code>roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p>Workspace Marketplace App Configuration Admin</p></td>
<td><p><code>chat.bots.get</code></p>
<p><code>clientauthconfig. clients. create</code></p>
<p><code>gsuiteaddons. deployments. create</code></p>
<p><code>gsuiteaddons. deployments. delete</code></p>
<p><code>gsuiteaddons.deployments.list</code></p>
<p><code>gsuiteaddons. deployments. update</code></p>
<p><code>oauthconfig.verification.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>workspacemarketplace.*</code></p>
<ul>
<li><code>workspacemarketplace. appConfiguration. update</code></li>
<li><code>workspacemarketplace. appConfiguration. view</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Workspace Marketplace permissions

| Permission                                       | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
|--------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `workspacemarketplace. appConfiguration. update` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Workspace Marketplace App Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin) ( `roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                        |
| `workspacemarketplace. appConfiguration. view`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Workspace Marketplace App Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin) ( `roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
