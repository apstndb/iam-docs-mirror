---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics
title: Maps Analytics roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Maps Analytics. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Maps Analytics roles

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
<td>Mapsanalytics Admin <sup>Beta</sup>
<p>( <code>roles/ mapsanalytics.admin</code> )</p>
<p>Admin role for mapsanalytics</p></td>
<td><p><code>mapsanalytics.*</code></p>
<ul>
<li><code>mapsanalytics.metricData.query</code></li>
<li><code>mapsanalytics. metricData. queryMobilitySolutionsOverageData</code></li>
<li><code>mapsanalytics. metricMetadata. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Maps Analytics Viewer <sup>Beta</sup>
<p>( <code>roles/ mapsanalytics.viewer</code> )</p>
<p>Grants read-only access to all of the Maps Analytics resources.</p></td>
<td><p><code>mapsanalytics.metricData.query</code></p>
<p><code>mapsanalytics. metricMetadata. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage. groups. listMembers</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td>Mobility Solutions Overages Viewer <sup>Beta</sup>
<p>( <code>roles/ mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p>Grants read-only access to Mobility Solutions Overages metric data.</p></td>
<td><p><code>mapsanalytics. metricData. queryMobilitySolutionsOverageData</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.list</code></p>
<p><code>serviceusage. groups. listMembers</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Maps Analytics permissions

| Permission                                                     | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|----------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `mapsanalytics.metricData.query`                               | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Mapsanalytics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin) ( `roles/ mapsanalytics.admin` ) [Maps Analytics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer) ( `roles/ mapsanalytics.viewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `mapsanalytics. metricData. queryMobilitySolutionsOverageData` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Mapsanalytics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin) ( `roles/ mapsanalytics.admin` ) [Mobility Solutions Overages Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer) ( `roles/ mapsanalytics.mobilitySolutionsOverageViewer` )                                                                                                                                                                                                                                                                                                                                                            |
| `mapsanalytics. metricMetadata. list`                          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Mapsanalytics Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin) ( `roles/ mapsanalytics.admin` ) [Maps Analytics Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer) ( `roles/ mapsanalytics.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) |
