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
<td>Config Controller Admin
<p>( <code>roles/ krmapihosting.admin</code> )</p>
<p>Full access to all Config Controller resources.</p></td>
<td><p><code>krmapihosting.*</code></p>
<ul>
<li><code>krmapihosting. krmApiHosts. create</code></li>
<li><code>krmapihosting. krmApiHosts. createTagBinding</code></li>
<li><code>krmapihosting. krmApiHosts. delete</code></li>
<li><code>krmapihosting. krmApiHosts. deleteTagBinding</code></li>
<li><code>krmapihosting.krmApiHosts.get</code></li>
<li><code>krmapihosting. krmApiHosts. getIamPolicy</code></li>
<li><code>krmapihosting.krmApiHosts.list</code></li>
<li><code>krmapihosting. krmApiHosts. listEffectiveTags</code></li>
<li><code>krmapihosting. krmApiHosts. listTagBindings</code></li>
<li><code>krmapihosting. krmApiHosts. setIamPolicy</code></li>
<li><code>krmapihosting. krmApiHosts. update</code></li>
<li><code>krmapihosting.locations.get</code></li>
<li><code>krmapihosting.locations.list</code></li>
<li><code>krmapihosting. operations. cancel</code></li>
<li><code>krmapihosting. operations. delete</code></li>
<li><code>krmapihosting.operations.get</code></li>
<li><code>krmapihosting.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Config Controller Editor
<p>( <code>roles/ krmapihosting.editor</code> )</p>
<p>Editor role for Config Controller</p></td>
<td><p><code>krmapihosting. krmApiHosts. create</code></p>
<p><code>krmapihosting. krmApiHosts. delete</code></p>
<p><code>krmapihosting.krmApiHosts.get</code></p>
<p><code>krmapihosting. krmApiHosts. getIamPolicy</code></p>
<p><code>krmapihosting.krmApiHosts.list</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>krmapihosting. krmApiHosts. update</code></p>
<p><code>krmapihosting.locations.*</code></p>
<ul>
<li><code>krmapihosting.locations.get</code></li>
<li><code>krmapihosting.locations.list</code></li>
</ul>
<p><code>krmapihosting.operations.*</code></p>
<ul>
<li><code>krmapihosting. operations. cancel</code></li>
<li><code>krmapihosting. operations. delete</code></li>
<li><code>krmapihosting.operations.get</code></li>
<li><code>krmapihosting.operations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Config Controller Viewer
<p>( <code>roles/ krmapihosting.viewer</code> )</p>
<p>Read-only access to all Config Controller resources.</p></td>
<td><p><code>krmapihosting.krmApiHosts.get</code></p>
<p><code>krmapihosting. krmApiHosts. getIamPolicy</code></p>
<p><code>krmapihosting.krmApiHosts.list</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>krmapihosting.locations.*</code></p>
<ul>
<li><code>krmapihosting.locations.get</code></li>
<li><code>krmapihosting.locations.list</code></li>
</ul>
<p><code>krmapihosting.operations.get</code></p>
<p><code>krmapihosting.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>KRM API Hosting AnthosApiEndpoint Service Agent
<p>( <code>roles/ krmapihosting.anthosApiEndpointServiceAgent</code> )</p>
<p>Grants permissions to resources managed by AnthosApiEndpoint.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute. instanceGroupManagers. get</code></p>
<p><code>container.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
<li><code>container. certificateSigningRequests. approve</code></li>
<li><code>container. certificateSigningRequests. create</code></li>
<li><code>container. certificateSigningRequests. delete</code></li>
<li><code>container. certificateSigningRequests. get</code></li>
<li><code>container. certificateSigningRequests. getStatus</code></li>
<li><code>container. certificateSigningRequests. list</code></li>
<li><code>container. certificateSigningRequests. update</code></li>
<li><code>container. certificateSigningRequests. updateStatus</code></li>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
<li><code>container.clusters.connect</code></li>
<li><code>container.clusters.create</code></li>
<li><code>container. clusters. createTagBinding</code></li>
<li><code>container.clusters.delete</code></li>
<li><code>container. clusters. deleteTagBinding</code></li>
<li><code>container.clusters.get</code></li>
<li><code>container. clusters. getCredentials</code></li>
<li><code>container.clusters.impersonate</code></li>
<li><code>container.clusters.list</code></li>
<li><code>container. clusters. listEffectiveTags</code></li>
<li><code>container. clusters. listTagBindings</code></li>
<li><code>container.clusters.update</code></li>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
<li><code>container. controllerRevisions. create</code></li>
<li><code>container. controllerRevisions. delete</code></li>
<li><code>container. controllerRevisions. get</code></li>
<li><code>container. controllerRevisions. list</code></li>
<li><code>container. controllerRevisions. update</code></li>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
<li><code>container.hostServiceAgent.use</code></li>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
<li><code>container. mutatingWebhookConfigurations. create</code></li>
<li><code>container. mutatingWebhookConfigurations. delete</code></li>
<li><code>container. mutatingWebhookConfigurations. get</code></li>
<li><code>container. mutatingWebhookConfigurations. list</code></li>
<li><code>container. mutatingWebhookConfigurations. update</code></li>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
<li><code>container. podSecurityPolicies. create</code></li>
<li><code>container. podSecurityPolicies. delete</code></li>
<li><code>container. podSecurityPolicies. get</code></li>
<li><code>container. podSecurityPolicies. list</code></li>
<li><code>container. podSecurityPolicies. update</code></li>
<li><code>container. podSecurityPolicies. use</code></li>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
<li><code>container.pods.attach</code></li>
<li><code>container.pods.create</code></li>
<li><code>container.pods.delete</code></li>
<li><code>container.pods.evict</code></li>
<li><code>container.pods.exec</code></li>
<li><code>container.pods.get</code></li>
<li><code>container.pods.getLogs</code></li>
<li><code>container.pods.getStatus</code></li>
<li><code>container.pods.initialize</code></li>
<li><code>container.pods.list</code></li>
<li><code>container.pods.portForward</code></li>
<li><code>container.pods.proxy</code></li>
<li><code>container.pods.update</code></li>
<li><code>container.pods.updateStatus</code></li>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
<li><code>container.roleBindings.create</code></li>
<li><code>container.roleBindings.delete</code></li>
<li><code>container.roleBindings.get</code></li>
<li><code>container.roleBindings.list</code></li>
<li><code>container.roleBindings.update</code></li>
<li><code>container.roles.bind</code></li>
<li><code>container.roles.create</code></li>
<li><code>container.roles.delete</code></li>
<li><code>container.roles.escalate</code></li>
<li><code>container.roles.get</code></li>
<li><code>container.roles.list</code></li>
<li><code>container.roles.update</code></li>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
<li><code>container. selfSubjectRulesReviews. create</code></li>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
<li><code>container.tokenReviews.create</code></li>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>gkehub.endpoints.connect</code></p>
<p><code>gkehub.features.*</code></p>
<ul>
<li><code>gkehub.features.create</code></li>
<li><code>gkehub.features.delete</code></li>
<li><code>gkehub.features.get</code></li>
<li><code>gkehub.features.getIamPolicy</code></li>
<li><code>gkehub.features.list</code></li>
<li><code>gkehub.features.setIamPolicy</code></li>
<li><code>gkehub.features.update</code></li>
</ul>
<p><code>gkehub.fleet.*</code></p>
<ul>
<li><code>gkehub.fleet.create</code></li>
<li><code>gkehub.fleet.createFreeTrial</code></li>
<li><code>gkehub.fleet.delete</code></li>
<li><code>gkehub.fleet.get</code></li>
<li><code>gkehub.fleet.getFreeTrial</code></li>
<li><code>gkehub.fleet.update</code></li>
<li><code>gkehub.fleet.updateFreeTrial</code></li>
</ul>
<p><code>gkehub.gateway.*</code></p>
<ul>
<li><code>gkehub.gateway.delete</code></li>
<li><code>gkehub. gateway. generateCredentials</code></li>
<li><code>gkehub.gateway.get</code></li>
<li><code>gkehub.gateway.patch</code></li>
<li><code>gkehub.gateway.post</code></li>
<li><code>gkehub.gateway.put</code></li>
<li><code>gkehub.gateway.stream</code></li>
</ul>
<p><code>gkehub.locations.*</code></p>
<ul>
<li><code>gkehub.locations.get</code></li>
<li><code>gkehub.locations.list</code></li>
</ul>
<p><code>gkehub.membershipbindings.*</code></p>
<ul>
<li><code>gkehub. membershipbindings. create</code></li>
<li><code>gkehub. membershipbindings. delete</code></li>
<li><code>gkehub.membershipbindings.get</code></li>
<li><code>gkehub.membershipbindings.list</code></li>
<li><code>gkehub. membershipbindings. update</code></li>
</ul>
<p><code>gkehub.membershipfeatures.*</code></p>
<ul>
<li><code>gkehub. membershipfeatures. create</code></li>
<li><code>gkehub. membershipfeatures. delete</code></li>
<li><code>gkehub.membershipfeatures.get</code></li>
<li><code>gkehub.membershipfeatures.list</code></li>
<li><code>gkehub. membershipfeatures. update</code></li>
</ul>
<p><code>gkehub.memberships.*</code></p>
<ul>
<li><code>gkehub.memberships.create</code></li>
<li><code>gkehub.memberships.delete</code></li>
<li><code>gkehub. memberships. generateConnectManifest</code></li>
<li><code>gkehub.memberships.get</code></li>
<li><code>gkehub. memberships. getIamPolicy</code></li>
<li><code>gkehub.memberships.list</code></li>
<li><code>gkehub. memberships. setIamPolicy</code></li>
<li><code>gkehub.memberships.update</code></li>
</ul>
<p><code>gkehub.namespaces.*</code></p>
<ul>
<li><code>gkehub.namespaces.create</code></li>
<li><code>gkehub.namespaces.delete</code></li>
<li><code>gkehub.namespaces.get</code></li>
<li><code>gkehub.namespaces.list</code></li>
<li><code>gkehub.namespaces.update</code></li>
</ul>
<p><code>gkehub.operations.*</code></p>
<ul>
<li><code>gkehub.operations.cancel</code></li>
<li><code>gkehub.operations.delete</code></li>
<li><code>gkehub.operations.get</code></li>
<li><code>gkehub.operations.list</code></li>
</ul>
<p><code>gkehub.rbacrolebindings.*</code></p>
<ul>
<li><code>gkehub.rbacrolebindings.create</code></li>
<li><code>gkehub.rbacrolebindings.delete</code></li>
<li><code>gkehub.rbacrolebindings.get</code></li>
<li><code>gkehub.rbacrolebindings.list</code></li>
<li><code>gkehub.rbacrolebindings.update</code></li>
</ul>
<p><code>gkehub.scopes.create</code></p>
<p><code>gkehub.scopes.delete</code></p>
<p><code>gkehub.scopes.get</code></p>
<p><code>gkehub.scopes.getIamPolicy</code></p>
<p><code>gkehub.scopes.list</code></p>
<p><code>gkehub. scopes. listBoundMemberships</code></p>
<p><code>gkehub.scopes.update</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>meshconfig.projects.init</code></p>
<p><code>recommender. containerDiagnosisInsights.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisInsights. get</code></li>
<li><code>recommender. containerDiagnosisInsights. list</code></li>
<li><code>recommender. containerDiagnosisInsights. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisRecommendations. get</code></li>
<li><code>recommender. containerDiagnosisRecommendations. list</code></li>
<li><code>recommender. containerDiagnosisRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. update</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
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
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
<tr class="even">
<td>KRM API Hosting Service Agent
<p>( <code>roles/ krmapihosting.serviceAgent</code> )</p>
<p>Gives KRM API Hosting service account access to managed resource.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute.regions.get</code></p>
<p><code>container.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
<li><code>container. certificateSigningRequests. approve</code></li>
<li><code>container. certificateSigningRequests. create</code></li>
<li><code>container. certificateSigningRequests. delete</code></li>
<li><code>container. certificateSigningRequests. get</code></li>
<li><code>container. certificateSigningRequests. getStatus</code></li>
<li><code>container. certificateSigningRequests. list</code></li>
<li><code>container. certificateSigningRequests. update</code></li>
<li><code>container. certificateSigningRequests. updateStatus</code></li>
<li><code>container. clusterRoleBindings. create</code></li>
<li><code>container. clusterRoleBindings. delete</code></li>
<li><code>container. clusterRoleBindings. get</code></li>
<li><code>container. clusterRoleBindings. list</code></li>
<li><code>container. clusterRoleBindings. update</code></li>
<li><code>container.clusterRoles.bind</code></li>
<li><code>container.clusterRoles.create</code></li>
<li><code>container.clusterRoles.delete</code></li>
<li><code>container. clusterRoles. escalate</code></li>
<li><code>container.clusterRoles.get</code></li>
<li><code>container.clusterRoles.list</code></li>
<li><code>container.clusterRoles.update</code></li>
<li><code>container.clusters.connect</code></li>
<li><code>container.clusters.create</code></li>
<li><code>container. clusters. createTagBinding</code></li>
<li><code>container.clusters.delete</code></li>
<li><code>container. clusters. deleteTagBinding</code></li>
<li><code>container.clusters.get</code></li>
<li><code>container. clusters. getCredentials</code></li>
<li><code>container.clusters.impersonate</code></li>
<li><code>container.clusters.list</code></li>
<li><code>container. clusters. listEffectiveTags</code></li>
<li><code>container. clusters. listTagBindings</code></li>
<li><code>container.clusters.update</code></li>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
<li><code>container. controllerRevisions. create</code></li>
<li><code>container. controllerRevisions. delete</code></li>
<li><code>container. controllerRevisions. get</code></li>
<li><code>container. controllerRevisions. list</code></li>
<li><code>container. controllerRevisions. update</code></li>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
<li><code>container.daemonSets.create</code></li>
<li><code>container.daemonSets.delete</code></li>
<li><code>container.daemonSets.get</code></li>
<li><code>container.daemonSets.getStatus</code></li>
<li><code>container.daemonSets.list</code></li>
<li><code>container.daemonSets.update</code></li>
<li><code>container. daemonSets. updateStatus</code></li>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
<li><code>container.hostServiceAgent.use</code></li>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
<li><code>container. mutatingWebhookConfigurations. create</code></li>
<li><code>container. mutatingWebhookConfigurations. delete</code></li>
<li><code>container. mutatingWebhookConfigurations. get</code></li>
<li><code>container. mutatingWebhookConfigurations. list</code></li>
<li><code>container. mutatingWebhookConfigurations. update</code></li>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
<li><code>container. podSecurityPolicies. create</code></li>
<li><code>container. podSecurityPolicies. delete</code></li>
<li><code>container. podSecurityPolicies. get</code></li>
<li><code>container. podSecurityPolicies. list</code></li>
<li><code>container. podSecurityPolicies. update</code></li>
<li><code>container. podSecurityPolicies. use</code></li>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
<li><code>container.pods.attach</code></li>
<li><code>container.pods.create</code></li>
<li><code>container.pods.delete</code></li>
<li><code>container.pods.evict</code></li>
<li><code>container.pods.exec</code></li>
<li><code>container.pods.get</code></li>
<li><code>container.pods.getLogs</code></li>
<li><code>container.pods.getStatus</code></li>
<li><code>container.pods.initialize</code></li>
<li><code>container.pods.list</code></li>
<li><code>container.pods.portForward</code></li>
<li><code>container.pods.proxy</code></li>
<li><code>container.pods.update</code></li>
<li><code>container.pods.updateStatus</code></li>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
<li><code>container.roleBindings.create</code></li>
<li><code>container.roleBindings.delete</code></li>
<li><code>container.roleBindings.get</code></li>
<li><code>container.roleBindings.list</code></li>
<li><code>container.roleBindings.update</code></li>
<li><code>container.roles.bind</code></li>
<li><code>container.roles.create</code></li>
<li><code>container.roles.delete</code></li>
<li><code>container.roles.escalate</code></li>
<li><code>container.roles.get</code></li>
<li><code>container.roles.list</code></li>
<li><code>container.roles.update</code></li>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
<li><code>container. selfSubjectRulesReviews. create</code></li>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
<li><code>container.tokenReviews.create</code></li>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>recommender. containerDiagnosisInsights.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisInsights. get</code></li>
<li><code>recommender. containerDiagnosisInsights. list</code></li>
<li><code>recommender. containerDiagnosisInsights. update</code></li>
</ul>
<p><code>recommender. containerDiagnosisRecommendations.*</code></p>
<ul>
<li><code>recommender. containerDiagnosisRecommendations. get</code></li>
<li><code>recommender. containerDiagnosisRecommendations. list</code></li>
<li><code>recommender. containerDiagnosisRecommendations. update</code></li>
</ul>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeConnectivityInsights. update</code></li>
</ul>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights.*</code></p>
<ul>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></li>
<li><code>recommender. networkAnalyzerGkeIpAddressInsights. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## KRM API Hosting permissions

