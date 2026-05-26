---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/apphub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/apphub
title: App Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for App Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## App Hub roles

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
<td><h4 id="apphub.admin" class="role-title add-link" data-text="App Hub Admin" tabindex="-1">App Hub Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p>Full access to App Hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apphub.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.applications.create</code></li>
<li><code dir="ltr" translate="no">apphub.applications.delete</code></li>
<li><code dir="ltr" translate="no">apphub.applications.get</code></li>
<li><code dir="ltr" translate="no">apphub.  applications.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">apphub.applications.list</code></li>
<li><code dir="ltr" translate="no">apphub.  applications.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">apphub.applications.update</code></li>
<li><code dir="ltr" translate="no">apphub.boundaries.attach</code></li>
<li><code dir="ltr" translate="no">apphub.boundaries.get</code></li>
<li><code dir="ltr" translate="no">apphub.boundaries.update</code></li>
<li><code dir="ltr" translate="no">apphub.discoveredServices.get</code></li>
<li><code dir="ltr" translate="no">apphub.discoveredServices.list</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredServices.  register</code></li>
<li><code dir="ltr" translate="no">apphub.discoveredWorkloads.get</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  register</code></li>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  get</code></li>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></li>
<li><code dir="ltr" translate="no">apphub.locations.get</code></li>
<li><code dir="ltr" translate="no">apphub.locations.list</code></li>
<li><code dir="ltr" translate="no">apphub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apphub.operations.delete</code></li>
<li><code dir="ltr" translate="no">apphub.operations.get</code></li>
<li><code dir="ltr" translate="no">apphub.operations.list</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  attach</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  detach</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  lookup</code></li>
<li><code dir="ltr" translate="no">apphub.services.create</code></li>
<li><code dir="ltr" translate="no">apphub.services.delete</code></li>
<li><code dir="ltr" translate="no">apphub.services.get</code></li>
<li><code dir="ltr" translate="no">apphub.services.list</code></li>
<li><code dir="ltr" translate="no">apphub.services.update</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.create</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.delete</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.get</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.list</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.editor" class="role-title add-link" data-text="App Hub Editor" tabindex="-1">App Hub Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p>Edit access to App Hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apphub.applications.create</code></p>
<p><code dir="ltr" translate="no">apphub.applications.delete</code></p>
<p><code dir="ltr" translate="no">apphub.applications.get</code></p>
<p><code dir="ltr" translate="no">apphub.applications.list</code></p>
<p><code dir="ltr" translate="no">apphub.applications.update</code></p>
<p><code dir="ltr" translate="no">apphub.boundaries.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.discoveredServices.get</code></li>
<li><code dir="ltr" translate="no">apphub.discoveredServices.list</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredServices.  register</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.discoveredWorkloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.discoveredWorkloads.get</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></li>
<li><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  register</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  get</code></li>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.locations.get</code></li>
<li><code dir="ltr" translate="no">apphub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apphub.operations.delete</code></li>
<li><code dir="ltr" translate="no">apphub.operations.get</code></li>
<li><code dir="ltr" translate="no">apphub.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  lookup</code></p>
<p><code dir="ltr" translate="no">apphub.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.services.create</code></li>
<li><code dir="ltr" translate="no">apphub.services.delete</code></li>
<li><code dir="ltr" translate="no">apphub.services.get</code></li>
<li><code dir="ltr" translate="no">apphub.services.list</code></li>
<li><code dir="ltr" translate="no">apphub.services.update</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.workloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.workloads.create</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.delete</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.get</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.list</code></li>
<li><code dir="ltr" translate="no">apphub.workloads.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.viewer" class="role-title add-link" data-text="App Hub Viewer" tabindex="-1">App Hub Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p>View access to App Hub resources.</p></td>
<td><p><code dir="ltr" translate="no">apphub.applications.get</code></p>
<p><code dir="ltr" translate="no">apphub.applications.list</code></p>
<p><code dir="ltr" translate="no">apphub.boundaries.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.list</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredWorkloads.get</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></p>
<p><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  get</code></li>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.locations.get</code></li>
<li><code dir="ltr" translate="no">apphub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.operations.get</code></p>
<p><code dir="ltr" translate="no">apphub.operations.list</code></p>
<p><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  lookup</code></p>
<p><code dir="ltr" translate="no">apphub.services.get</code></p>
<p><code dir="ltr" translate="no">apphub.services.list</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.get</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.appManagementViewer" class="role-title add-link" data-text="App Management Viewer Beta" tabindex="-1">App Management Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p>This role, an aggregation of read permissions across multiple app centric products.</p></td>
<td><p><code dir="ltr" translate="no">apphub.applications.get</code></p>
<p><code dir="ltr" translate="no">apphub.applications.list</code></p>
<p><code dir="ltr" translate="no">apphub.boundaries.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.get</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredServices.list</code></p>
<p><code dir="ltr" translate="no">apphub.discoveredWorkloads.get</code></p>
<p><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></p>
<p><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  get</code></li>
<li><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apphub.locations.get</code></li>
<li><code dir="ltr" translate="no">apphub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apphub.operations.get</code></p>
<p><code dir="ltr" translate="no">apphub.operations.list</code></p>
<p><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  lookup</code></p>
<p><code dir="ltr" translate="no">apphub.services.get</code></p>
<p><code dir="ltr" translate="no">apphub.services.list</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.get</code></p>
<p><code dir="ltr" translate="no">apphub.workloads.list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.analyzeMove</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAccessLevel</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformBatchPredictionJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformCustomJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformDataLabelingJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformEndpoints</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformHyperparameterTuningJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformMetadataStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformModelDeploymentMonitoringJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformModels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformPipelineJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformSpecialistPools</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformTrainingPipelines</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAllAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAnthosConnectedCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAnthosedgeCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayApi</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayApiConfig</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayGateway</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportApikeysKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineApplications</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportArtifactregistryDockerImages</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportArtifactregistryRepositories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportAssuredWorkloadsWorkloads</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpApiGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppConnectors</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpClientConnectorServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpClientGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryModels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryTables</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableAppProfile</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableBackup</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableInstance</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableTable</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudAssetFeeds</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployDeliveryPipelines</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployReleases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployRollouts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployTargets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIEvaluation</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIHumanReviewConfig</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAILabelerPool</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIProcessor</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIProcessorVersion</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudbillingBillingAccounts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudbillingProjectBillingInfos</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudfunctionsFunctions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudfunctionsGen2Functions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsCryptoKeyVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsCryptoKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsEkmConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsImportJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsKeyRings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudmemcacheInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerFolders</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerOrganizations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagValues</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComposerEnvironments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeAddress</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeAutoscalers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeBackendBuckets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeBackendServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeCommitments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeDisks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeExternalVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeFirewallPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeFirewalls</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeForwardingRules</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeGlobalAddress</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeGlobalForwardingRules</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHttpHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHttpsHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeImages</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceGroupManagers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInterconnect</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInterconnectAttachment</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeLicenses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNetworkEndpointGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNetworks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNodeGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNodeTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputePacketMirrorings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionAutoscaler</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionBackendServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionDisk</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionInstanceGroup</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionInstanceGroupManager</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeReservations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeResourcePolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRouters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSecurityPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeServiceAttachments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSnapshots</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSslCertificates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSslPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSubnetworks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetHttpProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetHttpsProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetPools</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetSslProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetTcpProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeUrlMaps</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeVpnTunnels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnectorVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnectors</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsProviders</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsRuntimeConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerAppsDeployment</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerAppsReplicaSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerBatchJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusterrole</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusterrolebinding</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerExtensionsIngresses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNamespace</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNetworkingIngresses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNetworkingNetworkPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNode</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNodepool</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerPod</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerReplicaSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerRole</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerRolebinding</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerregistryImage</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataMigrationConnectionProfiles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataMigrationMigrationJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataflowJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDatafusionInstance</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexAssets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexLakes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexTasks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocAutoscalingPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocBatches</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocSessions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocWorkflowTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamConnectionProfile</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamPrivateConnection</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamStream</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowAgents</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowConversationProfiles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowKnowledgeBases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowLocationSettings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpDeidentifyTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpDlpJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpInspectTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpJobTriggers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpStoredInfoTypes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDnsManagedZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDnsPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportDomainsRegistrations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportEventarcTriggers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportFileBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportFileInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportFirebaseAppInfos</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportFirebaseProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportFirestoreDatabases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGKEHubFeatures</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGKEHubMemberships</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerDeployments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesRealms</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupBackupPlans</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupRestorePlans</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupRestores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupVolumeBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupVolumeRestores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareConsentStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareDicomStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareFhirStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareHl7V2Stores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamRoles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamServiceAccountKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamServiceAccounts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnel</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnelInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnelZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.exportIapWeb</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebServiceVersion</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebType</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIdsEndpoints</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsAuthConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsCertificates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsExecutions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsIntegrationVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsIntegrations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSfdcChannels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSfdcInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSuspensions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportLoggingLogMetrics</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportLoggingLogSinks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportManagedidentitiesDomain</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreMetadataImports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportMonitoringAlertPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkConnectivityHubs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkConnectivitySpokes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkManagementConnectivityTests</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesEndpointPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesGrpcRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesHttpRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesMeshes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesServiceBindings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesTcpRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesTlsRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigOSPolicyAssignmentReports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigOSPolicyAssignments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigVulnerabilityReports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportPatchDeployments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubSnapshots</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubSubscriptions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubTopics</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportRedisInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSecretManagerSecretVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSecretManagerSecrets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceDirectoryNamespaces</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServicePerimeter</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumerProperty</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumerQuotaLimits</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementProducerOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementTenancyUnits</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementVisibility</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServicemanagementServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageAdminOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageConsumerOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerDatabases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdPhrases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdSettings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdSpeakers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeechCustomClasses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeechPhraseSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSqladminBackupRuns</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportSqladminInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportStorageBuckets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportTpuNodes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportVpcaccessConnector</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAccessLevel</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformBatchPredictionJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformCustomJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformDataLabelingJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformEndpoints</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformHyperparameterTuningJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformMetadataStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformModelDeploymentMonitoringJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformModels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformPipelineJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformSpecialistPools</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformTrainingPipelines</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAllAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAnthosConnectedCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAnthosedgeCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayApi</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayApiConfig</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayGateway</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listApikeysKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineApplications</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listArtifactregistryDockerImages</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listArtifactregistryRepositories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listAssuredWorkloadsWorkloads</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpApiGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppConnectors</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpClientConnectorServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpClientGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryModels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryTables</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableAppProfile</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableBackup</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableCluster</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableInstance</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableTable</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudAssetFeeds</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployDeliveryPipelines</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployReleases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployRollouts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployTargets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIEvaluation</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIHumanReviewConfig</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAILabelerPool</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIProcessor</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIProcessorVersion</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudbillingBillingAccounts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudbillingProjectBillingInfos</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudfunctionsFunctions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudfunctionsGen2Functions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsCryptoKeyVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsCryptoKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsEkmConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsImportJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsKeyRings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudmemcacheInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerFolders</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerOrganizations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagValues</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComposerEnvironments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeAddress</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeAutoscalers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeBackendBuckets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeBackendServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeCommitments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeDisks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeExternalVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeFirewallPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeFirewalls</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeForwardingRules</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeGlobalAddress</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeGlobalForwardingRules</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHttpHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHttpsHealthChecks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeImages</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceGroupManagers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInterconnect</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInterconnectAttachment</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeLicenses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNetworkEndpointGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNetworks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNodeGroups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNodeTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputePacketMirrorings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionAutoscaler</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionBackendServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionDisk</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionInstanceGroup</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionInstanceGroupManager</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeReservations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeResourcePolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRouters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSecurityPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeServiceAttachments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSnapshots</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSslCertificates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSslPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSubnetworks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetHttpProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetHttpsProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetPools</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetSslProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetTcpProxies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeUrlMaps</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeVpnGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listComputeVpnTunnels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnections</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnectorVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnectors</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsProviders</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsRuntimeConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerAppsDeployment</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerAppsReplicaSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerBatchJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusterrole</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusterrolebinding</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerExtensionsIngresses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNamespace</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNetworkingIngresses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNetworkingNetworkPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNode</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNodepool</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerPod</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerReplicaSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerRole</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerRolebinding</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listContainerregistryImage</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataMigrationConnectionProfiles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataMigrationMigrationJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataflowJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDatafusionInstance</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexAssets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexLakes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexTasks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocAutoscalingPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocBatches</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocSessions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocWorkflowTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamConnectionProfile</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamPrivateConnection</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamStream</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowAgents</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowConversationProfiles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowKnowledgeBases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowLocationSettings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDlpDeidentifyTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDlpDlpJobs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDlpInspectTemplates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDlpJobTriggers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDlpStoredInfoTypes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDnsManagedZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDnsPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listDomainsRegistrations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listEventarcTriggers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listFileBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listFileInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listFirebaseAppInfos</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listFirebaseProjects</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listFirestoreDatabases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGKEHubFeatures</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGKEHubMemberships</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerClusters</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerDeployments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesRealms</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupBackupPlans</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupRestorePlans</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupRestores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupVolumeBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupVolumeRestores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareConsentStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareDatasets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareDicomStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareFhirStores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareHl7V2Stores</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listIamRoles</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIamServiceAccountKeys</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIamServiceAccounts</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnel</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnelInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnelZones</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listIapWeb</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebServiceVersion</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebType</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIdsEndpoints</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsAuthConfigs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsCertificates</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsExecutions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsIntegrationVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsIntegrations</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSfdcChannels</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSfdcInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSuspensions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listLoggingLogMetrics</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listLoggingLogSinks</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listManagedidentitiesDomain</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreMetadataImports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listMonitoringAlertPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkConnectivityHubs</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkConnectivitySpokes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkManagementConnectivityTests</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesEndpointPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesGateways</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesGrpcRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesHttpRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesMeshes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesServiceBindings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesTcpRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesTlsRoutes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigOSPolicyAssignmentReports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigOSPolicyAssignments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigVulnerabilityReports</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listPatchDeployments</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubSnapshots</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubSubscriptions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubTopics</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listRedisInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listRunDomainMapping</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listRunRevision</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listRunService</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSecretManagerSecretVersions</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSecretManagerSecrets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceDirectoryNamespaces</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServicePerimeter</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumerProperty</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumerQuotaLimits</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementProducerOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementTenancyUnits</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementVisibility</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServicemanagementServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageAdminOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageConsumerOverrides</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageServices</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerBackups</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerDatabases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdPhrases</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdSettings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdSpeakers</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpeechCustomClasses</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSpeechPhraseSets</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSqladminBackupRuns</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listSqladminInstances</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listStorageBuckets</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listTpuNodes</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  listVpcaccessConnector</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">config.automigrationconfig.get</code></p>
<p><code dir="ltr" translate="no">config.  deploymentgrouprevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  get</code></li>
<li><code dir="ltr" translate="no">config.  deploymentgrouprevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.deploymentgroups.get</code></p>
<p><code dir="ltr" translate="no">config.deploymentgroups.list</code></p>
<p><code dir="ltr" translate="no">config.deployments.get</code></p>
<p><code dir="ltr" translate="no">config.  deployments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">config.deployments.list</code></p>
<p><code dir="ltr" translate="no">config.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.locations.get</code></li>
<li><code dir="ltr" translate="no">config.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.operations.get</code></p>
<p><code dir="ltr" translate="no">config.operations.list</code></p>
<p><code dir="ltr" translate="no">config.previews.get</code></p>
<p><code dir="ltr" translate="no">config.previews.list</code></p>
<p><code dir="ltr" translate="no">config.resources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.resources.get</code></li>
<li><code dir="ltr" translate="no">config.resources.list</code></li>
</ul>
<p><code dir="ltr" translate="no">config.revisions.get</code></p>
<p><code dir="ltr" translate="no">config.revisions.list</code></p>
<p><code dir="ltr" translate="no">config.terraformversions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">config.terraformversions.get</code></li>
<li><code dir="ltr" translate="no">config.terraformversions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplateRevisions.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  applicationTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.applications.get</code></p>
<p><code dir="ltr" translate="no">designcenter.applications.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplateRevisions.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplateRevisions.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplates.  get</code></p>
<p><code dir="ltr" translate="no">designcenter.  catalogTemplates.  list</code></p>
<p><code dir="ltr" translate="no">designcenter.catalogs.get</code></p>
<p><code dir="ltr" translate="no">designcenter.catalogs.list</code></p>
<p><code dir="ltr" translate="no">designcenter.components.get</code></p>
<p><code dir="ltr" translate="no">designcenter.components.list</code></p>
<p><code dir="ltr" translate="no">designcenter.connections.get</code></p>
<p><code dir="ltr" translate="no">designcenter.connections.list</code></p>
<p><code dir="ltr" translate="no">designcenter.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">designcenter.locations.get</code></li>
<li><code dir="ltr" translate="no">designcenter.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">designcenter.operations.get</code></p>
<p><code dir="ltr" translate="no">designcenter.operations.list</code></p>
<p><code dir="ltr" translate="no">designcenter.  sharedTemplateRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">designcenter.  sharedTemplateRevisions.  get</code></li>
<li><code dir="ltr" translate="no">designcenter.  sharedTemplateRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">designcenter.sharedTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">designcenter.  sharedTemplates.  get</code></li>
<li><code dir="ltr" translate="no">designcenter.  sharedTemplates.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">designcenter.shares.get</code></p>
<p><code dir="ltr" translate="no">designcenter.shares.list</code></p>
<p><code dir="ltr" translate="no">designcenter.spaces.get</code></p>
<p><code dir="ltr" translate="no">designcenter.  spaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">designcenter.spaces.list</code></p>
<p><code dir="ltr" translate="no">developerconnect.  deploymentEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  deploymentEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  insightsConfigs.  list</code></p>
<p><code dir="ltr" translate="no">developerconnect.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">developerconnect.locations.get</code></li>
<li><code dir="ltr" translate="no">developerconnect.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">developerconnect.  operations.  get</code></p>
<p><code dir="ltr" translate="no">developerconnect.  operations.  list</code></p>
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
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  uptimeCheckConfigs.  list</code></p>
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  appengineVersionCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryCapacityCommitmentsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryMaterializedViewRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryPartitionClusterRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryPartitionClusterRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryTableStatsInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigqueryTableStatsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  bigtableClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudCostGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudDeprecationGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudFunctionsPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudManageabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudPerformanceGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudRecentChangeRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudReliabilityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudSecurityGeneralRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlIdleInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceActivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceDiskUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOomProbabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceOutOfDiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstancePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlInstanceUnderprovisionedMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlOverprovisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudsqlUnderProvisionedInstanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  commitmentUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeAddressIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeDiskIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeFirewallInsightTypeConfigs.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeFirewallInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeFirewallInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeImageIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsagePredictionInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageTrendInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsagePredictionInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageTrendInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerCpuUsageTrendInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsagePredictionInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceGroupManagerMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceIdleResourceRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMachineTypeRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsageInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsageInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsagePredictionInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceMemoryUsagePredictionInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceNetworkThroughputInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  computeInstanceNetworkThroughputInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  containerDiagnosisRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.get</code></p>
<p><code dir="ltr" translate="no">recommender.costInsights.list</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  dataflowDiagnosticsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  errorReportingRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseFirebaseRulesRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  firestoreDatabaseReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpGuidedExperienceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectManagementRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  gmpProjectProductSuggestionsRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyLateralMovementInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyLateralMovementInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  iamServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  loggingProductSuggestionContainerRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreManageabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystorePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreUtilizationInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  memorystoreUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  monitoringProductSuggestionComputeRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerCloudSqlInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerCloudSqlInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerDynamicRouteInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerDynamicRouteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeServiceAccountInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerGkeServiceAccountInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerIpAddressInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerIpAddressInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerLoadBalancerInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerLoadBalancerInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerVpcConnectivityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  networkAnalyzerVpcConnectivityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  orgPolicyRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectChangeRiskRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationInsightTypeConfigs.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerProjectUtilizationRecommenderConfigs.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  resourcemanagerServiceLimitRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceCostRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceIdentityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServicePerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  runServiceSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerDatabaseSecurityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spannerProjectReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  spendBasedCommitmentRecommenderConfig.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  usageCommitmentRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicehealth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicehealth.artifacts.get</code></li>
<li><code dir="ltr" translate="no">servicehealth.artifacts.list</code></li>
<li><code dir="ltr" translate="no">servicehealth.events.get</code></li>
<li><code dir="ltr" translate="no">servicehealth.events.list</code></li>
<li><code dir="ltr" translate="no">servicehealth.locations.get</code></li>
<li><code dir="ltr" translate="no">servicehealth.locations.list</code></li>
<li><code dir="ltr" translate="no">servicehealth.  organizationEvents.  get</code></li>
<li><code dir="ltr" translate="no">servicehealth.  organizationEvents.  list</code></li>
<li><code dir="ltr" translate="no">servicehealth.  organizationImpacts.  get</code></li>
<li><code dir="ltr" translate="no">servicehealth.  organizationImpacts.  list</code></li>
<li><code dir="ltr" translate="no">servicehealth.statuses.get</code></li>
</ul>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## App Hub permissions

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
<td><h4 id="apphub.applications.create" class="permission-name add-link" data-text="apphub.applications.create" tabindex="-1"><code dir="ltr" translate="no">apphub.applications.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.applications.delete" class="permission-name add-link" data-text="apphub.applications.delete" tabindex="-1"><code dir="ltr" translate="no">apphub.applications.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.applications.get" class="permission-name add-link" data-text="apphub.applications.get" tabindex="-1"><code dir="ltr" translate="no">apphub.applications.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.applications.getIamPolicy" class="permission-name add-link" data-text="apphub.applications.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">apphub.  applications.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.applications.list" class="permission-name add-link" data-text="apphub.applications.list" tabindex="-1"><code dir="ltr" translate="no">apphub.applications.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.applications.setIamPolicy" class="permission-name add-link" data-text="apphub.applications.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">apphub.  applications.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.applications.update" class="permission-name add-link" data-text="apphub.applications.update" tabindex="-1"><code dir="ltr" translate="no">apphub.applications.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.boundaries.attach" class="permission-name add-link" data-text="apphub.boundaries.attach" tabindex="-1"><code dir="ltr" translate="no">apphub.boundaries.attach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.boundaries.get" class="permission-name add-link" data-text="apphub.boundaries.get" tabindex="-1"><code dir="ltr" translate="no">apphub.boundaries.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.boundaries.update" class="permission-name add-link" data-text="apphub.boundaries.update" tabindex="-1"><code dir="ltr" translate="no">apphub.boundaries.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.discoveredServices.get" class="permission-name add-link" data-text="apphub.discoveredServices.get" tabindex="-1"><code dir="ltr" translate="no">apphub.discoveredServices.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.discoveredServices.list" class="permission-name add-link" data-text="apphub.discoveredServices.list" tabindex="-1"><code dir="ltr" translate="no">apphub.discoveredServices.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.discoveredServices.register" class="permission-name add-link" data-text="apphub.discoveredServices.register" tabindex="-1"><code dir="ltr" translate="no">apphub.  discoveredServices.  register</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.discoveredWorkloads.get" class="permission-name add-link" data-text="apphub.discoveredWorkloads.get" tabindex="-1"><code dir="ltr" translate="no">apphub.discoveredWorkloads.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.discoveredWorkloads.list" class="permission-name add-link" data-text="apphub.discoveredWorkloads.list" tabindex="-1"><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.discoveredWorkloads.register" class="permission-name add-link" data-text="apphub.discoveredWorkloads.register" tabindex="-1"><code dir="ltr" translate="no">apphub.  discoveredWorkloads.  register</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.extendedMetadataSchemas.get" class="permission-name add-link" data-text="apphub.extendedMetadataSchemas.get" tabindex="-1"><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.extendedMetadataSchemas.list" class="permission-name add-link" data-text="apphub.extendedMetadataSchemas.list" tabindex="-1"><code dir="ltr" translate="no">apphub.  extendedMetadataSchemas.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.locations.get" class="permission-name add-link" data-text="apphub.locations.get" tabindex="-1"><code dir="ltr" translate="no">apphub.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.locations.list" class="permission-name add-link" data-text="apphub.locations.list" tabindex="-1"><code dir="ltr" translate="no">apphub.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.operations.cancel" class="permission-name add-link" data-text="apphub.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">apphub.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.operations.delete" class="permission-name add-link" data-text="apphub.operations.delete" tabindex="-1"><code dir="ltr" translate="no">apphub.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.operations.get" class="permission-name add-link" data-text="apphub.operations.get" tabindex="-1"><code dir="ltr" translate="no">apphub.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.operations.list" class="permission-name add-link" data-text="apphub.operations.list" tabindex="-1"><code dir="ltr" translate="no">apphub.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.serviceProjectAttachments.attach" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.attach" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  attach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.serviceProjectAttachments.create" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.create" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.serviceProjectAttachments.delete" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.delete" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.serviceProjectAttachments.detach" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.detach" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  detach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.serviceProjectAttachments.get" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.get" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.serviceProjectAttachments.list" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.list" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.serviceProjectAttachments.lookup" class="permission-name add-link" data-text="apphub.serviceProjectAttachments.lookup" tabindex="-1"><code dir="ltr" translate="no">apphub.  serviceProjectAttachments.  lookup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.services.create" class="permission-name add-link" data-text="apphub.services.create" tabindex="-1"><code dir="ltr" translate="no">apphub.services.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.services.delete" class="permission-name add-link" data-text="apphub.services.delete" tabindex="-1"><code dir="ltr" translate="no">apphub.services.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apphub.services.get" class="permission-name add-link" data-text="apphub.services.get" tabindex="-1"><code dir="ltr" translate="no">apphub.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.services.list" class="permission-name add-link" data-text="apphub.services.list" tabindex="-1"><code dir="ltr" translate="no">apphub.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.services.update" class="permission-name add-link" data-text="apphub.services.update" tabindex="-1"><code dir="ltr" translate="no">apphub.services.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.workloads.create" class="permission-name add-link" data-text="apphub.workloads.create" tabindex="-1"><code dir="ltr" translate="no">apphub.workloads.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.workloads.delete" class="permission-name add-link" data-text="apphub.workloads.delete" tabindex="-1"><code dir="ltr" translate="no">apphub.workloads.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.workloads.get" class="permission-name add-link" data-text="apphub.workloads.get" tabindex="-1"><code dir="ltr" translate="no">apphub.workloads.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="apphub.workloads.list" class="permission-name add-link" data-text="apphub.workloads.list" tabindex="-1"><code dir="ltr" translate="no">apphub.workloads.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="apphub.workloads.update" class="permission-name add-link" data-text="apphub.workloads.update" tabindex="-1"><code dir="ltr" translate="no">apphub.workloads.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apphub.editor</code> )</p></td>
</tr>
</tbody>
</table>
