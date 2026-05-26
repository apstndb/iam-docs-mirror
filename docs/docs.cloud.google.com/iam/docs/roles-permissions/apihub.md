---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/apihub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/apihub
title: API Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for API Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## API Hub roles

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
<td><h4 id="apihub.admin" class="role-title add-link" data-text="Cloud API Hub Admin" tabindex="-1">Cloud API Hub Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p>Full access to all API hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apigee.  projectorganizations.  get</code></p>
<p><code dir="ltr" translate="no">apihub.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.addons.get</code></li>
<li><code dir="ltr" translate="no">apihub.addons.list</code></li>
<li><code dir="ltr" translate="no">apihub.addons.manage</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.create</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.update</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.create</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.get</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.list</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.update</code></li>
<li><code dir="ltr" translate="no">apihub.apis.create</code></li>
<li><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.apis.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.apis.get</code></li>
<li><code dir="ltr" translate="no">apihub.apis.list</code></li>
<li><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></li>
<li><code dir="ltr" translate="no">apihub.apis.update</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.create</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.delete</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.get</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.list</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.update</code></li>
<li><code dir="ltr" translate="no">apihub.curations.create</code></li>
<li><code dir="ltr" translate="no">apihub.curations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.curations.get</code></li>
<li><code dir="ltr" translate="no">apihub.curations.list</code></li>
<li><code dir="ltr" translate="no">apihub.curations.update</code></li>
<li><code dir="ltr" translate="no">apihub.definitions.get</code></li>
<li><code dir="ltr" translate="no">apihub.definitions.list</code></li>
<li><code dir="ltr" translate="no">apihub.definitions.update</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.create</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.delete</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.get</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.list</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.update</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.create</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.delete</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.get</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.list</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.update</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.create</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.delete</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.get</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.list</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.update</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  create</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  delete</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  register</code></li>
<li><code dir="ltr" translate="no">apihub.  llmEnablements.  deregister</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.get</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.list</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.register</code></li>
<li><code dir="ltr" translate="no">apihub.  locations.  collectApiData</code></li>
<li><code dir="ltr" translate="no">apihub.  locations.  getApiInsights</code></li>
<li><code dir="ltr" translate="no">apihub.  locations.  searchResources</code></li>
<li><code dir="ltr" translate="no">apihub.  locations2.  searchResources</code></li>
<li><code dir="ltr" translate="no">apihub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apihub.operations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.operations.get</code></li>
<li><code dir="ltr" translate="no">apihub.operations.list</code></li>
<li><code dir="ltr" translate="no">apihub.  plugininstances.  applyConfig</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.create</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.delete</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.disable</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.enable</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.execute</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.get</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.list</code></li>
<li><code dir="ltr" translate="no">apihub.  plugininstances.  managePluginInstanceSourceData</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.update</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.create</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.delete</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.disable</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.enable</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.get</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.list</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  attach</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  lookup</code></li>
<li><code dir="ltr" translate="no">apihub.specs.create</code></li>
<li><code dir="ltr" translate="no">apihub.specs.delete</code></li>
<li><code dir="ltr" translate="no">apihub.specs.get</code></li>
<li><code dir="ltr" translate="no">apihub.specs.lint</code></li>
<li><code dir="ltr" translate="no">apihub.specs.list</code></li>
<li><code dir="ltr" translate="no">apihub.specs.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.specs.update</code></li>
<li><code dir="ltr" translate="no">apihub.styleGuides.get</code></li>
<li><code dir="ltr" translate="no">apihub.styleGuides.update</code></li>
<li><code dir="ltr" translate="no">apihub.versions.create</code></li>
<li><code dir="ltr" translate="no">apihub.versions.delete</code></li>
<li><code dir="ltr" translate="no">apihub.versions.get</code></li>
<li><code dir="ltr" translate="no">apihub.versions.list</code></li>
<li><code dir="ltr" translate="no">apihub.versions.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.versions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.editor" class="role-title add-link" data-text="Cloud API Hub Editor" tabindex="-1">Cloud API Hub Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Edit access to most of Cloud API Hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.addons.get</code></p>
<p><code dir="ltr" translate="no">apihub.addons.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.apiOperations.create</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.get</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.list</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.apiOperations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.apis.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.apis.create</code></li>
<li><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.apis.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.apis.get</code></li>
<li><code dir="ltr" translate="no">apihub.apis.list</code></li>
<li><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></li>
<li><code dir="ltr" translate="no">apihub.apis.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.attributes.get</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.list</code></p>
<p><code dir="ltr" translate="no">apihub.curations.get</code></p>
<p><code dir="ltr" translate="no">apihub.curations.list</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.definitions.get</code></li>
<li><code dir="ltr" translate="no">apihub.definitions.list</code></li>
<li><code dir="ltr" translate="no">apihub.definitions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.dependencies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.dependencies.create</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.delete</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.get</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.list</code></li>
<li><code dir="ltr" translate="no">apihub.dependencies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.deployments.create</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.delete</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.get</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.list</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">apihub.deployments.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  discoveredApiObservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  discoveredApiOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.externalApis.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.externalApis.create</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.delete</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.get</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.list</code></li>
<li><code dir="ltr" translate="no">apihub.externalApis.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  get</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.llmEnablements.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  llmEnablements.  deregister</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.get</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.list</code></li>
<li><code dir="ltr" translate="no">apihub.llmEnablements.register</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  locations.  collectApiData</code></p>
<p><code dir="ltr" translate="no">apihub.  locations.  searchResources</code></p>
<p><code dir="ltr" translate="no">apihub.operations.get</code></p>
<p><code dir="ltr" translate="no">apihub.operations.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.get</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.list</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.specs.create</code></li>
<li><code dir="ltr" translate="no">apihub.specs.delete</code></li>
<li><code dir="ltr" translate="no">apihub.specs.get</code></li>
<li><code dir="ltr" translate="no">apihub.specs.lint</code></li>
<li><code dir="ltr" translate="no">apihub.specs.list</code></li>
<li><code dir="ltr" translate="no">apihub.specs.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.specs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.styleGuides.get</code></p>
<p><code dir="ltr" translate="no">apihub.versions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.versions.create</code></li>
<li><code dir="ltr" translate="no">apihub.versions.delete</code></li>
<li><code dir="ltr" translate="no">apihub.versions.get</code></li>
<li><code dir="ltr" translate="no">apihub.versions.list</code></li>
<li><code dir="ltr" translate="no">apihub.versions.listAll</code></li>
<li><code dir="ltr" translate="no">apihub.versions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.viewer" class="role-title add-link" data-text="Cloud API Hub Viewer" tabindex="-1">Cloud API Hub Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p>View access to all Cloud API hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.addons.get</code></p>
<p><code dir="ltr" translate="no">apihub.addons.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.get</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.listAll</code></p>
<p><code dir="ltr" translate="no">apihub.apis.get</code></p>
<p><code dir="ltr" translate="no">apihub.apis.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.get</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.list</code></p>
<p><code dir="ltr" translate="no">apihub.curations.get</code></p>
<p><code dir="ltr" translate="no">apihub.curations.list</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.get</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.list</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.get</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.get</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.list</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.  discoveredApiObservations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  discoveredApiOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.externalApis.get</code></p>
<p><code dir="ltr" translate="no">apihub.externalApis.list</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  get</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.llmEnablements.get</code></p>
<p><code dir="ltr" translate="no">apihub.llmEnablements.list</code></p>
<p><code dir="ltr" translate="no">apihub.  locations.  searchResources</code></p>
<p><code dir="ltr" translate="no">apihub.operations.get</code></p>
<p><code dir="ltr" translate="no">apihub.operations.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.get</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.list</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.get</code></p>
<p><code dir="ltr" translate="no">apihub.specs.list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.listAll</code></p>
<p><code dir="ltr" translate="no">apihub.styleGuides.get</code></p>
<p><code dir="ltr" translate="no">apihub.versions.get</code></p>
<p><code dir="ltr" translate="no">apihub.versions.list</code></p>
<p><code dir="ltr" translate="no">apihub.versions.listAll</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.addonsAdmin" class="role-title add-link" data-text="Cloud API hub Addons Admin" tabindex="-1">Cloud API hub Addons Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p>
<p>Full access to all Cloud API hub addon resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.addons.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.addons.get</code></li>
<li><code dir="ltr" translate="no">apihub.addons.list</code></li>
<li><code dir="ltr" translate="no">apihub.addons.manage</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiInsightsViewer" class="role-title add-link" data-text="Cloud API hub Insights Viewer" tabindex="-1">Cloud API hub Insights Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p>View API hub insights dashboards.</p></td>
<td><p><code dir="ltr" translate="no">apigee.  projectorganizations.  get</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.get</code></p>
<p><code dir="ltr" translate="no">apihub.apis.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.get</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.list</code></p>
<p><code dir="ltr" translate="no">apihub.  locations.  getApiInsights</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.get</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.get</code></p>
<p><code dir="ltr" translate="no">monitoring.dashboards.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.attributeAdmin" class="role-title add-link" data-text="Cloud API hub Attributes Admin" tabindex="-1">Cloud API hub Attributes Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p>Full access to all Cloud API hub attribute's resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.attributes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.attributes.create</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.delete</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.get</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.list</code></li>
<li><code dir="ltr" translate="no">apihub.attributes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.pluginAdmin" class="role-title add-link" data-text="Cloud API hub Plugins Admin" tabindex="-1">Cloud API hub Plugins Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Full access to all Cloud API hub plugin's resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.curations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.curations.create</code></li>
<li><code dir="ltr" translate="no">apihub.curations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.curations.get</code></li>
<li><code dir="ltr" translate="no">apihub.curations.list</code></li>
<li><code dir="ltr" translate="no">apihub.curations.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  locations.  collectApiData</code></p>
<p><code dir="ltr" translate="no">apihub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apihub.operations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.operations.get</code></li>
<li><code dir="ltr" translate="no">apihub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.plugininstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  plugininstances.  applyConfig</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.create</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.delete</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.disable</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.enable</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.execute</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.get</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.list</code></li>
<li><code dir="ltr" translate="no">apihub.  plugininstances.  managePluginInstanceSourceData</code></li>
<li><code dir="ltr" translate="no">apihub.plugininstances.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.plugins.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.plugins.create</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.delete</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.disable</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.enable</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.get</code></li>
<li><code dir="ltr" translate="no">apihub.plugins.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.specs.lint</code></p>
<p><code dir="ltr" translate="no">apihub.styleGuides.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.styleGuides.get</code></li>
<li><code dir="ltr" translate="no">apihub.styleGuides.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.provisioningAdmin" class="role-title add-link" data-text="Cloud API hub Provisioning Admin" tabindex="-1">Cloud API hub Provisioning Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Full access to Cloud API hub provisioning related resources.</p></td>
<td><p><code dir="ltr" translate="no">apihub.apiHubInstances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.create</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.delete</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></li>
<li><code dir="ltr" translate="no">apihub.apiHubInstances.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  create</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  delete</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></li>
<li><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  register</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apihub.operations.delete</code></li>
<li><code dir="ltr" translate="no">apihub.operations.get</code></li>
<li><code dir="ltr" translate="no">apihub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  attach</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  lookup</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.runTimeProjectAttachmentsEditor" class="role-title add-link" data-text="Cloud API hub Runtime Project Attachment Editor" tabindex="-1">Cloud API hub Runtime Project Attachment Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.runTimeProjectAttachmentsEditor</code> )</p>
<p>Access to add/delete project as a runtime project attachment to API hub host project.</p></td>
<td><p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  attach</code></p></td>
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
<td><h4 id="apihub.runtimeProjectServiceAgent" class="role-title add-link" data-text="API-Hub Runtime Project Service Agent" tabindex="-1">API-Hub Runtime Project Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</p>
<p>Gives API-Hub Service Account access to runtime project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apigee.deployments.list</code></p>
<p><code dir="ltr" translate="no">apigee.  envgroupattachments.  list</code></p>
<p><code dir="ltr" translate="no">apigee.envgroups.list</code></p>
<p><code dir="ltr" translate="no">apigee.environments.get</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.create</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.delete</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.get</code></p>
<p><code dir="ltr" translate="no">apigee.organizations.update</code></p>
<p><code dir="ltr" translate="no">apigee.proxies.get</code></p>
<p><code dir="ltr" translate="no">apigee.proxyrevisions.get</code></p>
<p><code dir="ltr" translate="no">apihub.addons.get</code></p>
<p><code dir="ltr" translate="no">apihub.addons.list</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.delete</code></p>
<p><code dir="ltr" translate="no">apihub.apiOperations.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.create</code></p>
<p><code dir="ltr" translate="no">apihub.apis.delete</code></p>
<p><code dir="ltr" translate="no">apihub.apis.list</code></p>
<p><code dir="ltr" translate="no">apihub.apis.update</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.create</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.list</code></p>
<p><code dir="ltr" translate="no">apihub.attributes.update</code></p>
<p><code dir="ltr" translate="no">apihub.curations.list</code></p>
<p><code dir="ltr" translate="no">apihub.definitions.list</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.delete</code></p>
<p><code dir="ltr" translate="no">apihub.dependencies.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.create</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.delete</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.list</code></p>
<p><code dir="ltr" translate="no">apihub.deployments.update</code></p>
<p><code dir="ltr" translate="no">apihub.externalApis.list</code></p>
<p><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></p>
<p><code dir="ltr" translate="no">apihub.operations.get</code></p>
<p><code dir="ltr" translate="no">apihub.operations.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.create</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.delete</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.list</code></p>
<p><code dir="ltr" translate="no">apihub.plugininstances.update</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.create</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.delete</code></p>
<p><code dir="ltr" translate="no">apihub.plugins.list</code></p>
<p><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.create</code></p>
<p><code dir="ltr" translate="no">apihub.specs.delete</code></p>
<p><code dir="ltr" translate="no">apihub.specs.list</code></p>
<p><code dir="ltr" translate="no">apihub.specs.update</code></p>
<p><code dir="ltr" translate="no">apihub.versions.create</code></p>
<p><code dir="ltr" translate="no">apihub.versions.delete</code></p>
<p><code dir="ltr" translate="no">apihub.versions.list</code></p>
<p><code dir="ltr" translate="no">apihub.versions.update</code></p></td>
</tr>
</tbody>
</table>

