---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations
title: Recommendations roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Recommendations. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Recommendations roles

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
<td><h4 id="automlrecommendations.admin" class="role-title add-link" data-text="Recommendations AI Admin Beta" tabindex="-1">Recommendations AI Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p>Full access to all Recommendations AI resources.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  update</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  update</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  events.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  events.  get</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  events.  purge</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  events.  rejoin</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  pause</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  resume</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.update</code></p>
<p><code dir="ltr" translate="no">retail.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.operations.get</code></li>
<li><code dir="ltr" translate="no">retail.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.placements.predict</code></li>
<li><code dir="ltr" translate="no">retail.placements.search</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.products.create</code></p>
<p><code dir="ltr" translate="no">retail.products.delete</code></p>
<p><code dir="ltr" translate="no">retail.products.export</code></p>
<p><code dir="ltr" translate="no">retail.products.get</code></p>
<p><code dir="ltr" translate="no">retail.products.import</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.products.purge</code></p>
<p><code dir="ltr" translate="no">retail.products.update</code></p>
<p><code dir="ltr" translate="no">retail.retailProjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.  retailProjects.  acceptDataTerms</code></li>
<li><code dir="ltr" translate="no">retail.retailProjects.get</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.userEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.userEvents.create</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.import</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.purge</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.rejoin</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.editor" class="role-title add-link" data-text="Recommendations AI Editor Beta" tabindex="-1">Recommendations AI Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p>Editor of all Recommendations AI resources.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  pause</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  resume</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.update</code></p>
<p><code dir="ltr" translate="no">retail.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.operations.get</code></li>
<li><code dir="ltr" translate="no">retail.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.placements.predict</code></li>
<li><code dir="ltr" translate="no">retail.placements.search</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.products.create</code></p>
<p><code dir="ltr" translate="no">retail.products.delete</code></p>
<p><code dir="ltr" translate="no">retail.products.export</code></p>
<p><code dir="ltr" translate="no">retail.products.get</code></p>
<p><code dir="ltr" translate="no">retail.products.import</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.products.update</code></p>
<p><code dir="ltr" translate="no">retail.retailProjects.get</code></p>
<p><code dir="ltr" translate="no">retail.userEvents.create</code></p>
<p><code dir="ltr" translate="no">retail.userEvents.import</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.viewer" class="role-title add-link" data-text="Recommendations AI Viewer Beta" tabindex="-1">Recommendations AI Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p>Viewer of all Recommendations resources except <code dir="ltr" translate="no">apiKeys</code> . To view all resources, including <code dir="ltr" translate="no">apiKeys</code> , grant the Recommendations AI Admin Viewer role ( <code dir="ltr" translate="no">roles/automlrecommendations.adminViewer</code> ).</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.operations.get</code></li>
<li><code dir="ltr" translate="no">retail.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.placements.predict</code></li>
<li><code dir="ltr" translate="no">retail.placements.search</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.products.export</code></p>
<p><code dir="ltr" translate="no">retail.products.get</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.retailProjects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.adminViewer" class="role-title add-link" data-text="Recommendations AI Admin Viewer Beta" tabindex="-1">Recommendations AI Admin Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p>Viewer of all Recommendations AI resources.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.operations.get</code></li>
<li><code dir="ltr" translate="no">retail.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.placements.predict</code></li>
<li><code dir="ltr" translate="no">retail.placements.search</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.products.export</code></p>
<p><code dir="ltr" translate="no">retail.products.get</code></p>
<p><code dir="ltr" translate="no">retail.products.list</code></p>
<p><code dir="ltr" translate="no">retail.retailProjects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
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
<td><h4 id="automlrecommendations.serviceAgent" class="role-title add-link" data-text="Recommendations AI Service Agent" tabindex="-1">Recommendations AI Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  automlrecommendations.serviceAgent</code> )</p>
<p>Recommendations AI service uploads catalog feeds from Cloud Storage, reports results to the customer Cloud Storage bucket, writes logs to customer projects, and writes and reads Stackdriver metrics for customer projects.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">dataflow.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataflow.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.create</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.get</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.list</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.snapshot</code></li>
<li><code dir="ltr" translate="no">dataflow.jobs.updateContents</code></li>
</ul>
<p><code dir="ltr" translate="no">dataflow.messages.list</code></p>
<p><code dir="ltr" translate="no">dataflow.metrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.alerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.alerts.get</code></li>
<li><code dir="ltr" translate="no">monitoring.alerts.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.get</code></p>
<p><code dir="ltr" translate="no">monitoring.groups.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  notificationChannelDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  notificationChannels.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.services.get</code></p>
<p><code dir="ltr" translate="no">monitoring.services.list</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.get</code></p>
<p><code dir="ltr" translate="no">monitoring.slos.list</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.get</code></p>
<p><code dir="ltr" translate="no">monitoring.snoozes.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Recommendations permissions

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
<td><h4 id="automlrecommendations.apiKeys.create" class="permission-name add-link" data-text="automlrecommendations.apiKeys.create" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.apiKeys.delete" class="permission-name add-link" data-text="automlrecommendations.apiKeys.delete" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.apiKeys.list" class="permission-name add-link" data-text="automlrecommendations.apiKeys.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.catalogItems.create" class="permission-name add-link" data-text="automlrecommendations.catalogItems.create" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.catalogItems.delete" class="permission-name add-link" data-text="automlrecommendations.catalogItems.delete" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.catalogItems.get" class="permission-name add-link" data-text="automlrecommendations.catalogItems.get" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.catalogItems.list" class="permission-name add-link" data-text="automlrecommendations.catalogItems.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.catalogItems.update" class="permission-name add-link" data-text="automlrecommendations.catalogItems.update" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.catalogs.getStats" class="permission-name add-link" data-text="automlrecommendations.catalogs.getStats" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.catalogs.list" class="permission-name add-link" data-text="automlrecommendations.catalogs.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.catalogs.update" class="permission-name add-link" data-text="automlrecommendations.catalogs.update" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  catalogs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.eventStores.getStats" class="permission-name add-link" data-text="automlrecommendations.eventStores.getStats" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.eventStores.list" class="permission-name add-link" data-text="automlrecommendations.eventStores.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  eventStores.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.events.create" class="permission-name add-link" data-text="automlrecommendations.events.create" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  events.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.events.get" class="permission-name add-link" data-text="automlrecommendations.events.get" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  events.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.events.list" class="permission-name add-link" data-text="automlrecommendations.events.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.events.purge" class="permission-name add-link" data-text="automlrecommendations.events.purge" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  events.  purge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.events.rejoin" class="permission-name add-link" data-text="automlrecommendations.events.rejoin" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  events.  rejoin</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.placements.create" class="permission-name add-link" data-text="automlrecommendations.placements.create" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  placements.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.placements.delete" class="permission-name add-link" data-text="automlrecommendations.placements.delete" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  placements.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.placements.getStats" class="permission-name add-link" data-text="automlrecommendations.placements.getStats" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.placements.list" class="permission-name add-link" data-text="automlrecommendations.placements.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.recommendations.create" class="permission-name add-link" data-text="automlrecommendations.recommendations.create" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.recommendations.delete" class="permission-name add-link" data-text="automlrecommendations.recommendations.delete" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.recommendations.list" class="permission-name add-link" data-text="automlrecommendations.recommendations.list" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.viewer">Recommendations AI Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.adminViewer">Recommendations AI Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.recommendations.pause" class="permission-name add-link" data-text="automlrecommendations.recommendations.pause" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="automlrecommendations.recommendations.resume" class="permission-name add-link" data-text="automlrecommendations.recommendations.resume" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="automlrecommendations.recommendations.update" class="permission-name add-link" data-text="automlrecommendations.recommendations.update" tabindex="-1"><code dir="ltr" translate="no">automlrecommendations.  recommendations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
</tbody>
</table>
