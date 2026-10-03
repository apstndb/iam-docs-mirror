---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/translationhub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub
title: Translation Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Translation Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Translation Hub roles

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
<td>Translation Hub Admin <sup>Beta</sup>
<p>( <code>roles/ translationhub.admin</code> )</p>
<p>Admin of Translation Hub</p></td>
<td><p><code>automl.models.get</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.models.predict</code></p>
<p><code>cloudtranslate. customModels. get</code></p>
<p><code>cloudtranslate. customModels. list</code></p>
<p><code>cloudtranslate. customModels. predict</code></p>
<p><code>cloudtranslate. glossaries. create</code></p>
<p><code>cloudtranslate. glossaries. delete</code></p>
<p><code>cloudtranslate.glossaries.get</code></p>
<p><code>cloudtranslate.glossaries.list</code></p>
<p><code>cloudtranslate. glossaries. predict</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>translationhub.*</code></p>
<ul>
<li><code>translationhub.portals.create</code></li>
<li><code>translationhub.portals.delete</code></li>
<li><code>translationhub.portals.get</code></li>
<li><code>translationhub.portals.list</code></li>
<li><code>translationhub.portals.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Translation Hub Viewer <sup>Beta</sup>
<p>( <code>roles/ translationhub.viewer</code> )</p>
<p>Viewer role for Translation Hub</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>translationhub.portals.get</code></p>
<p><code>translationhub.portals.list</code></p></td>
</tr>
<tr class="odd">
<td>Translation Hub Portal User <sup>Beta</sup>
<p>( <code>roles/ translationhub.portalUser</code> )</p>
<p>Portal user of Translation Hub</p></td>
<td><p><code>automl.models.get</code></p>
<p><code>automl.models.list</code></p>
<p><code>automl.models.predict</code></p>
<p><code>cloudtranslate. customModels. get</code></p>
<p><code>cloudtranslate. customModels. list</code></p>
<p><code>cloudtranslate. customModels. predict</code></p>
<p><code>cloudtranslate.glossaries.get</code></p>
<p><code>cloudtranslate.glossaries.list</code></p>
<p><code>cloudtranslate. glossaries. predict</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>translationhub.portals.get</code></p>
<p><code>translationhub.portals.list</code></p></td>
</tr>
</tbody>
</table>

## Translation Hub permissions

| Permission                      | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `translationhub.portals.create` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Translation Hub Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin) ( `roles/ translationhub.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `translationhub.portals.delete` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Translation Hub Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin) ( `roles/ translationhub.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| `translationhub.portals.get`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Translation Hub Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin) ( `roles/ translationhub.admin` ) [Translation Hub Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer) ( `roles/ translationhub.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Translation Hub Portal User](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser) ( `roles/ translationhub.portalUser` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `translationhub.portals.list`   | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Translation Hub Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin) ( `roles/ translationhub.admin` ) [Translation Hub Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.viewer) ( `roles/ translationhub.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Translation Hub Portal User](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.portalUser) ( `roles/ translationhub.portalUser` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `translationhub.portals.update` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Translation Hub Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/translationhub#translationhub.admin) ( `roles/ translationhub.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
