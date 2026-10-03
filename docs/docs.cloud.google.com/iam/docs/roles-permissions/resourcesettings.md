---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings
title: Resource Settings roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Resource Settings. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Resource Settings roles

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
<td>Resource Settings Administrator
<p>( <code>roles/ resourcesettings.admin</code> )</p>
<p>Provides admin capabilities to set Resource Setting Values on resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code>resourcesettings.*</code></p>
<ul>
<li><code>resourcesettings.settings.get</code></li>
<li><code>resourcesettings.settings.list</code></li>
<li><code>resourcesettings. settings. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Resource Settings Viewer
<p>( <code>roles/ resourcesettings.viewer</code> )</p>
<p>Provides capabilities to view Resource Settings and Resource Setting Values on resources.</p></td>
<td><p><code>resourcesettings.settings.get</code></p>
<p><code>resourcesettings.settings.list</code></p></td>
</tr>
</tbody>
</table>

## Resource Settings permissions

| Permission                           | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|--------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `resourcesettings.settings.get`      | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Resource Settings Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin) ( `roles/ resourcesettings.admin` ) [Resource Settings Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.viewer) ( `roles/ resourcesettings.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `resourcesettings.settings.list`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Resource Settings Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin) ( `roles/ resourcesettings.admin` ) [Resource Settings Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.viewer) ( `roles/ resourcesettings.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `resourcesettings. settings. update` | [Resource Settings Administrator](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcesettings#resourcesettings.admin) ( `roles/ resourcesettings.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