## API Hub permissions

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
<td><h4 id="apihub.addons.get" class="permission-name add-link" data-text="apihub.addons.get" tabindex="-1"><code dir="ltr" translate="no">apihub.addons.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.addons.list" class="permission-name add-link" data-text="apihub.addons.list" tabindex="-1"><code dir="ltr" translate="no">apihub.addons.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.addons.manage" class="permission-name add-link" data-text="apihub.addons.manage" tabindex="-1"><code dir="ltr" translate="no">apihub.addons.manage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.addonsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiHubInstances.create" class="permission-name add-link" data-text="apihub.apiHubInstances.create" tabindex="-1"><code dir="ltr" translate="no">apihub.apiHubInstances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiHubInstances.delete" class="permission-name add-link" data-text="apihub.apiHubInstances.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.apiHubInstances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiHubInstances.get" class="permission-name add-link" data-text="apihub.apiHubInstances.get" tabindex="-1"><code dir="ltr" translate="no">apihub.apiHubInstances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiHubInstances.list" class="permission-name add-link" data-text="apihub.apiHubInstances.list" tabindex="-1"><code dir="ltr" translate="no">apihub.apiHubInstances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiHubInstances.update" class="permission-name add-link" data-text="apihub.apiHubInstances.update" tabindex="-1"><code dir="ltr" translate="no">apihub.apiHubInstances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiOperations.create" class="permission-name add-link" data-text="apihub.apiOperations.create" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiOperations.delete" class="permission-name add-link" data-text="apihub.apiOperations.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiOperations.get" class="permission-name add-link" data-text="apihub.apiOperations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiOperations.list" class="permission-name add-link" data-text="apihub.apiOperations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apiOperations.listAll" class="permission-name add-link" data-text="apihub.apiOperations.listAll" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.listAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apiOperations.update" class="permission-name add-link" data-text="apihub.apiOperations.update" tabindex="-1"><code dir="ltr" translate="no">apihub.apiOperations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apis.create" class="permission-name add-link" data-text="apihub.apis.create" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apis.createTagBinding" class="permission-name add-link" data-text="apihub.apis.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apis.delete" class="permission-name add-link" data-text="apihub.apis.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apis.deleteTagBinding" class="permission-name add-link" data-text="apihub.apis.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apis.get" class="permission-name add-link" data-text="apihub.apis.get" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apis.list" class="permission-name add-link" data-text="apihub.apis.list" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apis.listEffectiveTags" class="permission-name add-link" data-text="apihub.apis.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.apis.listTagBindings" class="permission-name add-link" data-text="apihub.apis.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.apis.update" class="permission-name add-link" data-text="apihub.apis.update" tabindex="-1"><code dir="ltr" translate="no">apihub.apis.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.attributes.create" class="permission-name add-link" data-text="apihub.attributes.create" tabindex="-1"><code dir="ltr" translate="no">apihub.attributes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.attributes.delete" class="permission-name add-link" data-text="apihub.attributes.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.attributes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.attributes.get" class="permission-name add-link" data-text="apihub.attributes.get" tabindex="-1"><code dir="ltr" translate="no">apihub.attributes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.attributes.list" class="permission-name add-link" data-text="apihub.attributes.list" tabindex="-1"><code dir="ltr" translate="no">apihub.attributes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.attributes.update" class="permission-name add-link" data-text="apihub.attributes.update" tabindex="-1"><code dir="ltr" translate="no">apihub.attributes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.attributeAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.curations.create" class="permission-name add-link" data-text="apihub.curations.create" tabindex="-1"><code dir="ltr" translate="no">apihub.curations.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.curations.delete" class="permission-name add-link" data-text="apihub.curations.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.curations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.curations.get" class="permission-name add-link" data-text="apihub.curations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.curations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.curations.list" class="permission-name add-link" data-text="apihub.curations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.curations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.curations.update" class="permission-name add-link" data-text="apihub.curations.update" tabindex="-1"><code dir="ltr" translate="no">apihub.curations.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.definitions.get" class="permission-name add-link" data-text="apihub.definitions.get" tabindex="-1"><code dir="ltr" translate="no">apihub.definitions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.definitions.list" class="permission-name add-link" data-text="apihub.definitions.list" tabindex="-1"><code dir="ltr" translate="no">apihub.definitions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.definitions.update" class="permission-name add-link" data-text="apihub.definitions.update" tabindex="-1"><code dir="ltr" translate="no">apihub.definitions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.dependencies.create" class="permission-name add-link" data-text="apihub.dependencies.create" tabindex="-1"><code dir="ltr" translate="no">apihub.dependencies.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.dependencies.delete" class="permission-name add-link" data-text="apihub.dependencies.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.dependencies.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.dependencies.get" class="permission-name add-link" data-text="apihub.dependencies.get" tabindex="-1"><code dir="ltr" translate="no">apihub.dependencies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.dependencies.list" class="permission-name add-link" data-text="apihub.dependencies.list" tabindex="-1"><code dir="ltr" translate="no">apihub.dependencies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.dependencies.update" class="permission-name add-link" data-text="apihub.dependencies.update" tabindex="-1"><code dir="ltr" translate="no">apihub.dependencies.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.deployments.create" class="permission-name add-link" data-text="apihub.deployments.create" tabindex="-1"><code dir="ltr" translate="no">apihub.deployments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.deployments.createTagBinding" class="permission-name add-link" data-text="apihub.deployments.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.deployments.delete" class="permission-name add-link" data-text="apihub.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.deployments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.deployments.deleteTagBinding" class="permission-name add-link" data-text="apihub.deployments.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.deployments.get" class="permission-name add-link" data-text="apihub.deployments.get" tabindex="-1"><code dir="ltr" translate="no">apihub.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.deployments.list" class="permission-name add-link" data-text="apihub.deployments.list" tabindex="-1"><code dir="ltr" translate="no">apihub.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.deployments.listEffectiveTags" class="permission-name add-link" data-text="apihub.deployments.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.deployments.listTagBindings" class="permission-name add-link" data-text="apihub.deployments.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.deployments.update" class="permission-name add-link" data-text="apihub.deployments.update" tabindex="-1"><code dir="ltr" translate="no">apihub.deployments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.discoveredApiObservations.get" class="permission-name add-link" data-text="apihub.discoveredApiObservations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.discoveredApiObservations.list" class="permission-name add-link" data-text="apihub.discoveredApiObservations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.  discoveredApiObservations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.discoveredApiOperations.get" class="permission-name add-link" data-text="apihub.discoveredApiOperations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.discoveredApiOperations.list" class="permission-name add-link" data-text="apihub.discoveredApiOperations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.  discoveredApiOperations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.externalApis.create" class="permission-name add-link" data-text="apihub.externalApis.create" tabindex="-1"><code dir="ltr" translate="no">apihub.externalApis.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.externalApis.delete" class="permission-name add-link" data-text="apihub.externalApis.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.externalApis.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.externalApis.get" class="permission-name add-link" data-text="apihub.externalApis.get" tabindex="-1"><code dir="ltr" translate="no">apihub.externalApis.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.externalApis.list" class="permission-name add-link" data-text="apihub.externalApis.list" tabindex="-1"><code dir="ltr" translate="no">apihub.externalApis.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.externalApis.update" class="permission-name add-link" data-text="apihub.externalApis.update" tabindex="-1"><code dir="ltr" translate="no">apihub.externalApis.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.hostProjectRegistrations.create" class="permission-name add-link" data-text="apihub.hostProjectRegistrations.create" tabindex="-1"><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.hostProjectRegistrations.delete" class="permission-name add-link" data-text="apihub.hostProjectRegistrations.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.hostProjectRegistrations.get" class="permission-name add-link" data-text="apihub.hostProjectRegistrations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.hostProjectRegistrations.list" class="permission-name add-link" data-text="apihub.hostProjectRegistrations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.hostProjectRegistrations.register" class="permission-name add-link" data-text="apihub.hostProjectRegistrations.register" tabindex="-1"><code dir="ltr" translate="no">apihub.  hostProjectRegistrations.  register</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.llmEnablements.deregister" class="permission-name add-link" data-text="apihub.llmEnablements.deregister" tabindex="-1"><code dir="ltr" translate="no">apihub.  llmEnablements.  deregister</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.llmEnablements.get" class="permission-name add-link" data-text="apihub.llmEnablements.get" tabindex="-1"><code dir="ltr" translate="no">apihub.llmEnablements.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.llmEnablements.list" class="permission-name add-link" data-text="apihub.llmEnablements.list" tabindex="-1"><code dir="ltr" translate="no">apihub.llmEnablements.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.llmEnablements.register" class="permission-name add-link" data-text="apihub.llmEnablements.register" tabindex="-1"><code dir="ltr" translate="no">apihub.llmEnablements.register</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.locations.collectApiData" class="permission-name add-link" data-text="apihub.locations.collectApiData" tabindex="-1"><code dir="ltr" translate="no">apihub.  locations.  collectApiData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.locations.getApiInsights" class="permission-name add-link" data-text="apihub.locations.getApiInsights" tabindex="-1"><code dir="ltr" translate="no">apihub.  locations.  getApiInsights</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.locations.searchResources" class="permission-name add-link" data-text="apihub.locations.searchResources" tabindex="-1"><code dir="ltr" translate="no">apihub.  locations.  searchResources</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.locations2.searchResources" class="permission-name add-link" data-text="apihub.locations2.searchResources" tabindex="-1"><code dir="ltr" translate="no">apihub.  locations2.  searchResources</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.operations.cancel" class="permission-name add-link" data-text="apihub.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">apihub.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.operations.delete" class="permission-name add-link" data-text="apihub.operations.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.operations.get" class="permission-name add-link" data-text="apihub.operations.get" tabindex="-1"><code dir="ltr" translate="no">apihub.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.operations.list" class="permission-name add-link" data-text="apihub.operations.list" tabindex="-1"><code dir="ltr" translate="no">apihub.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugininstances.applyConfig" class="permission-name add-link" data-text="apihub.plugininstances.applyConfig" tabindex="-1"><code dir="ltr" translate="no">apihub.  plugininstances.  applyConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugininstances.create" class="permission-name add-link" data-text="apihub.plugininstances.create" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugininstances.delete" class="permission-name add-link" data-text="apihub.plugininstances.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugininstances.disable" class="permission-name add-link" data-text="apihub.plugininstances.disable" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugininstances.enable" class="permission-name add-link" data-text="apihub.plugininstances.enable" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugininstances.execute" class="permission-name add-link" data-text="apihub.plugininstances.execute" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugininstances.get" class="permission-name add-link" data-text="apihub.plugininstances.get" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugininstances.list" class="permission-name add-link" data-text="apihub.plugininstances.list" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugininstances.managePluginInstanceSourceData" class="permission-name add-link" data-text="apihub.plugininstances.managePluginInstanceSourceData" tabindex="-1"><code dir="ltr" translate="no">apihub.  plugininstances.  managePluginInstanceSourceData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugininstances.update" class="permission-name add-link" data-text="apihub.plugininstances.update" tabindex="-1"><code dir="ltr" translate="no">apihub.plugininstances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugins.create" class="permission-name add-link" data-text="apihub.plugins.create" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugins.delete" class="permission-name add-link" data-text="apihub.plugins.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugins.disable" class="permission-name add-link" data-text="apihub.plugins.disable" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugins.enable" class="permission-name add-link" data-text="apihub.plugins.enable" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.plugins.get" class="permission-name add-link" data-text="apihub.plugins.get" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.plugins.list" class="permission-name add-link" data-text="apihub.plugins.list" tabindex="-1"><code dir="ltr" translate="no">apihub.plugins.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.runTimeProjectAttachments.attach" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.attach" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  attach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runTimeProjectAttachmentsEditor">Cloud API hub Runtime Project Attachment Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runTimeProjectAttachmentsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.runTimeProjectAttachments.create" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.create" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.runTimeProjectAttachments.delete" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.runTimeProjectAttachments.get" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.get" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.runTimeProjectAttachments.list" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.list" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.runTimeProjectAttachments.lookup" class="permission-name add-link" data-text="apihub.runTimeProjectAttachments.lookup" tabindex="-1"><code dir="ltr" translate="no">apihub.  runTimeProjectAttachments.  lookup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.specs.create" class="permission-name add-link" data-text="apihub.specs.create" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.specs.delete" class="permission-name add-link" data-text="apihub.specs.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.specs.get" class="permission-name add-link" data-text="apihub.specs.get" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.specs.lint" class="permission-name add-link" data-text="apihub.specs.lint" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.lint</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.specs.list" class="permission-name add-link" data-text="apihub.specs.list" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.specs.listAll" class="permission-name add-link" data-text="apihub.specs.listAll" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.listAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.specs.update" class="permission-name add-link" data-text="apihub.specs.update" tabindex="-1"><code dir="ltr" translate="no">apihub.specs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.styleGuides.get" class="permission-name add-link" data-text="apihub.styleGuides.get" tabindex="-1"><code dir="ltr" translate="no">apihub.styleGuides.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.styleGuides.update" class="permission-name add-link" data-text="apihub.styleGuides.update" tabindex="-1"><code dir="ltr" translate="no">apihub.styleGuides.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.pluginAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apihub.versions.create" class="permission-name add-link" data-text="apihub.versions.create" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.versions.delete" class="permission-name add-link" data-text="apihub.versions.delete" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.versions.get" class="permission-name add-link" data-text="apihub.versions.get" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.versions.list" class="permission-name add-link" data-text="apihub.versions.list" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apihub.versions.listAll" class="permission-name add-link" data-text="apihub.versions.listAll" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.listAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apihub.versions.update" class="permission-name add-link" data-text="apihub.versions.update" tabindex="-1"><code dir="ltr" translate="no">apihub.versions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
