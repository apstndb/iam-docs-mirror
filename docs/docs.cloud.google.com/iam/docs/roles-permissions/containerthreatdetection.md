---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/containerthreatdetection
title: Container Threat Detection roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Container Threat Detection. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Container Threat Detection roles

Container Threat Detection offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="containerthreatdetection.serviceAgent" class="role-title add-link" data-text="Container Threat Detection Service Agent" tabindex="-1">Container Threat Detection Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  containerthreatdetection.serviceAgent</code> )</p>
<p>Gives Container Threat Detection service account access to enable/disable Container Threat Detection and manage the Container Threat Detection Agent on Google Kubernetes Engine clusters.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">container.apiServices.get</code></p>
<p><code dir="ltr" translate="no">container.  apiServices.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.apiServices.list</code></p>
<p><code dir="ltr" translate="no">container.auditSinks.get</code></p>
<p><code dir="ltr" translate="no">container.auditSinks.list</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.get</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.bindings.get</code></p>
<p><code dir="ltr" translate="no">container.bindings.list</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  get</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  certificateSigningRequests.  list</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  create</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoleBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusterRoles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.clusterRoles.bind</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.create</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.delete</code></li>
<li><code dir="ltr" translate="no">container.  clusterRoles.  escalate</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.get</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.list</code></li>
<li><code dir="ltr" translate="no">container.clusterRoles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.connect</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.componentStatuses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  componentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">container.  componentStatuses.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.configMaps.get</code></p>
<p><code dir="ltr" translate="no">container.configMaps.list</code></p>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  get</code></p>
<p><code dir="ltr" translate="no">container.  controllerRevisions.  list</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.get</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.getStatus</code></p>
<p><code dir="ltr" translate="no">container.cronJobs.list</code></p>
<p><code dir="ltr" translate="no">container.csiDrivers.get</code></p>
<p><code dir="ltr" translate="no">container.csiDrivers.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodeInfos.get</code></p>
<p><code dir="ltr" translate="no">container.csiNodeInfos.list</code></p>
<p><code dir="ltr" translate="no">container.csiNodes.get</code></p>
<p><code dir="ltr" translate="no">container.csiNodes.list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></p>
<p><code dir="ltr" translate="no">container.daemonSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.daemonSets.create</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.delete</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.get</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.getStatus</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.list</code></li>
<li><code dir="ltr" translate="no">container.daemonSets.update</code></li>
<li><code dir="ltr" translate="no">container.  daemonSets.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.deployments.get</code></p>
<p><code dir="ltr" translate="no">container.deployments.getScale</code></p>
<p><code dir="ltr" translate="no">container.  deployments.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.deployments.list</code></p>
<p><code dir="ltr" translate="no">container.endpointSlices.get</code></p>
<p><code dir="ltr" translate="no">container.endpointSlices.list</code></p>
<p><code dir="ltr" translate="no">container.endpoints.get</code></p>
<p><code dir="ltr" translate="no">container.endpoints.list</code></p>
<p><code dir="ltr" translate="no">container.events.get</code></p>
<p><code dir="ltr" translate="no">container.events.list</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.get</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.list</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  get</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  horizontalPodAutoscalers.  list</code></p>
<p><code dir="ltr" translate="no">container.ingresses.get</code></p>
<p><code dir="ltr" translate="no">container.ingresses.getStatus</code></p>
<p><code dir="ltr" translate="no">container.ingresses.list</code></p>
<p><code dir="ltr" translate="no">container.  initializerConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  initializerConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.jobs.get</code></p>
<p><code dir="ltr" translate="no">container.jobs.getStatus</code></p>
<p><code dir="ltr" translate="no">container.jobs.list</code></p>
<p><code dir="ltr" translate="no">container.leases.get</code></p>
<p><code dir="ltr" translate="no">container.leases.list</code></p>
<p><code dir="ltr" translate="no">container.limitRanges.get</code></p>
<p><code dir="ltr" translate="no">container.limitRanges.list</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  get</code></p>
<p><code dir="ltr" translate="no">container.  managedCertificates.  list</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  mutatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.namespaces.get</code></p>
<p><code dir="ltr" translate="no">container.namespaces.getStatus</code></p>
<p><code dir="ltr" translate="no">container.namespaces.list</code></p>
<p><code dir="ltr" translate="no">container.networkPolicies.get</code></p>
<p><code dir="ltr" translate="no">container.networkPolicies.list</code></p>
<p><code dir="ltr" translate="no">container.  networkPolicies.  update</code></p>
<p><code dir="ltr" translate="no">container.nodes.get</code></p>
<p><code dir="ltr" translate="no">container.nodes.getStatus</code></p>
<p><code dir="ltr" translate="no">container.nodes.list</code></p>
<p><code dir="ltr" translate="no">container.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.operations.get</code></li>
<li><code dir="ltr" translate="no">container.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.  get</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumeClaims.  list</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumes.  get</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumes.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  persistentVolumes.  list</code></p>
<p><code dir="ltr" translate="no">container.petSets.get</code></p>
<p><code dir="ltr" translate="no">container.petSets.list</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  get</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  podDisruptionBudgets.  list</code></p>
<p><code dir="ltr" translate="no">container.podPresets.get</code></p>
<p><code dir="ltr" translate="no">container.podPresets.list</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  get</code></p>
<p><code dir="ltr" translate="no">container.  podSecurityPolicies.  list</code></p>
<p><code dir="ltr" translate="no">container.podTemplates.get</code></p>
<p><code dir="ltr" translate="no">container.podTemplates.list</code></p>
<p><code dir="ltr" translate="no">container.pods.attach</code></p>
<p><code dir="ltr" translate="no">container.pods.create</code></p>
<p><code dir="ltr" translate="no">container.pods.delete</code></p>
<p><code dir="ltr" translate="no">container.pods.exec</code></p>
<p><code dir="ltr" translate="no">container.pods.get</code></p>
<p><code dir="ltr" translate="no">container.pods.getLogs</code></p>
<p><code dir="ltr" translate="no">container.pods.getStatus</code></p>
<p><code dir="ltr" translate="no">container.pods.list</code></p>
<p><code dir="ltr" translate="no">container.pods.portForward</code></p>
<p><code dir="ltr" translate="no">container.pods.update</code></p>
<p><code dir="ltr" translate="no">container.priorityClasses.get</code></p>
<p><code dir="ltr" translate="no">container.priorityClasses.list</code></p>
<p><code dir="ltr" translate="no">container.replicaSets.get</code></p>
<p><code dir="ltr" translate="no">container.replicaSets.getScale</code></p>
<p><code dir="ltr" translate="no">container.  replicaSets.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.replicaSets.list</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  get</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  getScale</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  replicationControllers.  list</code></p>
<p><code dir="ltr" translate="no">container.resourceQuotas.get</code></p>
<p><code dir="ltr" translate="no">container.  resourceQuotas.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.resourceQuotas.list</code></p>
<p><code dir="ltr" translate="no">container.roleBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.roleBindings.create</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.delete</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.get</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.list</code></li>
<li><code dir="ltr" translate="no">container.roleBindings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.roles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.roles.bind</code></li>
<li><code dir="ltr" translate="no">container.roles.create</code></li>
<li><code dir="ltr" translate="no">container.roles.delete</code></li>
<li><code dir="ltr" translate="no">container.roles.escalate</code></li>
<li><code dir="ltr" translate="no">container.roles.get</code></li>
<li><code dir="ltr" translate="no">container.roles.list</code></li>
<li><code dir="ltr" translate="no">container.roles.update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.runtimeClasses.get</code></p>
<p><code dir="ltr" translate="no">container.runtimeClasses.list</code></p>
<p><code dir="ltr" translate="no">container.scheduledJobs.get</code></p>
<p><code dir="ltr" translate="no">container.scheduledJobs.list</code></p>
<p><code dir="ltr" translate="no">container.secrets.create</code></p>
<p><code dir="ltr" translate="no">container.secrets.delete</code></p>
<p><code dir="ltr" translate="no">container.secrets.list</code></p>
<p><code dir="ltr" translate="no">container.secrets.update</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  create</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  delete</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">container.serviceAccounts.list</code></p>
<p><code dir="ltr" translate="no">container.  serviceAccounts.  update</code></p>
<p><code dir="ltr" translate="no">container.services.get</code></p>
<p><code dir="ltr" translate="no">container.services.getStatus</code></p>
<p><code dir="ltr" translate="no">container.services.list</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.get</code></p>
<p><code dir="ltr" translate="no">container.  statefulSets.  getScale</code></p>
<p><code dir="ltr" translate="no">container.  statefulSets.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.statefulSets.list</code></p>
<p><code dir="ltr" translate="no">container.storageClasses.get</code></p>
<p><code dir="ltr" translate="no">container.storageClasses.list</code></p>
<p><code dir="ltr" translate="no">container.storageStates.get</code></p>
<p><code dir="ltr" translate="no">container.  storageStates.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.storageStates.list</code></p>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.  get</code></p>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  storageVersionMigrations.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyResources.  get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyResources.  list</code></p>
<p><code dir="ltr" translate="no">container.tokenReviews.create</code></p>
<p><code dir="ltr" translate="no">container.updateInfos.get</code></p>
<p><code dir="ltr" translate="no">container.updateInfos.list</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  get</code></p>
<p><code dir="ltr" translate="no">container.  validatingWebhookConfigurations.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeAttachments.  get</code></p>
<p><code dir="ltr" translate="no">container.  volumeAttachments.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  volumeAttachments.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  get</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotClasses.  list</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.  get</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.  getStatus</code></p>
<p><code dir="ltr" translate="no">container.  volumeSnapshotContents.  list</code></p>
<p><code dir="ltr" translate="no">container.volumeSnapshots.get</code></p>
<p><code dir="ltr" translate="no">container.volumeSnapshots.list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Container Threat Detection permissions

There are no IAM permissions for this service.
