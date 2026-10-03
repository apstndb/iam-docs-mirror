---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation
title: Appliance Activation Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Appliance Activation Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Appliance Activation Service roles

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
<td>Appliance Admin <sup>Beta</sup>
<p>( <code>roles/ applianceactivation.admin</code> )</p>
<p>Admin role for Appliance</p></td>
<td><p><code>applianceactivation.*</code></p>
<ul>
<li><code>applianceactivation. rttCommands. approve</code></li>
<li><code>applianceactivation. rttCommands. create</code></li>
<li><code>applianceactivation. rttCommands. get</code></li>
<li><code>applianceactivation. rttCommands. list</code></li>
<li><code>applianceactivation. rttCommands. sendResult</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Appliance Viewer <sup>Beta</sup>
<p>( <code>roles/ applianceactivation.viewer</code> )</p>
<p>Viewer role for Appliance</p></td>
<td><p><code>applianceactivation. rttCommands. get</code></p>
<p><code>applianceactivation. rttCommands. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Appliance troubleshooting commands approver <sup>Beta</sup>
<p>( <code>roles/ applianceactivation.approver</code> )</p>
<p>Grants access to approve commands to run on appliances</p></td>
<td><p><code>applianceactivation. rttCommands. approve</code></p>
<p><code>applianceactivation. rttCommands. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>On-appliance troubleshooting client <sup>Beta</sup>
<p>( <code>roles/ applianceactivation.client</code> )</p>
<p>Grants access to read commands for an appliance and send its result.</p></td>
<td><p><code>applianceactivation. rttCommands. get</code></p>
<p><code>applianceactivation. rttCommands. sendResult</code></p></td>
</tr>
<tr class="odd">
<td>Appliance troubleshooter <sup>Beta</sup>
<p>( <code>roles/ applianceactivation.troubleshooter</code> )</p>
<p>Grants access to send new commands to run on appliances and view the outputs</p></td>
<td><p><code>applianceactivation. rttCommands. create</code></p>
<p><code>applianceactivation. rttCommands. get</code></p>
<p><code>applianceactivation. rttCommands. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Appliance Activation Service permissions

| Permission                                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `applianceactivation. rttCommands. approve`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Appliance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin) ( `roles/ applianceactivation.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Appliance troubleshooting commands approver](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver) ( `roles/ applianceactivation.approver` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             |
| `applianceactivation. rttCommands. create`     | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Appliance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin) ( `roles/ applianceactivation.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Appliance troubleshooter](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter) ( `roles/ applianceactivation.troubleshooter` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `applianceactivation. rttCommands. get`        | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Appliance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin) ( `roles/ applianceactivation.admin` ) [Appliance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer) ( `roles/ applianceactivation.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Appliance troubleshooting commands approver](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver) ( `roles/ applianceactivation.approver` ) [On-appliance troubleshooting client](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.client) ( `roles/ applianceactivation.client` ) [Appliance troubleshooter](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter) ( `roles/ applianceactivation.troubleshooter` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                               |
| `applianceactivation. rttCommands. list`       | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Appliance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin) ( `roles/ applianceactivation.admin` ) [Appliance Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer) ( `roles/ applianceactivation.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Appliance troubleshooter](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter) ( `roles/ applianceactivation.troubleshooter` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `applianceactivation. rttCommands. sendResult` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Appliance Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin) ( `roles/ applianceactivation.admin` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [On-appliance troubleshooting client](https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.client) ( `roles/ applianceactivation.client` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
