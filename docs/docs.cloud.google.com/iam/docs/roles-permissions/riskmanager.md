---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/riskmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager
title: Cyber Insurance Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cyber Insurance Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cyber Insurance Hub roles

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
<td><h4 id="riskmanager.admin" class="role-title add-link" data-text="Risk Manager Admin Beta" tabindex="-1">Risk Manager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p>Grants all Risk Manager permissions</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  get</code></li>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></li>
<li><code dir="ltr" translate="no">riskmanager.operations.delete</code></li>
<li><code dir="ltr" translate="no">riskmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.operations.list</code></li>
<li><code dir="ltr" translate="no">riskmanager.policies.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.policies.list</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.create</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.delete</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.list</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.review</code></li>
<li><code dir="ltr" translate="no">riskmanager.reports.share</code></li>
<li><code dir="ltr" translate="no">riskmanager.  serviceAccount.  create</code></li>
<li><code dir="ltr" translate="no">riskmanager.settings.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.settings.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.editor" class="role-title add-link" data-text="Risk Manager Editor Beta" tabindex="-1">Risk Manager Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p>Access to edit Risk Manager resources</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  get</code></li>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.operations.delete</code></li>
<li><code dir="ltr" translate="no">riskmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.policies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.policies.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.policies.list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.reports.create</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.delete</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.get</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  serviceAccount.  create</code></p>
<p><code dir="ltr" translate="no">riskmanager.settings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.settings.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.settings.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.viewer" class="role-title add-link" data-text="Risk Manager Viewer Beta" tabindex="-1">Risk Manager Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p>Access to view Risk Manager resources</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  get</code></li>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.operations.get</code></p>
<p><code dir="ltr" translate="no">riskmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.policies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.policies.get</code></li>
<li><code dir="ltr" translate="no">riskmanager.policies.list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.reports.get</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.settings.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.reviewer" class="role-title add-link" data-text="Risk Manager Report Reviewer Beta" tabindex="-1">Risk Manager Report Reviewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p>
<p>Access to review Risk Manager reports</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  get</code></li>
<li><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">riskmanager.operations.get</code></p>
<p><code dir="ltr" translate="no">riskmanager.operations.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.get</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.list</code></p>
<p><code dir="ltr" translate="no">riskmanager.reports.review</code></p></td>
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
<td><h4 id="riskmanager.serviceAgent" class="role-title add-link" data-text="Risk Manager Service Agent" tabindex="-1">Risk Manager Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</p>
<p>Service agent that grants Risk Manager service access to fetch findings for generating Reports</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.analyzeMove</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  analyzeOrgPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAccessLevel</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAccessPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformBatchPredictionJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformCustomJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformDataLabelingJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformEndpoints</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformHyperparameterTuningJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformMetadataStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformModelDeploymentMonitoringJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformModels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformPipelineJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformSpecialistPools</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAiplatformTrainingPipelines</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAllAccessPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAnthosConnectedCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAnthosedgeCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayApi</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayApiConfig</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportApigatewayGateway</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportApikeysKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineApplications</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAppengineVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportArtifactregistryDockerImages</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportArtifactregistryRepositories</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportAssuredWorkloadsWorkloads</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpApiGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppConnectors</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpAppGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpClientConnectorServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBeyondCorpClientGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryModels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigqueryTables</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableAppProfile</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableBackup</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableInstance</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportBigtableTable</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudAssetFeeds</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployDeliveryPipelines</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployReleases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployRollouts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDeployTargets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIEvaluation</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIHumanReviewConfig</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAILabelerPool</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIProcessor</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudDocumentAIProcessorVersion</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudbillingBillingAccounts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudbillingProjectBillingInfos</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudfunctionsFunctions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudfunctionsGen2Functions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsCryptoKeyVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsCryptoKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsEkmConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsImportJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudkmsKeyRings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudmemcacheInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerFolders</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerOrganizations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagBindings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportCloudresourcemanagerTagValues</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComposerEnvironments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeAddress</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeAutoscalers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeBackendBuckets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeBackendServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeCommitments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeDisks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeExternalVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeFirewallPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeFirewalls</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeForwardingRules</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeGlobalAddress</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeGlobalForwardingRules</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHttpHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeHttpsHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeImages</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceGroupManagers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstanceTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInterconnect</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeInterconnectAttachment</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeLicenses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNetworkEndpointGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNetworks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNodeGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeNodeTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputePacketMirrorings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionAutoscaler</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionBackendServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionDisk</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionInstanceGroup</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRegionInstanceGroupManager</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeReservations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRouters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeServiceAttachments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSnapshots</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSslCertificates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSslPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeSubnetworks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetHttpProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetHttpsProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetPools</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetSslProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetTcpProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeTargetVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeUrlMaps</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportComputeVpnTunnels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnectorVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsConnectors</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsProviders</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportConnectorsRuntimeConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerAppsDeployment</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerAppsReplicaSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerBatchJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusterrole</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusterrolebinding</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerExtensionsIngresses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNamespace</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNetworkingIngresses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNetworkingNetworkPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNode</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerNodepool</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerPod</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerReplicaSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerRole</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerRolebinding</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportContainerregistryImage</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataMigrationConnectionProfiles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataMigrationMigrationJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataflowJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDatafusionInstance</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexAssets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexLakes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexTasks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataplexZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocAutoscalingPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocBatches</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocSessions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDataprocWorkflowTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamConnectionProfile</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamPrivateConnection</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDatastreamStream</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowAgents</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowConversationProfiles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowKnowledgeBases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDialogflowLocationSettings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpDeidentifyTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpDlpJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpInspectTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpJobTriggers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDlpStoredInfoTypes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDnsManagedZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDnsPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportDomainsRegistrations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportEventarcTriggers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportFileBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportFileInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportFirebaseAppInfos</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportFirebaseProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportFirestoreDatabases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGKEHubFeatures</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGKEHubMemberships</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesGameServerDeployments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGameservicesRealms</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupBackupPlans</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupRestorePlans</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupRestores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupVolumeBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportGkeBackupVolumeRestores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareConsentStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareDicomStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareFhirStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportHealthcareHl7V2Stores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIamRoles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIamServiceAccountKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIamServiceAccounts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnel</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnelInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapTunnelZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.exportIapWeb</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebServiceVersion</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIapWebType</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIdsEndpoints</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsAuthConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsCertificates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsExecutions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsIntegrationVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsIntegrations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSfdcChannels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSfdcInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportIntegrationsSuspensions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportLoggingLogMetrics</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportLoggingLogSinks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportManagedidentitiesDomain</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreMetadataImports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportMetastoreServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportMonitoringAlertPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkConnectivityHubs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkConnectivitySpokes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkManagementConnectivityTests</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesEndpointPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesGrpcRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesHttpRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesMeshes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesServiceBindings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesTcpRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportNetworkServicesTlsRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigOSPolicyAssignmentReports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigOSPolicyAssignments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportOSConfigVulnerabilityReports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportOrgPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportPatchDeployments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubSnapshots</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubSubscriptions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportPubsubTopics</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportRedisInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSecretManagerSecretVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSecretManagerSecrets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceDirectoryNamespaces</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServicePerimeter</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumerProperty</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumerQuotaLimits</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementConsumers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementProducerOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementTenancyUnits</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceconsumermanagementVisibility</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServicemanagementServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageAdminOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageConsumerOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportServiceusageServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerDatabases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpannerInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdPhrases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdSettings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeakerIdSpeakers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeechCustomClasses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSpeechPhraseSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSqladminBackupRuns</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportSqladminInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportStorageBuckets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportTpuNodes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  exportVpcaccessConnector</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAccessLevel</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAccessPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformBatchPredictionJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformCustomJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformDataLabelingJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformEndpoints</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformHyperparameterTuningJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformMetadataStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformModelDeploymentMonitoringJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformModels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformPipelineJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformSpecialistPools</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAiplatformTrainingPipelines</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAllAccessPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAnthosConnectedCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAnthosedgeCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayApi</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayApiConfig</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listApigatewayGateway</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listApikeysKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineApplications</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAppengineVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listArtifactregistryDockerImages</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listArtifactregistryRepositories</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listAssuredWorkloadsWorkloads</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpApiGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppConnectors</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpAppGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpClientConnectorServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBeyondCorpClientGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryModels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigqueryTables</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableAppProfile</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableBackup</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableCluster</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableInstance</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listBigtableTable</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudAssetFeeds</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployDeliveryPipelines</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployReleases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployRollouts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDeployTargets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIEvaluation</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIHumanReviewConfig</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAILabelerPool</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIProcessor</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudDocumentAIProcessorVersion</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudbillingBillingAccounts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudbillingProjectBillingInfos</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudfunctionsFunctions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudfunctionsGen2Functions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsCryptoKeyVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsCryptoKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsEkmConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsImportJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudkmsKeyRings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudmemcacheInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerFolders</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerOrganizations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagBindings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listCloudresourcemanagerTagValues</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComposerEnvironments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeAddress</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeAutoscalers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeBackendBuckets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeBackendServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeCommitments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeDisks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeExternalVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeFirewallPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeFirewalls</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeForwardingRules</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeGlobalAddress</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeGlobalForwardingRules</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHttpHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeHttpsHealthChecks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeImages</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceGroupManagers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstanceTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInterconnect</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeInterconnectAttachment</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeLicenses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNetworkEndpointGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNetworks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNodeGroups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeNodeTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputePacketMirrorings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionAutoscaler</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionBackendServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionDisk</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionInstanceGroup</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRegionInstanceGroupManager</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeReservations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeResourcePolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRouters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeServiceAttachments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSnapshots</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSslCertificates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSslPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeSubnetworks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetHttpProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetHttpsProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetPools</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetSslProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetTcpProxies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeTargetVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeUrlMaps</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeVpnGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listComputeVpnTunnels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnections</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnectorVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsConnectors</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsProviders</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listConnectorsRuntimeConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerAppsDeployment</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerAppsReplicaSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerBatchJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusterrole</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusterrolebinding</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerExtensionsIngresses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNamespace</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNetworkingIngresses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNetworkingNetworkPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNode</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerNodepool</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerPod</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerReplicaSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerRole</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerRolebinding</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listContainerregistryImage</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataMigrationConnectionProfiles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataMigrationMigrationJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataflowJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDatafusionInstance</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexAssets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexLakes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexTasks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataplexZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocAutoscalingPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocBatches</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocSessions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDataprocWorkflowTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamConnectionProfile</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamPrivateConnection</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDatastreamStream</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowAgents</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowConversationProfiles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowKnowledgeBases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDialogflowLocationSettings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDlpDeidentifyTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDlpDlpJobs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDlpInspectTemplates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDlpJobTriggers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDlpStoredInfoTypes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDnsManagedZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDnsPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listDomainsRegistrations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listEventarcTriggers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listFileBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listFileInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listFirebaseAppInfos</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listFirebaseProjects</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listFirestoreDatabases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGKEHubFeatures</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGKEHubMemberships</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerClusters</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesGameServerDeployments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGameservicesRealms</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupBackupPlans</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupRestorePlans</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupRestores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupVolumeBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listGkeBackupVolumeRestores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareConsentStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareDatasets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareDicomStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareFhirStores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listHealthcareHl7V2Stores</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.listIamRoles</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIamServiceAccountKeys</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIamServiceAccounts</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnel</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnelInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapTunnelZones</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.listIapWeb</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebServiceVersion</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIapWebType</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIdsEndpoints</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsAuthConfigs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsCertificates</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsExecutions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsIntegrationVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsIntegrations</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSfdcChannels</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSfdcInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listIntegrationsSuspensions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listLoggingLogMetrics</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listLoggingLogSinks</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listManagedidentitiesDomain</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreMetadataImports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listMetastoreServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listMonitoringAlertPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkConnectivityHubs</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkConnectivitySpokes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkManagementConnectivityTests</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesEndpointPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesGateways</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesGrpcRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesHttpRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesMeshes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesServiceBindings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesTcpRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listNetworkServicesTlsRoutes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigOSPolicyAssignmentReports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigOSPolicyAssignments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listOSConfigVulnerabilityReports</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listOSInventories</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listOrgPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listPatchDeployments</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubSnapshots</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubSubscriptions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listPubsubTopics</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listRedisInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.listResource</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listRunDomainMapping</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listRunRevision</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listRunService</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSecretManagerSecretVersions</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSecretManagerSecrets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceDirectoryNamespaces</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServicePerimeter</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumerProperty</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumerQuotaLimits</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementConsumers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementProducerOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementTenancyUnits</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceconsumermanagementVisibility</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServicemanagementServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageAdminOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageConsumerOverrides</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listServiceusageServices</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerBackups</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerDatabases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpannerInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdPhrases</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdSettings</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpeakerIdSpeakers</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpeechCustomClasses</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSpeechPhraseSets</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSqladminBackupRuns</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listSqladminInstances</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listStorageBuckets</code></li>
<li><code dir="ltr" translate="no">cloudasset.assets.listTpuNodes</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  listVpcaccessConnector</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></li>
<li><code dir="ltr" translate="no">cloudasset.  assets.  searchEnrichmentResourceOwners</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></p>
<p><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
</tbody>
</table>

