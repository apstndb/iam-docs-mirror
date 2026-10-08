---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/nestconsole
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole
title: Nest Console roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Nest Console. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Nest Console roles

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
<td>Nestconsole Admin
<p>( <code>roles/ nestconsole.admin</code> )</p>
<p>Admin role for nestconsole</p></td>
<td><p><code>nestconsole.*</code></p>
<ul>
<li><code>nestconsole. smarthomePreviews. update</code></li>
<li><code>nestconsole. smarthomeProjects. create</code></li>
<li><code>nestconsole. smarthomeProjects. delete</code></li>
<li><code>nestconsole. smarthomeProjects. get</code></li>
<li><code>nestconsole. smarthomeProjects. update</code></li>
<li><code>nestconsole. smarthomeVersions. create</code></li>
<li><code>nestconsole. smarthomeVersions. get</code></li>
<li><code>nestconsole. smarthomeVersions. submit</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Nestconsole Editor
<p>( <code>roles/ nestconsole.editor</code> )</p>
<p>Editor role for nestconsole</p></td>
<td><p><code>nestconsole. smarthomePreviews. update</code></p>
<p><code>nestconsole. smarthomeProjects. get</code></p>
<p><code>nestconsole. smarthomeProjects. update</code></p>
<p><code>nestconsole. smarthomeVersions.*</code></p>
<ul>
<li><code>nestconsole. smarthomeVersions. create</code></li>
<li><code>nestconsole. smarthomeVersions. get</code></li>
<li><code>nestconsole. smarthomeVersions. submit</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Nestconsole Viewer
<p>( <code>roles/ nestconsole.viewer</code> )</p>
<p>Viewer role for nestconsole</p></td>
<td><p><code>nestconsole. smarthomeProjects. get</code></p>
<p><code>nestconsole. smarthomeVersions. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Google Home Developer Console Admin
<p>( <code>roles/ nestconsole.homeDeveloperAdmin</code> )</p>
<p>Admin access to Google Home Developer Console resources</p></td>
<td><p><code>nestconsole.*</code></p>
<ul>
<li><code>nestconsole. smarthomePreviews. update</code></li>
<li><code>nestconsole. smarthomeProjects. create</code></li>
<li><code>nestconsole. smarthomeProjects. delete</code></li>
<li><code>nestconsole. smarthomeProjects. get</code></li>
<li><code>nestconsole. smarthomeProjects. update</code></li>
<li><code>nestconsole. smarthomeVersions. create</code></li>
<li><code>nestconsole. smarthomeVersions. get</code></li>
<li><code>nestconsole. smarthomeVersions. submit</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Google Home Developer Console Editor
<p>( <code>roles/ nestconsole.homeDeveloperEditor</code> )</p>
<p>Read-Write access to Google Home Developer Console resources</p></td>
<td><p><code>nestconsole. smarthomePreviews. update</code></p>
<p><code>nestconsole. smarthomeProjects. get</code></p>
<p><code>nestconsole. smarthomeProjects. update</code></p>
<p><code>nestconsole. smarthomeVersions.*</code></p>
<ul>
<li><code>nestconsole. smarthomeVersions. create</code></li>
<li><code>nestconsole. smarthomeVersions. get</code></li>
<li><code>nestconsole. smarthomeVersions. submit</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Google Home Developer Console Reader
<p>( <code>roles/ nestconsole.homeDeveloperViewer</code> )</p>
<p>Read-only access to Google Home Developer Console resources</p></td>
<td><p><code>nestconsole. smarthomeProjects. get</code></p>
<p><code>nestconsole. smarthomeVersions. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Nest Console permissions

| Permission                               | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `nestconsole. smarthomePreviews. update` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `nestconsole. smarthomeProjects. create` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `nestconsole. smarthomeProjects. delete` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `nestconsole. smarthomeProjects. get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Nestconsole Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer) ( `roles/ nestconsole.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` ) [Google Home Developer Console Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer) ( `roles/ nestconsole.homeDeveloperViewer` ) |
| `nestconsole. smarthomeProjects. update` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `nestconsole. smarthomeVersions. create` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `nestconsole. smarthomeVersions. get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Nestconsole Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.viewer) ( `roles/ nestconsole.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` ) [Google Home Developer Console Reader](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperViewer) ( `roles/ nestconsole.homeDeveloperViewer` ) |
| `nestconsole. smarthomeVersions. submit` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Nestconsole Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.admin) ( `roles/ nestconsole.admin` ) [Nestconsole Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.editor) ( `roles/ nestconsole.editor` ) [Google Home Developer Console Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperAdmin) ( `roles/ nestconsole.homeDeveloperAdmin` ) [Google Home Developer Console Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/nestconsole#nestconsole.homeDeveloperEditor) ( `roles/ nestconsole.homeDeveloperEditor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
