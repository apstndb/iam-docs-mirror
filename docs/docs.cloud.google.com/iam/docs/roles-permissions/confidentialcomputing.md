---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing
title: Confidential Computing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Confidential Computing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Confidential Computing roles

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
<td>Confidentialcomputing Admin
<p>( <code>roles/ confidentialcomputing.admin</code> )</p>
<p>Admin role for confidentialcomputing</p></td>
<td><p><code>confidentialcomputing.*</code></p>
<ul>
<li><code>confidentialcomputing. challenges. create</code></li>
<li><code>confidentialcomputing. challenges. verify</code></li>
<li><code>confidentialcomputing. challenges. verifygke</code></li>
<li><code>confidentialcomputing. locations. get</code></li>
<li><code>confidentialcomputing. locations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Confidentialcomputing Viewer
<p>( <code>roles/ confidentialcomputing.viewer</code> )</p>
<p>Viewer role for confidentialcomputing</p></td>
<td><p><code>confidentialcomputing. locations.*</code></p>
<ul>
<li><code>confidentialcomputing. locations. get</code></li>
<li><code>confidentialcomputing. locations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Confidential GKE Workload User
<p>( <code>roles/ confidentialcomputing.gkeWorkloadUser</code> )</p>
<p>Grants the ability to generate a GKE attestation token and run a workload in a GKE cluster.</p></td>
<td><p><code>confidentialcomputing. challenges. create</code></p>
<p><code>confidentialcomputing. challenges. verifygke</code></p>
<p><code>confidentialcomputing. locations.*</code></p>
<ul>
<li><code>confidentialcomputing. locations. get</code></li>
<li><code>confidentialcomputing. locations. list</code></li>
</ul>
<p><code>logging.logEntries.create</code></p></td>
</tr>
<tr class="even">
<td>Confidential Space Workload User
<p>( <code>roles/ confidentialcomputing.workloadUser</code> )</p>
<p>Grants the ability to generate an attestation token and run a workload in a VM. Intended for service accounts that run on Confidential Space VMs.</p></td>
<td><p><code>confidentialcomputing. challenges. create</code></p>
<p><code>confidentialcomputing. challenges. verify</code></p>
<p><code>confidentialcomputing. locations.*</code></p>
<ul>
<li><code>confidentialcomputing. locations. get</code></li>
<li><code>confidentialcomputing. locations. list</code></li>
</ul>
<p><code>logging.logEntries.create</code></p></td>
</tr>
</tbody>
</table>

## Confidential Computing permissions

| Permission                                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `confidentialcomputing. challenges. create`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Confidentialcomputing Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin) ( `roles/ confidentialcomputing.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Confidential GKE Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser) ( `roles/ confidentialcomputing.gkeWorkloadUser` ) [Confidential Space Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser) ( `roles/ confidentialcomputing.workloadUser` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| `confidentialcomputing. challenges. verify`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Confidentialcomputing Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin) ( `roles/ confidentialcomputing.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Confidential Space Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser) ( `roles/ confidentialcomputing.workloadUser` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| `confidentialcomputing. challenges. verifygke` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Confidentialcomputing Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin) ( `roles/ confidentialcomputing.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Confidential GKE Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser) ( `roles/ confidentialcomputing.gkeWorkloadUser` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `confidentialcomputing. locations. get`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Confidentialcomputing Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin) ( `roles/ confidentialcomputing.admin` ) [Confidentialcomputing Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer) ( `roles/ confidentialcomputing.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Confidential GKE Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser) ( `roles/ confidentialcomputing.gkeWorkloadUser` ) [Confidential Space Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser) ( `roles/ confidentialcomputing.workloadUser` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `confidentialcomputing. locations. list`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Confidentialcomputing Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.admin) ( `roles/ confidentialcomputing.admin` ) [Confidentialcomputing Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.viewer) ( `roles/ confidentialcomputing.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Confidential GKE Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.gkeWorkloadUser) ( `roles/ confidentialcomputing.gkeWorkloadUser` ) [Confidential Space Workload User](https://docs.cloud.google.com/iam/docs/roles-permissions/confidentialcomputing#confidentialcomputing.workloadUser) ( `roles/ confidentialcomputing.workloadUser` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
