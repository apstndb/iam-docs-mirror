---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting
title: KRM API Hosting roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for KRM API Hosting. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## KRM API Hosting roles

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
<td><h4 id="krmapihosting.admin" class="role-title add-link" data-text="Config Controller Admin" tabindex="-1">Config Controller Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p>Full access to all Config Controller resources.</p></td>
<td><p><code dir="ltr" translate="no">krmapihosting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  create</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  delete</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">krmapihosting.krmApiHosts.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  update</code></li>
<li><code dir="ltr" translate="no">krmapihosting.locations.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.locations.list</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">krmapihosting.operations.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.editor" class="role-title add-link" data-text="Config Controller Editor" tabindex="-1">Config Controller Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p>Editor role for Config Controller</p></td>
<td><p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  create</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  delete</code></p>
<p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.get</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  update</code></p>
<p><code dir="ltr" translate="no">krmapihosting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">krmapihosting.locations.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">krmapihosting.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">krmapihosting.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">krmapihosting.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">krmapihosting.operations.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.viewer" class="role-title add-link" data-text="Config Controller Viewer" tabindex="-1">Config Controller Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p>Read-only access to all Config Controller resources.</p></td>
<td><p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.get</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">krmapihosting.locations.get</code></li>
<li><code dir="ltr" translate="no">krmapihosting.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">krmapihosting.operations.get</code></p>
<p><code dir="ltr" translate="no">krmapihosting.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="krmapihosting.anthosApiEndpointServiceAgent" class="role-title add-link" data-text="KRM API Hosting AnthosApiEndpoint Service Agent" tabindex="-1">KRM API Hosting AnthosApiEndpoint Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  krmapihosting.anthosApiEndpointServiceAgent</code> )</p>
<p>Grants permissions to resources managed by AnthosApiEndpoint.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">container.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.apiServices.create</code></li>
<li><code dir="ltr" translate="no">container.apiServices.delete</code></li>
<li><code dir="ltr" translate="no">container.apiServices.get</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.apiServices.list</code></li>
<li><code dir="ltr" translate="no">container.apiServices.update</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.create</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.delete</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.get</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.list</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.update</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.bindings.create</code></li>
<li><code dir="ltr" translate="no">container.bindings.delete</code></li>
<li><code dir="ltr" translate="no">container.bindings.get</code></li>
<li><code dir="ltr" translate="no">container.bindings.list</code></li>
<li><code dir="ltr" translate="no">container.bindings.update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  approve</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  create</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  delete</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
<li><code dir="ltr" translate="no">container.clusters.connect</code></li>
<li><code dir="ltr" translate="no">container.clusters.create</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.get</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  getCredentials</code></li>
<li><code dir="ltr" translate="no">container.clusters.impersonate</code></li>
<li><code dir="ltr" translate="no">container.clusters.list</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">container.clusters.update</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  create</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  update</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.create</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.get</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.list</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  cronJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.create</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.delete</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.get</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.list</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  create</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  delete</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.get</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.list</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  update</code></li>
<li><code dir="ltr" translate="no">container.endpoints.create</code></li>
<li><code dir="ltr" translate="no">container.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">container.endpoints.get</code></li>
<li><code dir="ltr" translate="no">container.endpoints.list</code></li>
<li><code dir="ltr" translate="no">container.endpoints.update</code></li>
<li><code dir="ltr" translate="no">container.events.create</code></li>
<li><code dir="ltr" translate="no">container.events.delete</code></li>
<li><code dir="ltr" translate="no">container.events.get</code></li>
<li><code dir="ltr" translate="no">container.events.list</code></li>
<li><code dir="ltr" translate="no">container.events.update</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.hostServiceAgent.use</code></li>
<li><code dir="ltr" translate="no">container.ingresses.create</code></li>
<li><code dir="ltr" translate="no">container.ingresses.delete</code></li>
<li><code dir="ltr" translate="no">container.ingresses.get</code></li>
<li><code dir="ltr" translate="no">container.ingresses.getStatus</code></li>
<li><code dir="ltr" translate="no">container.ingresses.list</code></li>
<li><code dir="ltr" translate="no">container.ingresses.update</code></li>
<li><code dir="ltr" translate="no">container.  ingresses.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.jobs.create</code></li>
<li><code dir="ltr" translate="no">container.jobs.delete</code></li>
<li><code dir="ltr" translate="no">container.jobs.get</code></li>
<li><code dir="ltr" translate="no">container.jobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.jobs.list</code></li>
<li><code dir="ltr" translate="no">container.jobs.update</code></li>
<li><code dir="ltr" translate="no">container.jobs.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.leases.create</code></li>
<li><code dir="ltr" translate="no">container.leases.delete</code></li>
<li><code dir="ltr" translate="no">container.leases.get</code></li>
<li><code dir="ltr" translate="no">container.leases.list</code></li>
<li><code dir="ltr" translate="no">container.leases.update</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.create</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.delete</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.get</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.list</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.update</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  create</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  get</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  update</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.namespaces.create</code></li>
<li><code dir="ltr" translate="no">container.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">container.namespaces.finalize</code></li>
<li><code dir="ltr" translate="no">container.namespaces.get</code></li>
<li><code dir="ltr" translate="no">container.namespaces.getStatus</code></li>
<li><code dir="ltr" translate="no">container.namespaces.list</code></li>
<li><code dir="ltr" translate="no">container.namespaces.update</code></li>
<li><code dir="ltr" translate="no">container.  namespaces.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.get</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.list</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.nodes.create</code></li>
<li><code dir="ltr" translate="no">container.nodes.delete</code></li>
<li><code dir="ltr" translate="no">container.nodes.get</code></li>
<li><code dir="ltr" translate="no">container.nodes.getStatus</code></li>
<li><code dir="ltr" translate="no">container.nodes.list</code></li>
<li><code dir="ltr" translate="no">container.nodes.proxy</code></li>
<li><code dir="ltr" translate="no">container.nodes.update</code></li>
<li><code dir="ltr" translate="no">container.nodes.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.petSets.create</code></li>
<li><code dir="ltr" translate="no">container.petSets.delete</code></li>
<li><code dir="ltr" translate="no">container.petSets.get</code></li>
<li><code dir="ltr" translate="no">container.petSets.list</code></li>
<li><code dir="ltr" translate="no">container.petSets.update</code></li>
<li><code dir="ltr" translate="no">container.petSets.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  update</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.podPresets.create</code></li>
<li><code dir="ltr" translate="no">container.podPresets.delete</code></li>
<li><code dir="ltr" translate="no">container.podPresets.get</code></li>
<li><code dir="ltr" translate="no">container.podPresets.list</code></li>
<li><code dir="ltr" translate="no">container.podPresets.update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  use</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.create</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.delete</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.get</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.list</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.update</code></li>
<li><code dir="ltr" translate="no">container.pods.attach</code></li>
<li><code dir="ltr" translate="no">container.pods.create</code></li>
<li><code dir="ltr" translate="no">container.pods.delete</code></li>
<li><code dir="ltr" translate="no">container.pods.evict</code></li>
<li><code dir="ltr" translate="no">container.pods.exec</code></li>
<li><code dir="ltr" translate="no">container.pods.get</code></li>
<li><code dir="ltr" translate="no">container.pods.getLogs</code></li>
<li><code dir="ltr" translate="no">container.pods.getStatus</code></li>
<li><code dir="ltr" translate="no">container.pods.initialize</code></li>
<li><code dir="ltr" translate="no">container.pods.list</code></li>
<li><code dir="ltr" translate="no">container.pods.portForward</code></li>
<li><code dir="ltr" translate="no">container.pods.proxy</code></li>
<li><code dir="ltr" translate="no">container.pods.update</code></li>
<li><code dir="ltr" translate="no">container.pods.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.get</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.create</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.delete</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.get</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.list</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.update</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  create</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  get</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  list</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  update</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  create</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  delete</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.get</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.list</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  update</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.create</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.delete</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.get</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.list</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.update</code></li>
<li><code dir="ltr" translate="no">container.roles.bind</code></li>
<li><code dir="ltr" translate="no">container.roles.create</code></li>
<li><code dir="ltr" translate="no">container.roles.delete</code></li>
<li><code dir="ltr" translate="no">container.roles.escalate</code></li>
<li><code dir="ltr" translate="no">container.roles.get</code></li>
<li><code dir="ltr" translate="no">container.roles.list</code></li>
<li><code dir="ltr" translate="no">container.roles.update</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.get</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.create</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.get</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.list</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  scheduledJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectRulesReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  createToken</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.get</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.list</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></li>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.create</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.delete</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.get</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.list</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.update</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.get</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.storageStates.create</code></li>
<li><code dir="ltr" translate="no">container.storageStates.delete</code></li>
<li><code dir="ltr" translate="no">container.storageStates.get</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.storageStates.list</code></li>
<li><code dir="ltr" translate="no">container.storageStates.update</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  update</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  update</code></li>
<li><code dir="ltr" translate="no">container.tokenReviews.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.get</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.list</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.update</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.features.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.features.create</code></li>
<li><code dir="ltr" translate="no">gkehub.features.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.features.get</code></li>
<li><code dir="ltr" translate="no">gkehub.features.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.features.list</code></li>
<li><code dir="ltr" translate="no">gkehub.features.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.features.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.fleet.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.fleet.create</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.createFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.get</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.getFreeTrial</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.update</code></li>
<li><code dir="ltr" translate="no">gkehub.fleet.updateFreeTrial</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.gateway.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.gateway.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.get</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.patch</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.post</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.put</code></li>
<li><code dir="ltr" translate="no">gkehub.gateway.stream</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipbindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipbindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipbindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.membershipfeatures.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  create</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  delete</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.get</code></li>
<li><code dir="ltr" translate="no">gkehub.membershipfeatures.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  membershipfeatures.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.memberships.create</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  generateConnectManifest</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.get</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.list</code></li>
<li><code dir="ltr" translate="no">gkehub.  memberships.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">gkehub.memberships.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.namespaces.create</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.get</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.list</code></li>
<li><code dir="ltr" translate="no">gkehub.namespaces.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.rbacrolebindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.create</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.delete</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.get</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.list</code></li>
<li><code dir="ltr" translate="no">gkehub.rbacrolebindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.scopes.create</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.get</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.list</code></p>
<p><code dir="ltr" translate="no">gkehub.  scopes.  listBoundMemberships</code></p>
<p><code dir="ltr" translate="no">gkehub.scopes.update</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">meshconfig.projects.init</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.serviceAgent" class="role-title add-link" data-text="KRM API Hosting Service Agent" tabindex="-1">KRM API Hosting Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  krmapihosting.serviceAgent</code> )</p>
<p>Gives KRM API Hosting service account access to managed resource.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.regions.get</code></p>
<p><code dir="ltr" translate="no">container.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.apiServices.create</code></li>
<li><code dir="ltr" translate="no">container.apiServices.delete</code></li>
<li><code dir="ltr" translate="no">container.apiServices.get</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.apiServices.list</code></li>
<li><code dir="ltr" translate="no">container.apiServices.update</code></li>
<li><code dir="ltr" translate="no">container.  apiServices.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.create</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.delete</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.get</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.list</code></li>
<li><code dir="ltr" translate="no">container.auditSinks.update</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.bindings.create</code></li>
<li><code dir="ltr" translate="no">container.bindings.delete</code></li>
<li><code dir="ltr" translate="no">container.bindings.get</code></li>
<li><code dir="ltr" translate="no">container.bindings.list</code></li>
<li><code dir="ltr" translate="no">container.bindings.update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  approve</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  create</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  delete</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  update</code></li>
<li><code dir="ltr" translate="no">container.  certificateSigningRequests.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
<li><code dir="ltr" translate="no">container.clusters.connect</code></li>
<li><code dir="ltr" translate="no">container.clusters.create</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">container.clusters.get</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  getCredentials</code></li>
<li><code dir="ltr" translate="no">container.clusters.impersonate</code></li>
<li><code dir="ltr" translate="no">container.clusters.list</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">container.clusters.update</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.create</code></li>
<li><code dir="ltr" translate="no">container.configMaps.delete</code></li>
<li><code dir="ltr" translate="no">container.configMaps.get</code></li>
<li><code dir="ltr" translate="no">container.configMaps.list</code></li>
<li><code dir="ltr" translate="no">container.configMaps.update</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  create</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></li>
<li><code dir="ltr" translate="no">container.  controllerRevisions.  update</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.create</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.get</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.list</code></li>
<li><code dir="ltr" translate="no">container.cronJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  cronJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.create</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.delete</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.get</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.list</code></li>
<li><code dir="ltr" translate="no">container.csiDrivers.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodeInfos.update</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.create</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.delete</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.get</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.list</code></li>
<li><code dir="ltr" translate="no">container.csiNodes.update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></li>
<li><code dir="ltr" translate="no">container.  customResourceDefinitions.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  create</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  delete</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.get</code></li>
<li><code dir="ltr" translate="no">container.endpointSlices.list</code></li>
<li><code dir="ltr" translate="no">container.  endpointSlices.  update</code></li>
<li><code dir="ltr" translate="no">container.endpoints.create</code></li>
<li><code dir="ltr" translate="no">container.endpoints.delete</code></li>
<li><code dir="ltr" translate="no">container.endpoints.get</code></li>
<li><code dir="ltr" translate="no">container.endpoints.list</code></li>
<li><code dir="ltr" translate="no">container.endpoints.update</code></li>
<li><code dir="ltr" translate="no">container.events.create</code></li>
<li><code dir="ltr" translate="no">container.events.delete</code></li>
<li><code dir="ltr" translate="no">container.events.get</code></li>
<li><code dir="ltr" translate="no">container.events.list</code></li>
<li><code dir="ltr" translate="no">container.events.update</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  create</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  update</code></li>
<li><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.hostServiceAgent.use</code></li>
<li><code dir="ltr" translate="no">container.ingresses.create</code></li>
<li><code dir="ltr" translate="no">container.ingresses.delete</code></li>
<li><code dir="ltr" translate="no">container.ingresses.get</code></li>
<li><code dir="ltr" translate="no">container.ingresses.getStatus</code></li>
<li><code dir="ltr" translate="no">container.ingresses.list</code></li>
<li><code dir="ltr" translate="no">container.ingresses.update</code></li>
<li><code dir="ltr" translate="no">container.  ingresses.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  initializerConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.jobs.create</code></li>
<li><code dir="ltr" translate="no">container.jobs.delete</code></li>
<li><code dir="ltr" translate="no">container.jobs.get</code></li>
<li><code dir="ltr" translate="no">container.jobs.getStatus</code></li>
<li><code dir="ltr" translate="no">container.jobs.list</code></li>
<li><code dir="ltr" translate="no">container.jobs.update</code></li>
<li><code dir="ltr" translate="no">container.jobs.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.leases.create</code></li>
<li><code dir="ltr" translate="no">container.leases.delete</code></li>
<li><code dir="ltr" translate="no">container.leases.get</code></li>
<li><code dir="ltr" translate="no">container.leases.list</code></li>
<li><code dir="ltr" translate="no">container.leases.update</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.create</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.delete</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.get</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.list</code></li>
<li><code dir="ltr" translate="no">container.limitRanges.update</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  localSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  create</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  get</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  list</code></li>
<li><code dir="ltr" translate="no">container.  managedCertificates.  update</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.namespaces.create</code></li>
<li><code dir="ltr" translate="no">container.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">container.namespaces.finalize</code></li>
<li><code dir="ltr" translate="no">container.namespaces.get</code></li>
<li><code dir="ltr" translate="no">container.namespaces.getStatus</code></li>
<li><code dir="ltr" translate="no">container.namespaces.list</code></li>
<li><code dir="ltr" translate="no">container.namespaces.update</code></li>
<li><code dir="ltr" translate="no">container.  namespaces.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.get</code></li>
<li><code dir="ltr" translate="no">container.networkPolicies.list</code></li>
<li><code dir="ltr" translate="no">container.  networkPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.nodes.create</code></li>
<li><code dir="ltr" translate="no">container.nodes.delete</code></li>
<li><code dir="ltr" translate="no">container.nodes.get</code></li>
<li><code dir="ltr" translate="no">container.nodes.getStatus</code></li>
<li><code dir="ltr" translate="no">container.nodes.list</code></li>
<li><code dir="ltr" translate="no">container.nodes.proxy</code></li>
<li><code dir="ltr" translate="no">container.nodes.update</code></li>
<li><code dir="ltr" translate="no">container.nodes.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumeClaims.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  create</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  delete</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  update</code></li>
<li><code dir="ltr" translate="no">container.  persistentVolumes.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.petSets.create</code></li>
<li><code dir="ltr" translate="no">container.petSets.delete</code></li>
<li><code dir="ltr" translate="no">container.petSets.get</code></li>
<li><code dir="ltr" translate="no">container.petSets.list</code></li>
<li><code dir="ltr" translate="no">container.petSets.update</code></li>
<li><code dir="ltr" translate="no">container.petSets.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  create</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  update</code></li>
<li><code dir="ltr" translate="no">container.  podDisruptionBudgets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.podPresets.create</code></li>
<li><code dir="ltr" translate="no">container.podPresets.delete</code></li>
<li><code dir="ltr" translate="no">container.podPresets.get</code></li>
<li><code dir="ltr" translate="no">container.podPresets.list</code></li>
<li><code dir="ltr" translate="no">container.podPresets.update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  create</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  delete</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  update</code></li>
<li><code dir="ltr" translate="no">container.  podSecurityPolicies.  use</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.create</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.delete</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.get</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.list</code></li>
<li><code dir="ltr" translate="no">container.podTemplates.update</code></li>
<li><code dir="ltr" translate="no">container.pods.attach</code></li>
<li><code dir="ltr" translate="no">container.pods.create</code></li>
<li><code dir="ltr" translate="no">container.pods.delete</code></li>
<li><code dir="ltr" translate="no">container.pods.evict</code></li>
<li><code dir="ltr" translate="no">container.pods.exec</code></li>
<li><code dir="ltr" translate="no">container.pods.get</code></li>
<li><code dir="ltr" translate="no">container.pods.getLogs</code></li>
<li><code dir="ltr" translate="no">container.pods.getStatus</code></li>
<li><code dir="ltr" translate="no">container.pods.initialize</code></li>
<li><code dir="ltr" translate="no">container.pods.list</code></li>
<li><code dir="ltr" translate="no">container.pods.portForward</code></li>
<li><code dir="ltr" translate="no">container.pods.proxy</code></li>
<li><code dir="ltr" translate="no">container.pods.update</code></li>
<li><code dir="ltr" translate="no">container.pods.updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.get</code></li>
<li><code dir="ltr" translate="no">container.priorityClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  priorityClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.create</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.delete</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.get</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.list</code></li>
<li><code dir="ltr" translate="no">container.replicaSets.update</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicaSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  create</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  delete</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  get</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  list</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  update</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  replicationControllers.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  create</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  delete</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.get</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.resourceQuotas.list</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  update</code></li>
<li><code dir="ltr" translate="no">container.  resourceQuotas.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.create</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.delete</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.get</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.list</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.update</code></li>
<li><code dir="ltr" translate="no">container.roles.bind</code></li>
<li><code dir="ltr" translate="no">container.roles.create</code></li>
<li><code dir="ltr" translate="no">container.roles.delete</code></li>
<li><code dir="ltr" translate="no">container.roles.escalate</code></li>
<li><code dir="ltr" translate="no">container.roles.get</code></li>
<li><code dir="ltr" translate="no">container.roles.list</code></li>
<li><code dir="ltr" translate="no">container.roles.update</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.get</code></li>
<li><code dir="ltr" translate="no">container.runtimeClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  runtimeClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.create</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.delete</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.get</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.list</code></li>
<li><code dir="ltr" translate="no">container.scheduledJobs.update</code></li>
<li><code dir="ltr" translate="no">container.  scheduledJobs.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.secrets.create</code></li>
<li><code dir="ltr" translate="no">container.secrets.delete</code></li>
<li><code dir="ltr" translate="no">container.secrets.get</code></li>
<li><code dir="ltr" translate="no">container.secrets.list</code></li>
<li><code dir="ltr" translate="no">container.secrets.update</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  selfSubjectRulesReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  createToken</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.get</code></li>
<li><code dir="ltr" translate="no">container.serviceAccounts.list</code></li>
<li><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></li>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.create</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.delete</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.get</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.list</code></li>
<li><code dir="ltr" translate="no">container.statefulSets.update</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  statefulSets.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.get</code></li>
<li><code dir="ltr" translate="no">container.storageClasses.list</code></li>
<li><code dir="ltr" translate="no">container.  storageClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.storageStates.create</code></li>
<li><code dir="ltr" translate="no">container.storageStates.delete</code></li>
<li><code dir="ltr" translate="no">container.storageStates.get</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.storageStates.list</code></li>
<li><code dir="ltr" translate="no">container.storageStates.update</code></li>
<li><code dir="ltr" translate="no">container.  storageStates.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  create</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  update</code></li>
<li><code dir="ltr" translate="no">container.  storageVersionMigrations.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  create</code></li>
<li><code dir="ltr" translate="no">container.  subjectAccessReviews.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyResources.  update</code></li>
<li><code dir="ltr" translate="no">container.tokenReviews.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.create</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.delete</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.get</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.list</code></li>
<li><code dir="ltr" translate="no">container.updateInfos.update</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  create</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  delete</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></li>
<li><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeAttachments.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  delete</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshotContents.  updateStatus</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  create</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  delete</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.get</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.volumeSnapshots.list</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  update</code></li>
<li><code dir="ltr" translate="no">container.  volumeSnapshots.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## KRM API Hosting permissions

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
<td><h4 id="krmapihosting.krmApiHosts.create" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.create" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.krmApiHosts.createTagBinding" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.krmApiHosts.delete" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.delete" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.krmApiHosts.deleteTagBinding" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.krmApiHosts.get" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.get" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.krmApiHosts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.krmApiHosts.getIamPolicy" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.krmApiHosts.list" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.list" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.krmApiHosts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.krmApiHosts.listEffectiveTags" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.krmApiHosts.listTagBindings" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.krmApiHosts.setIamPolicy" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.krmApiHosts.update" class="permission-name add-link" data-text="krmapihosting.krmApiHosts.update" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.locations.get" class="permission-name add-link" data-text="krmapihosting.locations.get" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.locations.list" class="permission-name add-link" data-text="krmapihosting.locations.list" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.operations.cancel" class="permission-name add-link" data-text="krmapihosting.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.operations.delete" class="permission-name add-link" data-text="krmapihosting.operations.delete" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="krmapihosting.operations.get" class="permission-name add-link" data-text="krmapihosting.operations.get" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="krmapihosting.operations.list" class="permission-name add-link" data-text="krmapihosting.operations.list" tabindex="-1"><code dir="ltr" translate="no">krmapihosting.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin">Config Controller Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor">Config Controller Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer">Config Controller Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  krmapihosting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
