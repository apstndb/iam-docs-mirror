---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer
title: Policy Analyzer roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Policy Analyzer. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Policy Analyzer roles

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
<td>Policyanalyzer Admin <sup>Beta</sup>
<p>( <code>roles/ policyanalyzer.admin</code> )</p>
<p>Admin role for policyanalyzer</p></td>
<td><p><code>policyanalyzer.*</code></p>
<ul>
<li><code>policyanalyzer. resourceAuthorizationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountKeyLastAuthenticationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountLastAuthenticationActivities. query</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Policyanalyzer Viewer <sup>Beta</sup>
<p>( <code>roles/ policyanalyzer.viewer</code> )</p>
<p>Viewer role for policyanalyzer</p></td>
<td><p><code>policyanalyzer.*</code></p>
<ul>
<li><code>policyanalyzer. resourceAuthorizationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountKeyLastAuthenticationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountLastAuthenticationActivities. query</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Activity Analysis Viewer <sup>Beta</sup>
<p>( <code>roles/ policyanalyzer.activityAnalysisViewer</code> )</p>
<p>Viewer user that can read all activity analysis.</p></td>
<td><p><code>policyanalyzer.*</code></p>
<ul>
<li><code>policyanalyzer. resourceAuthorizationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountKeyLastAuthenticationActivities. query</code></li>
<li><code>policyanalyzer. serviceAccountLastAuthenticationActivities. query</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Policy Analyzer permissions

| Permission                                                             | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `policyanalyzer. resourceAuthorizationActivities. query`               | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Policyanalyzer Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin) ( `roles/ policyanalyzer.admin` ) [Policyanalyzer Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer) ( `roles/ policyanalyzer.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Deny Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin) ( `roles/ iam.denyAdmin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Activity Analysis Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer) ( `roles/ policyanalyzer.activityAnalysisViewer` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) |
| `policyanalyzer. serviceAccountKeyLastAuthenticationActivities. query` | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Policyanalyzer Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin) ( `roles/ policyanalyzer.admin` ) [Policyanalyzer Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer) ( `roles/ policyanalyzer.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Activity Analysis Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer) ( `roles/ policyanalyzer.activityAnalysisViewer` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                     |
| `policyanalyzer. serviceAccountLastAuthenticationActivities. query`    | [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Policyanalyzer Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.admin) ( `roles/ policyanalyzer.admin` ) [Policyanalyzer Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.viewer) ( `roles/ policyanalyzer.viewer` ) [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Activity Analysis Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/policyanalyzer#policyanalyzer.activityAnalysisViewer) ( `roles/ policyanalyzer.activityAnalysisViewer` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` )                                                                                                                     |
