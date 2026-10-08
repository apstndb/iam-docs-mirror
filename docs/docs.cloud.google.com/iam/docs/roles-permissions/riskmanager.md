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
<td>Risk Manager Admin <sup>Beta</sup>
<p>( <code>roles/ riskmanager.admin</code> )</p>
<p>Grants all Risk Manager permissions</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>riskmanager.*</code></p>
<ul>
<li><code>riskmanager. controlScoreBreakdowns. get</code></li>
<li><code>riskmanager. controlScoreBreakdowns. list</code></li>
<li><code>riskmanager.operations.delete</code></li>
<li><code>riskmanager.operations.get</code></li>
<li><code>riskmanager.operations.list</code></li>
<li><code>riskmanager.policies.get</code></li>
<li><code>riskmanager.policies.list</code></li>
<li><code>riskmanager.reports.create</code></li>
<li><code>riskmanager.reports.delete</code></li>
<li><code>riskmanager.reports.get</code></li>
<li><code>riskmanager.reports.list</code></li>
<li><code>riskmanager.reports.review</code></li>
<li><code>riskmanager.reports.share</code></li>
<li><code>riskmanager. serviceAccount. create</code></li>
<li><code>riskmanager.settings.get</code></li>
<li><code>riskmanager.settings.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Risk Manager Editor <sup>Beta</sup>
<p>( <code>roles/ riskmanager.editor</code> )</p>
<p>Access to edit Risk Manager resources</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>riskmanager. controlScoreBreakdowns.*</code></p>
<ul>
<li><code>riskmanager. controlScoreBreakdowns. get</code></li>
<li><code>riskmanager. controlScoreBreakdowns. list</code></li>
</ul>
<p><code>riskmanager.operations.*</code></p>
<ul>
<li><code>riskmanager.operations.delete</code></li>
<li><code>riskmanager.operations.get</code></li>
<li><code>riskmanager.operations.list</code></li>
</ul>
<p><code>riskmanager.policies.*</code></p>
<ul>
<li><code>riskmanager.policies.get</code></li>
<li><code>riskmanager.policies.list</code></li>
</ul>
<p><code>riskmanager.reports.create</code></p>
<p><code>riskmanager.reports.delete</code></p>
<p><code>riskmanager.reports.get</code></p>
<p><code>riskmanager.reports.list</code></p>
<p><code>riskmanager. serviceAccount. create</code></p>
<p><code>riskmanager.settings.*</code></p>
<ul>
<li><code>riskmanager.settings.get</code></li>
<li><code>riskmanager.settings.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Risk Manager Viewer <sup>Beta</sup>
<p>( <code>roles/ riskmanager.viewer</code> )</p>
<p>Access to view Risk Manager resources</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>riskmanager. controlScoreBreakdowns.*</code></p>
<ul>
<li><code>riskmanager. controlScoreBreakdowns. get</code></li>
<li><code>riskmanager. controlScoreBreakdowns. list</code></li>
</ul>
<p><code>riskmanager.operations.get</code></p>
<p><code>riskmanager.operations.list</code></p>
<p><code>riskmanager.policies.*</code></p>
<ul>
<li><code>riskmanager.policies.get</code></li>
<li><code>riskmanager.policies.list</code></li>
</ul>
<p><code>riskmanager.reports.get</code></p>
<p><code>riskmanager.reports.list</code></p>
<p><code>riskmanager.settings.get</code></p></td>
</tr>
<tr class="even">
<td>Risk Manager Report Reviewer <sup>Beta</sup>
<p>( <code>roles/ riskmanager.reviewer</code> )</p>
<p>Access to review Risk Manager reports</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>riskmanager. controlScoreBreakdowns.*</code></p>
<ul>
<li><code>riskmanager. controlScoreBreakdowns. get</code></li>
<li><code>riskmanager. controlScoreBreakdowns. list</code></li>
</ul>
<p><code>riskmanager.operations.get</code></p>
<p><code>riskmanager.operations.list</code></p>
<p><code>riskmanager.reports.get</code></p>
<p><code>riskmanager.reports.list</code></p>
<p><code>riskmanager.reports.review</code></p></td>
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
<td>Risk Manager Service Agent
<p>( <code>roles/ riskmanager.serviceAgent</code> )</p>
<p>Service agent that grants Risk Manager service access to fetch findings for generating Reports</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset.assets.*</code></p>
<ul>
<li><code>cloudasset. assets. analyzeIamPolicy</code></li>
<li><code>cloudasset.assets.analyzeMove</code></li>
<li><code>cloudasset. assets. analyzeOrgPolicy</code></li>
<li><code>cloudasset. assets. exportAccessLevel</code></li>
<li><code>cloudasset. assets. exportAccessPolicy</code></li>
<li><code>cloudasset. assets. exportAiplatformBatchPredictionJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformCustomJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformDataLabelingJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformDatasets</code></li>
<li><code>cloudasset. assets. exportAiplatformEndpoints</code></li>
<li><code>cloudasset. assets. exportAiplatformHyperparameterTuningJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformMetadataStores</code></li>
<li><code>cloudasset. assets. exportAiplatformModelDeploymentMonitoringJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformModels</code></li>
<li><code>cloudasset. assets. exportAiplatformPipelineJobs</code></li>
<li><code>cloudasset. assets. exportAiplatformSpecialistPools</code></li>
<li><code>cloudasset. assets. exportAiplatformTrainingPipelines</code></li>
<li><code>cloudasset. assets. exportAllAccessPolicy</code></li>
<li><code>cloudasset. assets. exportAnthosConnectedCluster</code></li>
<li><code>cloudasset. assets. exportAnthosedgeCluster</code></li>
<li><code>cloudasset. assets. exportApigatewayApi</code></li>
<li><code>cloudasset. assets. exportApigatewayApiConfig</code></li>
<li><code>cloudasset. assets. exportApigatewayGateway</code></li>
<li><code>cloudasset. assets. exportApikeysKeys</code></li>
<li><code>cloudasset. assets. exportAppengineApplications</code></li>
<li><code>cloudasset. assets. exportAppengineServices</code></li>
<li><code>cloudasset. assets. exportAppengineVersions</code></li>
<li><code>cloudasset. assets. exportArtifactregistryDockerImages</code></li>
<li><code>cloudasset. assets. exportArtifactregistryRepositories</code></li>
<li><code>cloudasset. assets. exportAssuredWorkloadsWorkloads</code></li>
<li><code>cloudasset. assets. exportBeyondCorpApiGateways</code></li>
<li><code>cloudasset. assets. exportBeyondCorpAppConnections</code></li>
<li><code>cloudasset. assets. exportBeyondCorpAppConnectors</code></li>
<li><code>cloudasset. assets. exportBeyondCorpAppGateways</code></li>
<li><code>cloudasset. assets. exportBeyondCorpClientConnectorServices</code></li>
<li><code>cloudasset. assets. exportBeyondCorpClientGateways</code></li>
<li><code>cloudasset. assets. exportBigqueryDatasets</code></li>
<li><code>cloudasset. assets. exportBigqueryModels</code></li>
<li><code>cloudasset. assets. exportBigqueryTables</code></li>
<li><code>cloudasset. assets. exportBigtableAppProfile</code></li>
<li><code>cloudasset. assets. exportBigtableBackup</code></li>
<li><code>cloudasset. assets. exportBigtableCluster</code></li>
<li><code>cloudasset. assets. exportBigtableInstance</code></li>
<li><code>cloudasset. assets. exportBigtableTable</code></li>
<li><code>cloudasset. assets. exportCloudAssetFeeds</code></li>
<li><code>cloudasset. assets. exportCloudDeployDeliveryPipelines</code></li>
<li><code>cloudasset. assets. exportCloudDeployReleases</code></li>
<li><code>cloudasset. assets. exportCloudDeployRollouts</code></li>
<li><code>cloudasset. assets. exportCloudDeployTargets</code></li>
<li><code>cloudasset. assets. exportCloudDocumentAIEvaluation</code></li>
<li><code>cloudasset. assets. exportCloudDocumentAIHumanReviewConfig</code></li>
<li><code>cloudasset. assets. exportCloudDocumentAILabelerPool</code></li>
<li><code>cloudasset. assets. exportCloudDocumentAIProcessor</code></li>
<li><code>cloudasset. assets. exportCloudDocumentAIProcessorVersion</code></li>
<li><code>cloudasset. assets. exportCloudbillingBillingAccounts</code></li>
<li><code>cloudasset. assets. exportCloudbillingProjectBillingInfos</code></li>
<li><code>cloudasset. assets. exportCloudfunctionsFunctions</code></li>
<li><code>cloudasset. assets. exportCloudfunctionsGen2Functions</code></li>
<li><code>cloudasset. assets. exportCloudkmsCryptoKeyVersions</code></li>
<li><code>cloudasset. assets. exportCloudkmsCryptoKeys</code></li>
<li><code>cloudasset. assets. exportCloudkmsEkmConnections</code></li>
<li><code>cloudasset. assets. exportCloudkmsImportJobs</code></li>
<li><code>cloudasset. assets. exportCloudkmsKeyRings</code></li>
<li><code>cloudasset. assets. exportCloudmemcacheInstances</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerFolders</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerOrganizations</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerProjects</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerTagBindings</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerTagKeys</code></li>
<li><code>cloudasset. assets. exportCloudresourcemanagerTagValues</code></li>
<li><code>cloudasset. assets. exportComposerEnvironments</code></li>
<li><code>cloudasset. assets. exportComputeAddress</code></li>
<li><code>cloudasset. assets. exportComputeAutoscalers</code></li>
<li><code>cloudasset. assets. exportComputeBackendBuckets</code></li>
<li><code>cloudasset. assets. exportComputeBackendServices</code></li>
<li><code>cloudasset. assets. exportComputeCommitments</code></li>
<li><code>cloudasset. assets. exportComputeDisks</code></li>
<li><code>cloudasset. assets. exportComputeExternalVpnGateways</code></li>
<li><code>cloudasset. assets. exportComputeFirewallPolicies</code></li>
<li><code>cloudasset. assets. exportComputeFirewalls</code></li>
<li><code>cloudasset. assets. exportComputeForwardingRules</code></li>
<li><code>cloudasset. assets. exportComputeGlobalAddress</code></li>
<li><code>cloudasset. assets. exportComputeGlobalForwardingRules</code></li>
<li><code>cloudasset. assets. exportComputeHealthChecks</code></li>
<li><code>cloudasset. assets. exportComputeHttpHealthChecks</code></li>
<li><code>cloudasset. assets. exportComputeHttpsHealthChecks</code></li>
<li><code>cloudasset. assets. exportComputeImages</code></li>
<li><code>cloudasset. assets. exportComputeInstanceGroupManagers</code></li>
<li><code>cloudasset. assets. exportComputeInstanceGroups</code></li>
<li><code>cloudasset. assets. exportComputeInstanceTemplates</code></li>
<li><code>cloudasset. assets. exportComputeInstances</code></li>
<li><code>cloudasset. assets. exportComputeInterconnect</code></li>
<li><code>cloudasset. assets. exportComputeInterconnectAttachment</code></li>
<li><code>cloudasset. assets. exportComputeLicenses</code></li>
<li><code>cloudasset. assets. exportComputeNetworkEndpointGroups</code></li>
<li><code>cloudasset. assets. exportComputeNetworks</code></li>
<li><code>cloudasset. assets. exportComputeNodeGroups</code></li>
<li><code>cloudasset. assets. exportComputeNodeTemplates</code></li>
<li><code>cloudasset. assets. exportComputePacketMirrorings</code></li>
<li><code>cloudasset. assets. exportComputeProjects</code></li>
<li><code>cloudasset. assets. exportComputeRegionAutoscaler</code></li>
<li><code>cloudasset. assets. exportComputeRegionBackendServices</code></li>
<li><code>cloudasset. assets. exportComputeRegionDisk</code></li>
<li><code>cloudasset. assets. exportComputeRegionInstanceGroup</code></li>
<li><code>cloudasset. assets. exportComputeRegionInstanceGroupManager</code></li>
<li><code>cloudasset. assets. exportComputeReservations</code></li>
<li><code>cloudasset. assets. exportComputeResourcePolicies</code></li>
<li><code>cloudasset. assets. exportComputeRouters</code></li>
<li><code>cloudasset. assets. exportComputeRoutes</code></li>
<li><code>cloudasset. assets. exportComputeSecurityPolicy</code></li>
<li><code>cloudasset. assets. exportComputeServiceAttachments</code></li>
<li><code>cloudasset. assets. exportComputeSnapshots</code></li>
<li><code>cloudasset. assets. exportComputeSslCertificates</code></li>
<li><code>cloudasset. assets. exportComputeSslPolicies</code></li>
<li><code>cloudasset. assets. exportComputeSubnetworks</code></li>
<li><code>cloudasset. assets. exportComputeTargetHttpProxies</code></li>
<li><code>cloudasset. assets. exportComputeTargetHttpsProxies</code></li>
<li><code>cloudasset. assets. exportComputeTargetInstances</code></li>
<li><code>cloudasset. assets. exportComputeTargetPools</code></li>
<li><code>cloudasset. assets. exportComputeTargetSslProxies</code></li>
<li><code>cloudasset. assets. exportComputeTargetTcpProxies</code></li>
<li><code>cloudasset. assets. exportComputeTargetVpnGateways</code></li>
<li><code>cloudasset. assets. exportComputeUrlMaps</code></li>
<li><code>cloudasset. assets. exportComputeVpnGateways</code></li>
<li><code>cloudasset. assets. exportComputeVpnTunnels</code></li>
<li><code>cloudasset. assets. exportConnectorsConnections</code></li>
<li><code>cloudasset. assets. exportConnectorsConnectorVersions</code></li>
<li><code>cloudasset. assets. exportConnectorsConnectors</code></li>
<li><code>cloudasset. assets. exportConnectorsProviders</code></li>
<li><code>cloudasset. assets. exportConnectorsRuntimeConfigs</code></li>
<li><code>cloudasset. assets. exportContainerAppsDeployment</code></li>
<li><code>cloudasset. assets. exportContainerAppsReplicaSets</code></li>
<li><code>cloudasset. assets. exportContainerBatchJobs</code></li>
<li><code>cloudasset. assets. exportContainerClusterrole</code></li>
<li><code>cloudasset. assets. exportContainerClusterrolebinding</code></li>
<li><code>cloudasset. assets. exportContainerClusters</code></li>
<li><code>cloudasset. assets. exportContainerExtensionsIngresses</code></li>
<li><code>cloudasset. assets. exportContainerJobs</code></li>
<li><code>cloudasset. assets. exportContainerNamespace</code></li>
<li><code>cloudasset. assets. exportContainerNetworkingIngresses</code></li>
<li><code>cloudasset. assets. exportContainerNetworkingNetworkPolicies</code></li>
<li><code>cloudasset. assets. exportContainerNode</code></li>
<li><code>cloudasset. assets. exportContainerNodepool</code></li>
<li><code>cloudasset. assets. exportContainerPod</code></li>
<li><code>cloudasset. assets. exportContainerReplicaSets</code></li>
<li><code>cloudasset. assets. exportContainerRole</code></li>
<li><code>cloudasset. assets. exportContainerRolebinding</code></li>
<li><code>cloudasset. assets. exportContainerServices</code></li>
<li><code>cloudasset. assets. exportContainerregistryImage</code></li>
<li><code>cloudasset. assets. exportDataMigrationConnectionProfiles</code></li>
<li><code>cloudasset. assets. exportDataMigrationMigrationJobs</code></li>
<li><code>cloudasset. assets. exportDataflowJobs</code></li>
<li><code>cloudasset. assets. exportDatafusionInstance</code></li>
<li><code>cloudasset. assets. exportDataplexAssets</code></li>
<li><code>cloudasset. assets. exportDataplexLakes</code></li>
<li><code>cloudasset. assets. exportDataplexTasks</code></li>
<li><code>cloudasset. assets. exportDataplexZones</code></li>
<li><code>cloudasset. assets. exportDataprocAutoscalingPolicies</code></li>
<li><code>cloudasset. assets. exportDataprocBatches</code></li>
<li><code>cloudasset. assets. exportDataprocClusters</code></li>
<li><code>cloudasset. assets. exportDataprocJobs</code></li>
<li><code>cloudasset. assets. exportDataprocSessions</code></li>
<li><code>cloudasset. assets. exportDataprocWorkflowTemplates</code></li>
<li><code>cloudasset. assets. exportDatastreamConnectionProfile</code></li>
<li><code>cloudasset. assets. exportDatastreamPrivateConnection</code></li>
<li><code>cloudasset. assets. exportDatastreamStream</code></li>
<li><code>cloudasset. assets. exportDialogflowAgents</code></li>
<li><code>cloudasset. assets. exportDialogflowConversationProfiles</code></li>
<li><code>cloudasset. assets. exportDialogflowKnowledgeBases</code></li>
<li><code>cloudasset. assets. exportDialogflowLocationSettings</code></li>
<li><code>cloudasset. assets. exportDlpDeidentifyTemplates</code></li>
<li><code>cloudasset. assets. exportDlpDlpJobs</code></li>
<li><code>cloudasset. assets. exportDlpInspectTemplates</code></li>
<li><code>cloudasset. assets. exportDlpJobTriggers</code></li>
<li><code>cloudasset. assets. exportDlpStoredInfoTypes</code></li>
<li><code>cloudasset. assets. exportDnsManagedZones</code></li>
<li><code>cloudasset. assets. exportDnsPolicies</code></li>
<li><code>cloudasset. assets. exportDomainsRegistrations</code></li>
<li><code>cloudasset. assets. exportEventarcTriggers</code></li>
<li><code>cloudasset. assets. exportFileBackups</code></li>
<li><code>cloudasset. assets. exportFileInstances</code></li>
<li><code>cloudasset. assets. exportFirebaseAppInfos</code></li>
<li><code>cloudasset. assets. exportFirebaseProjects</code></li>
<li><code>cloudasset. assets. exportFirestoreDatabases</code></li>
<li><code>cloudasset. assets. exportGKEHubFeatures</code></li>
<li><code>cloudasset. assets. exportGKEHubMemberships</code></li>
<li><code>cloudasset. assets. exportGameservicesGameServerClusters</code></li>
<li><code>cloudasset. assets. exportGameservicesGameServerConfigs</code></li>
<li><code>cloudasset. assets. exportGameservicesGameServerDeployments</code></li>
<li><code>cloudasset. assets. exportGameservicesRealms</code></li>
<li><code>cloudasset. assets. exportGkeBackupBackupPlans</code></li>
<li><code>cloudasset. assets. exportGkeBackupBackups</code></li>
<li><code>cloudasset. assets. exportGkeBackupRestorePlans</code></li>
<li><code>cloudasset. assets. exportGkeBackupRestores</code></li>
<li><code>cloudasset. assets. exportGkeBackupVolumeBackups</code></li>
<li><code>cloudasset. assets. exportGkeBackupVolumeRestores</code></li>
<li><code>cloudasset. assets. exportHealthcareConsentStores</code></li>
<li><code>cloudasset. assets. exportHealthcareDatasets</code></li>
<li><code>cloudasset. assets. exportHealthcareDicomStores</code></li>
<li><code>cloudasset. assets. exportHealthcareFhirStores</code></li>
<li><code>cloudasset. assets. exportHealthcareHl7V2Stores</code></li>
<li><code>cloudasset. assets. exportIamPolicy</code></li>
<li><code>cloudasset. assets. exportIamRoles</code></li>
<li><code>cloudasset. assets. exportIamServiceAccountKeys</code></li>
<li><code>cloudasset. assets. exportIamServiceAccounts</code></li>
<li><code>cloudasset. assets. exportIapTunnel</code></li>
<li><code>cloudasset. assets. exportIapTunnelInstances</code></li>
<li><code>cloudasset. assets. exportIapTunnelZones</code></li>
<li><code>cloudasset.assets.exportIapWeb</code></li>
<li><code>cloudasset. assets. exportIapWebServiceVersion</code></li>
<li><code>cloudasset. assets. exportIapWebServices</code></li>
<li><code>cloudasset. assets. exportIapWebType</code></li>
<li><code>cloudasset. assets. exportIdsEndpoints</code></li>
<li><code>cloudasset. assets. exportIntegrationsAuthConfigs</code></li>
<li><code>cloudasset. assets. exportIntegrationsCertificates</code></li>
<li><code>cloudasset. assets. exportIntegrationsExecutions</code></li>
<li><code>cloudasset. assets. exportIntegrationsIntegrationVersions</code></li>
<li><code>cloudasset. assets. exportIntegrationsIntegrations</code></li>
<li><code>cloudasset. assets. exportIntegrationsSfdcChannels</code></li>
<li><code>cloudasset. assets. exportIntegrationsSfdcInstances</code></li>
<li><code>cloudasset. assets. exportIntegrationsSuspensions</code></li>
<li><code>cloudasset. assets. exportLoggingLogMetrics</code></li>
<li><code>cloudasset. assets. exportLoggingLogSinks</code></li>
<li><code>cloudasset. assets. exportManagedidentitiesDomain</code></li>
<li><code>cloudasset. assets. exportMetastoreBackups</code></li>
<li><code>cloudasset. assets. exportMetastoreMetadataImports</code></li>
<li><code>cloudasset. assets. exportMetastoreServices</code></li>
<li><code>cloudasset. assets. exportMonitoringAlertPolicies</code></li>
<li><code>cloudasset. assets. exportNetworkConnectivityHubs</code></li>
<li><code>cloudasset. assets. exportNetworkConnectivitySpokes</code></li>
<li><code>cloudasset. assets. exportNetworkManagementConnectivityTests</code></li>
<li><code>cloudasset. assets. exportNetworkServicesEndpointPolicies</code></li>
<li><code>cloudasset. assets. exportNetworkServicesGateways</code></li>
<li><code>cloudasset. assets. exportNetworkServicesGrpcRoutes</code></li>
<li><code>cloudasset. assets. exportNetworkServicesHttpRoutes</code></li>
<li><code>cloudasset. assets. exportNetworkServicesMeshes</code></li>
<li><code>cloudasset. assets. exportNetworkServicesServiceBindings</code></li>
<li><code>cloudasset. assets. exportNetworkServicesTcpRoutes</code></li>
<li><code>cloudasset. assets. exportNetworkServicesTlsRoutes</code></li>
<li><code>cloudasset. assets. exportOSConfigOSPolicyAssignmentReports</code></li>
<li><code>cloudasset. assets. exportOSConfigOSPolicyAssignments</code></li>
<li><code>cloudasset. assets. exportOSConfigVulnerabilityReports</code></li>
<li><code>cloudasset. assets. exportOSInventories</code></li>
<li><code>cloudasset. assets. exportOrgPolicy</code></li>
<li><code>cloudasset. assets. exportPatchDeployments</code></li>
<li><code>cloudasset. assets. exportPubsubSnapshots</code></li>
<li><code>cloudasset. assets. exportPubsubSubscriptions</code></li>
<li><code>cloudasset. assets. exportPubsubTopics</code></li>
<li><code>cloudasset. assets. exportRedisInstances</code></li>
<li><code>cloudasset. assets. exportResource</code></li>
<li><code>cloudasset. assets. exportSecretManagerSecretVersions</code></li>
<li><code>cloudasset. assets. exportSecretManagerSecrets</code></li>
<li><code>cloudasset. assets. exportServiceDirectoryNamespaces</code></li>
<li><code>cloudasset. assets. exportServicePerimeter</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementConsumerProperty</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementConsumerQuotaLimits</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementConsumers</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementProducerOverrides</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementTenancyUnits</code></li>
<li><code>cloudasset. assets. exportServiceconsumermanagementVisibility</code></li>
<li><code>cloudasset. assets. exportServicemanagementServices</code></li>
<li><code>cloudasset. assets. exportServiceusageAdminOverrides</code></li>
<li><code>cloudasset. assets. exportServiceusageConsumerOverrides</code></li>
<li><code>cloudasset. assets. exportServiceusageServices</code></li>
<li><code>cloudasset. assets. exportSpannerBackups</code></li>
<li><code>cloudasset. assets. exportSpannerDatabases</code></li>
<li><code>cloudasset. assets. exportSpannerInstances</code></li>
<li><code>cloudasset. assets. exportSpeakerIdPhrases</code></li>
<li><code>cloudasset. assets. exportSpeakerIdSettings</code></li>
<li><code>cloudasset. assets. exportSpeakerIdSpeakers</code></li>
<li><code>cloudasset. assets. exportSpeechCustomClasses</code></li>
<li><code>cloudasset. assets. exportSpeechPhraseSets</code></li>
<li><code>cloudasset. assets. exportSqladminBackupRuns</code></li>
<li><code>cloudasset. assets. exportSqladminInstances</code></li>
<li><code>cloudasset. assets. exportStorageBuckets</code></li>
<li><code>cloudasset. assets. exportTpuNodes</code></li>
<li><code>cloudasset. assets. exportVpcaccessConnector</code></li>
<li><code>cloudasset. assets. listAccessLevel</code></li>
<li><code>cloudasset. assets. listAccessPolicy</code></li>
<li><code>cloudasset. assets. listAiplatformBatchPredictionJobs</code></li>
<li><code>cloudasset. assets. listAiplatformCustomJobs</code></li>
<li><code>cloudasset. assets. listAiplatformDataLabelingJobs</code></li>
<li><code>cloudasset. assets. listAiplatformDatasets</code></li>
<li><code>cloudasset. assets. listAiplatformEndpoints</code></li>
<li><code>cloudasset. assets. listAiplatformHyperparameterTuningJobs</code></li>
<li><code>cloudasset. assets. listAiplatformMetadataStores</code></li>
<li><code>cloudasset. assets. listAiplatformModelDeploymentMonitoringJobs</code></li>
<li><code>cloudasset. assets. listAiplatformModels</code></li>
<li><code>cloudasset. assets. listAiplatformPipelineJobs</code></li>
<li><code>cloudasset. assets. listAiplatformSpecialistPools</code></li>
<li><code>cloudasset. assets. listAiplatformTrainingPipelines</code></li>
<li><code>cloudasset. assets. listAllAccessPolicy</code></li>
<li><code>cloudasset. assets. listAnthosConnectedCluster</code></li>
<li><code>cloudasset. assets. listAnthosedgeCluster</code></li>
<li><code>cloudasset. assets. listApigatewayApi</code></li>
<li><code>cloudasset. assets. listApigatewayApiConfig</code></li>
<li><code>cloudasset. assets. listApigatewayGateway</code></li>
<li><code>cloudasset. assets. listApikeysKeys</code></li>
<li><code>cloudasset. assets. listAppengineApplications</code></li>
<li><code>cloudasset. assets. listAppengineServices</code></li>
<li><code>cloudasset. assets. listAppengineVersions</code></li>
<li><code>cloudasset. assets. listArtifactregistryDockerImages</code></li>
<li><code>cloudasset. assets. listArtifactregistryRepositories</code></li>
<li><code>cloudasset. assets. listAssuredWorkloadsWorkloads</code></li>
<li><code>cloudasset. assets. listBeyondCorpApiGateways</code></li>
<li><code>cloudasset. assets. listBeyondCorpAppConnections</code></li>
<li><code>cloudasset. assets. listBeyondCorpAppConnectors</code></li>
<li><code>cloudasset. assets. listBeyondCorpAppGateways</code></li>
<li><code>cloudasset. assets. listBeyondCorpClientConnectorServices</code></li>
<li><code>cloudasset. assets. listBeyondCorpClientGateways</code></li>
<li><code>cloudasset. assets. listBigqueryDatasets</code></li>
<li><code>cloudasset. assets. listBigqueryModels</code></li>
<li><code>cloudasset. assets. listBigqueryTables</code></li>
<li><code>cloudasset. assets. listBigtableAppProfile</code></li>
<li><code>cloudasset. assets. listBigtableBackup</code></li>
<li><code>cloudasset. assets. listBigtableCluster</code></li>
<li><code>cloudasset. assets. listBigtableInstance</code></li>
<li><code>cloudasset. assets. listBigtableTable</code></li>
<li><code>cloudasset. assets. listCloudAssetFeeds</code></li>
<li><code>cloudasset. assets. listCloudDeployDeliveryPipelines</code></li>
<li><code>cloudasset. assets. listCloudDeployReleases</code></li>
<li><code>cloudasset. assets. listCloudDeployRollouts</code></li>
<li><code>cloudasset. assets. listCloudDeployTargets</code></li>
<li><code>cloudasset. assets. listCloudDocumentAIEvaluation</code></li>
<li><code>cloudasset. assets. listCloudDocumentAIHumanReviewConfig</code></li>
<li><code>cloudasset. assets. listCloudDocumentAILabelerPool</code></li>
<li><code>cloudasset. assets. listCloudDocumentAIProcessor</code></li>
<li><code>cloudasset. assets. listCloudDocumentAIProcessorVersion</code></li>
<li><code>cloudasset. assets. listCloudbillingBillingAccounts</code></li>
<li><code>cloudasset. assets. listCloudbillingProjectBillingInfos</code></li>
<li><code>cloudasset. assets. listCloudfunctionsFunctions</code></li>
<li><code>cloudasset. assets. listCloudfunctionsGen2Functions</code></li>
<li><code>cloudasset. assets. listCloudkmsCryptoKeyVersions</code></li>
<li><code>cloudasset. assets. listCloudkmsCryptoKeys</code></li>
<li><code>cloudasset. assets. listCloudkmsEkmConnections</code></li>
<li><code>cloudasset. assets. listCloudkmsImportJobs</code></li>
<li><code>cloudasset. assets. listCloudkmsKeyRings</code></li>
<li><code>cloudasset. assets. listCloudmemcacheInstances</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerFolders</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerOrganizations</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerProjects</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerTagBindings</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerTagKeys</code></li>
<li><code>cloudasset. assets. listCloudresourcemanagerTagValues</code></li>
<li><code>cloudasset. assets. listComposerEnvironments</code></li>
<li><code>cloudasset. assets. listComputeAddress</code></li>
<li><code>cloudasset. assets. listComputeAutoscalers</code></li>
<li><code>cloudasset. assets. listComputeBackendBuckets</code></li>
<li><code>cloudasset. assets. listComputeBackendServices</code></li>
<li><code>cloudasset. assets. listComputeCommitments</code></li>
<li><code>cloudasset. assets. listComputeDisks</code></li>
<li><code>cloudasset. assets. listComputeExternalVpnGateways</code></li>
<li><code>cloudasset. assets. listComputeFirewallPolicies</code></li>
<li><code>cloudasset. assets. listComputeFirewalls</code></li>
<li><code>cloudasset. assets. listComputeForwardingRules</code></li>
<li><code>cloudasset. assets. listComputeGlobalAddress</code></li>
<li><code>cloudasset. assets. listComputeGlobalForwardingRules</code></li>
<li><code>cloudasset. assets. listComputeHealthChecks</code></li>
<li><code>cloudasset. assets. listComputeHttpHealthChecks</code></li>
<li><code>cloudasset. assets. listComputeHttpsHealthChecks</code></li>
<li><code>cloudasset. assets. listComputeImages</code></li>
<li><code>cloudasset. assets. listComputeInstanceGroupManagers</code></li>
<li><code>cloudasset. assets. listComputeInstanceGroups</code></li>
<li><code>cloudasset. assets. listComputeInstanceTemplates</code></li>
<li><code>cloudasset. assets. listComputeInstances</code></li>
<li><code>cloudasset. assets. listComputeInterconnect</code></li>
<li><code>cloudasset. assets. listComputeInterconnectAttachment</code></li>
<li><code>cloudasset. assets. listComputeLicenses</code></li>
<li><code>cloudasset. assets. listComputeNetworkEndpointGroups</code></li>
<li><code>cloudasset. assets. listComputeNetworks</code></li>
<li><code>cloudasset. assets. listComputeNodeGroups</code></li>
<li><code>cloudasset. assets. listComputeNodeTemplates</code></li>
<li><code>cloudasset. assets. listComputePacketMirrorings</code></li>
<li><code>cloudasset. assets. listComputeProjects</code></li>
<li><code>cloudasset. assets. listComputeRegionAutoscaler</code></li>
<li><code>cloudasset. assets. listComputeRegionBackendServices</code></li>
<li><code>cloudasset. assets. listComputeRegionDisk</code></li>
<li><code>cloudasset. assets. listComputeRegionInstanceGroup</code></li>
<li><code>cloudasset. assets. listComputeRegionInstanceGroupManager</code></li>
<li><code>cloudasset. assets. listComputeReservations</code></li>
<li><code>cloudasset. assets. listComputeResourcePolicies</code></li>
<li><code>cloudasset. assets. listComputeRouters</code></li>
<li><code>cloudasset. assets. listComputeRoutes</code></li>
<li><code>cloudasset. assets. listComputeSecurityPolicy</code></li>
<li><code>cloudasset. assets. listComputeServiceAttachments</code></li>
<li><code>cloudasset. assets. listComputeSnapshots</code></li>
<li><code>cloudasset. assets. listComputeSslCertificates</code></li>
<li><code>cloudasset. assets. listComputeSslPolicies</code></li>
<li><code>cloudasset. assets. listComputeSubnetworks</code></li>
<li><code>cloudasset. assets. listComputeTargetHttpProxies</code></li>
<li><code>cloudasset. assets. listComputeTargetHttpsProxies</code></li>
<li><code>cloudasset. assets. listComputeTargetInstances</code></li>
<li><code>cloudasset. assets. listComputeTargetPools</code></li>
<li><code>cloudasset. assets. listComputeTargetSslProxies</code></li>
<li><code>cloudasset. assets. listComputeTargetTcpProxies</code></li>
<li><code>cloudasset. assets. listComputeTargetVpnGateways</code></li>
<li><code>cloudasset. assets. listComputeUrlMaps</code></li>
<li><code>cloudasset. assets. listComputeVpnGateways</code></li>
<li><code>cloudasset. assets. listComputeVpnTunnels</code></li>
<li><code>cloudasset. assets. listConnectorsConnections</code></li>
<li><code>cloudasset. assets. listConnectorsConnectorVersions</code></li>
<li><code>cloudasset. assets. listConnectorsConnectors</code></li>
<li><code>cloudasset. assets. listConnectorsProviders</code></li>
<li><code>cloudasset. assets. listConnectorsRuntimeConfigs</code></li>
<li><code>cloudasset. assets. listContainerAppsDeployment</code></li>
<li><code>cloudasset. assets. listContainerAppsReplicaSets</code></li>
<li><code>cloudasset. assets. listContainerBatchJobs</code></li>
<li><code>cloudasset. assets. listContainerClusterrole</code></li>
<li><code>cloudasset. assets. listContainerClusterrolebinding</code></li>
<li><code>cloudasset. assets. listContainerClusters</code></li>
<li><code>cloudasset. assets. listContainerExtensionsIngresses</code></li>
<li><code>cloudasset. assets. listContainerJobs</code></li>
<li><code>cloudasset. assets. listContainerNamespace</code></li>
<li><code>cloudasset. assets. listContainerNetworkingIngresses</code></li>
<li><code>cloudasset. assets. listContainerNetworkingNetworkPolicies</code></li>
<li><code>cloudasset. assets. listContainerNode</code></li>
<li><code>cloudasset. assets. listContainerNodepool</code></li>
<li><code>cloudasset. assets. listContainerPod</code></li>
<li><code>cloudasset. assets. listContainerReplicaSets</code></li>
<li><code>cloudasset. assets. listContainerRole</code></li>
<li><code>cloudasset. assets. listContainerRolebinding</code></li>
<li><code>cloudasset. assets. listContainerServices</code></li>
<li><code>cloudasset. assets. listContainerregistryImage</code></li>
<li><code>cloudasset. assets. listDataMigrationConnectionProfiles</code></li>
<li><code>cloudasset. assets. listDataMigrationMigrationJobs</code></li>
<li><code>cloudasset. assets. listDataflowJobs</code></li>
<li><code>cloudasset. assets. listDatafusionInstance</code></li>
<li><code>cloudasset. assets. listDataplexAssets</code></li>
<li><code>cloudasset. assets. listDataplexLakes</code></li>
<li><code>cloudasset. assets. listDataplexTasks</code></li>
<li><code>cloudasset. assets. listDataplexZones</code></li>
<li><code>cloudasset. assets. listDataprocAutoscalingPolicies</code></li>
<li><code>cloudasset. assets. listDataprocBatches</code></li>
<li><code>cloudasset. assets. listDataprocClusters</code></li>
<li><code>cloudasset. assets. listDataprocJobs</code></li>
<li><code>cloudasset. assets. listDataprocSessions</code></li>
<li><code>cloudasset. assets. listDataprocWorkflowTemplates</code></li>
<li><code>cloudasset. assets. listDatastreamConnectionProfile</code></li>
<li><code>cloudasset. assets. listDatastreamPrivateConnection</code></li>
<li><code>cloudasset. assets. listDatastreamStream</code></li>
<li><code>cloudasset. assets. listDialogflowAgents</code></li>
<li><code>cloudasset. assets. listDialogflowConversationProfiles</code></li>
<li><code>cloudasset. assets. listDialogflowKnowledgeBases</code></li>
<li><code>cloudasset. assets. listDialogflowLocationSettings</code></li>
<li><code>cloudasset. assets. listDlpDeidentifyTemplates</code></li>
<li><code>cloudasset. assets. listDlpDlpJobs</code></li>
<li><code>cloudasset. assets. listDlpInspectTemplates</code></li>
<li><code>cloudasset. assets. listDlpJobTriggers</code></li>
<li><code>cloudasset. assets. listDlpStoredInfoTypes</code></li>
<li><code>cloudasset. assets. listDnsManagedZones</code></li>
<li><code>cloudasset. assets. listDnsPolicies</code></li>
<li><code>cloudasset. assets. listDomainsRegistrations</code></li>
<li><code>cloudasset. assets. listEventarcTriggers</code></li>
<li><code>cloudasset. assets. listFileBackups</code></li>
<li><code>cloudasset. assets. listFileInstances</code></li>
<li><code>cloudasset. assets. listFirebaseAppInfos</code></li>
<li><code>cloudasset. assets. listFirebaseProjects</code></li>
<li><code>cloudasset. assets. listFirestoreDatabases</code></li>
<li><code>cloudasset. assets. listGKEHubFeatures</code></li>
<li><code>cloudasset. assets. listGKEHubMemberships</code></li>
<li><code>cloudasset. assets. listGameservicesGameServerClusters</code></li>
<li><code>cloudasset. assets. listGameservicesGameServerConfigs</code></li>
<li><code>cloudasset. assets. listGameservicesGameServerDeployments</code></li>
<li><code>cloudasset. assets. listGameservicesRealms</code></li>
<li><code>cloudasset. assets. listGkeBackupBackupPlans</code></li>
<li><code>cloudasset. assets. listGkeBackupBackups</code></li>
<li><code>cloudasset. assets. listGkeBackupRestorePlans</code></li>
<li><code>cloudasset. assets. listGkeBackupRestores</code></li>
<li><code>cloudasset. assets. listGkeBackupVolumeBackups</code></li>
<li><code>cloudasset. assets. listGkeBackupVolumeRestores</code></li>
<li><code>cloudasset. assets. listHealthcareConsentStores</code></li>
<li><code>cloudasset. assets. listHealthcareDatasets</code></li>
<li><code>cloudasset. assets. listHealthcareDicomStores</code></li>
<li><code>cloudasset. assets. listHealthcareFhirStores</code></li>
<li><code>cloudasset. assets. listHealthcareHl7V2Stores</code></li>
<li><code>cloudasset. assets. listIamPolicy</code></li>
<li><code>cloudasset.assets.listIamRoles</code></li>
<li><code>cloudasset. assets. listIamServiceAccountKeys</code></li>
<li><code>cloudasset. assets. listIamServiceAccounts</code></li>
<li><code>cloudasset. assets. listIapTunnel</code></li>
<li><code>cloudasset. assets. listIapTunnelInstances</code></li>
<li><code>cloudasset. assets. listIapTunnelZones</code></li>
<li><code>cloudasset.assets.listIapWeb</code></li>
<li><code>cloudasset. assets. listIapWebServiceVersion</code></li>
<li><code>cloudasset. assets. listIapWebServices</code></li>
<li><code>cloudasset. assets. listIapWebType</code></li>
<li><code>cloudasset. assets. listIdsEndpoints</code></li>
<li><code>cloudasset. assets. listIntegrationsAuthConfigs</code></li>
<li><code>cloudasset. assets. listIntegrationsCertificates</code></li>
<li><code>cloudasset. assets. listIntegrationsExecutions</code></li>
<li><code>cloudasset. assets. listIntegrationsIntegrationVersions</code></li>
<li><code>cloudasset. assets. listIntegrationsIntegrations</code></li>
<li><code>cloudasset. assets. listIntegrationsSfdcChannels</code></li>
<li><code>cloudasset. assets. listIntegrationsSfdcInstances</code></li>
<li><code>cloudasset. assets. listIntegrationsSuspensions</code></li>
<li><code>cloudasset. assets. listLoggingLogMetrics</code></li>
<li><code>cloudasset. assets. listLoggingLogSinks</code></li>
<li><code>cloudasset. assets. listManagedidentitiesDomain</code></li>
<li><code>cloudasset. assets. listMetastoreBackups</code></li>
<li><code>cloudasset. assets. listMetastoreMetadataImports</code></li>
<li><code>cloudasset. assets. listMetastoreServices</code></li>
<li><code>cloudasset. assets. listMonitoringAlertPolicies</code></li>
<li><code>cloudasset. assets. listNetworkConnectivityHubs</code></li>
<li><code>cloudasset. assets. listNetworkConnectivitySpokes</code></li>
<li><code>cloudasset. assets. listNetworkManagementConnectivityTests</code></li>
<li><code>cloudasset. assets. listNetworkServicesEndpointPolicies</code></li>
<li><code>cloudasset. assets. listNetworkServicesGateways</code></li>
<li><code>cloudasset. assets. listNetworkServicesGrpcRoutes</code></li>
<li><code>cloudasset. assets. listNetworkServicesHttpRoutes</code></li>
<li><code>cloudasset. assets. listNetworkServicesMeshes</code></li>
<li><code>cloudasset. assets. listNetworkServicesServiceBindings</code></li>
<li><code>cloudasset. assets. listNetworkServicesTcpRoutes</code></li>
<li><code>cloudasset. assets. listNetworkServicesTlsRoutes</code></li>
<li><code>cloudasset. assets. listOSConfigOSPolicyAssignmentReports</code></li>
<li><code>cloudasset. assets. listOSConfigOSPolicyAssignments</code></li>
<li><code>cloudasset. assets. listOSConfigVulnerabilityReports</code></li>
<li><code>cloudasset. assets. listOSInventories</code></li>
<li><code>cloudasset. assets. listOrgPolicy</code></li>
<li><code>cloudasset. assets. listPatchDeployments</code></li>
<li><code>cloudasset. assets. listPubsubSnapshots</code></li>
<li><code>cloudasset. assets. listPubsubSubscriptions</code></li>
<li><code>cloudasset. assets. listPubsubTopics</code></li>
<li><code>cloudasset. assets. listRedisInstances</code></li>
<li><code>cloudasset.assets.listResource</code></li>
<li><code>cloudasset. assets. listRunDomainMapping</code></li>
<li><code>cloudasset. assets. listRunRevision</code></li>
<li><code>cloudasset. assets. listRunService</code></li>
<li><code>cloudasset. assets. listSecretManagerSecretVersions</code></li>
<li><code>cloudasset. assets. listSecretManagerSecrets</code></li>
<li><code>cloudasset. assets. listServiceDirectoryNamespaces</code></li>
<li><code>cloudasset. assets. listServicePerimeter</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementConsumerProperty</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementConsumerQuotaLimits</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementConsumers</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementProducerOverrides</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementTenancyUnits</code></li>
<li><code>cloudasset. assets. listServiceconsumermanagementVisibility</code></li>
<li><code>cloudasset. assets. listServicemanagementServices</code></li>
<li><code>cloudasset. assets. listServiceusageAdminOverrides</code></li>
<li><code>cloudasset. assets. listServiceusageConsumerOverrides</code></li>
<li><code>cloudasset. assets. listServiceusageServices</code></li>
<li><code>cloudasset. assets. listSpannerBackups</code></li>
<li><code>cloudasset. assets. listSpannerDatabases</code></li>
<li><code>cloudasset. assets. listSpannerInstances</code></li>
<li><code>cloudasset. assets. listSpeakerIdPhrases</code></li>
<li><code>cloudasset. assets. listSpeakerIdSettings</code></li>
<li><code>cloudasset. assets. listSpeakerIdSpeakers</code></li>
<li><code>cloudasset. assets. listSpeechCustomClasses</code></li>
<li><code>cloudasset. assets. listSpeechPhraseSets</code></li>
<li><code>cloudasset. assets. listSqladminBackupRuns</code></li>
<li><code>cloudasset. assets. listSqladminInstances</code></li>
<li><code>cloudasset. assets. listStorageBuckets</code></li>
<li><code>cloudasset.assets.listTpuNodes</code></li>
<li><code>cloudasset. assets. listVpcaccessConnector</code></li>
<li><code>cloudasset. assets. queryAccessPolicy</code></li>
<li><code>cloudasset. assets. queryIamPolicy</code></li>
<li><code>cloudasset. assets. queryOSInventories</code></li>
<li><code>cloudasset. assets. queryResource</code></li>
<li><code>cloudasset. assets. searchAllIamPolicies</code></li>
<li><code>cloudasset. assets. searchAllResources</code></li>
<li><code>cloudasset. assets. searchEnrichmentResourceOwners</code></li>
</ul>
<p><code>cloudasset. othercloudconnections. get</code></p>
<p><code>cloudasset. othercloudconnections. list</code></p>
<p><code>cloudasset. othercloudconnections. verify</code></p>
<p><code>cloudasset.savedqueries.get</code></p>
<p><code>cloudasset.savedqueries.list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter.assets.group</code></p>
<p><code>securitycenter.assets.list</code></p>
<p><code>securitycenter. assets. listAssetPropertyNames</code></p>
<p><code>securitycenter. bigQueryExports. get</code></p>
<p><code>securitycenter. bigQueryExports. list</code></p>
<p><code>securitycenter. complianceReports. aggregate</code></p>
<p><code>securitycenter. compliancesnapshots. list</code></p>
<p><code>securitycenter. containerthreatdetectionsettings. calculate</code></p>
<p><code>securitycenter. containerthreatdetectionsettings. get</code></p>
<p><code>securitycenter. effectivesecurityhealthanalyticscustommodules.*</code></p>
<ul>
<li><code>securitycenter. effectivesecurityhealthanalyticscustommodules. get</code></li>
<li><code>securitycenter. effectivesecurityhealthanalyticscustommodules. list</code></li>
</ul>
<p><code>securitycenter. eventthreatdetectionsettings. calculate</code></p>
<p><code>securitycenter. eventthreatdetectionsettings. get</code></p>
<p><code>securitycenter. findingexplanations. get</code></p>
<p><code>securitycenter.findings.group</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>securitycenter. findings. listFindingPropertyNames</code></p>
<p><code>securitycenter.graphs.*</code></p>
<ul>
<li><code>securitycenter.graphs.get</code></li>
<li><code>securitycenter.graphs.query</code></li>
</ul>
<p><code>securitycenter. integratedvulnerabilityscannersettings. calculate</code></p>
<p><code>securitycenter. integratedvulnerabilityscannersettings. get</code></p>
<p><code>securitycenter.issues.get</code></p>
<p><code>securitycenter.issues.group</code></p>
<p><code>securitycenter.issues.list</code></p>
<p><code>securitycenter. issues. listFilterValues</code></p>
<p><code>securitycenter.issues.retrieve</code></p>
<p><code>securitycenter.issues.search</code></p>
<p><code>securitycenter. issues. searchImpactedResources</code></p>
<p><code>securitycenter.muteconfigs.get</code></p>
<p><code>securitycenter. muteconfigs. list</code></p>
<p><code>securitycenter. notificationconfig. get</code></p>
<p><code>securitycenter. notificationconfig. list</code></p>
<p><code>securitycenter. organizationsettings. get</code></p>
<p><code>securitycenter. rapidvulnerabilitydetectionsettings. calculate</code></p>
<p><code>securitycenter. rapidvulnerabilitydetectionsettings. get</code></p>
<p><code>securitycenter. securitycentersettings. get</code></p>
<p><code>securitycenter. securityhealthanalyticscustommodules. get</code></p>
<p><code>securitycenter. securityhealthanalyticscustommodules. list</code></p>
<p><code>securitycenter. securityhealthanalyticssettings. calculate</code></p>
<p><code>securitycenter. securityhealthanalyticssettings. get</code></p>
<p><code>securitycenter.sources.get</code></p>
<p><code>securitycenter.sources.list</code></p>
<p><code>securitycenter. subscription. get</code></p>
<p><code>securitycenter. userinterfacemetadata. get</code></p>
<p><code>securitycenter. virtualmachinethreatdetectionsettings. calculate</code></p>
<p><code>securitycenter. virtualmachinethreatdetectionsettings. get</code></p>
<p><code>securitycenter. vulnerabilitysnapshots. list</code></p>
<p><code>securitycenter. websecurityscannersettings. calculate</code></p>
<p><code>securitycenter. websecurityscannersettings. get</code></p>
<p><code>securitycentermanagement. billingMetadata. get</code></p>
<p><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveEventThreatDetectionCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></li>
<li><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. list</code></li>
</ul>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. get</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. list</code></p>
<p><code>securitycentermanagement. eventThreatDetectionCustomModules. validate</code></p>
<p><code>securitycentermanagement. locations.*</code></p>
<ul>
<li><code>securitycentermanagement. locations. get</code></li>
<li><code>securitycentermanagement. locations. list</code></li>
</ul>
<p><code>securitycentermanagement. operations. get</code></p>
<p><code>securitycentermanagement. operations. list</code></p>
<p><code>securitycentermanagement. securityCenter. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. list</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkActivationOperation</code></p>
<p><code>securitycentermanagement. securityCommandCenter. checkOnboardingStatus</code></p>
<p><code>securitycentermanagement. securityCommandCenter. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. list</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. simulate</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. test</code></p></td>
</tr>
</tbody>
</table>

## Cyber Insurance Hub permissions

| Permission                                  | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|---------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `riskmanager. controlScoreBreakdowns. get`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `riskmanager. controlScoreBreakdowns. list` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` ) |
| `riskmanager.operations.delete`             | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `riskmanager.operations.get`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `riskmanager.operations.list`               | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` ) |
| `riskmanager.policies.get`                  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `riskmanager.policies.list`                 | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                             |
| `riskmanager.reports.create`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `riskmanager.reports.delete`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `riskmanager.reports.get`                   | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `riskmanager.reports.list`                  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` ) |
| `riskmanager.reports.review`                | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Report Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.reviewer) ( `roles/ riskmanager.reviewer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `riskmanager.reports.share`                 | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| `riskmanager. serviceAccount. create`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| `riskmanager.settings.get`                  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` ) [Risk Manager Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.viewer) ( `roles/ riskmanager.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `riskmanager.settings.update`               | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Risk Manager Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.admin) ( `roles/ riskmanager.admin` ) [Risk Manager Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.editor) ( `roles/ riskmanager.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
