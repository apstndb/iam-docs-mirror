---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner
title: Capacity Planner roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Capacity Planner. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Capacity Planner roles

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
<td>Capacityplanner Admin <sup>Beta</sup>
<p>( <code>roles/ capacityplanner.admin</code> )</p>
<p>Admin role for capacityplanner</p></td>
<td><p><code>capacityplanner.*</code></p>
<ul>
<li><code>capacityplanner. capacityPlans. create</code></li>
<li><code>capacityplanner. capacityPlans. delete</code></li>
<li><code>capacityplanner. capacityPlans. get</code></li>
<li><code>capacityplanner. capacityPlans. list</code></li>
<li><code>capacityplanner. capacityPlans. update</code></li>
<li><code>capacityplanner.forecasts.list</code></li>
<li><code>capacityplanner.operations.get</code></li>
<li><code>capacityplanner. planAlertInsights. list</code></li>
<li><code>capacityplanner. usageAlertInsights. list</code></li>
<li><code>capacityplanner. usageHistories. list</code></li>
<li><code>capacityplanner. usageHistories. summarize</code></li>
</ul>
<p><code>cloudquotas.quotas.get</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage. groups. listMembers</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>Capacity Planner Viewer <sup>Beta</sup>
<p>( <code>roles/ capacityplanner.viewer</code> )</p>
<p>Read-only access to Capacity Planner resources</p></td>
<td><p><code>capacityplanner. capacityPlans. get</code></p>
<p><code>capacityplanner. capacityPlans. list</code></p>
<p><code>capacityplanner.forecasts.list</code></p>
<p><code>capacityplanner.operations.get</code></p>
<p><code>capacityplanner. planAlertInsights. list</code></p>
<p><code>capacityplanner. usageAlertInsights. list</code></p>
<p><code>capacityplanner. usageHistories.*</code></p>
<ul>
<li><code>capacityplanner. usageHistories. list</code></li>
<li><code>capacityplanner. usageHistories. summarize</code></li>
</ul>
<p><code>cloudquotas.quotas.get</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage. groups. listMembers</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Capacity Planner <sup>Beta</sup>
<p>( <code>roles/ capacityplanner.planner</code> )</p>
<p>Role that enables capacity planning</p></td>
<td><p><code>capacityplanner.*</code></p>
<ul>
<li><code>capacityplanner. capacityPlans. create</code></li>
<li><code>capacityplanner. capacityPlans. delete</code></li>
<li><code>capacityplanner. capacityPlans. get</code></li>
<li><code>capacityplanner. capacityPlans. list</code></li>
<li><code>capacityplanner. capacityPlans. update</code></li>
<li><code>capacityplanner.forecasts.list</code></li>
<li><code>capacityplanner.operations.get</code></li>
<li><code>capacityplanner. planAlertInsights. list</code></li>
<li><code>capacityplanner. usageAlertInsights. list</code></li>
<li><code>capacityplanner. usageHistories. list</code></li>
<li><code>capacityplanner. usageHistories. summarize</code></li>
</ul>
<p><code>cloudquotas.quotas.get</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage. groups. listMembers</code></p>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Capacity Planner permissions

| Permission                                   | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|----------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `capacityplanner. capacityPlans. create`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `capacityplanner. capacityPlans. delete`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `capacityplanner. capacityPlans. get`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `capacityplanner. capacityPlans. list`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `capacityplanner. capacityPlans. update`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| `capacityplanner.forecasts.list`             | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `capacityplanner.operations.get`             | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `capacityplanner. planAlertInsights. list`   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `capacityplanner. usageAlertInsights. list`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `capacityplanner. usageHistories. list`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `capacityplanner. usageHistories. summarize` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Capacityplanner Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin) ( `roles/ capacityplanner.admin` ) [Capacity Planner Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer) ( `roles/ capacityplanner.viewer` ) [Capacity Planner](https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner) ( `roles/ capacityplanner.planner` ) [Cloud Hub Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator) ( `roles/ cloudhub.operator` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
