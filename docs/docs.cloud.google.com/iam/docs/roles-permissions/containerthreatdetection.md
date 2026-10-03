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
<td>Container Threat Detection Service Agent
<p>( <code>roles/ containerthreatdetection.serviceAgent</code> )</p>
<p>Gives Container Threat Detection service account access to enable/disable Container Threat Detection and manage the Container Threat Detection Agent on Google Kubernetes Engine clusters.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>container.apiServices.get</code></p>
<p><code>container. apiServices. getStatus</code></p>
<p><code>container.apiServices.list</code></p>
<p><code>container.auditSinks.get</code></p>
<p><code>container.auditSinks.list</code></p>
<p><code>container.backendConfigs.get</code></p>
<p><code>container.backendConfigs.list</code></p>
<p><code>container.bindings.get</code></p>
<p><code>container.bindings.list</code></p>
<p><code>container. certificateSigningRequests. get</code></p>
<p><code>container. certificateSigningRequests. getStatus</code></p>
<p><code>container. certificateSigningRequests. list</code></p>
<p><code>container. clusterRoleBindings.*</code></p>
<ul>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
</ul>
<p><code>container.clusterRoles.*</code></p>
<ul>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
</ul>
<p><code>container.clusters.connect</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.componentStatuses.*</code></p>
<ul>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
</ul>
<p><code>container.configMaps.get</code></p>
<p><code>container.configMaps.list</code></p>
<p><code>container. controllerRevisions. get</code></p>
<p><code>container. controllerRevisions. list</code></p>
<p><code>container.cronJobs.get</code></p>
<p><code>container.cronJobs.getStatus</code></p>
<p><code>container.cronJobs.list</code></p>
<p><code>container.csiDrivers.get</code></p>
<p><code>container.csiDrivers.list</code></p>
<p><code>container.csiNodeInfos.get</code></p>
<p><code>container.csiNodeInfos.list</code></p>
<p><code>container.csiNodes.get</code></p>
<p><code>container.csiNodes.list</code></p>
<p><code>container. customResourceDefinitions. create</code></p>
<p><code>container. customResourceDefinitions. delete</code></p>
<p><code>container. customResourceDefinitions. get</code></p>
<p><code>container. customResourceDefinitions. getStatus</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container. customResourceDefinitions. update</code></p>
<p><code>container.daemonSets.*</code></p>
<ul>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
</ul>
<p><code>container.deployments.get</code></p>
<p><code>container.deployments.getScale</code></p>
<p><code>container. deployments. getStatus</code></p>
<p><code>container.deployments.list</code></p>
<p><code>container.endpointSlices.get</code></p>
<p><code>container.endpointSlices.list</code></p>
<p><code>container.endpoints.get</code></p>
<p><code>container.endpoints.list</code></p>
<p><code>container.events.get</code></p>
<p><code>container.events.list</code></p>
<p><code>container.frontendConfigs.get</code></p>
<p><code>container.frontendConfigs.list</code></p>
<p><code>container. horizontalPodAutoscalers. get</code></p>
<p><code>container. horizontalPodAutoscalers. getStatus</code></p>
<p><code>container. horizontalPodAutoscalers. list</code></p>
<p><code>container.ingresses.get</code></p>
<p><code>container.ingresses.getStatus</code></p>
<p><code>container.ingresses.list</code></p>
<p><code>container. initializerConfigurations. get</code></p>
<p><code>container. initializerConfigurations. list</code></p>
<p><code>container.jobs.get</code></p>
<p><code>container.jobs.getStatus</code></p>
<p><code>container.jobs.list</code></p>
<p><code>container.leases.get</code></p>
<p><code>container.leases.list</code></p>
<p><code>container.limitRanges.get</code></p>
<p><code>container.limitRanges.list</code></p>
<p><code>container. managedCertificates. get</code></p>
<p><code>container. managedCertificates. list</code></p>
<p><code>container. mutatingWebhookConfigurations. get</code></p>
<p><code>container. mutatingWebhookConfigurations. list</code></p>
<p><code>container.namespaces.get</code></p>
<p><code>container.namespaces.getStatus</code></p>
<p><code>container.namespaces.list</code></p>
<p><code>container.networkPolicies.get</code></p>
<p><code>container.networkPolicies.list</code></p>
<p><code>container. networkPolicies. update</code></p>
<p><code>container.nodes.get</code></p>
<p><code>container.nodes.getStatus</code></p>
<p><code>container.nodes.list</code></p>
<p><code>container.operations.*</code></p>
<ul>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
</ul>
<p><code>container. persistentVolumeClaims. get</code></p>
<p><code>container. persistentVolumeClaims. getStatus</code></p>
<p><code>container. persistentVolumeClaims. list</code></p>
<p><code>container. persistentVolumes. get</code></p>
<p><code>container. persistentVolumes. getStatus</code></p>
<p><code>container. persistentVolumes. list</code></p>
<p><code>container.petSets.get</code></p>
<p><code>container.petSets.list</code></p>
<p><code>container. podDisruptionBudgets. get</code></p>
<p><code>container. podDisruptionBudgets. getStatus</code></p>
<p><code>container. podDisruptionBudgets. list</code></p>
<p><code>container.podPresets.get</code></p>
<p><code>container.podPresets.list</code></p>
<p><code>container. podSecurityPolicies. get</code></p>
<p><code>container. podSecurityPolicies. list</code></p>
<p><code>container.podTemplates.get</code></p>
<p><code>container.podTemplates.list</code></p>
<p><code>container.pods.attach</code></p>
<p><code>container.pods.create</code></p>
<p><code>container.pods.delete</code></p>
<p><code>container.pods.exec</code></p>
<p><code>container.pods.get</code></p>
<p><code>container.pods.getLogs</code></p>
<p><code>container.pods.getStatus</code></p>
<p><code>container.pods.list</code></p>
<p><code>container.pods.portForward</code></p>
<p><code>container.pods.update</code></p>
<p><code>container.priorityClasses.get</code></p>
<p><code>container.priorityClasses.list</code></p>
<p><code>container.replicaSets.get</code></p>
<p><code>container.replicaSets.getScale</code></p>
<p><code>container. replicaSets. getStatus</code></p>
<p><code>container.replicaSets.list</code></p>
<p><code>container. replicationControllers. get</code></p>
<p><code>container. replicationControllers. getScale</code></p>
<p><code>container. replicationControllers. getStatus</code></p>
<p><code>container. replicationControllers. list</code></p>
<p><code>container.resourceQuotas.get</code></p>
<p><code>container. resourceQuotas. getStatus</code></p>
<p><code>container.resourceQuotas.list</code></p>
<p><code>container.roleBindings.*</code></p>
<ul>
<li><code>container.roleBindings.create</code></li>
<li><code>container.roleBindings.delete</code></li>
<li><code>container.roleBindings.get</code></li>
<li><code>container.roleBindings.list</code></li>
<li><code>container.roleBindings.update</code></li>
</ul>
<p><code>container.roles.*</code></p>
<ul>
<li><code>container.roles.bind</code></li>
<li><code>container.roles.create</code></li>
<li><code>container.roles.delete</code></li>
<li><code>container.roles.escalate</code></li>
<li><code>container.roles.get</code></li>
<li><code>container.roles.list</code></li>
<li><code>container.roles.update</code></li>
</ul>
<p><code>container.runtimeClasses.get</code></p>
<p><code>container.runtimeClasses.list</code></p>
<p><code>container.scheduledJobs.get</code></p>
<p><code>container.scheduledJobs.list</code></p>
<p><code>container.secrets.create</code></p>
<p><code>container.secrets.delete</code></p>
<p><code>container.secrets.list</code></p>
<p><code>container.secrets.update</code></p>
<p><code>container. serviceAccounts. create</code></p>
<p><code>container. serviceAccounts. delete</code></p>
<p><code>container.serviceAccounts.get</code></p>
<p><code>container.serviceAccounts.list</code></p>
<p><code>container. serviceAccounts. update</code></p>
<p><code>container.services.get</code></p>
<p><code>container.services.getStatus</code></p>
<p><code>container.services.list</code></p>
<p><code>container.statefulSets.get</code></p>
<p><code>container. statefulSets. getScale</code></p>
<p><code>container. statefulSets. getStatus</code></p>
<p><code>container.statefulSets.list</code></p>
<p><code>container.storageClasses.get</code></p>
<p><code>container.storageClasses.list</code></p>
<p><code>container.storageStates.get</code></p>
<p><code>container. storageStates. getStatus</code></p>
<p><code>container.storageStates.list</code></p>
<p><code>container. storageVersionMigrations. get</code></p>
<p><code>container. storageVersionMigrations. getStatus</code></p>
<p><code>container. storageVersionMigrations. list</code></p>
<p><code>container. thirdPartyObjects. get</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. thirdPartyResources. get</code></p>
<p><code>container. thirdPartyResources. list</code></p>
<p><code>container.tokenReviews.create</code></p>
<p><code>container.updateInfos.get</code></p>
<p><code>container.updateInfos.list</code></p>
<p><code>container. validatingWebhookConfigurations. get</code></p>
<p><code>container. validatingWebhookConfigurations. list</code></p>
<p><code>container. volumeAttachments. get</code></p>
<p><code>container. volumeAttachments. getStatus</code></p>
<p><code>container. volumeAttachments. list</code></p>
<p><code>container. volumeSnapshotClasses. get</code></p>
<p><code>container. volumeSnapshotClasses. list</code></p>
<p><code>container. volumeSnapshotContents. get</code></p>
<p><code>container. volumeSnapshotContents. getStatus</code></p>
<p><code>container. volumeSnapshotContents. list</code></p>
<p><code>container.volumeSnapshots.get</code></p>
<p><code>container.volumeSnapshots.list</code></p>
<p><code>recommender. containerDiagnosisInsights. get</code></p>
<p><code>recommender. containerDiagnosisInsights. list</code></p>
<p><code>recommender. containerDiagnosisRecommendations. get</code></p>
<p><code>recommender. containerDiagnosisRecommendations. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></p>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Container Threat Detection permissions

There are no IAM permissions for this service.