## Cyber Insurance Hub permissions

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
<td><h4 id="riskmanager.controlScoreBreakdowns.get" class="permission-name add-link" data-text="riskmanager.controlScoreBreakdowns.get" tabindex="-1"><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.controlScoreBreakdowns.list" class="permission-name add-link" data-text="riskmanager.controlScoreBreakdowns.list" tabindex="-1"><code dir="ltr" translate="no">riskmanager.  controlScoreBreakdowns.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.operations.delete" class="permission-name add-link" data-text="riskmanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">riskmanager.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.operations.get" class="permission-name add-link" data-text="riskmanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">riskmanager.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.operations.list" class="permission-name add-link" data-text="riskmanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">riskmanager.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.policies.get" class="permission-name add-link" data-text="riskmanager.policies.get" tabindex="-1"><code dir="ltr" translate="no">riskmanager.policies.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.policies.list" class="permission-name add-link" data-text="riskmanager.policies.list" tabindex="-1"><code dir="ltr" translate="no">riskmanager.policies.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.reports.create" class="permission-name add-link" data-text="riskmanager.reports.create" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.reports.delete" class="permission-name add-link" data-text="riskmanager.reports.delete" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.reports.get" class="permission-name add-link" data-text="riskmanager.reports.get" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.reports.list" class="permission-name add-link" data-text="riskmanager.reports.list" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.reports.review" class="permission-name add-link" data-text="riskmanager.reports.review" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.review</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer">Risk Manager Report Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.reviewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.reports.share" class="permission-name add-link" data-text="riskmanager.reports.share" tabindex="-1"><code dir="ltr" translate="no">riskmanager.reports.share</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.serviceAccount.create" class="permission-name add-link" data-text="riskmanager.serviceAccount.create" tabindex="-1"><code dir="ltr" translate="no">riskmanager.  serviceAccount.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riskmanager.settings.get" class="permission-name add-link" data-text="riskmanager.settings.get" tabindex="-1"><code dir="ltr" translate="no">riskmanager.settings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer">Risk Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riskmanager.settings.update" class="permission-name add-link" data-text="riskmanager.settings.update" tabindex="-1"><code dir="ltr" translate="no">riskmanager.settings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin">Risk Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor">Risk Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.editor</code> )</p></td>
</tr>
</tbody>
</table>
