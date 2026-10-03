---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/maintenance
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance
title: Maintenance API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Maintenance API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Maintenance API roles

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
<td>Maintenance Admin
<p>( <code>roles/ maintenance.admin</code> )</p>
<p>Admin role for maintenance</p></td>
<td><p><code>maintenance.*</code></p>
<ul>
<li><code>maintenance.locations.get</code></li>
<li><code>maintenance.locations.list</code></li>
<li><code>maintenance. resourceMaintenances. get</code></li>
<li><code>maintenance. resourceMaintenances. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Maintenance API Viewer
<p>( <code>roles/ maintenance.viewer</code> )</p>
<p>Readonly access to Maintenance API resources.</p></td>
<td><p><code>maintenance.*</code></p>
<ul>
<li><code>maintenance.locations.get</code></li>
<li><code>maintenance.locations.list</code></li>
<li><code>maintenance. resourceMaintenances. get</code></li>
<li><code>maintenance. resourceMaintenances. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Maintenance API permissions

| Permission                                | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `maintenance.locations.get`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Maintenance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin) ( `roles/ maintenance.admin` ) [Maintenance API Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer) ( `roles/ maintenance.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `maintenance.locations.list`              | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Maintenance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin) ( `roles/ maintenance.admin` ) [Maintenance API Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer) ( `roles/ maintenance.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `maintenance. resourceMaintenances. get`  | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Maintenance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin) ( `roles/ maintenance.admin` ) [Maintenance API Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer) ( `roles/ maintenance.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `maintenance. resourceMaintenances. list` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Maintenance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.admin) ( `roles/ maintenance.admin` ) [Maintenance API Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/maintenance#maintenance.viewer) ( `roles/ maintenance.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
