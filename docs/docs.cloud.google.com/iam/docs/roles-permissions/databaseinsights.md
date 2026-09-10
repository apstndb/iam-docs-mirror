---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights
title: Database Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Database Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Database Insights roles

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
<td><h4 id="databaseinsights.admin" class="role-title add-link" data-text="Database Insights Admin" tabindex="-1">Database Insights Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p>Admin role for Database Insights</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.  activeQueries.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  activeQuery.  terminate</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  activitySummary.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  aggregatedEvents.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  aggregatedStats.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  clusterEvents.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  databaseIssues.  troubleshoot</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  dbCenter.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  dbPerformance.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  indexRecommendations.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  instanceEvents.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  detect</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  investigate</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  queryMetrics.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  queryStats.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  queryTimeSeries.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  recommendations.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  resourceRecommendations.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  systemMetrics.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  timeSeries.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  virtualDbxAgent.  query</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  waitEventStats.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  waitEventTimeSeries.  fetch</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  workloadRecommendations.  fetch</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.viewer" class="role-title add-link" data-text="Database Insights viewer" tabindex="-1">Database Insights viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p>Viewer role for Database Insights data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  activeQueries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  activitySummary.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  aggregatedStats.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  databaseIssues.  troubleshoot</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  dbCenter.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  dbPerformance.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  indexRecommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databaseinsights.  performanceIssues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  detect</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  investigate</code></li>
</ul>
<p><code dir="ltr" translate="no">databaseinsights.  queryMetrics.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryTimeSeries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  recommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  resourceRecommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  systemMetrics.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  timeSeries.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  virtualDbxAgent.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventTimeSeries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  workloadRecommendations.  fetch</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.assistantViewer" class="role-title add-link" data-text="Database Insights assistant viewer Beta" tabindex="-1">Database Insights assistant viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.assistantViewer</code> )</p>
<p>Viewer role for Database Insights assistant data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  performanceIssues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  detect</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  investigate</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.eventsViewer" class="role-title add-link" data-text="Events Service viewer" tabindex="-1">Events Service viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.eventsViewer</code> )</p>
<p>Viewer role for Events Service data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  aggregatedEvents.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  clusterEvents.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  instanceEvents.  query</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.intelligenceViewer" class="role-title add-link" data-text="Database Insights intelligence viewer Beta" tabindex="-1">Database Insights intelligence viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p>Viewer role for Database Insights intelligence data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  databaseIssues.  troubleshoot</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  dbCenter.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  dbPerformance.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  indexRecommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryMetrics.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryTimeSeries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  systemMetrics.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventTimeSeries.  fetch</code></p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.monitoringViewer" class="role-title add-link" data-text="Database Insights monitoring viewer" tabindex="-1">Database Insights monitoring viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p>Viewer role for Database Insights monitoring data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  activeQueries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  activitySummary.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  aggregatedStats.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databaseinsights.  queryStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  queryTimeSeries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  timeSeries.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventStats.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  waitEventTimeSeries.  fetch</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  workloadRecommendations.  fetch</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.operationsAdmin" class="role-title add-link" data-text="Database Insights performing operations" tabindex="-1">Database Insights performing operations</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.operationsAdmin</code> )</p>
<p>Admin role for performing Database Insights operations</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  activeQuery.  terminate</code></p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.recommendationViewer" class="role-title add-link" data-text="Database Insights recommendation viewer" tabindex="-1">Database Insights recommendation viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p>Viewer role for Database Insights recommendation data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  indexRecommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databaseinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databaseinsights.  recommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  resourceRecommendations.  query</code></p>
<p><code dir="ltr" translate="no">databaseinsights.  workloadRecommendations.  fetch</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.virtualDbxViewer" class="role-title add-link" data-text="Database Insights virtual Dbx viewer Beta" tabindex="-1">Database Insights virtual Dbx viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  databaseinsights.virtualDbxViewer</code> )</p>
<p>Viewer role for Database Insights virtual Dbx data</p></td>
<td><p><code dir="ltr" translate="no">databaseinsights.  virtualDbxAgent.  query</code></p></td>
</tr>
</tbody>
</table>

