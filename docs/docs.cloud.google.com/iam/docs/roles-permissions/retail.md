---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/retail
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/retail
title: AI Commerce Search API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for AI Commerce Search API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## AI Commerce Search API roles

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
<td><h4 id="retail.admin" class="role-title add-link" data-text="Retail Admin" tabindex="-1">Retail Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p>Full access to Retail api resources.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  delete</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  purge</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  rejoin</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  pause</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  resume</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.alertConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.alertConfigs.update</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  addCatalogAttribute</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  batchRemoveCatalogAttributes</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></li>
<li><code dir="ltr" translate="no">retail.attributesConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  importCatalogAttributes</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  removeCatalogAttribute</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  replaceCatalogAttribute</code></li>
<li><code dir="ltr" translate="no">retail.  attributesConfigs.  update</code></li>
<li><code dir="ltr" translate="no">retail.branches.get</code></li>
<li><code dir="ltr" translate="no">retail.branches.list</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></li>
<li><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.get</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.import</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.list</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.update</code></li>
<li><code dir="ltr" translate="no">retail.controls.create</code></li>
<li><code dir="ltr" translate="no">retail.controls.delete</code></li>
<li><code dir="ltr" translate="no">retail.controls.export</code></li>
<li><code dir="ltr" translate="no">retail.controls.get</code></li>
<li><code dir="ltr" translate="no">retail.controls.import</code></li>
<li><code dir="ltr" translate="no">retail.controls.list</code></li>
<li><code dir="ltr" translate="no">retail.controls.update</code></li>
<li><code dir="ltr" translate="no">retail.experiments.create</code></li>
<li><code dir="ltr" translate="no">retail.experiments.delete</code></li>
<li><code dir="ltr" translate="no">retail.experiments.get</code></li>
<li><code dir="ltr" translate="no">retail.experiments.list</code></li>
<li><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></li>
<li><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></li>
<li><code dir="ltr" translate="no">retail.experiments.update</code></li>
<li><code dir="ltr" translate="no">retail.merchantConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.merchantConfigs.update</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverUpdate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorCreate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorSubmit</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorUpdate</code></li>
<li><code dir="ltr" translate="no">retail.models.create</code></li>
<li><code dir="ltr" translate="no">retail.models.delete</code></li>
<li><code dir="ltr" translate="no">retail.models.get</code></li>
<li><code dir="ltr" translate="no">retail.models.list</code></li>
<li><code dir="ltr" translate="no">retail.models.pause</code></li>
<li><code dir="ltr" translate="no">retail.models.resume</code></li>
<li><code dir="ltr" translate="no">retail.models.tune</code></li>
<li><code dir="ltr" translate="no">retail.models.update</code></li>
<li><code dir="ltr" translate="no">retail.operations.get</code></li>
<li><code dir="ltr" translate="no">retail.operations.list</code></li>
<li><code dir="ltr" translate="no">retail.placements.predict</code></li>
<li><code dir="ltr" translate="no">retail.placements.search</code></li>
<li><code dir="ltr" translate="no">retail.products.create</code></li>
<li><code dir="ltr" translate="no">retail.products.delete</code></li>
<li><code dir="ltr" translate="no">retail.products.export</code></li>
<li><code dir="ltr" translate="no">retail.products.get</code></li>
<li><code dir="ltr" translate="no">retail.products.import</code></li>
<li><code dir="ltr" translate="no">retail.products.list</code></li>
<li><code dir="ltr" translate="no">retail.products.purge</code></li>
<li><code dir="ltr" translate="no">retail.products.setSponsorship</code></li>
<li><code dir="ltr" translate="no">retail.products.update</code></li>
<li><code dir="ltr" translate="no">retail.  retailProjects.  acceptDataTerms</code></li>
<li><code dir="ltr" translate="no">retail.retailProjects.get</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.create</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.delete</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.list</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.predict</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.search</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.update</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.create</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.import</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.purge</code></li>
<li><code dir="ltr" translate="no">retail.userEvents.rejoin</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="retail.editor" class="role-title add-link" data-text="Retail Editor" tabindex="-1">Retail Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p>Full access to Retail api resources except purge, rejoin, and setSponsorship.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  apiKeys.  delete</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  catalogs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  create</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  create</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  delete</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  pause</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  resume</code></li>
<li><code dir="ltr" translate="no">automlrecommendations.  recommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.alertConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.alertConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.alertConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  addCatalogAttribute</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></p>
<p><code dir="ltr" translate="no">retail.attributesConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  importCatalogAttributes</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  replaceCatalogAttribute</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  update</code></p>
<p><code dir="ltr" translate="no">retail.branches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.branches.get</code></li>
<li><code dir="ltr" translate="no">retail.branches.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.catalogs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></li>
<li><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.get</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.import</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.list</code></li>
<li><code dir="ltr" translate="no">retail.catalogs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.controls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.controls.create</code></li>
<li><code dir="ltr" translate="no">retail.controls.delete</code></li>
<li><code dir="ltr" translate="no">retail.controls.export</code></li>
<li><code dir="ltr" translate="no">retail.controls.get</code></li>
<li><code dir="ltr" translate="no">retail.controls.import</code></li>
<li><code dir="ltr" translate="no">retail.controls.list</code></li>
<li><code dir="ltr" translate="no">retail.controls.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.experiments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.experiments.create</code></li>
<li><code dir="ltr" translate="no">retail.experiments.delete</code></li>
<li><code dir="ltr" translate="no">retail.experiments.get</code></li>
<li><code dir="ltr" translate="no">retail.experiments.list</code></li>
<li><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></li>
<li><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></li>
<li><code dir="ltr" translate="no">retail.experiments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.merchantConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.merchantConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.merchantConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.merchantControls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverUpdate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorCreate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorSubmit</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorUpdate</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.models.create</code></li>
<li><code dir="ltr" translate="no">retail.models.delete</code></li>
<li><code dir="ltr" translate="no">retail.models.get</code></li>
<li><code dir="ltr" translate="no">retail.models.list</code></li>
<li><code dir="ltr" translate="no">retail.models.pause</code></li>
<li><code dir="ltr" translate="no">retail.models.resume</code></li>
<li><code dir="ltr" translate="no">retail.models.tune</code></li>
<li><code dir="ltr" translate="no">retail.models.update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">retail.servingConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.servingConfigs.create</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.delete</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.list</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.predict</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.search</code></li>
<li><code dir="ltr" translate="no">retail.servingConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.userEvents.create</code></p>
<p><code dir="ltr" translate="no">retail.userEvents.import</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.viewer" class="role-title add-link" data-text="Retail Viewer" tabindex="-1">Retail Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p>Grants access to read all resources in Retail.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">retail.alertConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></p>
<p><code dir="ltr" translate="no">retail.attributesConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.branches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.branches.get</code></li>
<li><code dir="ltr" translate="no">retail.branches.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></p>
<p><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.get</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.controls.export</code></p>
<p><code dir="ltr" translate="no">retail.controls.get</code></p>
<p><code dir="ltr" translate="no">retail.controls.list</code></p>
<p><code dir="ltr" translate="no">retail.experiments.get</code></p>
<p><code dir="ltr" translate="no">retail.experiments.list</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></p>
<p><code dir="ltr" translate="no">retail.merchantConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.models.get</code></p>
<p><code dir="ltr" translate="no">retail.models.list</code></p>
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
<p><code dir="ltr" translate="no">retail.servingConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.list</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.predict</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.search</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantApprover" class="role-title add-link" data-text="Retail Merchant Approver Beta" tabindex="-1">Retail Merchant Approver <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p>Grants access and approval rights to MerchantControls in the merchant console.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.alertConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></p>
<p><code dir="ltr" translate="no">retail.attributesConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.branches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.branches.get</code></li>
<li><code dir="ltr" translate="no">retail.branches.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></p>
<p><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.get</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.controls.export</code></p>
<p><code dir="ltr" translate="no">retail.controls.get</code></p>
<p><code dir="ltr" translate="no">retail.controls.list</code></p>
<p><code dir="ltr" translate="no">retail.experiments.get</code></p>
<p><code dir="ltr" translate="no">retail.experiments.list</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></p>
<p><code dir="ltr" translate="no">retail.merchantConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.merchantConfigs.get</code></li>
<li><code dir="ltr" translate="no">retail.merchantConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.merchantControls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  approverUpdate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorCreate</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorDelete</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorGet</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorList</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorSubmit</code></li>
<li><code dir="ltr" translate="no">retail.  merchantControls.  creatorUpdate</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.models.get</code></p>
<p><code dir="ltr" translate="no">retail.models.list</code></p>
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
<p><code dir="ltr" translate="no">retail.servingConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.list</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.predict</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.search</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantCreator" class="role-title add-link" data-text="Retail Merchant Creator Beta" tabindex="-1">Retail Merchant Creator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p>
<p>Grants access to own MerchantControls in the merchant console.</p></td>
<td><p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  get</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogItems.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  catalogs.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  eventStores.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  events.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  getStats</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  placements.  list</code></p>
<p><code dir="ltr" translate="no">automlrecommendations.  recommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">retail.alertConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></p>
<p><code dir="ltr" translate="no">retail.attributesConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.branches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">retail.branches.get</code></li>
<li><code dir="ltr" translate="no">retail.branches.list</code></li>
</ul>
<p><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></p>
<p><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.get</code></p>
<p><code dir="ltr" translate="no">retail.catalogs.list</code></p>
<p><code dir="ltr" translate="no">retail.controls.export</code></p>
<p><code dir="ltr" translate="no">retail.controls.get</code></p>
<p><code dir="ltr" translate="no">retail.controls.list</code></p>
<p><code dir="ltr" translate="no">retail.experiments.get</code></p>
<p><code dir="ltr" translate="no">retail.experiments.list</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></p>
<p><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></p>
<p><code dir="ltr" translate="no">retail.merchantConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorCreate</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorDelete</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorGet</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorList</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorSubmit</code></p>
<p><code dir="ltr" translate="no">retail.  merchantControls.  creatorUpdate</code></p>
<p><code dir="ltr" translate="no">retail.models.get</code></p>
<p><code dir="ltr" translate="no">retail.models.list</code></p>
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
<p><code dir="ltr" translate="no">retail.servingConfigs.get</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.list</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.predict</code></p>
<p><code dir="ltr" translate="no">retail.servingConfigs.search</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p></td>
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
<td><h4 id="retail.serviceAgent" class="role-title add-link" data-text="Retail Service Agent" tabindex="-1">Retail Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  retail.serviceAgent</code> )</p>
<p>Retail service uploads product feeds and user events from Cloud Storage and BigQuery, reports results to the customer Cloud Storage bucket, writes logs to customer projects, and writes and reads Google Cloud Observability metrics for customer projects.</p>
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

