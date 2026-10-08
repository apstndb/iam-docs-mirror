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
<td>Database Insights Viewer
<p>( <code>roles/ databaseinsights.viewer</code> )</p>
<p>Viewer role for Database Insights data</p></td>
<td><p><code>databaseinsights. activeQueries. fetch</code></p>
<p><code>databaseinsights. activitySummary. fetch</code></p>
<p><code>databaseinsights. aggregatedEvents. query</code></p>
<p><code>databaseinsights. aggregatedStats. query</code></p>
<p><code>databaseinsights. clusterEvents. query</code></p>
<p><code>databaseinsights. databaseIssues. troubleshoot</code></p>
<p><code>databaseinsights. dbCenter. query</code></p>
<p><code>databaseinsights. dbPerformance. query</code></p>
<p><code>databaseinsights. indexRecommendations. query</code></p>
<p><code>databaseinsights. instanceEvents. query</code></p>
<p><code>databaseinsights.locations.*</code></p>
<ul>
<li><code>databaseinsights.locations.get</code></li>
<li><code>databaseinsights. locations. list</code></li>
</ul>
<p><code>databaseinsights. performanceIssues.*</code></p>
<ul>
<li><code>databaseinsights. performanceIssues. detect</code></li>
<li><code>databaseinsights. performanceIssues. investigate</code></li>
</ul>
<p><code>databaseinsights. queryMetrics. fetch</code></p>
<p><code>databaseinsights. queryStats. fetch</code></p>
<p><code>databaseinsights. queryTimeSeries. fetch</code></p>
<p><code>databaseinsights. recommendations. query</code></p>
<p><code>databaseinsights. resourceRecommendations. query</code></p>
<p><code>databaseinsights. systemMetrics. fetch</code></p>
<p><code>databaseinsights. timeSeries. query</code></p>
<p><code>databaseinsights. virtualDbxAgent. query</code></p>
<p><code>databaseinsights. waitEventStats. fetch</code></p>
<p><code>databaseinsights. waitEventTimeSeries. fetch</code></p>
<p><code>databaseinsights. workloadRecommendations. fetch</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Database Insights assistant viewer <sup>Beta</sup>
<p>( <code>roles/ databaseinsights.assistantViewer</code> )</p>
<p>Viewer role for Database Insights assistant data</p></td>
<td><p><code>databaseinsights. performanceIssues.*</code></p>
<ul>
<li><code>databaseinsights. performanceIssues. detect</code></li>
<li><code>databaseinsights. performanceIssues. investigate</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Events Service viewer
<p>( <code>roles/ databaseinsights.eventsViewer</code> )</p>
<p>Viewer role for Events Service data</p></td>
<td><p><code>databaseinsights. aggregatedEvents. query</code></p>
<p><code>databaseinsights. clusterEvents. query</code></p>
<p><code>databaseinsights. instanceEvents. query</code></p></td>
</tr>
<tr class="even">
<td>Database Insights intelligence viewer <sup>Beta</sup>
<p>( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p>Viewer role for Database Insights intelligence data</p></td>
<td><p><code>databaseinsights. databaseIssues. troubleshoot</code></p>
<p><code>databaseinsights. dbCenter. query</code></p>
<p><code>databaseinsights. dbPerformance. query</code></p>
<p><code>databaseinsights. indexRecommendations. query</code></p>
<p><code>databaseinsights. queryMetrics. fetch</code></p>
<p><code>databaseinsights. queryStats. fetch</code></p>
<p><code>databaseinsights. queryTimeSeries. fetch</code></p>
<p><code>databaseinsights. systemMetrics. fetch</code></p>
<p><code>databaseinsights. waitEventStats. fetch</code></p>
<p><code>databaseinsights. waitEventTimeSeries. fetch</code></p></td>
</tr>
<tr class="odd">
<td>Database Insights monitoring viewer
<p>( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p>Viewer role for Database Insights monitoring data</p></td>
<td><p><code>databaseinsights. activeQueries. fetch</code></p>
<p><code>databaseinsights. activitySummary. fetch</code></p>
<p><code>databaseinsights. aggregatedStats. query</code></p>
<p><code>databaseinsights.locations.*</code></p>
<ul>
<li><code>databaseinsights.locations.get</code></li>
<li><code>databaseinsights. locations. list</code></li>
</ul>
<p><code>databaseinsights. queryStats. fetch</code></p>
<p><code>databaseinsights. queryTimeSeries. fetch</code></p>
<p><code>databaseinsights. timeSeries. query</code></p>
<p><code>databaseinsights. waitEventStats. fetch</code></p>
<p><code>databaseinsights. waitEventTimeSeries. fetch</code></p>
<p><code>databaseinsights. workloadRecommendations. fetch</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Database Insights performing operations
<p>( <code>roles/ databaseinsights.operationsAdmin</code> )</p>
<p>Admin role for performing Database Insights operations</p></td>
<td><p><code>databaseinsights. activeQuery. terminate</code></p></td>
</tr>
<tr class="odd">
<td>Database Insights recommendation viewer
<p>( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p>Viewer role for Database Insights recommendation data</p></td>
<td><p><code>databaseinsights. indexRecommendations. query</code></p>
<p><code>databaseinsights.locations.*</code></p>
<ul>
<li><code>databaseinsights.locations.get</code></li>
<li><code>databaseinsights. locations. list</code></li>
</ul>
<p><code>databaseinsights. recommendations. query</code></p>
<p><code>databaseinsights. resourceRecommendations. query</code></p>
<p><code>databaseinsights. workloadRecommendations. fetch</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Database Insights virtual Dbx viewer <sup>Beta</sup>
<p>( <code>roles/ databaseinsights.virtualDbxViewer</code> )</p>
<p>Viewer role for Database Insights virtual Dbx data</p></td>
<td><p><code>databaseinsights. virtualDbxAgent. query</code></p></td>
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
<td>Database Insights Service Agent
<p>( <code>roles/ databaseinsights.serviceAgent</code> )</p>
<p>Default role for the Database Insights service agent.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>alloydb.clusters.get</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb.databases.list</code></p>
<p><code>alloydb.instances.get</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>alloydb.locations.*</code></p>
<ul>
<li><code>alloydb.locations.get</code></li>
<li><code>alloydb.locations.list</code></li>
</ul>
<p><code>alloydb.operations.get</code></p>
<p><code>alloydb.operations.list</code></p>
<p><code>alloydb. supportedDatabaseFlags. list</code></p>
<p><code>bigtable.appProfiles.list</code></p>
<p><code>bigtable.backups.list</code></p>
<p><code>bigtable.clusters.get</code></p>
<p><code>bigtable.clusters.list</code></p>
<p><code>bigtable.instances.get</code></p>
<p><code>bigtable.instances.list</code></p>
<p><code>bigtable.locations.list</code></p>
<p><code>bigtable.tables.get</code></p>
<p><code>bigtable.tables.list</code></p>
<p><code>cloudsql.backupRuns.list</code></p>
<p><code>cloudsql.databases.get</code></p>
<p><code>cloudsql.databases.list</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>cloudtrace.traces.patch</code></p>
<p><code>databasecenter. databaseGroups. list</code></p>
<p><code>databasecenter.fleetStats.list</code></p>
<p><code>databasecenter.userLabels.list</code></p>
<p><code>databasecenter.userTags.list</code></p>
<p><code>databaseinsights. databaseIssues. troubleshoot</code></p>
<p><code>databaseinsights. dbCenter. query</code></p>
<p><code>databaseinsights. dbPerformance. query</code></p>
<p><code>databaseinsights. indexRecommendations. query</code></p>
<p><code>databaseinsights. queryMetrics. fetch</code></p>
<p><code>databaseinsights. queryStats. fetch</code></p>
<p><code>databaseinsights. queryTimeSeries. fetch</code></p>
<p><code>databaseinsights. systemMetrics. fetch</code></p>
<p><code>databaseinsights. virtualDbxAgent. query</code></p>
<p><code>databaseinsights. waitEventStats. fetch</code></p>
<p><code>databaseinsights. waitEventTimeSeries. fetch</code></p>
<p><code>datastore.backupSchedules.list</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.locations.list</code></p>
<p><code>datastore.operations.get</code></p>
<p><code>datastore.operations.list</code></p>
<p><code>discoveryengine. collections. get</code></p>
<p><code>discoveryengine. dataConnectors. acquireAccessToken</code></p>
<p><code>discoveryengine. dataConnectors. get</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring.metricsScopes.link</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>serviceusage.operations.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>spanner.backupOperations.list</code></p>
<p><code>spanner. databaseOperations. list</code></p>
<p><code>spanner.databaseRoles.list</code></p>
<p><code>spanner.databases.get</code></p>
<p><code>spanner.databases.list</code></p>
<p><code>spanner.instanceConfigs.get</code></p>
<p><code>spanner.instanceConfigs.list</code></p>
<p><code>spanner. instanceOperations. list</code></p>
<p><code>spanner. instancePartitions. list</code></p>
<p><code>spanner.instances.get</code></p>
<p><code>spanner.instances.list</code></p>
<p><code>telemetry.traces.write</code></p></td>
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
<td><code>databaseinsights. activeQueries. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. activeQuery. terminate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.operationsAdmin">Database Insights performing operations</a> ( <code>roles/ databaseinsights.operationsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. activitySummary. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. aggregatedEvents. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code>roles/ databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. aggregatedStats. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. clusterEvents. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code>roles/ databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. databaseIssues. troubleshoot</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. dbCenter. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. dbPerformance. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. indexRecommendations. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. instanceEvents. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.eventsViewer">Events Service viewer</a> ( <code>roles/ databaseinsights.eventsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. performanceIssues. detect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.assistantViewer">Database Insights assistant viewer</a> ( <code>roles/ databaseinsights.assistantViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. performanceIssues. investigate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.assistantViewer">Database Insights assistant viewer</a> ( <code>roles/ databaseinsights.assistantViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. queryMetrics. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. queryStats. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. queryTimeSeries. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. recommendations. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>databaseinsights. resourceRecommendations. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. systemMetrics. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. timeSeries. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. virtualDbxAgent. query</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.virtualDbxViewer">Database Insights virtual Dbx viewer</a> ( <code>roles/ databaseinsights.virtualDbxViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. waitEventStats. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>databaseinsights. waitEventTimeSeries. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.intelligenceViewer">Database Insights intelligence viewer</a> ( <code>roles/ databaseinsights.intelligenceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>databaseinsights. workloadRecommendations. fetch</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.viewer">Database Insights Viewer</a> ( <code>roles/ databaseinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.monitoringViewer">Database Insights monitoring viewer</a> ( <code>roles/ databaseinsights.monitoringViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.recommendationViewer">Database Insights recommendation viewer</a> ( <code>roles/ databaseinsights.recommendationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