## Database Insights permissions

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
<td><h4 id="databaseinsights.activeQueries.fetch" class="permission-name add-link" data-text="databaseinsights.activeQueries.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  activeQueries.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.activeQuery.terminate" class="permission-name add-link" data-text="databaseinsights.activeQuery.terminate" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  activeQuery.  terminate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.operationsAdmin">Database Insights performing operations</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.operationsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.activitySummary.fetch" class="permission-name add-link" data-text="databaseinsights.activitySummary.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  activitySummary.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.aggregatedEvents.query" class="permission-name add-link" data-text="databaseinsights.aggregatedEvents.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  aggregatedEvents.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.aggregatedStats.query" class="permission-name add-link" data-text="databaseinsights.aggregatedStats.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  aggregatedStats.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.clusterEvents.query" class="permission-name add-link" data-text="databaseinsights.clusterEvents.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  clusterEvents.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.databaseIssues.troubleshoot" class="permission-name add-link" data-text="databaseinsights.databaseIssues.troubleshoot" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  databaseIssues.  troubleshoot</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.dbCenter.query" class="permission-name add-link" data-text="databaseinsights.dbCenter.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  dbCenter.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.dbPerformance.query" class="permission-name add-link" data-text="databaseinsights.dbPerformance.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  dbPerformance.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.indexRecommendations.query" class="permission-name add-link" data-text="databaseinsights.indexRecommendations.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  indexRecommendations.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.instanceEvents.query" class="permission-name add-link" data-text="databaseinsights.instanceEvents.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  instanceEvents.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.locations.get" class="permission-name add-link" data-text="databaseinsights.locations.get" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.locations.list" class="permission-name add-link" data-text="databaseinsights.locations.list" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.performanceIssues.detect" class="permission-name add-link" data-text="databaseinsights.performanceIssues.detect" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  detect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.assistantViewer">Database Insights assistant viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.assistantViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.performanceIssues.investigate" class="permission-name add-link" data-text="databaseinsights.performanceIssues.investigate" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  performanceIssues.  investigate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.assistantViewer">Database Insights assistant viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.assistantViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.queryMetrics.fetch" class="permission-name add-link" data-text="databaseinsights.queryMetrics.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  queryMetrics.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.queryStats.fetch" class="permission-name add-link" data-text="databaseinsights.queryStats.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  queryStats.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.queryTimeSeries.fetch" class="permission-name add-link" data-text="databaseinsights.queryTimeSeries.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  queryTimeSeries.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.recommendations.query" class="permission-name add-link" data-text="databaseinsights.recommendations.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  recommendations.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.resourceRecommendations.query" class="permission-name add-link" data-text="databaseinsights.resourceRecommendations.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  resourceRecommendations.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.systemMetrics.fetch" class="permission-name add-link" data-text="databaseinsights.systemMetrics.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  systemMetrics.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.timeSeries.query" class="permission-name add-link" data-text="databaseinsights.timeSeries.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  timeSeries.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.virtualDbxAgent.query" class="permission-name add-link" data-text="databaseinsights.virtualDbxAgent.query" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  virtualDbxAgent.  query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.virtualDbxViewer">Database Insights virtual Dbx viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.virtualDbxViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.waitEventStats.fetch" class="permission-name add-link" data-text="databaseinsights.waitEventStats.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  waitEventStats.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="databaseinsights.waitEventTimeSeries.fetch" class="permission-name add-link" data-text="databaseinsights.waitEventTimeSeries.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  waitEventTimeSeries.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="databaseinsights.workloadRecommendations.fetch" class="permission-name add-link" data-text="databaseinsights.workloadRecommendations.fetch" tabindex="-1"><code dir="ltr" translate="no">databaseinsights.  workloadRecommendations.  fetch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.admin">Database Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
