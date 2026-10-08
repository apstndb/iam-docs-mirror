---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloud
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloud
title: Google Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud roles

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
<td>Cloud Admin <sup>Beta</sup>
<p>( <code>roles/ cloud.admin</code> )</p>
<p>Admin role for cloud</p></td>
<td><p><code>cloud.*</code></p>
<ul>
<li><code>cloud.locations.get</code></li>
<li><code>cloud.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud Viewer <sup>Beta</sup>
<p>( <code>roles/ cloud.viewer</code> )</p>
<p>Viewer role for cloud</p></td>
<td><p><code>cloud.*</code></p>
<ul>
<li><code>cloud.locations.get</code></li>
<li><code>cloud.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Location reader <sup>Beta</sup>
<p>( <code>roles/ cloud.locationReader</code> )</p>
<p>Read and enumerate locations available for resource creation.</p></td>
<td><p><code>cloud.*</code></p>
<ul>
<li><code>cloud.locations.get</code></li>
<li><code>cloud.locations.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Cloud permissions

| Permission             | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
|------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `cloud.locations.get`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin) ( `roles/ cloud.admin` ) [Cloud Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer) ( `roles/ cloud.viewer` ) [Location reader](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.locationReader) ( `roles/ cloud.locationReader` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `cloud.locations.list` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Cloud Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.admin) ( `roles/ cloud.admin` ) [Cloud Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.viewer) ( `roles/ cloud.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Location reader](https://docs.cloud.google.com/iam/docs/roles-permissions/cloud#cloud.locationReader) ( `roles/ cloud.locationReader` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
