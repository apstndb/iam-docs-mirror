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
<td>Anthos Multi-cloud Admin
<p>( <code>roles/ gkemulticloud.admin</code> )</p>
<p>Admin access to Anthos Multi-cloud resources.</p></td>
<td><p><code>gkemulticloud.*</code></p>
<ul>
<li><code>gkemulticloud. attachedClusters. create</code></li>
<li><code>gkemulticloud. attachedClusters. createTagBinding</code></li>
<li><code>gkemulticloud. attachedClusters. delete</code></li>
<li><code>gkemulticloud. attachedClusters. deleteTagBinding</code></li>
<li><code>gkemulticloud. attachedClusters. generateInstallManifest</code></li>
<li><code>gkemulticloud. attachedClusters. get</code></li>
<li><code>gkemulticloud. attachedClusters. import</code></li>
<li><code>gkemulticloud. attachedClusters. list</code></li>
<li><code>gkemulticloud. attachedClusters. listEffectiveTags</code></li>
<li><code>gkemulticloud. attachedClusters. listTagBindings</code></li>
<li><code>gkemulticloud. attachedClusters. update</code></li>
<li><code>gkemulticloud. attachedServerConfigs. get</code></li>
<li><code>gkemulticloud. awsClusters. create</code></li>
<li><code>gkemulticloud. awsClusters. delete</code></li>
<li><code>gkemulticloud. awsClusters. generateAccessToken</code></li>
<li><code>gkemulticloud.awsClusters.get</code></li>
<li><code>gkemulticloud. awsClusters. getAdminKubeconfig</code></li>
<li><code>gkemulticloud.awsClusters.list</code></li>
<li><code>gkemulticloud. awsClusters. update</code></li>
<li><code>gkemulticloud. awsNodePools. create</code></li>
<li><code>gkemulticloud. awsNodePools. delete</code></li>
<li><code>gkemulticloud.awsNodePools.get</code></li>
<li><code>gkemulticloud. awsNodePools. list</code></li>
<li><code>gkemulticloud. awsNodePools. update</code></li>
<li><code>gkemulticloud. awsServerConfigs. get</code></li>
<li><code>gkemulticloud. azureClients. create</code></li>
<li><code>gkemulticloud. azureClients. delete</code></li>
<li><code>gkemulticloud.azureClients.get</code></li>
<li><code>gkemulticloud. azureClients. list</code></li>
<li><code>gkemulticloud. azureClusters. create</code></li>
<li><code>gkemulticloud. azureClusters. delete</code></li>
<li><code>gkemulticloud. azureClusters. generateAccessToken</code></li>
<li><code>gkemulticloud. azureClusters. get</code></li>
<li><code>gkemulticloud. azureClusters. getAdminKubeconfig</code></li>
<li><code>gkemulticloud. azureClusters. list</code></li>
<li><code>gkemulticloud. azureClusters. update</code></li>
<li><code>gkemulticloud. azureNodePools. create</code></li>
<li><code>gkemulticloud. azureNodePools. delete</code></li>
<li><code>gkemulticloud. azureNodePools. get</code></li>
<li><code>gkemulticloud. azureNodePools. list</code></li>
<li><code>gkemulticloud. azureNodePools. update</code></li>
<li><code>gkemulticloud. azureServerConfigs. get</code></li>
<li><code>gkemulticloud. operations. cancel</code></li>
<li><code>gkemulticloud. operations. delete</code></li>
<li><code>gkemulticloud.operations.get</code></li>
<li><code>gkemulticloud.operations.list</code></li>
<li><code>gkemulticloud.operations.wait</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Anthos Multi-cloud Editor
<p>( <code>roles/ gkemulticloud.editor</code> )</p>
<p>Editor role for Anthos Multi-cloud</p></td>
<td><p><code>gkemulticloud. attachedClusters. create</code></p>
<p><code>gkemulticloud. attachedClusters. delete</code></p>
<p><code>gkemulticloud. attachedClusters. generateInstallManifest</code></p>
<p><code>gkemulticloud. attachedClusters. get</code></p>
<p><code>gkemulticloud. attachedClusters. import</code></p>
<p><code>gkemulticloud. attachedClusters. list</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkemulticloud. attachedClusters. update</code></p>
<p><code>gkemulticloud. attachedServerConfigs. get</code></p>
<p><code>gkemulticloud. awsClusters. create</code></p>
<p><code>gkemulticloud. awsClusters. delete</code></p>
<p><code>gkemulticloud. awsClusters. generateAccessToken</code></p>
<p><code>gkemulticloud.awsClusters.get</code></p>
<p><code>gkemulticloud.awsClusters.list</code></p>
<p><code>gkemulticloud. awsClusters. update</code></p>
<p><code>gkemulticloud.awsNodePools.*</code></p>
<ul>
<li><code>gkemulticloud. awsNodePools. create</code></li>
<li><code>gkemulticloud. awsNodePools. delete</code></li>
<li><code>gkemulticloud.awsNodePools.get</code></li>
<li><code>gkemulticloud. awsNodePools. list</code></li>
<li><code>gkemulticloud. awsNodePools. update</code></li>
</ul>
<p><code>gkemulticloud. awsServerConfigs. get</code></p>
<p><code>gkemulticloud.azureClients.*</code></p>
<ul>
<li><code>gkemulticloud. azureClients. create</code></li>
<li><code>gkemulticloud. azureClients. delete</code></li>
<li><code>gkemulticloud.azureClients.get</code></li>
<li><code>gkemulticloud. azureClients. list</code></li>
</ul>
<p><code>gkemulticloud. azureClusters. create</code></p>
<p><code>gkemulticloud. azureClusters. delete</code></p>
<p><code>gkemulticloud. azureClusters. generateAccessToken</code></p>
<p><code>gkemulticloud. azureClusters. get</code></p>
<p><code>gkemulticloud. azureClusters. list</code></p>
<p><code>gkemulticloud. azureClusters. update</code></p>
<p><code>gkemulticloud.azureNodePools.*</code></p>
<ul>
<li><code>gkemulticloud. azureNodePools. create</code></li>
<li><code>gkemulticloud. azureNodePools. delete</code></li>
<li><code>gkemulticloud. azureNodePools. get</code></li>
<li><code>gkemulticloud. azureNodePools. list</code></li>
<li><code>gkemulticloud. azureNodePools. update</code></li>
</ul>
<p><code>gkemulticloud. azureServerConfigs. get</code></p>
<p><code>gkemulticloud.operations.*</code></p>
<ul>
<li><code>gkemulticloud. operations. cancel</code></li>
<li><code>gkemulticloud. operations. delete</code></li>
<li><code>gkemulticloud.operations.get</code></li>
<li><code>gkemulticloud.operations.list</code></li>
<li><code>gkemulticloud.operations.wait</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Anthos Multi-cloud Viewer
<p>( <code>roles/ gkemulticloud.viewer</code> )</p>
<p>Viewer access to Anthos Multi-cloud resources.</p></td>
<td><p><code>gkemulticloud. attachedClusters. generateInstallManifest</code></p>
<p><code>gkemulticloud. attachedClusters. get</code></p>
<p><code>gkemulticloud. attachedClusters. list</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkemulticloud. attachedServerConfigs. get</code></p>
<p><code>gkemulticloud. awsClusters. generateAccessToken</code></p>
<p><code>gkemulticloud.awsClusters.get</code></p>
<p><code>gkemulticloud.awsClusters.list</code></p>
<p><code>gkemulticloud.awsNodePools.get</code></p>
<p><code>gkemulticloud. awsNodePools. list</code></p>
<p><code>gkemulticloud. awsServerConfigs. get</code></p>
<p><code>gkemulticloud.azureClients.get</code></p>
<p><code>gkemulticloud. azureClients. list</code></p>
<p><code>gkemulticloud. azureClusters. generateAccessToken</code></p>
<p><code>gkemulticloud. azureClusters. get</code></p>
<p><code>gkemulticloud. azureClusters. list</code></p>
<p><code>gkemulticloud. azureNodePools. get</code></p>
<p><code>gkemulticloud. azureNodePools. list</code></p>
<p><code>gkemulticloud. azureServerConfigs. get</code></p>
<p><code>gkemulticloud.operations.get</code></p>
<p><code>gkemulticloud.operations.list</code></p>
<p><code>gkemulticloud.operations.wait</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Anthos Multi-cloud Telemetry Writer
<p>( <code>roles/ gkemulticloud.telemetryWriter</code> )</p>
<p>Grant access to write cluster telemetry data such as logs, metrics, and resource metadata.</p></td>
<td><p><code>kubernetesmetadata.*</code></p>
<ul>
<li><code>kubernetesmetadata. metadata. config</code></li>
<li><code>kubernetesmetadata. metadata. publish</code></li>
<li><code>kubernetesmetadata. metadata. snapshot</code></li>
</ul>
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
<p><code>opsconfigmonitoring. resourceMetadata. write</code></p></td>
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
<td>Anthos Multi-Cloud Container Service Agent
<p>( <code>roles/ gkemulticloud.containerServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Container Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>binaryauthorization. platformPolicies. evaluatePolicy</code></p>
<p><code>binaryauthorization. platformPolicies. get</code></p>
<p><code>binaryauthorization. platformPolicies. list</code></p>
<p><code>binaryauthorization. policy. evaluatePolicy</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>kubernetesmetadata.*</code></p>
<ul>
<li><code>kubernetesmetadata. metadata. config</code></li>
<li><code>kubernetesmetadata. metadata. publish</code></li>
<li><code>kubernetesmetadata. metadata. snapshot</code></li>
</ul>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logEntries.route</code></p>
<p><code>monitoring.alertPolicies.get</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring.alerts.*</code></p>
<ul>
<li><code>monitoring.alerts.get</code></li>
<li><code>monitoring.alerts.list</code></li>
</ul>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. create</code></p>
<p><code>monitoring. metricDescriptors. get</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannelDescriptors.*</code></p>
<ul>
<li><code>monitoring. notificationChannelDescriptors. get</code></li>
<li><code>monitoring. notificationChannelDescriptors. list</code></li>
</ul>
<p><code>monitoring. notificationChannels. get</code></p>
<p><code>monitoring. notificationChannels. list</code></p>
<p><code>monitoring.services.get</code></p>
<p><code>monitoring.services.list</code></p>
<p><code>monitoring.slos.get</code></p>
<p><code>monitoring.slos.list</code></p>
<p><code>monitoring.snoozes.get</code></p>
<p><code>monitoring.snoozes.list</code></p>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>opsconfigmonitoring.*</code></p>
<ul>
<li><code>opsconfigmonitoring. resourceMetadata. list</code></li>
<li><code>opsconfigmonitoring. resourceMetadata. write</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p></td>
</tr>
<tr class="even">
<td>Anthos Multi-Cloud Control Plane Machine Service Agent
<p>( <code>roles/ gkemulticloud.controlPlaneMachineServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Control Plane Machine Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. dockerimages. get</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="odd">
<td>Anthos Multi-Cloud Node Pool Machine Service Agent
<p>( <code>roles/ gkemulticloud.nodePoolMachineServiceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Node Pool Machine Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. dockerimages. get</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>Anthos Multi-Cloud Service Agent
<p>( <code>roles/ gkemulticloud.serviceAgent</code> )</p>
<p>Grants the Anthos Multi-Cloud Service Account access to manage resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>gkehub.features.*</code></p>
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
<p><code>gkemulticloud. awsClusters. delete</code></p>
<p><code>gkemulticloud. awsNodePools. delete</code></p>
<p><code>gkemulticloud. azureClients. delete</code></p>
<p><code>gkemulticloud. azureClusters. delete</code></p>
<p><code>gkemulticloud. azureNodePools. delete</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td><code>gkemulticloud. attachedClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedClusters. createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. attachedClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedClusters. deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. attachedClusters. generateInstallManifest</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedClusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. attachedClusters. import</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedClusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. attachedClusters. listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedClusters. listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. attachedClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. attachedServerConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. awsClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsClusters. generateAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud.awsClusters.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsClusters. getAdminKubeconfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud.awsClusters.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. awsNodePools. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsNodePools. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>gkemulticloud.awsNodePools.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsNodePools. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. awsNodePools. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. awsServerConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureClients. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureClients. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>gkemulticloud.azureClients.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureClients. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureClusters. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureClusters. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureClusters. generateAccessToken</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureClusters. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkehub#gkehub.serviceAgent">GKE Hub Service Agent</a> ( <code>roles/ gkehub.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureClusters. getAdminKubeconfig</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureClusters. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureClusters. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureNodePools. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureNodePools. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.serviceAgent">Anthos Multi-Cloud Service Agent</a> ( <code>roles/ gkemulticloud.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureNodePools. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureNodePools. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. azureNodePools. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. azureServerConfigs. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>gkemulticloud.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>gkemulticloud.operations.wait</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.admin">Anthos Multi-cloud Admin</a> ( <code>roles/ gkemulticloud.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.editor">Anthos Multi-cloud Editor</a> ( <code>roles/ gkemulticloud.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gkemulticloud#gkemulticloud.viewer">Anthos Multi-cloud Viewer</a> ( <code>roles/ gkemulticloud.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
