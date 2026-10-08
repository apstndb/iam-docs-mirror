---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications
title: Advisory Notifications roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Advisory Notifications. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Advisory Notifications roles

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
<td>Advisory Notifications Admin
<p>( <code>roles/ advisorynotifications.admin</code> )</p>
<p>Grants write access to settings in Advisory Notifications</p></td>
<td><p><code>advisorynotifications.*</code></p>
<ul>
<li><code>advisorynotifications. notifications. get</code></li>
<li><code>advisorynotifications. notifications. list</code></li>
<li><code>advisorynotifications. settings. get</code></li>
<li><code>advisorynotifications. settings. update</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td>Advisory Notifications Viewer
<p>( <code>roles/ advisorynotifications.viewer</code> )</p>
<p>Grants view access in Advisory Notifications</p></td>
<td><p><code>advisorynotifications. notifications.*</code></p>
<ul>
<li><code>advisorynotifications. notifications. get</code></li>
<li><code>advisorynotifications. notifications. list</code></li>
</ul>
<p><code>advisorynotifications. settings. get</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Advisory Notifications permissions

| Permission                                   | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|----------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `advisorynotifications. notifications. get`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Advisory Notifications Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin) ( `roles/ advisorynotifications.admin` ) [Advisory Notifications Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer) ( `roles/ advisorynotifications.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `advisorynotifications. notifications. list` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Advisory Notifications Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin) ( `roles/ advisorynotifications.admin` ) [Advisory Notifications Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer) ( `roles/ advisorynotifications.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `advisorynotifications. settings. get`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Advisory Notifications Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin) ( `roles/ advisorynotifications.admin` ) [Advisory Notifications Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.viewer) ( `roles/ advisorynotifications.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `advisorynotifications. settings. update`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Advisory Notifications Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/advisorynotifications#advisorynotifications.admin) ( `roles/ advisorynotifications.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
