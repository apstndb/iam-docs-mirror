---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudhub
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub
title: Cloud Hub roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Hub. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Hub roles

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
<td><h4 id="cloudhub.operator" class="role-title add-link" data-text="Cloud Hub Operator Beta" tabindex="-1">Cloud Hub Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p>Allows users to view and interact with Cloud Hub.</p></td>
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
<p><code dir="ltr" translate="no">apptopology.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apptopology.  applicationTopologies.  generate</code></li>
<li><code dir="ltr" translate="no">apptopology.  discoveredResourcesTopologies.  generate</code></li>
<li><code dir="ltr" translate="no">apptopology.domains.get</code></li>
<li><code dir="ltr" translate="no">apptopology.domains.list</code></li>
<li><code dir="ltr" translate="no">apptopology.locations.get</code></li>
<li><code dir="ltr" translate="no">apptopology.locations.list</code></li>
<li><code dir="ltr" translate="no">apptopology.operations.get</code></li>
<li><code dir="ltr" translate="no">apptopology.operations.list</code></li>
<li><code dir="ltr" translate="no">apptopology.schemas.get</code></li>
<li><code dir="ltr" translate="no">apptopology.topologyViews.get</code></li>
<li><code dir="ltr" translate="no">apptopology.topologyViews.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.auditReports.get</code></p>
<p><code dir="ltr" translate="no">auditmanager.auditReports.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  auditSchedules.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.controlReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.controls.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.findings.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.get</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">billing.resourceCosts.get</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  capacityPlans.  get</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  capacityPlans.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.forecasts.list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.operations.get</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  planAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageAlertInsights.  list</code></p>
<p><code dir="ltr" translate="no">capacityplanner.  usageHistories.*</code></p>
<ul>
<li><code dir="ltr" translate="no">capacityplanner.  usageHistories.  list</code></li>
<li><code dir="ltr" translate="no">capacityplanner.  usageHistories.  summarize</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.assets.*</code></p>
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
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudquotas.quotas.get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cmEnrollments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controlComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controlReports.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findingSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  findings.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceReports.  aggregate</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceReports.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceSummaries.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsupport.properties.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.get</code></p>
<p><code dir="ltr" translate="no">cloudsupport.techCases.list</code></p>
<p><code dir="ltr" translate="no">compute.futureReservations.get</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  list</code></p>
<p><code dir="ltr" translate="no">compute.reservations.get</code></p>
<p><code dir="ltr" translate="no">compute.reservations.list</code></p>
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
<p><code dir="ltr" translate="no">errorreporting.  applications.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  groupMetadata.  get</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
<p><code dir="ltr" translate="no">logging.buckets.get</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.links.get</code></p>
<p><code dir="ltr" translate="no">logging.links.list</code></p>
<p><code dir="ltr" translate="no">logging.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.locations.get</code></li>
<li><code dir="ltr" translate="no">logging.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.get</code></p>
<p><code dir="ltr" translate="no">logging.logScopes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.get</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.list</code></p>
<p><code dir="ltr" translate="no">logging.operations.get</code></p>
<p><code dir="ltr" translate="no">logging.operations.list</code></p>
<p><code dir="ltr" translate="no">logging.queries.getShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.listShared</code></p>
<p><code dir="ltr" translate="no">logging.queries.usePrivate</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.usage.get</code></p>
<p><code dir="ltr" translate="no">logging.views.get</code></p>
<p><code dir="ltr" translate="no">logging.views.list</code></p>
<p><code dir="ltr" translate="no">maintenance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">maintenance.locations.get</code></li>
<li><code dir="ltr" translate="no">maintenance.locations.list</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  get</code></li>
<li><code dir="ltr" translate="no">maintenance.  resourceMaintenances.  list</code></li>
</ul>
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
<p><code dir="ltr" translate="no">observability.scopes.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  exposurepathexplan.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.issues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
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

## Cloud Hub permissions

There are no IAM permissions for this service.
