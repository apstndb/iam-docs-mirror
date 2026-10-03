---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/devicerun
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun
title: Device Run roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Device Run. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Device Run roles

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
<td>Device Run Admin <sup>Beta</sup>
<p>( <code>roles/ devicerun.admin</code> )</p>
<p>Full access to Device Run resources.</p></td>
<td><p><code>cloudtestservice. environmentcatalog. get</code></p>
<p><code>devicerun.*</code></p>
<ul>
<li><code>devicerun.devices.get</code></li>
<li><code>devicerun.devices.list</code></li>
<li><code>devicerun.locations.get</code></li>
<li><code>devicerun.locations.list</code></li>
<li><code>devicerun.operations.cancel</code></li>
<li><code>devicerun.operations.delete</code></li>
<li><code>devicerun.operations.get</code></li>
<li><code>devicerun.operations.list</code></li>
<li><code>devicerun.sessions.create</code></li>
<li><code>devicerun.sessions.delete</code></li>
<li><code>devicerun.sessions.get</code></li>
<li><code>devicerun.sessions.list</code></li>
<li><code>devicerun.softwareVersions.get</code></li>
<li><code>devicerun. softwareVersions. list</code></li>
</ul>
<p><code>devicestreaming.*</code></p>
<ul>
<li><code>devicestreaming. deviceSessions. cancel</code></li>
<li><code>devicestreaming. deviceSessions. create</code></li>
<li><code>devicestreaming. deviceSessions. get</code></li>
<li><code>devicestreaming. deviceSessions. list</code></li>
<li><code>devicestreaming. deviceSessions. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Device Run Viewer <sup>Beta</sup>
<p>( <code>roles/ devicerun.viewer</code> )</p>
<p>Readonly access to Device Run resources.</p></td>
<td><p><code>cloudtestservice. environmentcatalog. get</code></p>
<p><code>devicerun.devices.*</code></p>
<ul>
<li><code>devicerun.devices.get</code></li>
<li><code>devicerun.devices.list</code></li>
</ul>
<p><code>devicerun.locations.*</code></p>
<ul>
<li><code>devicerun.locations.get</code></li>
<li><code>devicerun.locations.list</code></li>
</ul>
<p><code>devicerun.operations.get</code></p>
<p><code>devicerun.operations.list</code></p>
<p><code>devicerun.sessions.get</code></p>
<p><code>devicerun.sessions.list</code></p>
<p><code>devicerun.softwareVersions.*</code></p>
<ul>
<li><code>devicerun.softwareVersions.get</code></li>
<li><code>devicerun. softwareVersions. list</code></li>
</ul>
<p><code>devicestreaming. deviceSessions. get</code></p>
<p><code>devicestreaming. deviceSessions. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Device Run Service Agent
<p>( <code>roles/ devicerun.serviceAgent</code> )</p>
<p>Grants Device Run Service Agent permissions required to manage resources in the consumer project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>pubsub.topics.publish</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.list</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p></td>
</tr>
</tbody>
</table>

## Device Run permissions

| Permission                          | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
|-------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `devicerun.devices.get`             | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `devicerun.devices.list`            | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `devicerun.locations.get`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `devicerun.locations.list`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `devicerun.operations.cancel`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `devicerun.operations.delete`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `devicerun.operations.get`          | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `devicerun.operations.list`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `devicerun.sessions.create`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `devicerun.sessions.delete`         | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `devicerun.sessions.get`            | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `devicerun.sessions.list`           | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `devicerun.softwareVersions.get`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `devicerun. softwareVersions. list` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Device Run Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin) ( `roles/ devicerun.admin` ) [Device Run Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer) ( `roles/ devicerun.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
