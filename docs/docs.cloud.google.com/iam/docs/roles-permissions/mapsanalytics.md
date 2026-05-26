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
<td><h4 id="mapsanalytics.admin" class="role-title add-link" data-text="Mapsanalytics Admin Beta" tabindex="-1">Mapsanalytics Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p>Admin role for mapsanalytics</p></td>
<td><p><code dir="ltr" translate="no">mapsanalytics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">mapsanalytics.metricData.query</code></li>
<li><code dir="ltr" translate="no">mapsanalytics.  metricData.  queryMobilitySolutionsOverageData</code></li>
<li><code dir="ltr" translate="no">mapsanalytics.  metricMetadata.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="mapsanalytics.viewer" class="role-title add-link" data-text="Maps Analytics Viewer Beta" tabindex="-1">Maps Analytics Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  mapsanalytics.viewer</code> )</p>
<p>Grants read-only access to all of the Maps Analytics resources.</p></td>
<td><p><code dir="ltr" translate="no">mapsanalytics.metricData.query</code></p>
<p><code dir="ltr" translate="no">mapsanalytics.  metricMetadata.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsanalytics.mobilitySolutionsOverageViewer" class="role-title add-link" data-text="Mobility Solutions Overages Viewer Beta" tabindex="-1">Mobility Solutions Overages Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  mapsanalytics.mobilitySolutionsOverageViewer</code> )</p>
<p>Grants read-only access to Mobility Solutions Overages metric data.</p></td>
<td><p><code dir="ltr" translate="no">mapsanalytics.  metricData.  queryMobilitySolutionsOverageData</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Maps Analytics permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="mapsanalytics.metricData.query" class="permission-name add-link" data-text="mapsanalytics.metricData.query" tabindex="-1"><code dir="ltr" translate="no">mapsanalytics.metricData.query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.viewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="mapsanalytics.metricData.queryMobilitySolutionsOverageData" class="permission-name add-link" data-text="mapsanalytics.metricData.queryMobilitySolutionsOverageData" tabindex="-1"><code dir="ltr" translate="no">mapsanalytics.  metricData.  queryMobilitySolutionsOverageData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.mobilitySolutionsOverageViewer">Mobility Solutions Overages Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.mobilitySolutionsOverageViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="mapsanalytics.metricMetadata.list" class="permission-name add-link" data-text="mapsanalytics.metricMetadata.list" tabindex="-1"><code dir="ltr" translate="no">mapsanalytics.  metricMetadata.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.admin">Mapsanalytics Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/mapsanalytics#mapsanalytics.viewer">Maps Analytics Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  mapsanalytics.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
</tbody>
</table>