## AI Commerce Search API permissions

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
<td><h4 id="retail.alertConfigs.get" class="permission-name add-link" data-text="retail.alertConfigs.get" tabindex="-1"><code dir="ltr" translate="no">retail.alertConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.alertConfigs.update" class="permission-name add-link" data-text="retail.alertConfigs.update" tabindex="-1"><code dir="ltr" translate="no">retail.alertConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.attributesConfigs.addCatalogAttribute" class="permission-name add-link" data-text="retail.attributesConfigs.addCatalogAttribute" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  addCatalogAttribute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.attributesConfigs.batchRemoveCatalogAttributes" class="permission-name add-link" data-text="retail.attributesConfigs.batchRemoveCatalogAttributes" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  batchRemoveCatalogAttributes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.attributesConfigs.exportCatalogAttributes" class="permission-name add-link" data-text="retail.attributesConfigs.exportCatalogAttributes" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  exportCatalogAttributes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.attributesConfigs.get" class="permission-name add-link" data-text="retail.attributesConfigs.get" tabindex="-1"><code dir="ltr" translate="no">retail.attributesConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.attributesConfigs.importCatalogAttributes" class="permission-name add-link" data-text="retail.attributesConfigs.importCatalogAttributes" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  importCatalogAttributes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.attributesConfigs.removeCatalogAttribute" class="permission-name add-link" data-text="retail.attributesConfigs.removeCatalogAttribute" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  removeCatalogAttribute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.attributesConfigs.replaceCatalogAttribute" class="permission-name add-link" data-text="retail.attributesConfigs.replaceCatalogAttribute" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  replaceCatalogAttribute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.attributesConfigs.update" class="permission-name add-link" data-text="retail.attributesConfigs.update" tabindex="-1"><code dir="ltr" translate="no">retail.  attributesConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.branches.get" class="permission-name add-link" data-text="retail.branches.get" tabindex="-1"><code dir="ltr" translate="no">retail.branches.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.branches.list" class="permission-name add-link" data-text="retail.branches.list" tabindex="-1"><code dir="ltr" translate="no">retail.branches.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.catalogs.completeQuery" class="permission-name add-link" data-text="retail.catalogs.completeQuery" tabindex="-1"><code dir="ltr" translate="no">retail.catalogs.completeQuery</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.catalogs.exportAnalyticsMetrics" class="permission-name add-link" data-text="retail.catalogs.exportAnalyticsMetrics" tabindex="-1"><code dir="ltr" translate="no">retail.  catalogs.  exportAnalyticsMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.catalogs.get" class="permission-name add-link" data-text="retail.catalogs.get" tabindex="-1"><code dir="ltr" translate="no">retail.catalogs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.catalogs.import" class="permission-name add-link" data-text="retail.catalogs.import" tabindex="-1"><code dir="ltr" translate="no">retail.catalogs.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.catalogs.list" class="permission-name add-link" data-text="retail.catalogs.list" tabindex="-1"><code dir="ltr" translate="no">retail.catalogs.list</code></h4></td>
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
<td><h4 id="retail.catalogs.update" class="permission-name add-link" data-text="retail.catalogs.update" tabindex="-1"><code dir="ltr" translate="no">retail.catalogs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.controls.create" class="permission-name add-link" data-text="retail.controls.create" tabindex="-1"><code dir="ltr" translate="no">retail.controls.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.controls.delete" class="permission-name add-link" data-text="retail.controls.delete" tabindex="-1"><code dir="ltr" translate="no">retail.controls.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.controls.export" class="permission-name add-link" data-text="retail.controls.export" tabindex="-1"><code dir="ltr" translate="no">retail.controls.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.controls.get" class="permission-name add-link" data-text="retail.controls.get" tabindex="-1"><code dir="ltr" translate="no">retail.controls.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.controls.import" class="permission-name add-link" data-text="retail.controls.import" tabindex="-1"><code dir="ltr" translate="no">retail.controls.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.controls.list" class="permission-name add-link" data-text="retail.controls.list" tabindex="-1"><code dir="ltr" translate="no">retail.controls.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.controls.update" class="permission-name add-link" data-text="retail.controls.update" tabindex="-1"><code dir="ltr" translate="no">retail.controls.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.experiments.create" class="permission-name add-link" data-text="retail.experiments.create" tabindex="-1"><code dir="ltr" translate="no">retail.experiments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.experiments.delete" class="permission-name add-link" data-text="retail.experiments.delete" tabindex="-1"><code dir="ltr" translate="no">retail.experiments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.experiments.get" class="permission-name add-link" data-text="retail.experiments.get" tabindex="-1"><code dir="ltr" translate="no">retail.experiments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.experiments.list" class="permission-name add-link" data-text="retail.experiments.list" tabindex="-1"><code dir="ltr" translate="no">retail.experiments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.experiments.loadExperimentLookerDashboard" class="permission-name add-link" data-text="retail.experiments.loadExperimentLookerDashboard" tabindex="-1"><code dir="ltr" translate="no">retail.  experiments.  loadExperimentLookerDashboard</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.experiments.queryTrafficMetrics" class="permission-name add-link" data-text="retail.experiments.queryTrafficMetrics" tabindex="-1"><code dir="ltr" translate="no">retail.  experiments.  queryTrafficMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.experiments.update" class="permission-name add-link" data-text="retail.experiments.update" tabindex="-1"><code dir="ltr" translate="no">retail.experiments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantConfigs.get" class="permission-name add-link" data-text="retail.merchantConfigs.get" tabindex="-1"><code dir="ltr" translate="no">retail.merchantConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantConfigs.update" class="permission-name add-link" data-text="retail.merchantConfigs.update" tabindex="-1"><code dir="ltr" translate="no">retail.merchantConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantControls.approverDelete" class="permission-name add-link" data-text="retail.merchantControls.approverDelete" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  approverDelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantControls.approverGet" class="permission-name add-link" data-text="retail.merchantControls.approverGet" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  approverGet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantControls.approverList" class="permission-name add-link" data-text="retail.merchantControls.approverList" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  approverList</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantControls.approverUpdate" class="permission-name add-link" data-text="retail.merchantControls.approverUpdate" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  approverUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantControls.creatorCreate" class="permission-name add-link" data-text="retail.merchantControls.creatorCreate" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorCreate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantControls.creatorDelete" class="permission-name add-link" data-text="retail.merchantControls.creatorDelete" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorDelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantControls.creatorGet" class="permission-name add-link" data-text="retail.merchantControls.creatorGet" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorGet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantControls.creatorList" class="permission-name add-link" data-text="retail.merchantControls.creatorList" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorList</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.merchantControls.creatorSubmit" class="permission-name add-link" data-text="retail.merchantControls.creatorSubmit" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorSubmit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.merchantControls.creatorUpdate" class="permission-name add-link" data-text="retail.merchantControls.creatorUpdate" tabindex="-1"><code dir="ltr" translate="no">retail.  merchantControls.  creatorUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.models.create" class="permission-name add-link" data-text="retail.models.create" tabindex="-1"><code dir="ltr" translate="no">retail.models.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.models.delete" class="permission-name add-link" data-text="retail.models.delete" tabindex="-1"><code dir="ltr" translate="no">retail.models.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.models.get" class="permission-name add-link" data-text="retail.models.get" tabindex="-1"><code dir="ltr" translate="no">retail.models.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.models.list" class="permission-name add-link" data-text="retail.models.list" tabindex="-1"><code dir="ltr" translate="no">retail.models.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.models.pause" class="permission-name add-link" data-text="retail.models.pause" tabindex="-1"><code dir="ltr" translate="no">retail.models.pause</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.models.resume" class="permission-name add-link" data-text="retail.models.resume" tabindex="-1"><code dir="ltr" translate="no">retail.models.resume</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.models.tune" class="permission-name add-link" data-text="retail.models.tune" tabindex="-1"><code dir="ltr" translate="no">retail.models.tune</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.models.update" class="permission-name add-link" data-text="retail.models.update" tabindex="-1"><code dir="ltr" translate="no">retail.models.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.operations.get" class="permission-name add-link" data-text="retail.operations.get" tabindex="-1"><code dir="ltr" translate="no">retail.operations.get</code></h4></td>
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
<td><h4 id="retail.operations.list" class="permission-name add-link" data-text="retail.operations.list" tabindex="-1"><code dir="ltr" translate="no">retail.operations.list</code></h4></td>
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
<td><h4 id="retail.placements.predict" class="permission-name add-link" data-text="retail.placements.predict" tabindex="-1"><code dir="ltr" translate="no">retail.placements.predict</code></h4></td>
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
<td><h4 id="retail.placements.search" class="permission-name add-link" data-text="retail.placements.search" tabindex="-1"><code dir="ltr" translate="no">retail.placements.search</code></h4></td>
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
<td><h4 id="retail.products.create" class="permission-name add-link" data-text="retail.products.create" tabindex="-1"><code dir="ltr" translate="no">retail.products.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.products.delete" class="permission-name add-link" data-text="retail.products.delete" tabindex="-1"><code dir="ltr" translate="no">retail.products.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.products.export" class="permission-name add-link" data-text="retail.products.export" tabindex="-1"><code dir="ltr" translate="no">retail.products.export</code></h4></td>
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
<td><h4 id="retail.products.get" class="permission-name add-link" data-text="retail.products.get" tabindex="-1"><code dir="ltr" translate="no">retail.products.get</code></h4></td>
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
<td><h4 id="retail.products.import" class="permission-name add-link" data-text="retail.products.import" tabindex="-1"><code dir="ltr" translate="no">retail.products.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.products.list" class="permission-name add-link" data-text="retail.products.list" tabindex="-1"><code dir="ltr" translate="no">retail.products.list</code></h4></td>
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
<td><h4 id="retail.products.purge" class="permission-name add-link" data-text="retail.products.purge" tabindex="-1"><code dir="ltr" translate="no">retail.products.purge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.products.setSponsorship" class="permission-name add-link" data-text="retail.products.setSponsorship" tabindex="-1"><code dir="ltr" translate="no">retail.products.setSponsorship</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.products.update" class="permission-name add-link" data-text="retail.products.update" tabindex="-1"><code dir="ltr" translate="no">retail.products.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.retailProjects.acceptDataTerms" class="permission-name add-link" data-text="retail.retailProjects.acceptDataTerms" tabindex="-1"><code dir="ltr" translate="no">retail.  retailProjects.  acceptDataTerms</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.retailProjects.get" class="permission-name add-link" data-text="retail.retailProjects.get" tabindex="-1"><code dir="ltr" translate="no">retail.retailProjects.get</code></h4></td>
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
<td><h4 id="retail.servingConfigs.create" class="permission-name add-link" data-text="retail.servingConfigs.create" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.servingConfigs.delete" class="permission-name add-link" data-text="retail.servingConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.servingConfigs.get" class="permission-name add-link" data-text="retail.servingConfigs.get" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.servingConfigs.list" class="permission-name add-link" data-text="retail.servingConfigs.list" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.servingConfigs.predict" class="permission-name add-link" data-text="retail.servingConfigs.predict" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.predict</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.servingConfigs.search" class="permission-name add-link" data-text="retail.servingConfigs.search" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.viewer">Retail Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantApprover">Retail Merchant Approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantApprover</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.merchantCreator">Retail Merchant Creator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.merchantCreator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.servingConfigs.update" class="permission-name add-link" data-text="retail.servingConfigs.update" tabindex="-1"><code dir="ltr" translate="no">retail.servingConfigs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.userEvents.create" class="permission-name add-link" data-text="retail.userEvents.create" tabindex="-1"><code dir="ltr" translate="no">retail.userEvents.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.userEvents.import" class="permission-name add-link" data-text="retail.userEvents.import" tabindex="-1"><code dir="ltr" translate="no">retail.userEvents.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.editor">Recommendations AI Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.editor">Retail Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="retail.userEvents.purge" class="permission-name add-link" data-text="retail.userEvents.purge" tabindex="-1"><code dir="ltr" translate="no">retail.userEvents.purge</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="retail.userEvents.rejoin" class="permission-name add-link" data-text="retail.userEvents.rejoin" tabindex="-1"><code dir="ltr" translate="no">retail.userEvents.rejoin</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/automlrecommendations#automlrecommendations.admin">Recommendations AI Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  automlrecommendations.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/retail#retail.admin">Retail Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  retail.admin</code> )</p></td>
</tr>
</tbody>
</table>
