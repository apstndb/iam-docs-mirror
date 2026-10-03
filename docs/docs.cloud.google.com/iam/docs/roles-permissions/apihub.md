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
<td>Cloud API Hub Admin
<p>( <code>roles/ apihub.admin</code> )</p>
<p>Full access to all API hub resources.</p></td>
<td><p><code>apigee. projectorganizations. get</code></p>
<p><code>apihub.*</code></p>
<ul>
<li><code>apihub.addons.get</code></li>
<li><code>apihub.addons.list</code></li>
<li><code>apihub.addons.manage</code></li>
<li><code>apihub.apiHubInstances.create</code></li>
<li><code>apihub.apiHubInstances.delete</code></li>
<li><code>apihub.apiHubInstances.get</code></li>
<li><code>apihub.apiHubInstances.list</code></li>
<li><code>apihub.apiHubInstances.update</code></li>
<li><code>apihub.apiOperations.create</code></li>
<li><code>apihub.apiOperations.delete</code></li>
<li><code>apihub.apiOperations.get</code></li>
<li><code>apihub.apiOperations.list</code></li>
<li><code>apihub.apiOperations.listAll</code></li>
<li><code>apihub.apiOperations.update</code></li>
<li><code>apihub.apis.create</code></li>
<li><code>apihub.apis.createTagBinding</code></li>
<li><code>apihub.apis.delete</code></li>
<li><code>apihub.apis.deleteTagBinding</code></li>
<li><code>apihub.apis.get</code></li>
<li><code>apihub.apis.list</code></li>
<li><code>apihub.apis.listEffectiveTags</code></li>
<li><code>apihub.apis.listTagBindings</code></li>
<li><code>apihub.apis.update</code></li>
<li><code>apihub.attributes.create</code></li>
<li><code>apihub.attributes.delete</code></li>
<li><code>apihub.attributes.get</code></li>
<li><code>apihub.attributes.list</code></li>
<li><code>apihub.attributes.update</code></li>
<li><code>apihub.curations.create</code></li>
<li><code>apihub.curations.delete</code></li>
<li><code>apihub.curations.get</code></li>
<li><code>apihub.curations.list</code></li>
<li><code>apihub.curations.update</code></li>
<li><code>apihub.definitions.get</code></li>
<li><code>apihub.definitions.list</code></li>
<li><code>apihub.definitions.update</code></li>
<li><code>apihub.dependencies.create</code></li>
<li><code>apihub.dependencies.delete</code></li>
<li><code>apihub.dependencies.get</code></li>
<li><code>apihub.dependencies.list</code></li>
<li><code>apihub.dependencies.update</code></li>
<li><code>apihub.deployments.create</code></li>
<li><code>apihub. deployments. createTagBinding</code></li>
<li><code>apihub.deployments.delete</code></li>
<li><code>apihub. deployments. deleteTagBinding</code></li>
<li><code>apihub.deployments.get</code></li>
<li><code>apihub.deployments.list</code></li>
<li><code>apihub. deployments. listEffectiveTags</code></li>
<li><code>apihub. deployments. listTagBindings</code></li>
<li><code>apihub.deployments.update</code></li>
<li><code>apihub. discoveredApiObservations. get</code></li>
<li><code>apihub. discoveredApiObservations. list</code></li>
<li><code>apihub. discoveredApiOperations. get</code></li>
<li><code>apihub. discoveredApiOperations. list</code></li>
<li><code>apihub.externalApis.create</code></li>
<li><code>apihub.externalApis.delete</code></li>
<li><code>apihub.externalApis.get</code></li>
<li><code>apihub.externalApis.list</code></li>
<li><code>apihub.externalApis.update</code></li>
<li><code>apihub. hostProjectRegistrations. create</code></li>
<li><code>apihub. hostProjectRegistrations. delete</code></li>
<li><code>apihub. hostProjectRegistrations. get</code></li>
<li><code>apihub. hostProjectRegistrations. list</code></li>
<li><code>apihub. hostProjectRegistrations. register</code></li>
<li><code>apihub. llmEnablements. deregister</code></li>
<li><code>apihub.llmEnablements.get</code></li>
<li><code>apihub.llmEnablements.list</code></li>
<li><code>apihub.llmEnablements.register</code></li>
<li><code>apihub. locations. collectApiData</code></li>
<li><code>apihub. locations. getApiInsights</code></li>
<li><code>apihub. locations. searchResources</code></li>
<li><code>apihub. locations2. searchResources</code></li>
<li><code>apihub.operations.cancel</code></li>
<li><code>apihub.operations.delete</code></li>
<li><code>apihub.operations.get</code></li>
<li><code>apihub.operations.list</code></li>
<li><code>apihub. plugininstances. applyConfig</code></li>
<li><code>apihub.plugininstances.create</code></li>
<li><code>apihub.plugininstances.delete</code></li>
<li><code>apihub.plugininstances.disable</code></li>
<li><code>apihub.plugininstances.enable</code></li>
<li><code>apihub.plugininstances.execute</code></li>
<li><code>apihub.plugininstances.get</code></li>
<li><code>apihub.plugininstances.list</code></li>
<li><code>apihub. plugininstances. managePluginInstanceSourceData</code></li>
<li><code>apihub.plugininstances.update</code></li>
<li><code>apihub.plugins.create</code></li>
<li><code>apihub.plugins.delete</code></li>
<li><code>apihub.plugins.disable</code></li>
<li><code>apihub.plugins.enable</code></li>
<li><code>apihub.plugins.get</code></li>
<li><code>apihub.plugins.list</code></li>
<li><code>apihub. runTimeProjectAttachments. attach</code></li>
<li><code>apihub. runTimeProjectAttachments. create</code></li>
<li><code>apihub. runTimeProjectAttachments. delete</code></li>
<li><code>apihub. runTimeProjectAttachments. get</code></li>
<li><code>apihub. runTimeProjectAttachments. list</code></li>
<li><code>apihub. runTimeProjectAttachments. lookup</code></li>
<li><code>apihub.specs.create</code></li>
<li><code>apihub.specs.delete</code></li>
<li><code>apihub.specs.get</code></li>
<li><code>apihub.specs.lint</code></li>
<li><code>apihub.specs.list</code></li>
<li><code>apihub.specs.listAll</code></li>
<li><code>apihub.specs.update</code></li>
<li><code>apihub.styleGuides.get</code></li>
<li><code>apihub.styleGuides.update</code></li>
<li><code>apihub.versions.create</code></li>
<li><code>apihub.versions.delete</code></li>
<li><code>apihub.versions.get</code></li>
<li><code>apihub.versions.list</code></li>
<li><code>apihub.versions.listAll</code></li>
<li><code>apihub.versions.update</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud API Hub Editor
<p>( <code>roles/ apihub.editor</code> )</p>
<p>Edit access to most of Cloud API Hub resources.</p></td>
<td><p><code>apihub.addons.get</code></p>
<p><code>apihub.addons.list</code></p>
<p><code>apihub.apiHubInstances.get</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apiOperations.*</code></p>
<ul>
<li><code>apihub.apiOperations.create</code></li>
<li><code>apihub.apiOperations.delete</code></li>
<li><code>apihub.apiOperations.get</code></li>
<li><code>apihub.apiOperations.list</code></li>
<li><code>apihub.apiOperations.listAll</code></li>
<li><code>apihub.apiOperations.update</code></li>
</ul>
<p><code>apihub.apis.*</code></p>
<ul>
<li><code>apihub.apis.create</code></li>
<li><code>apihub.apis.createTagBinding</code></li>
<li><code>apihub.apis.delete</code></li>
<li><code>apihub.apis.deleteTagBinding</code></li>
<li><code>apihub.apis.get</code></li>
<li><code>apihub.apis.list</code></li>
<li><code>apihub.apis.listEffectiveTags</code></li>
<li><code>apihub.apis.listTagBindings</code></li>
<li><code>apihub.apis.update</code></li>
</ul>
<p><code>apihub.attributes.get</code></p>
<p><code>apihub.attributes.list</code></p>
<p><code>apihub.curations.get</code></p>
<p><code>apihub.curations.list</code></p>
<p><code>apihub.definitions.*</code></p>
<ul>
<li><code>apihub.definitions.get</code></li>
<li><code>apihub.definitions.list</code></li>
<li><code>apihub.definitions.update</code></li>
</ul>
<p><code>apihub.dependencies.*</code></p>
<ul>
<li><code>apihub.dependencies.create</code></li>
<li><code>apihub.dependencies.delete</code></li>
<li><code>apihub.dependencies.get</code></li>
<li><code>apihub.dependencies.list</code></li>
<li><code>apihub.dependencies.update</code></li>
</ul>
<p><code>apihub.deployments.*</code></p>
<ul>
<li><code>apihub.deployments.create</code></li>
<li><code>apihub. deployments. createTagBinding</code></li>
<li><code>apihub.deployments.delete</code></li>
<li><code>apihub. deployments. deleteTagBinding</code></li>
<li><code>apihub.deployments.get</code></li>
<li><code>apihub.deployments.list</code></li>
<li><code>apihub. deployments. listEffectiveTags</code></li>
<li><code>apihub. deployments. listTagBindings</code></li>
<li><code>apihub.deployments.update</code></li>
</ul>
<p><code>apihub. discoveredApiObservations.*</code></p>
<ul>
<li><code>apihub. discoveredApiObservations. get</code></li>
<li><code>apihub. discoveredApiObservations. list</code></li>
</ul>
<p><code>apihub. discoveredApiOperations.*</code></p>
<ul>
<li><code>apihub. discoveredApiOperations. get</code></li>
<li><code>apihub. discoveredApiOperations. list</code></li>
</ul>
<p><code>apihub.externalApis.*</code></p>
<ul>
<li><code>apihub.externalApis.create</code></li>
<li><code>apihub.externalApis.delete</code></li>
<li><code>apihub.externalApis.get</code></li>
<li><code>apihub.externalApis.list</code></li>
<li><code>apihub.externalApis.update</code></li>
</ul>
<p><code>apihub. hostProjectRegistrations. get</code></p>
<p><code>apihub. hostProjectRegistrations. list</code></p>
<p><code>apihub.llmEnablements.*</code></p>
<ul>
<li><code>apihub. llmEnablements. deregister</code></li>
<li><code>apihub.llmEnablements.get</code></li>
<li><code>apihub.llmEnablements.list</code></li>
<li><code>apihub.llmEnablements.register</code></li>
</ul>
<p><code>apihub. locations. collectApiData</code></p>
<p><code>apihub. locations. searchResources</code></p>
<p><code>apihub.operations.get</code></p>
<p><code>apihub.operations.list</code></p>
<p><code>apihub.plugininstances.get</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugins.get</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub. runTimeProjectAttachments. get</code></p>
<p><code>apihub. runTimeProjectAttachments. list</code></p>
<p><code>apihub.specs.*</code></p>
<ul>
<li><code>apihub.specs.create</code></li>
<li><code>apihub.specs.delete</code></li>
<li><code>apihub.specs.get</code></li>
<li><code>apihub.specs.lint</code></li>
<li><code>apihub.specs.list</code></li>
<li><code>apihub.specs.listAll</code></li>
<li><code>apihub.specs.update</code></li>
</ul>
<p><code>apihub.styleGuides.get</code></p>
<p><code>apihub.versions.*</code></p>
<ul>
<li><code>apihub.versions.create</code></li>
<li><code>apihub.versions.delete</code></li>
<li><code>apihub.versions.get</code></li>
<li><code>apihub.versions.list</code></li>
<li><code>apihub.versions.listAll</code></li>
<li><code>apihub.versions.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud API Hub Viewer
<p>( <code>roles/ apihub.viewer</code> )</p>
<p>View access to all Cloud API hub resources.</p></td>
<td><p><code>apihub.addons.get</code></p>
<p><code>apihub.addons.list</code></p>
<p><code>apihub.apiHubInstances.get</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apiOperations.get</code></p>
<p><code>apihub.apiOperations.list</code></p>
<p><code>apihub.apiOperations.listAll</code></p>
<p><code>apihub.apis.get</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.apis.listEffectiveTags</code></p>
<p><code>apihub.apis.listTagBindings</code></p>
<p><code>apihub.attributes.get</code></p>
<p><code>apihub.attributes.list</code></p>
<p><code>apihub.curations.get</code></p>
<p><code>apihub.curations.list</code></p>
<p><code>apihub.definitions.get</code></p>
<p><code>apihub.definitions.list</code></p>
<p><code>apihub.dependencies.get</code></p>
<p><code>apihub.dependencies.list</code></p>
<p><code>apihub.deployments.get</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub. deployments. listEffectiveTags</code></p>
<p><code>apihub. deployments. listTagBindings</code></p>
<p><code>apihub. discoveredApiObservations.*</code></p>
<ul>
<li><code>apihub. discoveredApiObservations. get</code></li>
<li><code>apihub. discoveredApiObservations. list</code></li>
</ul>
<p><code>apihub. discoveredApiOperations.*</code></p>
<ul>
<li><code>apihub. discoveredApiOperations. get</code></li>
<li><code>apihub. discoveredApiOperations. list</code></li>
</ul>
<p><code>apihub.externalApis.get</code></p>
<p><code>apihub.externalApis.list</code></p>
<p><code>apihub. hostProjectRegistrations. get</code></p>
<p><code>apihub. hostProjectRegistrations. list</code></p>
<p><code>apihub.llmEnablements.get</code></p>
<p><code>apihub.llmEnablements.list</code></p>
<p><code>apihub. locations. searchResources</code></p>
<p><code>apihub.operations.get</code></p>
<p><code>apihub.operations.list</code></p>
<p><code>apihub.plugininstances.get</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugins.get</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub. runTimeProjectAttachments. get</code></p>
<p><code>apihub. runTimeProjectAttachments. list</code></p>
<p><code>apihub.specs.get</code></p>
<p><code>apihub.specs.list</code></p>
<p><code>apihub.specs.listAll</code></p>
<p><code>apihub.styleGuides.get</code></p>
<p><code>apihub.versions.get</code></p>
<p><code>apihub.versions.list</code></p>
<p><code>apihub.versions.listAll</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud API hub Addons Admin
<p>( <code>roles/ apihub.addonsAdmin</code> )</p>
<p>Full access to all Cloud API hub addon resources.</p></td>
<td><p><code>apihub.addons.*</code></p>
<ul>
<li><code>apihub.addons.get</code></li>
<li><code>apihub.addons.list</code></li>
<li><code>apihub.addons.manage</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud API hub Insights Viewer
<p>( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p>View API hub insights dashboards.</p></td>
<td><p><code>apigee. projectorganizations. get</code></p>
<p><code>apihub.apiHubInstances.get</code></p>
<p><code>apihub.apiHubInstances.list</code></p>
<p><code>apihub.apis.get</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.deployments.get</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub. locations. getApiInsights</code></p>
<p><code>apihub.plugininstances.get</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Cloud API hub Attributes Admin
<p>( <code>roles/ apihub.attributeAdmin</code> )</p>
<p>Full access to all Cloud API hub attribute's resources.</p></td>
<td><p><code>apihub.attributes.*</code></p>
<ul>
<li><code>apihub.attributes.create</code></li>
<li><code>apihub.attributes.delete</code></li>
<li><code>apihub.attributes.get</code></li>
<li><code>apihub.attributes.list</code></li>
<li><code>apihub.attributes.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud API hub Plugins Admin
<p>( <code>roles/ apihub.pluginAdmin</code> )</p>
<p>Full access to all Cloud API hub plugin's resources.</p></td>
<td><p><code>apihub.curations.*</code></p>
<ul>
<li><code>apihub.curations.create</code></li>
<li><code>apihub.curations.delete</code></li>
<li><code>apihub.curations.get</code></li>
<li><code>apihub.curations.list</code></li>
<li><code>apihub.curations.update</code></li>
</ul>
<p><code>apihub. locations. collectApiData</code></p>
<p><code>apihub.operations.*</code></p>
<ul>
<li><code>apihub.operations.cancel</code></li>
<li><code>apihub.operations.delete</code></li>
<li><code>apihub.operations.get</code></li>
<li><code>apihub.operations.list</code></li>
</ul>
<p><code>apihub.plugininstances.*</code></p>
<ul>
<li><code>apihub. plugininstances. applyConfig</code></li>
<li><code>apihub.plugininstances.create</code></li>
<li><code>apihub.plugininstances.delete</code></li>
<li><code>apihub.plugininstances.disable</code></li>
<li><code>apihub.plugininstances.enable</code></li>
<li><code>apihub.plugininstances.execute</code></li>
<li><code>apihub.plugininstances.get</code></li>
<li><code>apihub.plugininstances.list</code></li>
<li><code>apihub. plugininstances. managePluginInstanceSourceData</code></li>
<li><code>apihub.plugininstances.update</code></li>
</ul>
<p><code>apihub.plugins.*</code></p>
<ul>
<li><code>apihub.plugins.create</code></li>
<li><code>apihub.plugins.delete</code></li>
<li><code>apihub.plugins.disable</code></li>
<li><code>apihub.plugins.enable</code></li>
<li><code>apihub.plugins.get</code></li>
<li><code>apihub.plugins.list</code></li>
</ul>
<p><code>apihub.specs.lint</code></p>
<p><code>apihub.styleGuides.*</code></p>
<ul>
<li><code>apihub.styleGuides.get</code></li>
<li><code>apihub.styleGuides.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Cloud API hub Provisioning Admin
<p>( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p>Full access to Cloud API hub provisioning related resources.</p></td>
<td><p><code>apihub.apiHubInstances.*</code></p>
<ul>
<li><code>apihub.apiHubInstances.create</code></li>
<li><code>apihub.apiHubInstances.delete</code></li>
<li><code>apihub.apiHubInstances.get</code></li>
<li><code>apihub.apiHubInstances.list</code></li>
<li><code>apihub.apiHubInstances.update</code></li>
</ul>
<p><code>apihub. hostProjectRegistrations.*</code></p>
<ul>
<li><code>apihub. hostProjectRegistrations. create</code></li>
<li><code>apihub. hostProjectRegistrations. delete</code></li>
<li><code>apihub. hostProjectRegistrations. get</code></li>
<li><code>apihub. hostProjectRegistrations. list</code></li>
<li><code>apihub. hostProjectRegistrations. register</code></li>
</ul>
<p><code>apihub.operations.*</code></p>
<ul>
<li><code>apihub.operations.cancel</code></li>
<li><code>apihub.operations.delete</code></li>
<li><code>apihub.operations.get</code></li>
<li><code>apihub.operations.list</code></li>
</ul>
<p><code>apihub. runTimeProjectAttachments.*</code></p>
<ul>
<li><code>apihub. runTimeProjectAttachments. attach</code></li>
<li><code>apihub. runTimeProjectAttachments. create</code></li>
<li><code>apihub. runTimeProjectAttachments. delete</code></li>
<li><code>apihub. runTimeProjectAttachments. get</code></li>
<li><code>apihub. runTimeProjectAttachments. list</code></li>
<li><code>apihub. runTimeProjectAttachments. lookup</code></li>
</ul>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Cloud API hub Runtime Project Attachment Editor
<p>( <code>roles/ apihub.runTimeProjectAttachmentsEditor</code> )</p>
<p>Access to add/delete project as a runtime project attachment to API hub host project.</p></td>
<td><p><code>apihub. runTimeProjectAttachments. attach</code></p></td>
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
<td>API-Hub Runtime Project Service Agent
<p>( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</p>
<p>Gives API-Hub Service Account access to runtime project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>apigee.deployments.list</code></p>
<p><code>apigee. envgroupattachments. list</code></p>
<p><code>apigee.envgroups.list</code></p>
<p><code>apigee.environments.get</code></p>
<p><code>apigee.organizations.create</code></p>
<p><code>apigee.organizations.delete</code></p>
<p><code>apigee.organizations.get</code></p>
<p><code>apigee.organizations.update</code></p>
<p><code>apigee.proxies.get</code></p>
<p><code>apigee.proxyrevisions.get</code></p>
<p><code>apihub.addons.get</code></p>
<p><code>apihub.addons.list</code></p>
<p><code>apihub.apiOperations.delete</code></p>
<p><code>apihub.apiOperations.list</code></p>
<p><code>apihub.apis.create</code></p>
<p><code>apihub.apis.delete</code></p>
<p><code>apihub.apis.list</code></p>
<p><code>apihub.apis.update</code></p>
<p><code>apihub.attributes.create</code></p>
<p><code>apihub.attributes.list</code></p>
<p><code>apihub.attributes.update</code></p>
<p><code>apihub.curations.list</code></p>
<p><code>apihub.definitions.list</code></p>
<p><code>apihub.dependencies.delete</code></p>
<p><code>apihub.dependencies.list</code></p>
<p><code>apihub.deployments.create</code></p>
<p><code>apihub.deployments.delete</code></p>
<p><code>apihub.deployments.list</code></p>
<p><code>apihub.deployments.update</code></p>
<p><code>apihub.externalApis.list</code></p>
<p><code>apihub. hostProjectRegistrations. list</code></p>
<p><code>apihub.operations.get</code></p>
<p><code>apihub.operations.list</code></p>
<p><code>apihub.plugininstances.create</code></p>
<p><code>apihub.plugininstances.delete</code></p>
<p><code>apihub.plugininstances.list</code></p>
<p><code>apihub.plugininstances.update</code></p>
<p><code>apihub.plugins.create</code></p>
<p><code>apihub.plugins.delete</code></p>
<p><code>apihub.plugins.list</code></p>
<p><code>apihub. runTimeProjectAttachments. list</code></p>
<p><code>apihub.specs.create</code></p>
<p><code>apihub.specs.delete</code></p>
<p><code>apihub.specs.list</code></p>
<p><code>apihub.specs.update</code></p>
<p><code>apihub.versions.create</code></p>
<p><code>apihub.versions.delete</code></p>
<p><code>apihub.versions.list</code></p>
<p><code>apihub.versions.update</code></p></td>
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
<td><code>apihub.addons.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code>roles/ apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.addons.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code>roles/ apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.addons.manage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.addonsAdmin">Cloud API hub Addons Admin</a> ( <code>roles/ apihub.addonsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.apiHubInstances.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.apiHubInstances.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.apiHubInstances.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.apiHubInstances.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.apiHubInstances.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.apiOperations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.apiOperations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.apiOperations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.apiOperations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.apiOperations.listAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.apiOperations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.apis.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.apis.createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.apis.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.apis.deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.apis.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code>roles/ apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code>roles/ apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.apis.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.apis.listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.apis.listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.apis.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.attributes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.attributes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.attributes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.attributes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.attributes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.attributeAdmin">Cloud API hub Attributes Admin</a> ( <code>roles/ apihub.attributeAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.curations.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.curations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.curations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.curations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.curations.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.definitions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.definitions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.definitions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.dependencies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.dependencies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.dependencies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.dependencies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.dependencies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.deployments.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. deployments. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.deployments.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. deployments. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.deployments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.deployments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityAdmin">Apigee Security Admin</a> ( <code>roles/ apigee.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.securityViewer">Apigee Security Viewer</a> ( <code>roles/ apigee.securityViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. deployments. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub. deployments. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.deployments.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. discoveredApiObservations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub. discoveredApiObservations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub. discoveredApiOperations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub. discoveredApiOperations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.externalApis.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.externalApis.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.externalApis.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.externalApis.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.externalApis.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub. hostProjectRegistrations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. hostProjectRegistrations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. hostProjectRegistrations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. hostProjectRegistrations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. hostProjectRegistrations. register</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. llmEnablements. deregister</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.llmEnablements.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.llmEnablements.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.llmEnablements.register</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub. locations. collectApiData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub. locations. getApiInsights</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub. locations. searchResources</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub. locations2. searchResources</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. plugininstances. applyConfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugininstances.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugininstances.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugininstances.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugininstances.enable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugininstances.execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugininstances.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugininstances.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.apiInsightsViewer">Cloud API hub Insights Viewer</a> ( <code>roles/ apihub.apiInsightsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. plugininstances. managePluginInstanceSourceData</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.plugininstances.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugins.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugins.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugins.disable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugins.enable</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.plugins.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.plugins.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. runTimeProjectAttachments. attach</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runTimeProjectAttachmentsEditor">Cloud API hub Runtime Project Attachment Editor</a> ( <code>roles/ apihub.runTimeProjectAttachmentsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. runTimeProjectAttachments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. runTimeProjectAttachments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. runTimeProjectAttachments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub. runTimeProjectAttachments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.admin">ApiGateway Admin</a> ( <code>roles/ apigateway.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.editor">ApiGateway Editor</a> ( <code>roles/ apigateway.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigateway#apigateway.viewer">ApiGateway Viewer</a> ( <code>roles/ apigateway.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub. runTimeProjectAttachments. lookup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.provisioningAdmin">Cloud API hub Provisioning Admin</a> ( <code>roles/ apihub.provisioningAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.specs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.specs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.specs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.specs.lint</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.specs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.specs.listAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.specs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.styleGuides.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.styleGuides.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.pluginAdmin">Cloud API hub Plugins Admin</a> ( <code>roles/ apihub.pluginAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apihub.versions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.versions.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.versions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.coreServiceAgent">Apigee Core Service Agent</a> ( <code>roles/ apigee.coreServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.serviceAgent">Apigee Service Agent</a> ( <code>roles/ apigee.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apihub.versions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apihub.versions.listAll</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiAdminV2">Apigee API Admin</a> ( <code>roles/ apigee.apiAdminV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.viewer">Cloud API Hub Viewer</a> ( <code>roles/ apihub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.apiReaderV2">Apigee API Reader</a> ( <code>roles/ apigee.apiReaderV2</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apihub.versions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigee#apigee.admin">Apigee Organization Admin</a> ( <code>roles/ apigee.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.admin">Cloud API Hub Admin</a> ( <code>roles/ apihub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.editor">Cloud API Hub Editor</a> ( <code>roles/ apihub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apihub#apihub.runtimeProjectServiceAgent">API-Hub Runtime Project Service Agent</a> ( <code>roles/ apihub.runtimeProjectServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
