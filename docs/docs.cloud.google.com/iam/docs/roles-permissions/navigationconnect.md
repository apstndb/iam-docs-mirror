---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect
title: Navigation Connect roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Navigation Connect. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Navigation Connect roles

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
<td>Navigation Connect Admin <sup>Beta</sup>
<p>( <code>roles/ navigationconnect.admin</code> )</p>
<p>Full access to Navigation Connect resources.</p></td>
<td><p><code>navigationconnect.*</code></p>
<ul>
<li><code>navigationconnect.trips.cancel</code></li>
<li><code>navigationconnect.trips.create</code></li>
<li><code>navigationconnect.trips.get</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Navigation Connect Viewer <sup>Beta</sup>
<p>( <code>roles/ navigationconnect.viewer</code> )</p>
<p>Read-only access to Navigation Connect resources.</p></td>
<td><p><code>navigationconnect.trips.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Navigation Connect permissions

| Permission                       | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
|----------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `navigationconnect.trips.cancel` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Navigation Connect Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin) ( `roles/ navigationconnect.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `navigationconnect.trips.create` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Navigation Connect Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin) ( `roles/ navigationconnect.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `navigationconnect.trips.get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Navigation Connect Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.admin) ( `roles/ navigationconnect.admin` ) [Navigation Connect Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/navigationconnect#navigationconnect.viewer) ( `roles/ navigationconnect.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
