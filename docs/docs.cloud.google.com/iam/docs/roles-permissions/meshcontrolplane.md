---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/meshcontrolplane
title: Cloud Service Mesh control plane roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Service Mesh control plane. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Service Mesh control plane roles

Cloud Service Mesh control plane offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Mesh Managed Control Plane Service Agent
<p>( <code>roles/ meshcontrolplane.serviceAgent</code> )</p>
<p>Anthos Service Mesh Managed Control Plane Agent</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>container.apiServices.*</code></p>
<ul>
<li><code>container.apiServices.create</code></li>
<li><code>container.apiServices.delete</code></li>
<li><code>container.apiServices.get</code></li>
<li><code>container. apiServices. getStatus</code></li>
<li><code>container.apiServices.list</code></li>
<li><code>container.apiServices.update</code></li>
<li><code>container. apiServices. updateStatus</code></li>
</ul>
<p><code>container.auditSinks.*</code></p>
<ul>
<li><code>container.auditSinks.create</code></li>
<li><code>container.auditSinks.delete</code></li>
<li><code>container.auditSinks.get</code></li>
<li><code>container.auditSinks.list</code></li>
<li><code>container.auditSinks.update</code></li>
</ul>
<p><code>container.backendConfigs.*</code></p>
<ul>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
</ul>
<p><code>container.bindings.*</code></p>
<ul>
<li><code>container.bindings.create</code></li>
<li><code>container.bindings.delete</code></li>
<li><code>container.bindings.get</code></li>
<li><code>container.bindings.list</code></li>
<li><code>container.bindings.update</code></li>
</ul>
<p><code>container. certificateSigningRequests.*</code></p>
<ul>
<li><code>container. certificateSigningRequests. approve</code></li>
<li><code>container. certificateSigningRequests. create</code></li>
<li><code>container. certificateSigningRequests. delete</code></li>
<li><code>container. certificateSigningRequests. get</code></li>
<li><code>container. certificateSigningRequests. getStatus</code></li>
<li><code>container. certificateSigningRequests. list</code></li>
<li><code>container. certificateSigningRequests. update</code></li>
<li><code>container. certificateSigningRequests. updateStatus</code></li>
</ul>
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
<p><code>container.clusters.get</code></p>
<p><code>container. clusters. getCredentials</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container.clusters.update</code></p>
<p><code>container.componentStatuses.*</code></p>
<ul>
<li><code>container. componentStatuses. get</code></li>
<li><code>container. componentStatuses. list</code></li>
</ul>
<p><code>container.configMaps.*</code></p>
<ul>
<li><code>container.configMaps.create</code></li>
<li><code>container.configMaps.delete</code></li>
<li><code>container.configMaps.get</code></li>
<li><code>container.configMaps.list</code></li>
<li><code>container.configMaps.update</code></li>
</ul>
<p><code>container. controllerRevisions.*</code></p>
<ul>
<li><code>container. controllerRevisions. create</code></li>
<li><code>container. controllerRevisions. delete</code></li>
<li><code>container. controllerRevisions. get</code></li>
<li><code>container. controllerRevisions. list</code></li>
<li><code>container. controllerRevisions. update</code></li>
</ul>
<p><code>container.cronJobs.*</code></p>
<ul>
<li><code>container.cronJobs.create</code></li>
<li><code>container.cronJobs.delete</code></li>
<li><code>container.cronJobs.get</code></li>
<li><code>container.cronJobs.getStatus</code></li>
<li><code>container.cronJobs.list</code></li>
<li><code>container.cronJobs.update</code></li>
<li><code>container. cronJobs. updateStatus</code></li>
</ul>
<p><code>container.csiDrivers.*</code></p>
<ul>
<li><code>container.csiDrivers.create</code></li>
<li><code>container.csiDrivers.delete</code></li>
<li><code>container.csiDrivers.get</code></li>
<li><code>container.csiDrivers.list</code></li>
<li><code>container.csiDrivers.update</code></li>
</ul>
<p><code>container.csiNodeInfos.*</code></p>
<ul>
<li><code>container.csiNodeInfos.create</code></li>
<li><code>container.csiNodeInfos.delete</code></li>
<li><code>container.csiNodeInfos.get</code></li>
<li><code>container.csiNodeInfos.list</code></li>
<li><code>container.csiNodeInfos.update</code></li>
</ul>
<p><code>container.csiNodes.*</code></p>
<ul>
<li><code>container.csiNodes.create</code></li>
<li><code>container.csiNodes.delete</code></li>
<li><code>container.csiNodes.get</code></li>
<li><code>container.csiNodes.list</code></li>
<li><code>container.csiNodes.update</code></li>
</ul>
<p><code>container. customResourceDefinitions.*</code></p>
<ul>
<li><code>container. customResourceDefinitions. create</code></li>
<li><code>container. customResourceDefinitions. delete</code></li>
<li><code>container. customResourceDefinitions. get</code></li>
<li><code>container. customResourceDefinitions. getStatus</code></li>
<li><code>container. customResourceDefinitions. list</code></li>
<li><code>container. customResourceDefinitions. update</code></li>
<li><code>container. customResourceDefinitions. updateStatus</code></li>
</ul>
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
<p><code>container.deployments.*</code></p>
<ul>
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
</ul>
<p><code>container.endpointSlices.*</code></p>
<ul>
<li><code>container. endpointSlices. create</code></li>
<li><code>container. endpointSlices. delete</code></li>
<li><code>container.endpointSlices.get</code></li>
<li><code>container.endpointSlices.list</code></li>
<li><code>container. endpointSlices. update</code></li>
</ul>
<p><code>container.endpoints.*</code></p>
<ul>
<li><code>container.endpoints.create</code></li>
<li><code>container.endpoints.delete</code></li>
<li><code>container.endpoints.get</code></li>
<li><code>container.endpoints.list</code></li>
<li><code>container.endpoints.update</code></li>
</ul>
<p><code>container.events.*</code></p>
<ul>
<li><code>container.events.create</code></li>
<li><code>container.events.delete</code></li>
<li><code>container.events.get</code></li>
<li><code>container.events.list</code></li>
<li><code>container.events.update</code></li>
</ul>
<p><code>container.frontendConfigs.*</code></p>
<ul>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
</ul>
<p><code>container. horizontalPodAutoscalers.*</code></p>
<ul>
<li><code>container. horizontalPodAutoscalers. create</code></li>
<li><code>container. horizontalPodAutoscalers. delete</code></li>
<li><code>container. horizontalPodAutoscalers. get</code></li>
<li><code>container. horizontalPodAutoscalers. getStatus</code></li>
<li><code>container. horizontalPodAutoscalers. list</code></li>
<li><code>container. horizontalPodAutoscalers. update</code></li>
<li><code>container. horizontalPodAutoscalers. updateStatus</code></li>
</ul>
<p><code>container.hostServiceAgent.use</code></p>
<p><code>container.ingresses.*</code></p>
<ul>
<li><code>container.ingresses.create</code></li>
<li><code>container.ingresses.delete</code></li>
<li><code>container.ingresses.get</code></li>
<li><code>container.ingresses.getStatus</code></li>
<li><code>container.ingresses.list</code></li>
<li><code>container.ingresses.update</code></li>
<li><code>container. ingresses. updateStatus</code></li>
</ul>
<p><code>container. initializerConfigurations.*</code></p>
<ul>
<li><code>container. initializerConfigurations. create</code></li>
<li><code>container. initializerConfigurations. delete</code></li>
<li><code>container. initializerConfigurations. get</code></li>
<li><code>container. initializerConfigurations. list</code></li>
<li><code>container. initializerConfigurations. update</code></li>
</ul>
<p><code>container.jobs.*</code></p>
<ul>
<li><code>container.jobs.create</code></li>
<li><code>container.jobs.delete</code></li>
<li><code>container.jobs.get</code></li>
<li><code>container.jobs.getStatus</code></li>
<li><code>container.jobs.list</code></li>
<li><code>container.jobs.update</code></li>
<li><code>container.jobs.updateStatus</code></li>
</ul>
<p><code>container.leases.*</code></p>
<ul>
<li><code>container.leases.create</code></li>
<li><code>container.leases.delete</code></li>
<li><code>container.leases.get</code></li>
<li><code>container.leases.list</code></li>
<li><code>container.leases.update</code></li>
</ul>
<p><code>container.limitRanges.*</code></p>
<ul>
<li><code>container.limitRanges.create</code></li>
<li><code>container.limitRanges.delete</code></li>
<li><code>container.limitRanges.get</code></li>
<li><code>container.limitRanges.list</code></li>
<li><code>container.limitRanges.update</code></li>
</ul>
<p><code>container. localSubjectAccessReviews.*</code></p>
<ul>
<li><code>container. localSubjectAccessReviews. create</code></li>
<li><code>container. localSubjectAccessReviews. list</code></li>
</ul>
<p><code>container. managedCertificates.*</code></p>
<ul>
<li><code>container. managedCertificates. create</code></li>
<li><code>container. managedCertificates. delete</code></li>
<li><code>container. managedCertificates. get</code></li>
<li><code>container. managedCertificates. list</code></li>
<li><code>container. managedCertificates. update</code></li>
</ul>
<p><code>container. mutatingWebhookConfigurations.*</code></p>
<ul>
<li><code>container. mutatingWebhookConfigurations. create</code></li>
<li><code>container. mutatingWebhookConfigurations. delete</code></li>
<li><code>container. mutatingWebhookConfigurations. get</code></li>
<li><code>container. mutatingWebhookConfigurations. list</code></li>
<li><code>container. mutatingWebhookConfigurations. update</code></li>
</ul>
<p><code>container.namespaces.*</code></p>
<ul>
<li><code>container.namespaces.create</code></li>
<li><code>container.namespaces.delete</code></li>
<li><code>container.namespaces.finalize</code></li>
<li><code>container.namespaces.get</code></li>
<li><code>container.namespaces.getStatus</code></li>
<li><code>container.namespaces.list</code></li>
<li><code>container.namespaces.update</code></li>
<li><code>container. namespaces. updateStatus</code></li>
</ul>
<p><code>container.networkPolicies.*</code></p>
<ul>
<li><code>container. networkPolicies. create</code></li>
<li><code>container. networkPolicies. delete</code></li>
<li><code>container.networkPolicies.get</code></li>
<li><code>container.networkPolicies.list</code></li>
<li><code>container. networkPolicies. update</code></li>
</ul>
<p><code>container.nodes.*</code></p>
<ul>
<li><code>container.nodes.create</code></li>
<li><code>container.nodes.delete</code></li>
<li><code>container.nodes.get</code></li>
<li><code>container.nodes.getStatus</code></li>
<li><code>container.nodes.list</code></li>
<li><code>container.nodes.proxy</code></li>
<li><code>container.nodes.update</code></li>
<li><code>container.nodes.updateStatus</code></li>
</ul>
<p><code>container.operations.*</code></p>
<ul>
<li><code>container.operations.get</code></li>
<li><code>container.operations.list</code></li>
</ul>
<p><code>container. persistentVolumeClaims.*</code></p>
<ul>
<li><code>container. persistentVolumeClaims. create</code></li>
<li><code>container. persistentVolumeClaims. delete</code></li>
<li><code>container. persistentVolumeClaims. get</code></li>
<li><code>container. persistentVolumeClaims. getStatus</code></li>
<li><code>container. persistentVolumeClaims. list</code></li>
<li><code>container. persistentVolumeClaims. update</code></li>
<li><code>container. persistentVolumeClaims. updateStatus</code></li>
</ul>
<p><code>container.persistentVolumes.*</code></p>
<ul>
<li><code>container. persistentVolumes. create</code></li>
<li><code>container. persistentVolumes. delete</code></li>
<li><code>container. persistentVolumes. get</code></li>
<li><code>container. persistentVolumes. getStatus</code></li>
<li><code>container. persistentVolumes. list</code></li>
<li><code>container. persistentVolumes. update</code></li>
<li><code>container. persistentVolumes. updateStatus</code></li>
</ul>
<p><code>container.petSets.*</code></p>
<ul>
<li><code>container.petSets.create</code></li>
<li><code>container.petSets.delete</code></li>
<li><code>container.petSets.get</code></li>
<li><code>container.petSets.list</code></li>
<li><code>container.petSets.update</code></li>
<li><code>container.petSets.updateStatus</code></li>
</ul>
<p><code>container. podDisruptionBudgets.*</code></p>
<ul>
<li><code>container. podDisruptionBudgets. create</code></li>
<li><code>container. podDisruptionBudgets. delete</code></li>
<li><code>container. podDisruptionBudgets. get</code></li>
<li><code>container. podDisruptionBudgets. getStatus</code></li>
<li><code>container. podDisruptionBudgets. list</code></li>
<li><code>container. podDisruptionBudgets. update</code></li>
<li><code>container. podDisruptionBudgets. updateStatus</code></li>
</ul>
<p><code>container.podPresets.*</code></p>
<ul>
<li><code>container.podPresets.create</code></li>
<li><code>container.podPresets.delete</code></li>
<li><code>container.podPresets.get</code></li>
<li><code>container.podPresets.list</code></li>
<li><code>container.podPresets.update</code></li>
</ul>
<p><code>container. podSecurityPolicies.*</code></p>
<ul>
<li><code>container. podSecurityPolicies. create</code></li>
<li><code>container. podSecurityPolicies. delete</code></li>
<li><code>container. podSecurityPolicies. get</code></li>
<li><code>container. podSecurityPolicies. list</code></li>
<li><code>container. podSecurityPolicies. update</code></li>
<li><code>container. podSecurityPolicies. use</code></li>
</ul>
<p><code>container.podTemplates.*</code></p>
<ul>
<li><code>container.podTemplates.create</code></li>
<li><code>container.podTemplates.delete</code></li>
<li><code>container.podTemplates.get</code></li>
<li><code>container.podTemplates.list</code></li>
<li><code>container.podTemplates.update</code></li>
</ul>
<p><code>container.pods.*</code></p>
<ul>
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
</ul>
<p><code>container.priorityClasses.*</code></p>
<ul>
<li><code>container. priorityClasses. create</code></li>
<li><code>container. priorityClasses. delete</code></li>
<li><code>container.priorityClasses.get</code></li>
<li><code>container.priorityClasses.list</code></li>
<li><code>container. priorityClasses. update</code></li>
</ul>
<p><code>container.replicaSets.*</code></p>
<ul>
<li><code>container.replicaSets.create</code></li>
<li><code>container.replicaSets.delete</code></li>
<li><code>container.replicaSets.get</code></li>
<li><code>container.replicaSets.getScale</code></li>
<li><code>container. replicaSets. getStatus</code></li>
<li><code>container.replicaSets.list</code></li>
<li><code>container.replicaSets.update</code></li>
<li><code>container. replicaSets. updateScale</code></li>
<li><code>container. replicaSets. updateStatus</code></li>
</ul>
<p><code>container. replicationControllers.*</code></p>
<ul>
<li><code>container. replicationControllers. create</code></li>
<li><code>container. replicationControllers. delete</code></li>
<li><code>container. replicationControllers. get</code></li>
<li><code>container. replicationControllers. getScale</code></li>
<li><code>container. replicationControllers. getStatus</code></li>
<li><code>container. replicationControllers. list</code></li>
<li><code>container. replicationControllers. update</code></li>
<li><code>container. replicationControllers. updateScale</code></li>
<li><code>container. replicationControllers. updateStatus</code></li>
</ul>
<p><code>container.resourceQuotas.*</code></p>
<ul>
<li><code>container. resourceQuotas. create</code></li>
<li><code>container. resourceQuotas. delete</code></li>
<li><code>container.resourceQuotas.get</code></li>
<li><code>container. resourceQuotas. getStatus</code></li>
<li><code>container.resourceQuotas.list</code></li>
<li><code>container. resourceQuotas. update</code></li>
<li><code>container. resourceQuotas. updateStatus</code></li>
</ul>
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
<p><code>container.runtimeClasses.*</code></p>
<ul>
<li><code>container. runtimeClasses. create</code></li>
<li><code>container. runtimeClasses. delete</code></li>
<li><code>container.runtimeClasses.get</code></li>
<li><code>container.runtimeClasses.list</code></li>
<li><code>container. runtimeClasses. update</code></li>
</ul>
<p><code>container.scheduledJobs.*</code></p>
<ul>
<li><code>container.scheduledJobs.create</code></li>
<li><code>container.scheduledJobs.delete</code></li>
<li><code>container.scheduledJobs.get</code></li>
<li><code>container.scheduledJobs.list</code></li>
<li><code>container.scheduledJobs.update</code></li>
<li><code>container. scheduledJobs. updateStatus</code></li>
</ul>
<p><code>container.secrets.*</code></p>
<ul>
<li><code>container.secrets.create</code></li>
<li><code>container.secrets.delete</code></li>
<li><code>container.secrets.get</code></li>
<li><code>container.secrets.list</code></li>
<li><code>container.secrets.update</code></li>
</ul>
<p><code>container. selfSubjectAccessReviews.*</code></p>
<ul>
<li><code>container. selfSubjectAccessReviews. create</code></li>
<li><code>container. selfSubjectAccessReviews. list</code></li>
</ul>
<p><code>container. selfSubjectRulesReviews. create</code></p>
<p><code>container.serviceAccounts.*</code></p>
<ul>
<li><code>container. serviceAccounts. create</code></li>
<li><code>container. serviceAccounts. createToken</code></li>
<li><code>container. serviceAccounts. delete</code></li>
<li><code>container.serviceAccounts.get</code></li>
<li><code>container.serviceAccounts.list</code></li>
<li><code>container. serviceAccounts. update</code></li>
</ul>
<p><code>container.services.*</code></p>
<ul>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
</ul>
<p><code>container.statefulSets.*</code></p>
<ul>
<li><code>container.statefulSets.create</code></li>
<li><code>container.statefulSets.delete</code></li>
<li><code>container.statefulSets.get</code></li>
<li><code>container. statefulSets. getScale</code></li>
<li><code>container. statefulSets. getStatus</code></li>
<li><code>container.statefulSets.list</code></li>
<li><code>container.statefulSets.update</code></li>
<li><code>container. statefulSets. updateScale</code></li>
<li><code>container. statefulSets. updateStatus</code></li>
</ul>
<p><code>container.storageClasses.*</code></p>
<ul>
<li><code>container. storageClasses. create</code></li>
<li><code>container. storageClasses. delete</code></li>
<li><code>container.storageClasses.get</code></li>
<li><code>container.storageClasses.list</code></li>
<li><code>container. storageClasses. update</code></li>
</ul>
<p><code>container.storageStates.*</code></p>
<ul>
<li><code>container.storageStates.create</code></li>
<li><code>container.storageStates.delete</code></li>
<li><code>container.storageStates.get</code></li>
<li><code>container. storageStates. getStatus</code></li>
<li><code>container.storageStates.list</code></li>
<li><code>container.storageStates.update</code></li>
<li><code>container. storageStates. updateStatus</code></li>
</ul>
<p><code>container. storageVersionMigrations.*</code></p>
<ul>
<li><code>container. storageVersionMigrations. create</code></li>
<li><code>container. storageVersionMigrations. delete</code></li>
<li><code>container. storageVersionMigrations. get</code></li>
<li><code>container. storageVersionMigrations. getStatus</code></li>
<li><code>container. storageVersionMigrations. list</code></li>
<li><code>container. storageVersionMigrations. update</code></li>
<li><code>container. storageVersionMigrations. updateStatus</code></li>
</ul>
<p><code>container. subjectAccessReviews.*</code></p>
<ul>
<li><code>container. subjectAccessReviews. create</code></li>
<li><code>container. subjectAccessReviews. list</code></li>
</ul>
<p><code>container.thirdPartyObjects.*</code></p>
<ul>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
</ul>
<p><code>container. thirdPartyResources.*</code></p>
<ul>
<li><code>container. thirdPartyResources. create</code></li>
<li><code>container. thirdPartyResources. delete</code></li>
<li><code>container. thirdPartyResources. get</code></li>
<li><code>container. thirdPartyResources. list</code></li>
<li><code>container. thirdPartyResources. update</code></li>
</ul>
<p><code>container.tokenReviews.create</code></p>
<p><code>container.updateInfos.*</code></p>
<ul>
<li><code>container.updateInfos.create</code></li>
<li><code>container.updateInfos.delete</code></li>
<li><code>container.updateInfos.get</code></li>
<li><code>container.updateInfos.list</code></li>
<li><code>container.updateInfos.update</code></li>
</ul>
<p><code>container. validatingWebhookConfigurations.*</code></p>
<ul>
<li><code>container. validatingWebhookConfigurations. create</code></li>
<li><code>container. validatingWebhookConfigurations. delete</code></li>
<li><code>container. validatingWebhookConfigurations. get</code></li>
<li><code>container. validatingWebhookConfigurations. list</code></li>
<li><code>container. validatingWebhookConfigurations. update</code></li>
</ul>
<p><code>container.volumeAttachments.*</code></p>
<ul>
<li><code>container. volumeAttachments. create</code></li>
<li><code>container. volumeAttachments. delete</code></li>
<li><code>container. volumeAttachments. get</code></li>
<li><code>container. volumeAttachments. getStatus</code></li>
<li><code>container. volumeAttachments. list</code></li>
<li><code>container. volumeAttachments. update</code></li>
<li><code>container. volumeAttachments. updateStatus</code></li>
</ul>
<p><code>container. volumeSnapshotClasses.*</code></p>
<ul>
<li><code>container. volumeSnapshotClasses. create</code></li>
<li><code>container. volumeSnapshotClasses. delete</code></li>
<li><code>container. volumeSnapshotClasses. get</code></li>
<li><code>container. volumeSnapshotClasses. list</code></li>
<li><code>container. volumeSnapshotClasses. update</code></li>
</ul>
<p><code>container. volumeSnapshotContents.*</code></p>
<ul>
<li><code>container. volumeSnapshotContents. create</code></li>
<li><code>container. volumeSnapshotContents. delete</code></li>
<li><code>container. volumeSnapshotContents. get</code></li>
<li><code>container. volumeSnapshotContents. getStatus</code></li>
<li><code>container. volumeSnapshotContents. list</code></li>
<li><code>container. volumeSnapshotContents. update</code></li>
<li><code>container. volumeSnapshotContents. updateStatus</code></li>
</ul>
<p><code>container.volumeSnapshots.*</code></p>
<ul>
<li><code>container. volumeSnapshots. create</code></li>
<li><code>container. volumeSnapshots. delete</code></li>
<li><code>container.volumeSnapshots.get</code></li>
<li><code>container. volumeSnapshots. getStatus</code></li>
<li><code>container.volumeSnapshots.list</code></li>
<li><code>container. volumeSnapshots. update</code></li>
<li><code>container. volumeSnapshots. updateStatus</code></li>
</ul>
<p><code>gkehub.features.get</code></p>
<p><code>gkehub.features.getIamPolicy</code></p>
<p><code>gkehub.features.list</code></p>
<p><code>gkehub.fleet.get</code></p>
<p><code>gkehub.fleet.getFreeTrial</code></p>
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
<p><code>gkehub.membershipbindings.get</code></p>
<p><code>gkehub.membershipbindings.list</code></p>
<p><code>gkehub.membershipfeatures.get</code></p>
<p><code>gkehub.membershipfeatures.list</code></p>
<p><code>gkehub. memberships. generateConnectManifest</code></p>
<p><code>gkehub.memberships.get</code></p>
<p><code>gkehub. memberships. getIamPolicy</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>gkehub.namespaces.get</code></p>
<p><code>gkehub.namespaces.list</code></p>
<p><code>gkehub.operations.get</code></p>
<p><code>gkehub.operations.list</code></p>
<p><code>gkehub.rbacrolebindings.get</code></p>
<p><code>gkehub.rbacrolebindings.list</code></p>
<p><code>gkehub.scopes.get</code></p>
<p><code>gkehub.scopes.getIamPolicy</code></p>
<p><code>gkehub.scopes.list</code></p>
<p><code>gkehub. scopes. listBoundMemberships</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>trafficdirector.*</code></p>
<ul>
<li><code>trafficdirector. networks. getConfigs</code></li>
<li><code>trafficdirector. networks. reportMetrics</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Cloud Service Mesh control plane permissions

There are no IAM permissions for this service.
