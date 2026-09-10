---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud
title: GKE Multi-Cloud roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for GKE Multi-Cloud. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## GKE Multi-Cloud roles

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
<td><h4 id="gkemulticloud.admin" class="role-title add-link" data-text="Anthos Multi-cloud Admin" tabindex="-1">Anthos Multi-cloud Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p>Admin access to Anthos Multi-cloud resources.</p></td>
<td><p><code dir="ltr" translate="no">gkemulticloud.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  generateInstallManifest</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  import</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  attachedServerConfigs.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  generateAccessToken</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.awsClusters.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  getAdminKubeconfig</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.awsNodePools.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  update</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsServerConfigs.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.azureClients.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  generateAccessToken</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  getAdminKubeconfig</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  update</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  update</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureServerConfigs.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.editor" class="role-title add-link" data-text="Anthos Multi-cloud Editor" tabindex="-1">Anthos Multi-cloud Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Editor role for Anthos Multi-cloud</p></td>
<td><p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  generateInstallManifest</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  import</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsNodePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.awsNodePools.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  awsServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.azureClients.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.azureClients.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  create</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  update</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.azureNodePools.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  create</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  azureServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkemulticloud.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.get</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.list</code></li>
<li><code dir="ltr" translate="no">gkemulticloud.operations.wait</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.viewer" class="role-title add-link" data-text="Anthos Multi-cloud Viewer" tabindex="-1">Anthos Multi-cloud Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p>Viewer access to Anthos Multi-cloud resources.</p></td>
<td><p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  generateInstallManifest</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.awsNodePools.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.azureClients.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  generateAccessToken</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureServerConfigs.  get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.get</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.list</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.operations.wait</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.telemetryWriter" class="role-title add-link" data-text="Anthos Multi-cloud Telemetry Writer" tabindex="-1">Anthos Multi-cloud Telemetry Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.telemetryWriter</code> )</p>
<p>Grant access to write cluster telemetry data such as logs, metrics, and resource metadata.</p></td>
<td><p><code dir="ltr" translate="no">kubernetesmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.route</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  write</code></p></td>
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
<td><h4 id="gkemulticloud.containerServiceAgent" class="role-title add-link" data-text="Anthos Multi-Cloud Container Service Agent" tabindex="-1">Anthos Multi-Cloud Container Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.containerServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Container Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  platformPolicies.  list</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.  policy.  evaluatePolicy</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">kubernetesmetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  config</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  publish</code></li>
<li><code dir="ltr" translate="no">kubernetesmetadata.  metadata.  snapshot</code></li>
</ul>
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
<p><code dir="ltr" translate="no">opsconfigmonitoring.*</code></p>
<ul>
<li><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></li>
<li><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  write</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.controlPlaneMachineServiceAgent" class="role-title add-link" data-text="Anthos Multi-Cloud Control Plane Machine Service Agent" tabindex="-1">Anthos Multi-Cloud Control Plane Machine Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.controlPlaneMachineServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Control Plane Machine Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.nodePoolMachineServiceAgent" class="role-title add-link" data-text="Anthos Multi-Cloud Node Pool Machine Service Agent" tabindex="-1">Anthos Multi-Cloud Node Pool Machine Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.nodePoolMachineServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Node Pool Machine Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.serviceAgent" class="role-title add-link" data-text="Anthos Multi-Cloud Service Agent" tabindex="-1">Anthos Multi-Cloud Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">gkehub.features.*</code></p>
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
<p><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClients.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  delete</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## GKE Multi-Cloud permissions

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
<td><h4 id="gkemulticloud.attachedClusters.create" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedClusters.createTagBinding" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.createTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  createTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.attachedClusters.delete" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedClusters.deleteTagBinding" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.deleteTagBinding" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  deleteTagBinding</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.attachedClusters.generateInstallManifest" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.generateInstallManifest" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  generateInstallManifest</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedClusters.get" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.attachedClusters.import" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.import" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedClusters.list" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.attachedClusters.listEffectiveTags" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.listEffectiveTags" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedClusters.listTagBindings" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.listTagBindings" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.attachedClusters.update" class="permission-name add-link" data-text="gkemulticloud.attachedClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.attachedServerConfigs.get" class="permission-name add-link" data-text="gkemulticloud.attachedServerConfigs.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  attachedServerConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsClusters.create" class="permission-name add-link" data-text="gkemulticloud.awsClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsClusters.delete" class="permission-name add-link" data-text="gkemulticloud.awsClusters.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsClusters.generateAccessToken" class="permission-name add-link" data-text="gkemulticloud.awsClusters.generateAccessToken" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  generateAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsClusters.get" class="permission-name add-link" data-text="gkemulticloud.awsClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.awsClusters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsClusters.getAdminKubeconfig" class="permission-name add-link" data-text="gkemulticloud.awsClusters.getAdminKubeconfig" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  getAdminKubeconfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsClusters.list" class="permission-name add-link" data-text="gkemulticloud.awsClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.awsClusters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsClusters.update" class="permission-name add-link" data-text="gkemulticloud.awsClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsNodePools.create" class="permission-name add-link" data-text="gkemulticloud.awsNodePools.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsNodePools.delete" class="permission-name add-link" data-text="gkemulticloud.awsNodePools.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsNodePools.get" class="permission-name add-link" data-text="gkemulticloud.awsNodePools.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.awsNodePools.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsNodePools.list" class="permission-name add-link" data-text="gkemulticloud.awsNodePools.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.awsNodePools.update" class="permission-name add-link" data-text="gkemulticloud.awsNodePools.update" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsNodePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.awsServerConfigs.get" class="permission-name add-link" data-text="gkemulticloud.awsServerConfigs.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  awsServerConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClients.create" class="permission-name add-link" data-text="gkemulticloud.azureClients.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClients.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureClients.delete" class="permission-name add-link" data-text="gkemulticloud.azureClients.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClients.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClients.get" class="permission-name add-link" data-text="gkemulticloud.azureClients.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.azureClients.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureClients.list" class="permission-name add-link" data-text="gkemulticloud.azureClients.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClients.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClusters.create" class="permission-name add-link" data-text="gkemulticloud.azureClusters.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureClusters.delete" class="permission-name add-link" data-text="gkemulticloud.azureClusters.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClusters.generateAccessToken" class="permission-name add-link" data-text="gkemulticloud.azureClusters.generateAccessToken" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  generateAccessToken</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureClusters.get" class="permission-name add-link" data-text="gkemulticloud.azureClusters.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkehub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClusters.getAdminKubeconfig" class="permission-name add-link" data-text="gkemulticloud.azureClusters.getAdminKubeconfig" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  getAdminKubeconfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureClusters.list" class="permission-name add-link" data-text="gkemulticloud.azureClusters.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureClusters.update" class="permission-name add-link" data-text="gkemulticloud.azureClusters.update" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureClusters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureNodePools.create" class="permission-name add-link" data-text="gkemulticloud.azureNodePools.create" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureNodePools.delete" class="permission-name add-link" data-text="gkemulticloud.azureNodePools.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureNodePools.get" class="permission-name add-link" data-text="gkemulticloud.azureNodePools.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureNodePools.list" class="permission-name add-link" data-text="gkemulticloud.azureNodePools.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.azureNodePools.update" class="permission-name add-link" data-text="gkemulticloud.azureNodePools.update" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureNodePools.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.azureServerConfigs.get" class="permission-name add-link" data-text="gkemulticloud.azureServerConfigs.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  azureServerConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.operations.cancel" class="permission-name add-link" data-text="gkemulticloud.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.operations.delete" class="permission-name add-link" data-text="gkemulticloud.operations.delete" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.operations.get" class="permission-name add-link" data-text="gkemulticloud.operations.get" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gkemulticloud.operations.list" class="permission-name add-link" data-text="gkemulticloud.operations.list" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gkemulticloud.operations.wait" class="permission-name add-link" data-text="gkemulticloud.operations.wait" tabindex="-1"><code dir="ltr" translate="no">gkemulticloud.operations.wait</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