| Permission                                      | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `krmapihosting. krmApiHosts. create`            | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `krmapihosting. krmApiHosts. createTagBinding`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `krmapihosting. krmApiHosts. delete`            | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `krmapihosting. krmApiHosts. deleteTagBinding`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| `krmapihosting.krmApiHosts.get`                 | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `krmapihosting. krmApiHosts. getIamPolicy`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                   |
| `krmapihosting.krmApiHosts.list`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                   |
| `krmapihosting. krmApiHosts. listEffectiveTags` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Tag Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer) ( `roles/ resourcemanager.tagViewer` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `krmapihosting. krmApiHosts. listTagBindings`   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Tag User](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser) ( `roles/ resourcemanager.tagUser` ) [Tag Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer) ( `roles/ resourcemanager.tagViewer` ) [DLP Organization Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver) ( `roles/ dlp.orgdriver` ) [DLP Project Data Profiles Driver](https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver) ( `roles/ dlp.projectdriver` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `krmapihosting. krmApiHosts. setIamPolicy`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `krmapihosting. krmApiHosts. update`            | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `krmapihosting.locations.get`                   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `krmapihosting.locations.list`                  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                   |
| `krmapihosting. operations. cancel`             | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `krmapihosting. operations. delete`             | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `krmapihosting.operations.get`                  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `krmapihosting.operations.list`                 | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Config Controller Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.admin) ( `roles/ krmapihosting.admin` ) [Config Controller Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.editor) ( `roles/ krmapihosting.editor` ) [Config Controller Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/krmapihosting#krmapihosting.viewer) ( `roles/ krmapihosting.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                   |
