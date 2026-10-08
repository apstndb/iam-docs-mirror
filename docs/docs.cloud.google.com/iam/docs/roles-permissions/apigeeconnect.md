---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect
title: Apigee Connect roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Apigee Connect. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Apigee Connect roles

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
<td>Apigee Connect Admin
<p>( <code>roles/ apigeeconnect.Admin</code> )</p>
<p>Admin of Apigee Connect</p></td>
<td><p><code>apigeeconnect.*</code></p>
<ul>
<li><code>apigeeconnect.connections.list</code></li>
<li><code>apigeeconnect. endpoints. connect</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Apigeeconnect Viewer
<p>( <code>roles/ apigeeconnect.viewer</code> )</p>
<p>Viewer role for apigeeconnect</p></td>
<td><p><code>apigeeconnect.connections.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Apigee Connect Agent
<p>( <code>roles/ apigeeconnect.Agent</code> )</p>
<p>Ability to set up Apigee Connect agent between external clusters and Google.</p></td>
<td><p><code>apigeeconnect. endpoints. connect</code></p></td>
</tr>
</tbody>
</table>

## Apigee Connect permissions

| Permission                          | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|-------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `apigeeconnect.connections.list`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Apigee Connect Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.Admin) ( `roles/ apigeeconnect.Admin` ) [Apigeeconnect Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer) ( `roles/ apigeeconnect.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `apigeeconnect. endpoints. connect` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Apigee Connect Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.Admin) ( `roles/ apigeeconnect.Admin` ) [Apigee Connect Agent](https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.Agent) ( `roles/ apigeeconnect.Agent` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
