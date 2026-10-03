---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice
title: RISC Configuration Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for RISC Configuration Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## RISC Configuration Service roles

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
<td>RISC Configuration Admin <sup>Beta</sup>
<p>( <code>roles/ riscconfigs.admin</code> )</p>
<p>Read/write access to RISC config resources.</p></td>
<td><p><code>clientauthconfig.clients.list</code></p>
<p><code>riscconfigurationservice.*</code></p>
<ul>
<li><code>riscconfigurationservice. riscconfigs. createOrUpdate</code></li>
<li><code>riscconfigurationservice. riscconfigs. delete</code></li>
<li><code>riscconfigurationservice. riscconfigs. get</code></li>
</ul></td>
</tr>
<tr class="even">
<td>RISC Configuration Viewer <sup>Beta</sup>
<p>( <code>roles/ riscconfigs.viewer</code> )</p>
<p>Read-only access to RISC config resources.</p></td>
<td><p><code>clientauthconfig.clients.list</code></p>
<p><code>riscconfigurationservice. riscconfigs. get</code></p></td>
</tr>
</tbody>
</table>

## RISC Configuration Service permissions

| Permission                                              | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `riscconfigurationservice. riscconfigs. createOrUpdate` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [RISC Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin) ( `roles/ riscconfigs.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `riscconfigurationservice. riscconfigs. delete`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [RISC Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin) ( `roles/ riscconfigs.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `riscconfigurationservice. riscconfigs. get`            | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [RISC Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin) ( `roles/ riscconfigs.admin` ) [RISC Configuration Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.viewer) ( `roles/ riscconfigs.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
