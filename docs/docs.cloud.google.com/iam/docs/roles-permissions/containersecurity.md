---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/containersecurity
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity
title: Container Security roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Container Security. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Container Security roles

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
<td>Containersecurity Admin <sup>Beta</sup>
<p>( <code>roles/ containersecurity.admin</code> )</p>
<p>Admin role for containersecurity</p></td>
<td><p><code>container.clusters.list</code></p>
<p><code>containersecurity.*</code></p>
<ul>
<li><code>containersecurity. clusterSummaries. list</code></li>
<li><code>containersecurity. findings. list</code></li>
<li><code>containersecurity. locations. get</code></li>
<li><code>containersecurity. locations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>GKE Security Posture Viewer <sup>Beta</sup>
<p>( <code>roles/ containersecurity.viewer</code> )</p>
<p>Read-only access to GKE Security Posture resources.</p></td>
<td><p><code>container.clusters.list</code></p>
<p><code>containersecurity.*</code></p>
<ul>
<li><code>containersecurity. clusterSummaries. list</code></li>
<li><code>containersecurity. findings. list</code></li>
<li><code>containersecurity. locations. get</code></li>
<li><code>containersecurity. locations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Container Security permissions

| Permission                                  | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `containersecurity. clusterSummaries. list` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Containersecurity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin) ( `roles/ containersecurity.admin` ) [GKE Security Posture Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer) ( `roles/ containersecurity.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` )                                                                                                                                                                                                                                                                                                                        |
| `containersecurity. findings. list`         | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Containersecurity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin) ( `roles/ containersecurity.admin` ) [GKE Security Posture Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer) ( `roles/ containersecurity.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` )                                                                                                                                                                                                                                                                                                                        |
| `containersecurity. locations. get`         | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Containersecurity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin) ( `roles/ containersecurity.admin` ) [GKE Security Posture Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer) ( `roles/ containersecurity.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `containersecurity. locations. list`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Containersecurity Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.admin) ( `roles/ containersecurity.admin` ) [GKE Security Posture Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/containersecurity#containersecurity.viewer) ( `roles/ containersecurity.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
