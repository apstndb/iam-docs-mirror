---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/monitoring
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring
title: Cloud Monitoring roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Monitoring. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Monitoring roles

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
<td>Monitoring Admin
<p>( <code>roles/ monitoring.admin</code> )</p>
<p>Provides full access to Cloud Monitoring.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudnotifications. activities. list</code></p>
<p><code>monitoring.*</code></p>
<ul>
<li><code>monitoring. alertPolicies. create</code></li>
<li><code>monitoring. alertPolicies. createTagBinding</code></li>
<li><code>monitoring. alertPolicies. delete</code></li>
<li><code>monitoring. alertPolicies. deleteTagBinding</code></li>
<li><code>monitoring.alertPolicies.get</code></li>
<li><code>monitoring.alertPolicies.list</code></li>
<li><code>monitoring. alertPolicies. listEffectiveTags</code></li>
<li><code>monitoring. alertPolicies. listTagBindings</code></li>
<li><code>monitoring. alertPolicies. update</code></li>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
<li><code>monitoring.dashboards.create</code></li>
<li><code>monitoring. dashboards. createTagBinding</code></li>
<li><code>monitoring.dashboards.delete</code></li>
<li><code>monitoring. dashboards. deleteTagBinding</code></li>
<li><code>monitoring.dashboards.get</code></li>
<li><code>monitoring.dashboards.list</code></li>
<li><code>monitoring. dashboards. listEffectiveTags</code></li>
<li><code>monitoring. dashboards. listTagBindings</code></li>
<li><code>monitoring.dashboards.update</code></li>
<li><code>monitoring.groups.create</code></li>
<li><code>monitoring.groups.delete</code></li>
<li><code>monitoring.groups.get</code></li>
<li><code>monitoring.groups.list</code></li>
<li><code>monitoring.groups.update</code></li>
<li><code>monitoring. metricDescriptors. create</code></li>
<li><code>monitoring. metricDescriptors. delete</code></li>
<li><code>monitoring. metricDescriptors. get</code></li>
<li><code>monitoring. metricDescriptors. list</code></li>
<li><code>monitoring.metricsScopes.link</code></li>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
<li><code>monitoring. notificationChannels. create</code></li>
<li><code>monitoring. notificationChannels. delete</code></li>
<li><code>monitoring. notificationChannels. get</code></li>
<li><code>monitoring. notificationChannels. getVerificationCode</code></li>
<li><code>monitoring. notificationChannels. list</code></li>
<li><code>monitoring. notificationChannels. sendVerificationCode</code></li>
<li><code>monitoring. notificationChannels. update</code></li>
<li><code>monitoring. notificationChannels. verify</code></li>
<li><code>monitoring.services.create</code></li>
<li><code>monitoring.services.delete</code></li>
<li><code>monitoring.services.get</code></li>
<li><code>monitoring.services.list</code></li>
<li><code>monitoring.services.update</code></li>
<li><code>monitoring.slos.create</code></li>
<li><code>monitoring.slos.delete</code></li>
<li><code>monitoring.slos.get</code></li>
<li><code>monitoring.slos.list</code></li>
<li><code>monitoring.slos.update</code></li>
<li><code>monitoring.snoozes.create</code></li>
<li><code>monitoring.snoozes.get</code></li>
<li><code>monitoring.snoozes.list</code></li>
<li><code>monitoring.snoozes.update</code></li>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
<li><code>monitoring. uptimeCheckConfigs. create</code></li>
<li><code>monitoring. uptimeCheckConfigs. delete</code></li>
<li><code>monitoring. uptimeCheckConfigs. get</code></li>
<li><code>monitoring. uptimeCheckConfigs. list</code></li>
<li><code>monitoring. uptimeCheckConfigs. update</code></li>
</ul>
<p><code>opsconfigmonitoring.*</code></p>
<ul>
<li><code>opsconfigmonitoring. resourceMetadata. list</code></li>
<li><code>opsconfigmonitoring. resourceMetadata. write</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>stackdriver.*</code></p>
<ul>
<li><code>stackdriver.projects.edit</code></li>
<li><code>stackdriver.projects.get</code></li>
<li><code>stackdriver. resourceMetadata. list</code></li>
<li><code>stackdriver. resourceMetadata. write</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Editor
<p>( <code>roles/ monitoring.editor</code> )</p>
<p>Provides full access to information about all monitoring data and configurations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudnotifications. activities. list</code></p>
<p><code>monitoring.alertPolicies.*</code></p>
<ul>
<li><code>monitoring. alertPolicies. create</code></li>
<li><code>monitoring. alertPolicies. createTagBinding</code></li>
<li><code>monitoring. alertPolicies. delete</code></li>
<li><code>monitoring. alertPolicies. deleteTagBinding</code></li>
<li><code>monitoring.alertPolicies.get</code></li>
<li><code>monitoring.alertPolicies.list</code></li>
<li><code>monitoring. alertPolicies. listEffectiveTags</code></li>
<li><code>monitoring. alertPolicies. listTagBindings</code></li>
<li><code>monitoring. alertPolicies. update</code></li>
</ul>
<p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul>
<p><code>monitoring.dashboards.*</code></p>
<ul>
<li><code>monitoring.dashboards.create</code></li>
<li><code>monitoring. dashboards. createTagBinding</code></li>
<li><code>monitoring.dashboards.delete</code></li>
<li><code>monitoring. dashboards. deleteTagBinding</code></li>
<li><code>monitoring.dashboards.get</code></li>
<li><code>monitoring.dashboards.list</code></li>
<li><code>monitoring. dashboards. listEffectiveTags</code></li>
<li><code>monitoring. dashboards. listTagBindings</code></li>
<li><code>monitoring.dashboards.update</code></li>
</ul>
<p><code>monitoring.groups.*</code></p>
<ul>
<li><code>monitoring.groups.create</code></li>
<li><code>monitoring.groups.delete</code></li>
<li><code>monitoring.groups.get</code></li>
<li><code>monitoring.groups.list</code></li>
<li><code>monitoring.groups.update</code></li>
</ul>
<p><code>monitoring.metricDescriptors.*</code></p>
<ul>
<li><code>monitoring. metricDescriptors. create</code></li>
<li><code>monitoring. metricDescriptors. delete</code></li>
<li><code>monitoring. metricDescriptors. get</code></li>
<li><code>monitoring. metricDescriptors. list</code></li>
</ul>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. create</code></p>
<p><code>monitoring. notificationChannels. delete</code></p>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring. notificationChannels. sendVerificationCode</code></p>
<p><code>monitoring. notificationChannels. update</code></p>
<p><code>monitoring. notificationChannels. verify</code></p>
<p><code>monitoring.services.*</code></p>
<ul>
<li><code>monitoring.services.create</code></li>
<li><code>monitoring.services.delete</code></li>
<li><code>monitoring.services.get</code></li>
<li><code>monitoring.services.list</code></li>
<li><code>monitoring.services.update</code></li>
</ul>
<p><code>monitoring.slos.*</code></p>
<ul>
<li><code>monitoring.slos.create</code></li>
<li><code>monitoring.slos.delete</code></li>
<li><code>monitoring.slos.get</code></li>
<li><code>monitoring.slos.list</code></li>
<li><code>monitoring.slos.update</code></li>
</ul>
<p><code>monitoring.snoozes.*</code></p>
<ul>
<li><code>monitoring.snoozes.create</code></li>
<li><code>monitoring.snoozes.get</code></li>
<li><code>monitoring.snoozes.list</code></li>
<li><code>monitoring.snoozes.update</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>monitoring. uptimeCheckConfigs.*</code></p>
<ul>
<li><code>monitoring. uptimeCheckConfigs. create</code></li>
<li><code>monitoring. uptimeCheckConfigs. delete</code></li>
<li><code>monitoring. uptimeCheckConfigs. get</code></li>
<li><code>monitoring. uptimeCheckConfigs. list</code></li>
<li><code>monitoring. uptimeCheckConfigs. update</code></li>
</ul>
<p><code>opsconfigmonitoring.*</code></p>
<ul>
<li><code>opsconfigmonitoring. resourceMetadata. list</code></li>
<li><code>opsconfigmonitoring. resourceMetadata. write</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>stackdriver.*</code></p>
<ul>
<li><code>stackdriver.projects.edit</code></li>
<li><code>stackdriver.projects.get</code></li>
<li><code>stackdriver. resourceMetadata. list</code></li>
<li><code>stackdriver. resourceMetadata. write</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Monitoring Metric Writer
<p>( <code>roles/ monitoring.metricWriter</code> )</p>
<p>Provides write-only access to metrics. This provides exactly the permissions needed by the Cloud Monitoring agent and other systems that send metrics.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p></td>
</tr>
<tr class="even">
<td>Monitoring Viewer
<p>( <code>roles/ monitoring.viewer</code> )</p>
<p>Provides read-only access to get and list information about all monitoring data and configurations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudnotifications. activities. list</code></p>
<p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.get</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.get</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.get</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p></td>
</tr>
<tr class="odd">
<td>Opsconfigmonitoring Admin <sup>Beta</sup>
<p>( <code>roles/ opsconfigmonitoring.admin</code> )</p>
<p>Admin role for opsconfigmonitoring</p></td>
<td><p><code>opsconfigmonitoring.*</code></p>
<ul>
<li><code>opsconfigmonitoring. resourceMetadata. list</code></li>
<li><code>opsconfigmonitoring. resourceMetadata. write</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Opsconfigmonitoring Viewer <sup>Beta</sup>
<p>( <code>roles/ opsconfigmonitoring.viewer</code> )</p>
<p>Viewer role for opsconfigmonitoring</p></td>
<td><p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Stackdriver Admin
<p>( <code>roles/ stackdriver.admin</code> )</p>
<p>Admin role for stackdriver</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>stackdriver.*</code></p>
<ul>
<li><code>stackdriver.projects.edit</code></li>
<li><code>stackdriver.projects.get</code></li>
<li><code>stackdriver. resourceMetadata. list</code></li>
<li><code>stackdriver. resourceMetadata. write</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Stackdriver Resource Metadata Writer <sup>Beta</sup>
<p>( <code>roles/ stackdriver.resourceMetadata.writer</code> )</p>
<p>Write-only access to resource metadata. This provides exactly the permissions needed by the Stackdriver metadata agent and other systems that send metadata.</p></td>
<td><p><code>stackdriver. resourceMetadata. write</code></p></td>
</tr>
<tr class="odd">
<td>Stackdriver Viewer
<p>( <code>roles/ stackdriver.viewer</code> )</p>
<p>Viewer role for stackdriver</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p></td>
</tr>
<tr class="even">
<td>Monitoring AlertPolicy Editor
<p>( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p>Read/write access to alerting policies.</p></td>
<td><p><code>monitoring.alertPolicies.*</code></p>
<ul>
<li><code>monitoring. alertPolicies. create</code></li>
<li><code>monitoring. alertPolicies. createTagBinding</code></li>
<li><code>monitoring. alertPolicies. delete</code></li>
<li><code>monitoring. alertPolicies. deleteTagBinding</code></li>
<li><code>monitoring.alertPolicies.get</code></li>
<li><code>monitoring.alertPolicies.list</code></li>
<li><code>monitoring. alertPolicies. listEffectiveTags</code></li>
<li><code>monitoring. alertPolicies. listTagBindings</code></li>
<li><code>monitoring. alertPolicies. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Monitoring AlertPolicy Viewer
<p>( <code>roles/ monitoring.alertPolicyViewer</code> )</p>
<p>Read-only access to alerting policies.</p></td>
<td><p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>Monitoring Alert Viewer
<p>( <code>roles/ monitoring.alertViewer</code> )</p>
<p>Read access to alerts.</p></td>
<td><p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Monitoring Cloud Console Incident Editor <sup>Beta</sup>
<p>( <code>roles/ monitoring.cloudConsoleIncidentEditor</code> )</p>
<p>Read/write access to incidents from Cloud Console.</p></td>
<td><p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Cloud Console Incident Viewer <sup>Beta</sup>
<p>( <code>roles/ monitoring.cloudConsoleIncidentViewer</code> )</p>
<p>Read access to incidents from Cloud Console.</p></td>
<td><p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Monitoring Dashboard Configuration Editor
<p>( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p>Read/write access to dashboard configurations.</p></td>
<td><p><code>monitoring.dashboards.*</code></p>
<ul>
<li><code>monitoring.dashboards.create</code></li>
<li><code>monitoring. dashboards. createTagBinding</code></li>
<li><code>monitoring.dashboards.delete</code></li>
<li><code>monitoring. dashboards. deleteTagBinding</code></li>
<li><code>monitoring.dashboards.get</code></li>
<li><code>monitoring.dashboards.list</code></li>
<li><code>monitoring. dashboards. listEffectiveTags</code></li>
<li><code>monitoring. dashboards. listTagBindings</code></li>
<li><code>monitoring.dashboards.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Dashboard Configuration Viewer
<p>( <code>roles/ monitoring.dashboardViewer</code> )</p>
<p>Read-only access to dashboard configurations.</p></td>
<td><p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td>Monitoring Metrics Scopes Admin <sup>Beta</sup>
<p>( <code>roles/ monitoring.metricsScopesAdmin</code> )</p>
<p>Access to add and remove monitored projects from metrics scopes.</p></td>
<td><p><code>monitoring.metricsScopes.link</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Monitoring Metrics Scopes Viewer <sup>Beta</sup>
<p>( <code>roles/ monitoring.metricsScopesViewer</code> )</p>
<p>Read-only access to metrics scopes and their monitored projects.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Monitoring NotificationChannel Editor <sup>Beta</sup>
<p>( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p>Read/write access to notification channels.</p></td>
<td><p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. create</code></p>
<p><code>monitoring. notificationChannels. delete</code></p>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring. notificationChannels. sendVerificationCode</code></p>
<p><code>monitoring. notificationChannels. update</code></p>
<p><code>monitoring. notificationChannels. verify</code></p></td>
</tr>
<tr class="even">
<td>Monitoring NotificationChannel Viewer <sup>Beta</sup>
<p>( <code>roles/ monitoring.notificationChannelViewer</code> )</p>
<p>Read-only access to notification channels.</p></td>
<td><p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p></td>
</tr>
<tr class="odd">
<td>Monitoring Services Editor
<p>( <code>roles/ monitoring.servicesEditor</code> )</p>
<p>Read/write access to services.</p></td>
<td><p><code>monitoring.services.*</code></p>
<ul>
<li><code>monitoring.services.create</code></li>
<li><code>monitoring.services.delete</code></li>
<li><code>monitoring.services.get</code></li>
<li><code>monitoring.services.list</code></li>
<li><code>monitoring.services.update</code></li>
</ul>
<p><code>monitoring.slos.*</code></p>
<ul>
<li><code>monitoring.slos.create</code></li>
<li><code>monitoring.slos.delete</code></li>
<li><code>monitoring.slos.get</code></li>
<li><code>monitoring.slos.list</code></li>
<li><code>monitoring.slos.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Services Viewer
<p>( <code>roles/ monitoring.servicesViewer</code> )</p>
<p>Read-only access to services.</p></td>
<td><p><code>monitoring.services.get</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.get</code></p>
<p><code>monitoring.slos.list</code></p></td>
</tr>
<tr class="odd">
<td>Monitoring Snooze Editor
<p>( <code>roles/ monitoring.snoozeEditor</code> )</p></td>
<td><p><code>monitoring.snoozes.*</code></p>
<ul>
<li><code>monitoring.snoozes.create</code></li>
<li><code>monitoring.snoozes.get</code></li>
<li><code>monitoring.snoozes.list</code></li>
<li><code>monitoring.snoozes.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Snooze Viewer
<p>( <code>roles/ monitoring.snoozeViewer</code> )</p></td>
<td><p><code>monitoring.snoozes.get</code></p>
<p><code>monitoring.snoozes.list</code></p></td>
</tr>
<tr class="odd">
<td>Monitoring Uptime Check Configuration Editor <sup>Beta</sup>
<p>( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p>Read/write access to uptime check configurations.</p></td>
<td><p><code>monitoring. uptimeCheckConfigs.*</code></p>
<ul>
<li><code>monitoring. uptimeCheckConfigs. create</code></li>
<li><code>monitoring. uptimeCheckConfigs. delete</code></li>
<li><code>monitoring. uptimeCheckConfigs. get</code></li>
<li><code>monitoring. uptimeCheckConfigs. list</code></li>
<li><code>monitoring. uptimeCheckConfigs. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Monitoring Uptime Check Configuration Viewer <sup>Beta</sup>
<p>( <code>roles/ monitoring.uptimeCheckConfigViewer</code> )</p>
<p>Read-only access to uptime check configurations.</p></td>
<td><p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p></td>
</tr>
<tr class="odd">
<td>Ops Config Monitoring Resource Metadata Viewer <sup>Beta</sup>
<p>( <code>roles/ opsconfigmonitoring.resourceMetadata.viewer</code> )</p>
<p>Read-only access to resource metadata.</p></td>
<td><p><code>opsconfigmonitoring. resourceMetadata. list</code></p></td>
</tr>
<tr class="even">
<td>Ops Config Monitoring Resource Metadata Writer <sup>Beta</sup>
<p>( <code>roles/ opsconfigmonitoring.resourceMetadata.writer</code> )</p>
<p>Write-only access to resource metadata. This provides exactly the permissions needed by the Ops Config Monitoring metadata agent and other systems that send metadata.</p></td>
<td><p><code>opsconfigmonitoring. resourceMetadata. write</code></p></td>
</tr>
<tr class="odd">
<td>Stackdriver Accounts Editor
<p>( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p>Read/write access to manage Stackdriver account structure.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>stackdriver.projects.*</code></p>
<ul>
<li><code>stackdriver.projects.edit</code></li>
<li><code>stackdriver.projects.get</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Stackdriver Accounts Viewer
<p>( <code>roles/ stackdriver.accounts.viewer</code> )</p>
<p>Read-only access to get and list information about Stackdriver account structure.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>stackdriver.projects.get</code></p></td>
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
<td>Monitoring Service Agent
<p>( <code>roles/ monitoring.notificationServiceAgent</code> )</p>
<p>Grants permissions to deliver notifications directly to resources within the target project, such as delivering to Pub/Sub topics within the project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.jobs.create</code></p>
<p><code>cloudfunctions.functions.get</code></p>
<p><code>cloudtrace.traces.patch</code></p>
<p><code>logging.links.list</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring. notificationChannels. update</code></p>
<p><code>monitoring.timeSeries.list</code></p>
<p><code>observability.links.list</code></p>
<p><code>run.routes.invoke</code></p>
<p><code>servicedirectory. networks. access</code></p>
<p><code>servicedirectory. services. resolve</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Cloud Monitoring permissions

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
<td><code>monitoring. alertPolicies. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. alertPolicies. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring. alertPolicies. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. alertPolicies. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.alertPolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyViewer">Monitoring AlertPolicy Viewer</a> ( <code>roles/ monitoring.alertPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.alertPolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyViewer">Monitoring AlertPolicy Viewer</a> ( <code>roles/ monitoring.alertPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. alertPolicies. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyViewer">Monitoring AlertPolicy Viewer</a> ( <code>roles/ monitoring.alertPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. alertPolicies. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyViewer">Monitoring AlertPolicy Viewer</a> ( <code>roles/ monitoring.alertPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. alertPolicies. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertPolicyEditor">Monitoring AlertPolicy Editor</a> ( <code>roles/ monitoring.alertPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.alerts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertViewer">Monitoring Alert Viewer</a> ( <code>roles/ monitoring.alertViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.cloudConsoleIncidentEditor">Monitoring Cloud Console Incident Editor</a> ( <code>roles/ monitoring.cloudConsoleIncidentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.cloudConsoleIncidentViewer">Monitoring Cloud Console Incident Viewer</a> ( <code>roles/ monitoring.cloudConsoleIncidentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.alerts.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.alertViewer">Monitoring Alert Viewer</a> ( <code>roles/ monitoring.alertViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.cloudConsoleIncidentEditor">Monitoring Cloud Console Incident Editor</a> ( <code>roles/ monitoring.cloudConsoleIncidentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.cloudConsoleIncidentViewer">Monitoring Cloud Console Incident Viewer</a> ( <code>roles/ monitoring.cloudConsoleIncidentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.dashboards.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. dashboards. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.dashboards.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. dashboards. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.dashboards.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardViewer">Monitoring Dashboard Configuration Viewer</a> ( <code>roles/ monitoring.dashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.dashboards.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardViewer">Monitoring Dashboard Configuration Viewer</a> ( <code>roles/ monitoring.dashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. dashboards. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardViewer">Monitoring Dashboard Configuration Viewer</a> ( <code>roles/ monitoring.dashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. dashboards. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardViewer">Monitoring Dashboard Configuration Viewer</a> ( <code>roles/ monitoring.dashboardViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.dashboards.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.dashboardEditor">Monitoring Dashboard Configuration Editor</a> ( <code>roles/ monitoring.dashboardEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.groups.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.groups.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.groups.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.groups.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.groups.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. metricDescriptors. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code>roles/ container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code>roles/ rapidmigrationassessment.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. metricDescriptors. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. metricDescriptors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code>roles/ bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code>roles/ bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.viewer">Bigtable Viewer</a> ( <code>roles/ bigtable.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code>roles/ bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. metricDescriptors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code>roles/ bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code>roles/ bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.viewer">Bigtable Viewer</a> ( <code>roles/ bigtable.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code>roles/ bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code>roles/ container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code>roles/ rapidmigrationassessment.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.metricsScopes.link</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricsScopesAdmin">Monitoring Metrics Scopes Admin</a> ( <code>roles/ monitoring.metricsScopesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/observability#observability.scopesEditor">Observability Scopes Editor</a> ( <code>roles/ observability.scopesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. monitoredResourceDescriptors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. monitoredResourceDescriptors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. notificationChannelDescriptors. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelViewer">Monitoring NotificationChannel Viewer</a> ( <code>roles/ monitoring.notificationChannelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. notificationChannelDescriptors. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelViewer">Monitoring NotificationChannel Viewer</a> ( <code>roles/ monitoring.notificationChannelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. notificationChannels. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. notificationChannels. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. notificationChannels. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelViewer">Monitoring NotificationChannel Viewer</a> ( <code>roles/ monitoring.notificationChannelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.modelMonitoringServiceAgent">Vertex AI Model Monitoring Service Agent</a> ( <code>roles/ aiplatform.modelMonitoringServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. notificationChannels. getVerificationCode</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring. notificationChannels. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelViewer">Monitoring NotificationChannel Viewer</a> ( <code>roles/ monitoring.notificationChannelViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. notificationChannels. sendVerificationCode</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring. notificationChannels. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. notificationChannels. verify</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationChannelEditor">Monitoring NotificationChannel Editor</a> ( <code>roles/ monitoring.notificationChannelEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.services.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.services.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesViewer">Monitoring Services Viewer</a> ( <code>roles/ monitoring.servicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesViewer">Monitoring Services Viewer</a> ( <code>roles/ monitoring.servicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.services.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.slos.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.slos.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.slos.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesViewer">Monitoring Services Viewer</a> ( <code>roles/ monitoring.servicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.slos.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesViewer">Monitoring Services Viewer</a> ( <code>roles/ monitoring.servicesViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.slos.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.servicesEditor">Monitoring Services Editor</a> ( <code>roles/ monitoring.servicesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.snoozes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeEditor">Monitoring Snooze Editor</a> ( <code>roles/ monitoring.snoozeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>monitoring.snoozes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeEditor">Monitoring Snooze Editor</a> ( <code>roles/ monitoring.snoozeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeViewer">Monitoring Snooze Viewer</a> ( <code>roles/ monitoring.snoozeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring.snoozes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeEditor">Monitoring Snooze Editor</a> ( <code>roles/ monitoring.snoozeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeViewer">Monitoring Snooze Viewer</a> ( <code>roles/ monitoring.snoozeViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.snoozes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.snoozeEditor">Monitoring Snooze Editor</a> ( <code>roles/ monitoring.snoozeEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>monitoring.timeSeries.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code>roles/ bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.metricWriter">Monitoring Metric Writer</a> ( <code>roles/ monitoring.metricWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectAdmin">Storage Object Admin</a> ( <code>roles/ storage.objectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.objectUser">Storage Object User</a> ( <code>roles/ storage.objectUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/alloydb#alloydb.client">AlloyDB Client</a> ( <code>roles/ alloydb.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code>roles/ bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.environmentAndStorageObjectAdmin">Environment and Storage Object Administrator</a> ( <code>roles/ composer.environmentAndStorageObjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code>roles/ container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.worker">Dataflow Worker</a> ( <code>roles/ dataflow.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseapphosting#firebaseapphosting.computeRunner">Firebase App Hosting Compute Runner</a> ( <code>roles/ firebaseapphosting.computeRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReader">Cloud Spanner Database Reader</a> ( <code>roles/ spanner.databaseReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseReaderWithDataBoost">Cloud Spanner Database Reader with DataBoost</a> ( <code>roles/ spanner.databaseReaderWithDataBoost</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseUser">Cloud Spanner Database User</a> ( <code>roles/ spanner.databaseUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.graphIntelligenceUser">Cloud Spanner Database Graph Intelligence features user</a> ( <code>roles/ spanner.graphIntelligenceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storagetransfer#storagetransfer.transferAgent">Storage Transfer Agent</a> ( <code>roles/ storagetransfer.transferAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.metricsWriter">Cloud Telemetry Metrics Writer</a> ( <code>roles/ telemetry.metricsWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telemetry#telemetry.writer">Cloud Telemetry Writer</a> ( <code>roles/ telemetry.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.customCodeServiceAgent">Vertex AI Custom Code Service Agent</a> ( <code>roles/ aiplatform.customCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.extensionCustomCodeServiceAgent">Vertex AI Extension Custom Code Service Agent</a> ( <code>roles/ aiplatform.extensionCustomCodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.notebookServiceAgent">Vertex AI Notebook Service Agent</a> ( <code>roles/ aiplatform.notebookServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.reasoningEngineServiceAgent">Vertex AI Reasoning Engine Service Agent</a> ( <code>roles/ aiplatform.reasoningEngineServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.serviceAgent">Vertex AI Service Agent</a> ( <code>roles/ aiplatform.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code>roles/ anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigqueryconnection#bigqueryconnection.serviceAgent">BigQuery Connection Service Agent</a> ( <code>roles/ bigqueryconnection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.serviceAgent">Gemini for Google Cloud Service Agent</a> ( <code>roles/ cloudaicompanion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/connectors#connectors.serviceAgent">Connectors Platform Service Agent</a> ( <code>roles/ connectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocrm#dataprocrm.nodeServiceAgent">Dataproc Resource Manager Node Service Agent</a> ( <code>roles/ dataprocrm.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/file#file.serviceAgent">Cloud Filestore Service Agent</a> ( <code>roles/ file.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasetelemetry#firebasetelemetry.serviceAgent">Firebase Telemetry Service Agent</a> ( <code>roles/ firebasetelemetry.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/kuberun#kuberun.eventsDataPlaneServiceAgent">KubeRun Events Data Plane Service Agent</a> ( <code>roles/ kuberun.eventsDataPlaneServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memcache#memcache.serviceAgent">Cloud Memorystore Memcached Service Agent</a> ( <code>roles/ memcache.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/memorystore#memorystore.serviceAgent">Cloud Memorystore Service Agent</a> ( <code>roles/ memorystore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane#meshcontrolplane.serviceAgent">Mesh Managed Control Plane Service Agent</a> ( <code>roles/ meshcontrolplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#meshdataplane.serviceAgent">Mesh Data Plane Service Agent</a> ( <code>roles/ meshdataplane.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/rapidmigrationassessment#rapidmigrationassessment.serviceAgent">RMA Service Agent</a> ( <code>roles/ rapidmigrationassessment.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/redis#redis.serviceAgent">Cloud Memorystore Redis Service Agent</a> ( <code>roles/ redis.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#tpu.serviceAgent">Cloud TPU API Service Agent</a> ( <code>roles/ tpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visionai#visionai.serviceAgent">Cloud Vision AI Service Agent</a> ( <code>roles/ visionai.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring.timeSeries.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.admin">Bigtable Administrator</a> ( <code>roles/ bigtable.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.editor">Bigtable Editor</a> ( <code>roles/ bigtable.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.user">Bigtable User</a> ( <code>roles/ bigtable.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.viewer">Bigtable Viewer</a> ( <code>roles/ bigtable.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.admin">Capacityplanner Admin</a> ( <code>roles/ capacityplanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.viewer">Capacity Planner Viewer</a> ( <code>roles/ capacityplanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudquotas#cloudquotas.admin">Cloud Quotas Admin</a> ( <code>roles/ cloudquotas.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.admin">Cloud SQL Admin</a> ( <code>roles/ cloudsql.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.editor">Cloud SQL Editor</a> ( <code>roles/ cloudsql.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsql#cloudsql.viewer">Cloud SQL Viewer</a> ( <code>roles/ cloudsql.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.admin">Cloud Tasks Admin</a> ( <code>roles/ cloudtasks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.editor">Cloud Tasks Editor</a> ( <code>roles/ cloudtasks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtasks#cloudtasks.viewer">Cloud Tasks Viewer</a> ( <code>roles/ cloudtasks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code>roles/ looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.admin">reCAPTCHA Enterprise Admin</a> ( <code>roles/ recaptchaenterprise.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.editor">Recaptchaenterprise Editor</a> ( <code>roles/ recaptchaenterprise.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recaptchaenterprise#recaptchaenterprise.viewer">reCAPTCHA Enterprise Viewer</a> ( <code>roles/ recaptchaenterprise.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageAdmin">Service Usage Admin</a> ( <code>roles/ serviceusage.serviceUsageAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageConsumer">Service Usage Consumer</a> ( <code>roles/ serviceusage.serviceUsageConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceusage#serviceusage.serviceUsageViewer">Service Usage Viewer</a> ( <code>roles/ serviceusage.serviceUsageViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.admin">Cloud Spanner Admin</a> ( <code>roles/ spanner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.editor">Cloud Spanner Editor</a> ( <code>roles/ spanner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.viewer">Cloud Spanner Viewer</a> ( <code>roles/ spanner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/telcoautomation#telcoautomation.admin">Telco Automation Admin</a> ( <code>roles/ telcoautomation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.readOnlyAdmin">Apigee Read-only Admin</a> ( <code>roles/ apigee.readOnlyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigtable#bigtable.reader">Bigtable Reader</a> ( <code>roles/ bigtable.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/capacityplanner#capacityplanner.planner">Capacity Planner</a> ( <code>roles/ capacityplanner.planner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/config#config.agent">Cloud Infrastructure Manager Agent</a> ( <code>roles/ config.agent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAccount">Kubernetes Engine Default Node Service Account</a> ( <code>roles/ container.defaultNodeServiceAccount</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code>roles/ firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityAdmin">Firebase Quality Admin</a> ( <code>roles/ firebase.qualityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.qualityViewer">Firebase Quality Viewer</a> ( <code>roles/ firebase.qualityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeEditorProjectLevel">Fleet Project-level Scope Editor</a> ( <code>roles/ gkehub.scopeEditorProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.scopeViewerProjectLevel">Fleet Project-level Scope Viewer</a> ( <code>roles/ gkehub.scopeViewerProjectLevel</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsAdmin">Service Extensions Admin</a> ( <code>roles/ networkservices.serviceExtensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkservices#networkservices.serviceExtensionsViewer">Service Extensions Viewer</a> ( <code>roles/ networkservices.serviceExtensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallAdmin">Firewall Recommender Admin</a> ( <code>roles/ recommender.firewallAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.firewallViewer">Firewall Recommender Viewer</a> ( <code>roles/ recommender.firewallViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaAdmin">Quota Administrator</a> ( <code>roles/ servicemanagement.quotaAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.quotaViewer">Quota Viewer</a> ( <code>roles/ servicemanagement.quotaViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.backupAdmin">Cloud Spanner Backup Admin</a> ( <code>roles/ spanner.backupAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.databaseAdmin">Cloud Spanner Database Admin</a> ( <code>roles/ spanner.databaseAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/spanner#spanner.restoreAdmin">Cloud Spanner Restore Admin</a> ( <code>roles/ spanner.restoreAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/aiplatform#aiplatform.telemetryServiceAgent">Vertex AI Telemetry Service Agent</a> ( <code>roles/ aiplatform.telemetryServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.serviceAgent">Blockchain Node Engine Service Agent</a> ( <code>roles/ blockchainnodeengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/businessaicode#businessaicode.serviceAgent">Business AI Code Service Agent</a> ( <code>roles/ businessaicode.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.defaultNodeServiceAgent">Kubernetes Engine Default Node Service Agent</a> ( <code>roles/ container.defaultNodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.nodeServiceAgent">[Deprecated] Kubernetes Engine Node Service Agent</a> ( <code>roles/ container.nodeServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/databaseinsights#databaseinsights.serviceAgent">Database Insights Service Agent</a> ( <code>roles/ databaseinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datastream#datastream.serviceAgent">Datastream Service Agent</a> ( <code>roles/ datastream.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.serviceAgent">Workload Manager Service Agent</a> ( <code>roles/ workloadmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. uptimeCheckConfigs. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigEditor">Monitoring Uptime Check Configuration Editor</a> ( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. uptimeCheckConfigs. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigEditor">Monitoring Uptime Check Configuration Editor</a> ( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. uptimeCheckConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigEditor">Monitoring Uptime Check Configuration Editor</a> ( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigViewer">Monitoring Uptime Check Configuration Viewer</a> ( <code>roles/ monitoring.uptimeCheckConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>monitoring. uptimeCheckConfigs. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigEditor">Monitoring Uptime Check Configuration Editor</a> ( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigViewer">Monitoring Uptime Check Configuration Viewer</a> ( <code>roles/ monitoring.uptimeCheckConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>monitoring. uptimeCheckConfigs. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.uptimeCheckConfigEditor">Monitoring Uptime Check Configuration Editor</a> ( <code>roles/ monitoring.uptimeCheckConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>opsconfigmonitoring. resourceMetadata. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code>roles/ opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.viewer">Opsconfigmonitoring Viewer</a> ( <code>roles/ opsconfigmonitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.resourceMetadata.viewer">Ops Config Monitoring Resource Metadata Viewer</a> ( <code>roles/ opsconfigmonitoring.resourceMetadata.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>opsconfigmonitoring. resourceMetadata. write</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.admin">Opsconfigmonitoring Admin</a> ( <code>roles/ opsconfigmonitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.telemetryWriter">Anthos Multi-cloud Telemetry Writer</a> ( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#opsconfigmonitoring.resourceMetadata.writer">Ops Config Monitoring Resource Metadata Writer</a> ( <code>roles/ opsconfigmonitoring.resourceMetadata.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>stackdriver.projects.edit</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>stackdriver.projects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code>roles/ errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code>roles/ errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code>roles/ errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code>roles/ stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.editor">Stackdriver Accounts Editor</a> ( <code>roles/ stackdriver.accounts.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.accounts.viewer">Stackdriver Accounts Viewer</a> ( <code>roles/ stackdriver.accounts.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code>roles/ securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code>roles/ securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code>roles/ securitycenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>stackdriver. resourceMetadata. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.admin">App Topology Admin</a> ( <code>roles/ apptopology.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apptopology#apptopology.viewer">App Topology Viewer</a> ( <code>roles/ apptopology.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.admin">Discovery Engine Admin</a> ( <code>roles/ discoveryengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.viewer">Monitoring Viewer</a> ( <code>roles/ monitoring.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.viewer">Stackdriver Viewer</a> ( <code>roles/ stackdriver.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storage#storage.admin">Storage Admin</a> ( <code>roles/ storage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceAdmin">Gemini Enterprise Admin</a> ( <code>roles/ discoveryengine.agentspaceAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code>roles/ firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.mlEngineer">ML Engineer</a> ( <code>roles/ iam.mlEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.serviceAgent">Recommendations AI Service Agent</a> ( <code>roles/ automlrecommendations.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.serviceAgent">Compute Engine Service Agent</a> ( <code>roles/ compute.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datapipelines#datapipelines.serviceAgent">Datapipelines Service Agent</a> ( <code>roles/ datapipelines.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.serviceAgent">Dataproc Service Agent</a> ( <code>roles/ dataproc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.containerServiceAgent">Anthos Multi-Cloud Container Service Agent</a> ( <code>roles/ gkemulticloud.containerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/healthcare#healthcare.serviceAgent">Healthcare Service Agent</a> ( <code>roles/ healthcare.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ml#ml.serviceAgent">AI Platform Service Agent</a> ( <code>roles/ ml.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.serviceAgent">Retail Service Agent</a> ( <code>roles/ retail.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/visualinspection#visualinspection.serviceAgent">Visual Inspection AI Service Agent</a> ( <code>roles/ visualinspection.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>stackdriver. resourceMetadata. write</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.admin">Monitoring Admin</a> ( <code>roles/ monitoring.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.editor">Monitoring Editor</a> ( <code>roles/ monitoring.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.admin">Stackdriver Admin</a> ( <code>roles/ stackdriver.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#stackdriver.resourceMetadata.writer">Stackdriver Resource Metadata Writer</a> ( <code>roles/ stackdriver.resourceMetadata.writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.devOps">Dev Ops</a> ( <code>roles/ iam.devOps</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code>roles/ iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgecontainer#edgecontainer.clusterServiceAgent">Edge Container Cluster Service Agent</a> ( <code>roles/ edgecontainer.clusterServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
