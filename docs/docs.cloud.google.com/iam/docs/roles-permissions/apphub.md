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
<td>App Hub Admin
<p>( <code>roles/ apphub.admin</code> )</p>
<p>Full access to App Hub resources.</p></td>
<td><p><code>apphub.*</code></p>
<ul>
<li><code>apphub.applications.create</code></li>
<li><code>apphub.applications.delete</code></li>
<li><code>apphub.applications.get</code></li>
<li><code>apphub. applications. getIamPolicy</code></li>
<li><code>apphub.applications.list</code></li>
<li><code>apphub. applications. setIamPolicy</code></li>
<li><code>apphub.applications.update</code></li>
<li><code>apphub.boundaries.attach</code></li>
<li><code>apphub.boundaries.get</code></li>
<li><code>apphub.boundaries.update</code></li>
<li><code>apphub.discoveredServices.get</code></li>
<li><code>apphub.discoveredServices.list</code></li>
<li><code>apphub. discoveredServices. register</code></li>
<li><code>apphub.discoveredWorkloads.get</code></li>
<li><code>apphub. discoveredWorkloads. list</code></li>
<li><code>apphub. discoveredWorkloads. register</code></li>
<li><code>apphub. extendedMetadataSchemas. get</code></li>
<li><code>apphub. extendedMetadataSchemas. list</code></li>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
<li><code>apphub.operations.cancel</code></li>
<li><code>apphub.operations.delete</code></li>
<li><code>apphub.operations.get</code></li>
<li><code>apphub.operations.list</code></li>
<li><code>apphub. serviceProjectAttachments. attach</code></li>
<li><code>apphub. serviceProjectAttachments. create</code></li>
<li><code>apphub. serviceProjectAttachments. delete</code></li>
<li><code>apphub. serviceProjectAttachments. detach</code></li>
<li><code>apphub. serviceProjectAttachments. get</code></li>
<li><code>apphub. serviceProjectAttachments. list</code></li>
<li><code>apphub. serviceProjectAttachments. lookup</code></li>
<li><code>apphub.services.create</code></li>
<li><code>apphub.services.delete</code></li>
<li><code>apphub.services.get</code></li>
<li><code>apphub.services.list</code></li>
<li><code>apphub.services.update</code></li>
<li><code>apphub.workloads.create</code></li>
<li><code>apphub.workloads.delete</code></li>
<li><code>apphub.workloads.get</code></li>
<li><code>apphub.workloads.list</code></li>
<li><code>apphub.workloads.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Hub Editor
<p>( <code>roles/ apphub.editor</code> )</p>
<p>Edit access to App Hub resources.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.boundaries.get</code></p>
<p><code>apphub.discoveredServices.*</code></p>
<ul>
<li><code>apphub.discoveredServices.get</code></li>
<li><code>apphub.discoveredServices.list</code></li>
<li><code>apphub. discoveredServices. register</code></li>
</ul>
<p><code>apphub.discoveredWorkloads.*</code></p>
<ul>
<li><code>apphub.discoveredWorkloads.get</code></li>
<li><code>apphub. discoveredWorkloads. list</code></li>
<li><code>apphub. discoveredWorkloads. register</code></li>
</ul>
<p><code>apphub. extendedMetadataSchemas.*</code></p>
<ul>
<li><code>apphub. extendedMetadataSchemas. get</code></li>
<li><code>apphub. extendedMetadataSchemas. list</code></li>
</ul>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub.operations.*</code></p>
<ul>
<li><code>apphub.operations.cancel</code></li>
<li><code>apphub.operations.delete</code></li>
<li><code>apphub.operations.get</code></li>
<li><code>apphub.operations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. lookup</code></p>
<p><code>apphub.services.*</code></p>
<ul>
<li><code>apphub.services.create</code></li>
<li><code>apphub.services.delete</code></li>
<li><code>apphub.services.get</code></li>
<li><code>apphub.services.list</code></li>
<li><code>apphub.services.update</code></li>
</ul>
<p><code>apphub.workloads.*</code></p>
<ul>
<li><code>apphub.workloads.create</code></li>
<li><code>apphub.workloads.delete</code></li>
<li><code>apphub.workloads.get</code></li>
<li><code>apphub.workloads.list</code></li>
<li><code>apphub.workloads.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>App Hub Viewer
<p>( <code>roles/ apphub.viewer</code> )</p>
<p>View access to App Hub resources.</p></td>
<td><p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.boundaries.get</code></p>
<p><code>apphub.discoveredServices.get</code></p>
<p><code>apphub.discoveredServices.list</code></p>
<p><code>apphub.discoveredWorkloads.get</code></p>
<p><code>apphub. discoveredWorkloads. list</code></p>
<p><code>apphub. extendedMetadataSchemas.*</code></p>
<ul>
<li><code>apphub. extendedMetadataSchemas. get</code></li>
<li><code>apphub. extendedMetadataSchemas. list</code></li>
</ul>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub.operations.get</code></p>
<p><code>apphub.operations.list</code></p>
<p><code>apphub. serviceProjectAttachments. lookup</code></p>
<p><code>apphub.services.get</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.get</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>App Management Viewer <sup>Beta</sup>
<p>( <code>roles/ apphub.appManagementViewer</code> )</p>
<p>This role, an aggregation of read permissions across multiple app centric products.</p></td>
<td><p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.boundaries.get</code></p>
<p><code>apphub.discoveredServices.get</code></p>
<p><code>apphub.discoveredServices.list</code></p>
<p><code>apphub.discoveredWorkloads.get</code></p>
<p><code>apphub. discoveredWorkloads. list</code></p>
<p><code>apphub. extendedMetadataSchemas.*</code></p>
<ul>
<li><code>apphub. extendedMetadataSchemas. get</code></li>
<li><code>apphub. extendedMetadataSchemas. list</code></li>
</ul>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub.operations.get</code></p>
<p><code>apphub.operations.list</code></p>
<p><code>apphub. serviceProjectAttachments. lookup</code></p>
<p><code>apphub.services.get</code></p>
<p><code>apphub.services.list</code></p>
<p><code>apphub.workloads.get</code></p>
<p><code>apphub.workloads.list</code></p>
<p><code>auditmanager.auditReports.get</code></p>
<p><code>auditmanager.auditReports.list</code></p>
<p><code>auditmanager. auditSchedules. get</code></p>
<p><code>auditmanager. auditSchedules. list</code></p>
<p><code>auditmanager. billingSettings. get</code></p>
<p><code>auditmanager.controlReports.*</code></p>
<ul>
<li><code>auditmanager. controlReports. get</code></li>
<li><code>auditmanager. controlReports. list</code></li>
</ul>
<p><code>auditmanager.controls.list</code></p>
<p><code>auditmanager.findings.list</code></p>
<p><code>auditmanager.locations.get</code></p>
<p><code>auditmanager.locations.list</code></p>
<p><code>auditmanager.operations.*</code></p>
<ul>
<li><code>auditmanager.operations.get</code></li>
<li><code>auditmanager.operations.list</code></li>
</ul>
<p><code>auditmanager. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>auditmanager. resourceEnrollmentStatuses. get</code></li>
<li><code>auditmanager. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>cloudasset.assets.analyzeMove</code></p>
<p><code>cloudasset. assets. analyzeOrgPolicy</code></p>
<p><code>cloudasset. assets. exportAccessLevel</code></p>
<p><code>cloudasset. assets. exportAccessPolicy</code></p>
<p><code>cloudasset. assets. exportAiplatformBatchPredictionJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformCustomJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformDataLabelingJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformDatasets</code></p>
<p><code>cloudasset. assets. exportAiplatformEndpoints</code></p>
<p><code>cloudasset. assets. exportAiplatformHyperparameterTuningJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformMetadataStores</code></p>
<p><code>cloudasset. assets. exportAiplatformModelDeploymentMonitoringJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformModels</code></p>
<p><code>cloudasset. assets. exportAiplatformPipelineJobs</code></p>
<p><code>cloudasset. assets. exportAiplatformSpecialistPools</code></p>
<p><code>cloudasset. assets. exportAiplatformTrainingPipelines</code></p>
<p><code>cloudasset. assets. exportAllAccessPolicy</code></p>
<p><code>cloudasset. assets. exportAnthosConnectedCluster</code></p>
<p><code>cloudasset. assets. exportAnthosedgeCluster</code></p>
<p><code>cloudasset. assets. exportApigatewayApi</code></p>
<p><code>cloudasset. assets. exportApigatewayApiConfig</code></p>
<p><code>cloudasset. assets. exportApigatewayGateway</code></p>
<p><code>cloudasset. assets. exportApikeysKeys</code></p>
<p><code>cloudasset. assets. exportAppengineApplications</code></p>
<p><code>cloudasset. assets. exportAppengineServices</code></p>
<p><code>cloudasset. assets. exportAppengineVersions</code></p>
<p><code>cloudasset. assets. exportArtifactregistryDockerImages</code></p>
<p><code>cloudasset. assets. exportArtifactregistryRepositories</code></p>
<p><code>cloudasset. assets. exportAssuredWorkloadsWorkloads</code></p>
<p><code>cloudasset. assets. exportBeyondCorpApiGateways</code></p>
<p><code>cloudasset. assets. exportBeyondCorpAppConnections</code></p>
<p><code>cloudasset. assets. exportBeyondCorpAppConnectors</code></p>
<p><code>cloudasset. assets. exportBeyondCorpAppGateways</code></p>
<p><code>cloudasset. assets. exportBeyondCorpClientConnectorServices</code></p>
<p><code>cloudasset. assets. exportBeyondCorpClientGateways</code></p>
<p><code>cloudasset. assets. exportBigqueryDatasets</code></p>
<p><code>cloudasset. assets. exportBigqueryModels</code></p>
<p><code>cloudasset. assets. exportBigqueryTables</code></p>
<p><code>cloudasset. assets. exportBigtableAppProfile</code></p>
<p><code>cloudasset. assets. exportBigtableBackup</code></p>
<p><code>cloudasset. assets. exportBigtableCluster</code></p>
<p><code>cloudasset. assets. exportBigtableInstance</code></p>
<p><code>cloudasset. assets. exportBigtableTable</code></p>
<p><code>cloudasset. assets. exportCloudAssetFeeds</code></p>
<p><code>cloudasset. assets. exportCloudDeployDeliveryPipelines</code></p>
<p><code>cloudasset. assets. exportCloudDeployReleases</code></p>
<p><code>cloudasset. assets. exportCloudDeployRollouts</code></p>
<p><code>cloudasset. assets. exportCloudDeployTargets</code></p>
<p><code>cloudasset. assets. exportCloudDocumentAIEvaluation</code></p>
<p><code>cloudasset. assets. exportCloudDocumentAIHumanReviewConfig</code></p>
<p><code>cloudasset. assets. exportCloudDocumentAILabelerPool</code></p>
<p><code>cloudasset. assets. exportCloudDocumentAIProcessor</code></p>
<p><code>cloudasset. assets. exportCloudDocumentAIProcessorVersion</code></p>
<p><code>cloudasset. assets. exportCloudbillingBillingAccounts</code></p>
<p><code>cloudasset. assets. exportCloudbillingProjectBillingInfos</code></p>
<p><code>cloudasset. assets. exportCloudfunctionsFunctions</code></p>
<p><code>cloudasset. assets. exportCloudfunctionsGen2Functions</code></p>
<p><code>cloudasset. assets. exportCloudkmsCryptoKeyVersions</code></p>
<p><code>cloudasset. assets. exportCloudkmsCryptoKeys</code></p>
<p><code>cloudasset. assets. exportCloudkmsEkmConnections</code></p>
<p><code>cloudasset. assets. exportCloudkmsImportJobs</code></p>
<p><code>cloudasset. assets. exportCloudkmsKeyRings</code></p>
<p><code>cloudasset. assets. exportCloudmemcacheInstances</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerFolders</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerOrganizations</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerProjects</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerTagBindings</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerTagKeys</code></p>
<p><code>cloudasset. assets. exportCloudresourcemanagerTagValues</code></p>
<p><code>cloudasset. assets. exportComposerEnvironments</code></p>
<p><code>cloudasset. assets. exportComputeAddress</code></p>
<p><code>cloudasset. assets. exportComputeAutoscalers</code></p>
<p><code>cloudasset. assets. exportComputeBackendBuckets</code></p>
<p><code>cloudasset. assets. exportComputeBackendServices</code></p>
<p><code>cloudasset. assets. exportComputeCommitments</code></p>
<p><code>cloudasset. assets. exportComputeDisks</code></p>
<p><code>cloudasset. assets. exportComputeExternalVpnGateways</code></p>
<p><code>cloudasset. assets. exportComputeFirewallPolicies</code></p>
<p><code>cloudasset. assets. exportComputeFirewalls</code></p>
<p><code>cloudasset. assets. exportComputeForwardingRules</code></p>
<p><code>cloudasset. assets. exportComputeGlobalAddress</code></p>
<p><code>cloudasset. assets. exportComputeGlobalForwardingRules</code></p>
<p><code>cloudasset. assets. exportComputeHealthChecks</code></p>
<p><code>cloudasset. assets. exportComputeHttpHealthChecks</code></p>
<p><code>cloudasset. assets. exportComputeHttpsHealthChecks</code></p>
<p><code>cloudasset. assets. exportComputeImages</code></p>
<p><code>cloudasset. assets. exportComputeInstanceGroupManagers</code></p>
<p><code>cloudasset. assets. exportComputeInstanceGroups</code></p>
<p><code>cloudasset. assets. exportComputeInstanceTemplates</code></p>
<p><code>cloudasset. assets. exportComputeInstances</code></p>
<p><code>cloudasset. assets. exportComputeInterconnect</code></p>
<p><code>cloudasset. assets. exportComputeInterconnectAttachment</code></p>
<p><code>cloudasset. assets. exportComputeLicenses</code></p>
<p><code>cloudasset. assets. exportComputeNetworkEndpointGroups</code></p>
<p><code>cloudasset. assets. exportComputeNetworks</code></p>
<p><code>cloudasset. assets. exportComputeNodeGroups</code></p>
<p><code>cloudasset. assets. exportComputeNodeTemplates</code></p>
<p><code>cloudasset. assets. exportComputePacketMirrorings</code></p>
<p><code>cloudasset. assets. exportComputeProjects</code></p>
<p><code>cloudasset. assets. exportComputeRegionAutoscaler</code></p>
<p><code>cloudasset. assets. exportComputeRegionBackendServices</code></p>
<p><code>cloudasset. assets. exportComputeRegionDisk</code></p>
<p><code>cloudasset. assets. exportComputeRegionInstanceGroup</code></p>
<p><code>cloudasset. assets. exportComputeRegionInstanceGroupManager</code></p>
<p><code>cloudasset. assets. exportComputeReservations</code></p>
<p><code>cloudasset. assets. exportComputeResourcePolicies</code></p>
<p><code>cloudasset. assets. exportComputeRouters</code></p>
<p><code>cloudasset. assets. exportComputeRoutes</code></p>
<p><code>cloudasset. assets. exportComputeSecurityPolicy</code></p>
<p><code>cloudasset. assets. exportComputeServiceAttachments</code></p>
<p><code>cloudasset. assets. exportComputeSnapshots</code></p>
<p><code>cloudasset. assets. exportComputeSslCertificates</code></p>
<p><code>cloudasset. assets. exportComputeSslPolicies</code></p>
<p><code>cloudasset. assets. exportComputeSubnetworks</code></p>
<p><code>cloudasset. assets. exportComputeTargetHttpProxies</code></p>
<p><code>cloudasset. assets. exportComputeTargetHttpsProxies</code></p>
<p><code>cloudasset. assets. exportComputeTargetInstances</code></p>
<p><code>cloudasset. assets. exportComputeTargetPools</code></p>
<p><code>cloudasset. assets. exportComputeTargetSslProxies</code></p>
<p><code>cloudasset. assets. exportComputeTargetTcpProxies</code></p>
<p><code>cloudasset. assets. exportComputeTargetVpnGateways</code></p>
<p><code>cloudasset. assets. exportComputeUrlMaps</code></p>
<p><code>cloudasset. assets. exportComputeVpnGateways</code></p>
<p><code>cloudasset. assets. exportComputeVpnTunnels</code></p>
<p><code>cloudasset. assets. exportConnectorsConnections</code></p>
<p><code>cloudasset. assets. exportConnectorsConnectorVersions</code></p>
<p><code>cloudasset. assets. exportConnectorsConnectors</code></p>
<p><code>cloudasset. assets. exportConnectorsProviders</code></p>
<p><code>cloudasset. assets. exportConnectorsRuntimeConfigs</code></p>
<p><code>cloudasset. assets. exportContainerAppsDeployment</code></p>
<p><code>cloudasset. assets. exportContainerAppsReplicaSets</code></p>
<p><code>cloudasset. assets. exportContainerBatchJobs</code></p>
<p><code>cloudasset. assets. exportContainerClusterrole</code></p>
<p><code>cloudasset. assets. exportContainerClusterrolebinding</code></p>
<p><code>cloudasset. assets. exportContainerClusters</code></p>
<p><code>cloudasset. assets. exportContainerExtensionsIngresses</code></p>
<p><code>cloudasset. assets. exportContainerJobs</code></p>
<p><code>cloudasset. assets. exportContainerNamespace</code></p>
<p><code>cloudasset. assets. exportContainerNetworkingIngresses</code></p>
<p><code>cloudasset. assets. exportContainerNetworkingNetworkPolicies</code></p>
<p><code>cloudasset. assets. exportContainerNode</code></p>
<p><code>cloudasset. assets. exportContainerNodepool</code></p>
<p><code>cloudasset. assets. exportContainerPod</code></p>
<p><code>cloudasset. assets. exportContainerReplicaSets</code></p>
<p><code>cloudasset. assets. exportContainerRole</code></p>
<p><code>cloudasset. assets. exportContainerRolebinding</code></p>
<p><code>cloudasset. assets. exportContainerServices</code></p>
<p><code>cloudasset. assets. exportContainerregistryImage</code></p>
<p><code>cloudasset. assets. exportDataMigrationConnectionProfiles</code></p>
<p><code>cloudasset. assets. exportDataMigrationMigrationJobs</code></p>
<p><code>cloudasset. assets. exportDataflowJobs</code></p>
<p><code>cloudasset. assets. exportDatafusionInstance</code></p>
<p><code>cloudasset. assets. exportDataplexAssets</code></p>
<p><code>cloudasset. assets. exportDataplexLakes</code></p>
<p><code>cloudasset. assets. exportDataplexTasks</code></p>
<p><code>cloudasset. assets. exportDataplexZones</code></p>
<p><code>cloudasset. assets. exportDataprocAutoscalingPolicies</code></p>
<p><code>cloudasset. assets. exportDataprocBatches</code></p>
<p><code>cloudasset. assets. exportDataprocClusters</code></p>
<p><code>cloudasset. assets. exportDataprocJobs</code></p>
<p><code>cloudasset. assets. exportDataprocSessions</code></p>
<p><code>cloudasset. assets. exportDataprocWorkflowTemplates</code></p>
<p><code>cloudasset. assets. exportDatastreamConnectionProfile</code></p>
<p><code>cloudasset. assets. exportDatastreamPrivateConnection</code></p>
<p><code>cloudasset. assets. exportDatastreamStream</code></p>
<p><code>cloudasset. assets. exportDialogflowAgents</code></p>
<p><code>cloudasset. assets. exportDialogflowConversationProfiles</code></p>
<p><code>cloudasset. assets. exportDialogflowKnowledgeBases</code></p>
<p><code>cloudasset. assets. exportDialogflowLocationSettings</code></p>
<p><code>cloudasset. assets. exportDlpDeidentifyTemplates</code></p>
<p><code>cloudasset. assets. exportDlpDlpJobs</code></p>
<p><code>cloudasset. assets. exportDlpInspectTemplates</code></p>
<p><code>cloudasset. assets. exportDlpJobTriggers</code></p>
<p><code>cloudasset. assets. exportDlpStoredInfoTypes</code></p>
<p><code>cloudasset. assets. exportDnsManagedZones</code></p>
<p><code>cloudasset. assets. exportDnsPolicies</code></p>
<p><code>cloudasset. assets. exportDomainsRegistrations</code></p>
<p><code>cloudasset. assets. exportEventarcTriggers</code></p>
<p><code>cloudasset. assets. exportFileBackups</code></p>
<p><code>cloudasset. assets. exportFileInstances</code></p>
<p><code>cloudasset. assets. exportFirebaseAppInfos</code></p>
<p><code>cloudasset. assets. exportFirebaseProjects</code></p>
<p><code>cloudasset. assets. exportFirestoreDatabases</code></p>
<p><code>cloudasset. assets. exportGKEHubFeatures</code></p>
<p><code>cloudasset. assets. exportGKEHubMemberships</code></p>
<p><code>cloudasset. assets. exportGameservicesGameServerClusters</code></p>
<p><code>cloudasset. assets. exportGameservicesGameServerConfigs</code></p>
<p><code>cloudasset. assets. exportGameservicesGameServerDeployments</code></p>
<p><code>cloudasset. assets. exportGameservicesRealms</code></p>
<p><code>cloudasset. assets. exportGkeBackupBackupPlans</code></p>
<p><code>cloudasset. assets. exportGkeBackupBackups</code></p>
<p><code>cloudasset. assets. exportGkeBackupRestorePlans</code></p>
<p><code>cloudasset. assets. exportGkeBackupRestores</code></p>
<p><code>cloudasset. assets. exportGkeBackupVolumeBackups</code></p>
<p><code>cloudasset. assets. exportGkeBackupVolumeRestores</code></p>
<p><code>cloudasset. assets. exportHealthcareConsentStores</code></p>
<p><code>cloudasset. assets. exportHealthcareDatasets</code></p>
<p><code>cloudasset. assets. exportHealthcareDicomStores</code></p>
<p><code>cloudasset. assets. exportHealthcareFhirStores</code></p>
<p><code>cloudasset. assets. exportHealthcareHl7V2Stores</code></p>
<p><code>cloudasset. assets. exportIamPolicy</code></p>
<p><code>cloudasset. assets. exportIamRoles</code></p>
<p><code>cloudasset. assets. exportIamServiceAccountKeys</code></p>
<p><code>cloudasset. assets. exportIamServiceAccounts</code></p>
<p><code>cloudasset. assets. exportIapTunnel</code></p>
<p><code>cloudasset. assets. exportIapTunnelInstances</code></p>
<p><code>cloudasset. assets. exportIapTunnelZones</code></p>
<p><code>cloudasset.assets.exportIapWeb</code></p>
<p><code>cloudasset. assets. exportIapWebServiceVersion</code></p>
<p><code>cloudasset. assets. exportIapWebServices</code></p>
<p><code>cloudasset. assets. exportIapWebType</code></p>
<p><code>cloudasset. assets. exportIdsEndpoints</code></p>
<p><code>cloudasset. assets. exportIntegrationsAuthConfigs</code></p>
<p><code>cloudasset. assets. exportIntegrationsCertificates</code></p>
<p><code>cloudasset. assets. exportIntegrationsExecutions</code></p>
<p><code>cloudasset. assets. exportIntegrationsIntegrationVersions</code></p>
<p><code>cloudasset. assets. exportIntegrationsIntegrations</code></p>
<p><code>cloudasset. assets. exportIntegrationsSfdcChannels</code></p>
<p><code>cloudasset. assets. exportIntegrationsSfdcInstances</code></p>
<p><code>cloudasset. assets. exportIntegrationsSuspensions</code></p>
<p><code>cloudasset. assets. exportLoggingLogMetrics</code></p>
<p><code>cloudasset. assets. exportLoggingLogSinks</code></p>
<p><code>cloudasset. assets. exportManagedidentitiesDomain</code></p>
<p><code>cloudasset. assets. exportMetastoreBackups</code></p>
<p><code>cloudasset. assets. exportMetastoreMetadataImports</code></p>
<p><code>cloudasset. assets. exportMetastoreServices</code></p>
<p><code>cloudasset. assets. exportMonitoringAlertPolicies</code></p>
<p><code>cloudasset. assets. exportNetworkConnectivityHubs</code></p>
<p><code>cloudasset. assets. exportNetworkConnectivitySpokes</code></p>
<p><code>cloudasset. assets. exportNetworkManagementConnectivityTests</code></p>
<p><code>cloudasset. assets. exportNetworkServicesEndpointPolicies</code></p>
<p><code>cloudasset. assets. exportNetworkServicesGateways</code></p>
<p><code>cloudasset. assets. exportNetworkServicesGrpcRoutes</code></p>
<p><code>cloudasset. assets. exportNetworkServicesHttpRoutes</code></p>
<p><code>cloudasset. assets. exportNetworkServicesMeshes</code></p>
<p><code>cloudasset. assets. exportNetworkServicesServiceBindings</code></p>
<p><code>cloudasset. assets. exportNetworkServicesTcpRoutes</code></p>
<p><code>cloudasset. assets. exportNetworkServicesTlsRoutes</code></p>
<p><code>cloudasset. assets. exportOSConfigOSPolicyAssignmentReports</code></p>
<p><code>cloudasset. assets. exportOSConfigOSPolicyAssignments</code></p>
<p><code>cloudasset. assets. exportOSConfigVulnerabilityReports</code></p>
<p><code>cloudasset. assets. exportOSInventories</code></p>
<p><code>cloudasset. assets. exportOrgPolicy</code></p>
<p><code>cloudasset. assets. exportPatchDeployments</code></p>
<p><code>cloudasset. assets. exportPubsubSnapshots</code></p>
<p><code>cloudasset. assets. exportPubsubSubscriptions</code></p>
<p><code>cloudasset. assets. exportPubsubTopics</code></p>
<p><code>cloudasset. assets. exportRedisInstances</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset. assets. exportSecretManagerSecretVersions</code></p>
<p><code>cloudasset. assets. exportSecretManagerSecrets</code></p>
<p><code>cloudasset. assets. exportServiceDirectoryNamespaces</code></p>
<p><code>cloudasset. assets. exportServicePerimeter</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementConsumerProperty</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementConsumerQuotaLimits</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementConsumers</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementProducerOverrides</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementTenancyUnits</code></p>
<p><code>cloudasset. assets. exportServiceconsumermanagementVisibility</code></p>
<p><code>cloudasset. assets. exportServicemanagementServices</code></p>
<p><code>cloudasset. assets. exportServiceusageAdminOverrides</code></p>
<p><code>cloudasset. assets. exportServiceusageConsumerOverrides</code></p>
<p><code>cloudasset. assets. exportServiceusageServices</code></p>
<p><code>cloudasset. assets. exportSpannerBackups</code></p>
<p><code>cloudasset. assets. exportSpannerDatabases</code></p>
<p><code>cloudasset. assets. exportSpannerInstances</code></p>
<p><code>cloudasset. assets. exportSpeakerIdPhrases</code></p>
<p><code>cloudasset. assets. exportSpeakerIdSettings</code></p>
<p><code>cloudasset. assets. exportSpeakerIdSpeakers</code></p>
<p><code>cloudasset. assets. exportSpeechCustomClasses</code></p>
<p><code>cloudasset. assets. exportSpeechPhraseSets</code></p>
<p><code>cloudasset. assets. exportSqladminBackupRuns</code></p>
<p><code>cloudasset. assets. exportSqladminInstances</code></p>
<p><code>cloudasset. assets. exportStorageBuckets</code></p>
<p><code>cloudasset. assets. exportTpuNodes</code></p>
<p><code>cloudasset. assets. exportVpcaccessConnector</code></p>
<p><code>cloudasset. assets. listAccessLevel</code></p>
<p><code>cloudasset. assets. listAccessPolicy</code></p>
<p><code>cloudasset. assets. listAiplatformBatchPredictionJobs</code></p>
<p><code>cloudasset. assets. listAiplatformCustomJobs</code></p>
<p><code>cloudasset. assets. listAiplatformDataLabelingJobs</code></p>
<p><code>cloudasset. assets. listAiplatformDatasets</code></p>
<p><code>cloudasset. assets. listAiplatformEndpoints</code></p>
<p><code>cloudasset. assets. listAiplatformHyperparameterTuningJobs</code></p>
<p><code>cloudasset. assets. listAiplatformMetadataStores</code></p>
<p><code>cloudasset. assets. listAiplatformModelDeploymentMonitoringJobs</code></p>
<p><code>cloudasset. assets. listAiplatformModels</code></p>
<p><code>cloudasset. assets. listAiplatformPipelineJobs</code></p>
<p><code>cloudasset. assets. listAiplatformSpecialistPools</code></p>
<p><code>cloudasset. assets. listAiplatformTrainingPipelines</code></p>
<p><code>cloudasset. assets. listAllAccessPolicy</code></p>
<p><code>cloudasset. assets. listAnthosConnectedCluster</code></p>
<p><code>cloudasset. assets. listAnthosedgeCluster</code></p>
<p><code>cloudasset. assets. listApigatewayApi</code></p>
<p><code>cloudasset. assets. listApigatewayApiConfig</code></p>
<p><code>cloudasset. assets. listApigatewayGateway</code></p>
<p><code>cloudasset. assets. listApikeysKeys</code></p>
<p><code>cloudasset. assets. listAppengineApplications</code></p>
<p><code>cloudasset. assets. listAppengineServices</code></p>
<p><code>cloudasset. assets. listAppengineVersions</code></p>
<p><code>cloudasset. assets. listArtifactregistryDockerImages</code></p>
<p><code>cloudasset. assets. listArtifactregistryRepositories</code></p>
<p><code>cloudasset. assets. listAssuredWorkloadsWorkloads</code></p>
<p><code>cloudasset. assets. listBeyondCorpApiGateways</code></p>
<p><code>cloudasset. assets. listBeyondCorpAppConnections</code></p>
<p><code>cloudasset. assets. listBeyondCorpAppConnectors</code></p>
<p><code>cloudasset. assets. listBeyondCorpAppGateways</code></p>
<p><code>cloudasset. assets. listBeyondCorpClientConnectorServices</code></p>
<p><code>cloudasset. assets. listBeyondCorpClientGateways</code></p>
<p><code>cloudasset. assets. listBigqueryDatasets</code></p>
<p><code>cloudasset. assets. listBigqueryModels</code></p>
<p><code>cloudasset. assets. listBigqueryTables</code></p>
<p><code>cloudasset. assets. listBigtableAppProfile</code></p>
<p><code>cloudasset. assets. listBigtableBackup</code></p>
<p><code>cloudasset. assets. listBigtableCluster</code></p>
<p><code>cloudasset. assets. listBigtableInstance</code></p>
<p><code>cloudasset. assets. listBigtableTable</code></p>
<p><code>cloudasset. assets. listCloudAssetFeeds</code></p>
<p><code>cloudasset. assets. listCloudDeployDeliveryPipelines</code></p>
<p><code>cloudasset. assets. listCloudDeployReleases</code></p>
<p><code>cloudasset. assets. listCloudDeployRollouts</code></p>
<p><code>cloudasset. assets. listCloudDeployTargets</code></p>
<p><code>cloudasset. assets. listCloudDocumentAIEvaluation</code></p>
<p><code>cloudasset. assets. listCloudDocumentAIHumanReviewConfig</code></p>
<p><code>cloudasset. assets. listCloudDocumentAILabelerPool</code></p>
<p><code>cloudasset. assets. listCloudDocumentAIProcessor</code></p>
<p><code>cloudasset. assets. listCloudDocumentAIProcessorVersion</code></p>
<p><code>cloudasset. assets. listCloudbillingBillingAccounts</code></p>
<p><code>cloudasset. assets. listCloudbillingProjectBillingInfos</code></p>
<p><code>cloudasset. assets. listCloudfunctionsFunctions</code></p>
<p><code>cloudasset. assets. listCloudfunctionsGen2Functions</code></p>
<p><code>cloudasset. assets. listCloudkmsCryptoKeyVersions</code></p>
<p><code>cloudasset. assets. listCloudkmsCryptoKeys</code></p>
<p><code>cloudasset. assets. listCloudkmsEkmConnections</code></p>
<p><code>cloudasset. assets. listCloudkmsImportJobs</code></p>
<p><code>cloudasset. assets. listCloudkmsKeyRings</code></p>
<p><code>cloudasset. assets. listCloudmemcacheInstances</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerFolders</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerOrganizations</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerProjects</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerTagBindings</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerTagKeys</code></p>
<p><code>cloudasset. assets. listCloudresourcemanagerTagValues</code></p>
<p><code>cloudasset. assets. listComposerEnvironments</code></p>
<p><code>cloudasset. assets. listComputeAddress</code></p>
<p><code>cloudasset. assets. listComputeAutoscalers</code></p>
<p><code>cloudasset. assets. listComputeBackendBuckets</code></p>
<p><code>cloudasset. assets. listComputeBackendServices</code></p>
<p><code>cloudasset. assets. listComputeCommitments</code></p>
<p><code>cloudasset. assets. listComputeDisks</code></p>
<p><code>cloudasset. assets. listComputeExternalVpnGateways</code></p>
<p><code>cloudasset. assets. listComputeFirewallPolicies</code></p>
<p><code>cloudasset. assets. listComputeFirewalls</code></p>
<p><code>cloudasset. assets. listComputeForwardingRules</code></p>
<p><code>cloudasset. assets. listComputeGlobalAddress</code></p>
<p><code>cloudasset. assets. listComputeGlobalForwardingRules</code></p>
<p><code>cloudasset. assets. listComputeHealthChecks</code></p>
<p><code>cloudasset. assets. listComputeHttpHealthChecks</code></p>
<p><code>cloudasset. assets. listComputeHttpsHealthChecks</code></p>
<p><code>cloudasset. assets. listComputeImages</code></p>
<p><code>cloudasset. assets. listComputeInstanceGroupManagers</code></p>
<p><code>cloudasset. assets. listComputeInstanceGroups</code></p>
<p><code>cloudasset. assets. listComputeInstanceTemplates</code></p>
<p><code>cloudasset. assets. listComputeInstances</code></p>
<p><code>cloudasset. assets. listComputeInterconnect</code></p>
<p><code>cloudasset. assets. listComputeInterconnectAttachment</code></p>
<p><code>cloudasset. assets. listComputeLicenses</code></p>
<p><code>cloudasset. assets. listComputeNetworkEndpointGroups</code></p>
<p><code>cloudasset. assets. listComputeNetworks</code></p>
<p><code>cloudasset. assets. listComputeNodeGroups</code></p>
<p><code>cloudasset. assets. listComputeNodeTemplates</code></p>
<p><code>cloudasset. assets. listComputePacketMirrorings</code></p>
<p><code>cloudasset. assets. listComputeProjects</code></p>
<p><code>cloudasset. assets. listComputeRegionAutoscaler</code></p>
<p><code>cloudasset. assets. listComputeRegionBackendServices</code></p>
<p><code>cloudasset. assets. listComputeRegionDisk</code></p>
<p><code>cloudasset. assets. listComputeRegionInstanceGroup</code></p>
<p><code>cloudasset. assets. listComputeRegionInstanceGroupManager</code></p>
<p><code>cloudasset. assets. listComputeReservations</code></p>
<p><code>cloudasset. assets. listComputeResourcePolicies</code></p>
<p><code>cloudasset. assets. listComputeRouters</code></p>
<p><code>cloudasset. assets. listComputeRoutes</code></p>
<p><code>cloudasset. assets. listComputeSecurityPolicy</code></p>
<p><code>cloudasset. assets. listComputeServiceAttachments</code></p>
<p><code>cloudasset. assets. listComputeSnapshots</code></p>
<p><code>cloudasset. assets. listComputeSslCertificates</code></p>
<p><code>cloudasset. assets. listComputeSslPolicies</code></p>
<p><code>cloudasset. assets. listComputeSubnetworks</code></p>
<p><code>cloudasset. assets. listComputeTargetHttpProxies</code></p>
<p><code>cloudasset. assets. listComputeTargetHttpsProxies</code></p>
<p><code>cloudasset. assets. listComputeTargetInstances</code></p>
<p><code>cloudasset. assets. listComputeTargetPools</code></p>
<p><code>cloudasset. assets. listComputeTargetSslProxies</code></p>
<p><code>cloudasset. assets. listComputeTargetTcpProxies</code></p>
<p><code>cloudasset. assets. listComputeTargetVpnGateways</code></p>
<p><code>cloudasset. assets. listComputeUrlMaps</code></p>
<p><code>cloudasset. assets. listComputeVpnGateways</code></p>
<p><code>cloudasset. assets. listComputeVpnTunnels</code></p>
<p><code>cloudasset. assets. listConnectorsConnections</code></p>
<p><code>cloudasset. assets. listConnectorsConnectorVersions</code></p>
<p><code>cloudasset. assets. listConnectorsConnectors</code></p>
<p><code>cloudasset. assets. listConnectorsProviders</code></p>
<p><code>cloudasset. assets. listConnectorsRuntimeConfigs</code></p>
<p><code>cloudasset. assets. listContainerAppsDeployment</code></p>
<p><code>cloudasset. assets. listContainerAppsReplicaSets</code></p>
<p><code>cloudasset. assets. listContainerBatchJobs</code></p>
<p><code>cloudasset. assets. listContainerClusterrole</code></p>
<p><code>cloudasset. assets. listContainerClusterrolebinding</code></p>
<p><code>cloudasset. assets. listContainerClusters</code></p>
<p><code>cloudasset. assets. listContainerExtensionsIngresses</code></p>
<p><code>cloudasset. assets. listContainerJobs</code></p>
<p><code>cloudasset. assets. listContainerNamespace</code></p>
<p><code>cloudasset. assets. listContainerNetworkingIngresses</code></p>
<p><code>cloudasset. assets. listContainerNetworkingNetworkPolicies</code></p>
<p><code>cloudasset. assets. listContainerNode</code></p>
<p><code>cloudasset. assets. listContainerNodepool</code></p>
<p><code>cloudasset. assets. listContainerPod</code></p>
<p><code>cloudasset. assets. listContainerReplicaSets</code></p>
<p><code>cloudasset. assets. listContainerRole</code></p>
<p><code>cloudasset. assets. listContainerRolebinding</code></p>
<p><code>cloudasset. assets. listContainerServices</code></p>
<p><code>cloudasset. assets. listContainerregistryImage</code></p>
<p><code>cloudasset. assets. listDataMigrationConnectionProfiles</code></p>
<p><code>cloudasset. assets. listDataMigrationMigrationJobs</code></p>
<p><code>cloudasset. assets. listDataflowJobs</code></p>
<p><code>cloudasset. assets. listDatafusionInstance</code></p>
<p><code>cloudasset. assets. listDataplexAssets</code></p>
<p><code>cloudasset. assets. listDataplexLakes</code></p>
<p><code>cloudasset. assets. listDataplexTasks</code></p>
<p><code>cloudasset. assets. listDataplexZones</code></p>
<p><code>cloudasset. assets. listDataprocAutoscalingPolicies</code></p>
<p><code>cloudasset. assets. listDataprocBatches</code></p>
<p><code>cloudasset. assets. listDataprocClusters</code></p>
<p><code>cloudasset. assets. listDataprocJobs</code></p>
<p><code>cloudasset. assets. listDataprocSessions</code></p>
<p><code>cloudasset. assets. listDataprocWorkflowTemplates</code></p>
<p><code>cloudasset. assets. listDatastreamConnectionProfile</code></p>
<p><code>cloudasset. assets. listDatastreamPrivateConnection</code></p>
<p><code>cloudasset. assets. listDatastreamStream</code></p>
<p><code>cloudasset. assets. listDialogflowAgents</code></p>
<p><code>cloudasset. assets. listDialogflowConversationProfiles</code></p>
<p><code>cloudasset. assets. listDialogflowKnowledgeBases</code></p>
<p><code>cloudasset. assets. listDialogflowLocationSettings</code></p>
<p><code>cloudasset. assets. listDlpDeidentifyTemplates</code></p>
<p><code>cloudasset. assets. listDlpDlpJobs</code></p>
<p><code>cloudasset. assets. listDlpInspectTemplates</code></p>
<p><code>cloudasset. assets. listDlpJobTriggers</code></p>
<p><code>cloudasset. assets. listDlpStoredInfoTypes</code></p>
<p><code>cloudasset. assets. listDnsManagedZones</code></p>
<p><code>cloudasset. assets. listDnsPolicies</code></p>
<p><code>cloudasset. assets. listDomainsRegistrations</code></p>
<p><code>cloudasset. assets. listEventarcTriggers</code></p>
<p><code>cloudasset. assets. listFileBackups</code></p>
<p><code>cloudasset. assets. listFileInstances</code></p>
<p><code>cloudasset. assets. listFirebaseAppInfos</code></p>
<p><code>cloudasset. assets. listFirebaseProjects</code></p>
<p><code>cloudasset. assets. listFirestoreDatabases</code></p>
<p><code>cloudasset. assets. listGKEHubFeatures</code></p>
<p><code>cloudasset. assets. listGKEHubMemberships</code></p>
<p><code>cloudasset. assets. listGameservicesGameServerClusters</code></p>
<p><code>cloudasset. assets. listGameservicesGameServerConfigs</code></p>
<p><code>cloudasset. assets. listGameservicesGameServerDeployments</code></p>
<p><code>cloudasset. assets. listGameservicesRealms</code></p>
<p><code>cloudasset. assets. listGkeBackupBackupPlans</code></p>
<p><code>cloudasset. assets. listGkeBackupBackups</code></p>
<p><code>cloudasset. assets. listGkeBackupRestorePlans</code></p>
<p><code>cloudasset. assets. listGkeBackupRestores</code></p>
<p><code>cloudasset. assets. listGkeBackupVolumeBackups</code></p>
<p><code>cloudasset. assets. listGkeBackupVolumeRestores</code></p>
<p><code>cloudasset. assets. listHealthcareConsentStores</code></p>
<p><code>cloudasset. assets. listHealthcareDatasets</code></p>
<p><code>cloudasset. assets. listHealthcareDicomStores</code></p>
<p><code>cloudasset. assets. listHealthcareFhirStores</code></p>
<p><code>cloudasset. assets. listHealthcareHl7V2Stores</code></p>
<p><code>cloudasset. assets. listIamPolicy</code></p>
<p><code>cloudasset.assets.listIamRoles</code></p>
<p><code>cloudasset. assets. listIamServiceAccountKeys</code></p>
<p><code>cloudasset. assets. listIamServiceAccounts</code></p>
<p><code>cloudasset. assets. listIapTunnel</code></p>
<p><code>cloudasset. assets. listIapTunnelInstances</code></p>
<p><code>cloudasset. assets. listIapTunnelZones</code></p>
<p><code>cloudasset.assets.listIapWeb</code></p>
<p><code>cloudasset. assets. listIapWebServiceVersion</code></p>
<p><code>cloudasset. assets. listIapWebServices</code></p>
<p><code>cloudasset. assets. listIapWebType</code></p>
<p><code>cloudasset. assets. listIdsEndpoints</code></p>
<p><code>cloudasset. assets. listIntegrationsAuthConfigs</code></p>
<p><code>cloudasset. assets. listIntegrationsCertificates</code></p>
<p><code>cloudasset. assets. listIntegrationsExecutions</code></p>
<p><code>cloudasset. assets. listIntegrationsIntegrationVersions</code></p>
<p><code>cloudasset. assets. listIntegrationsIntegrations</code></p>
<p><code>cloudasset. assets. listIntegrationsSfdcChannels</code></p>
<p><code>cloudasset. assets. listIntegrationsSfdcInstances</code></p>
<p><code>cloudasset. assets. listIntegrationsSuspensions</code></p>
<p><code>cloudasset. assets. listLoggingLogMetrics</code></p>
<p><code>cloudasset. assets. listLoggingLogSinks</code></p>
<p><code>cloudasset. assets. listManagedidentitiesDomain</code></p>
<p><code>cloudasset. assets. listMetastoreBackups</code></p>
<p><code>cloudasset. assets. listMetastoreMetadataImports</code></p>
<p><code>cloudasset. assets. listMetastoreServices</code></p>
<p><code>cloudasset. assets. listMonitoringAlertPolicies</code></p>
<p><code>cloudasset. assets. listNetworkConnectivityHubs</code></p>
<p><code>cloudasset. assets. listNetworkConnectivitySpokes</code></p>
<p><code>cloudasset. assets. listNetworkManagementConnectivityTests</code></p>
<p><code>cloudasset. assets. listNetworkServicesEndpointPolicies</code></p>
<p><code>cloudasset. assets. listNetworkServicesGateways</code></p>
<p><code>cloudasset. assets. listNetworkServicesGrpcRoutes</code></p>
<p><code>cloudasset. assets. listNetworkServicesHttpRoutes</code></p>
<p><code>cloudasset. assets. listNetworkServicesMeshes</code></p>
<p><code>cloudasset. assets. listNetworkServicesServiceBindings</code></p>
<p><code>cloudasset. assets. listNetworkServicesTcpRoutes</code></p>
<p><code>cloudasset. assets. listNetworkServicesTlsRoutes</code></p>
<p><code>cloudasset. assets. listOSConfigOSPolicyAssignmentReports</code></p>
<p><code>cloudasset. assets. listOSConfigOSPolicyAssignments</code></p>
<p><code>cloudasset. assets. listOSConfigVulnerabilityReports</code></p>
<p><code>cloudasset. assets. listOSInventories</code></p>
<p><code>cloudasset. assets. listOrgPolicy</code></p>
<p><code>cloudasset. assets. listPatchDeployments</code></p>
<p><code>cloudasset. assets. listPubsubSnapshots</code></p>
<p><code>cloudasset. assets. listPubsubSubscriptions</code></p>
<p><code>cloudasset. assets. listPubsubTopics</code></p>
<p><code>cloudasset. assets. listRedisInstances</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. listRunDomainMapping</code></p>
<p><code>cloudasset. assets. listRunRevision</code></p>
<p><code>cloudasset. assets. listRunService</code></p>
<p><code>cloudasset. assets. listSecretManagerSecretVersions</code></p>
<p><code>cloudasset. assets. listSecretManagerSecrets</code></p>
<p><code>cloudasset. assets. listServiceDirectoryNamespaces</code></p>
<p><code>cloudasset. assets. listServicePerimeter</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementConsumerProperty</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementConsumerQuotaLimits</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementConsumers</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementProducerOverrides</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementTenancyUnits</code></p>
<p><code>cloudasset. assets. listServiceconsumermanagementVisibility</code></p>
<p><code>cloudasset. assets. listServicemanagementServices</code></p>
<p><code>cloudasset. assets. listServiceusageAdminOverrides</code></p>
<p><code>cloudasset. assets. listServiceusageConsumerOverrides</code></p>
<p><code>cloudasset. assets. listServiceusageServices</code></p>
<p><code>cloudasset. assets. listSpannerBackups</code></p>
<p><code>cloudasset. assets. listSpannerDatabases</code></p>
<p><code>cloudasset. assets. listSpannerInstances</code></p>
<p><code>cloudasset. assets. listSpeakerIdPhrases</code></p>
<p><code>cloudasset. assets. listSpeakerIdSettings</code></p>
<p><code>cloudasset. assets. listSpeakerIdSpeakers</code></p>
<p><code>cloudasset. assets. listSpeechCustomClasses</code></p>
<p><code>cloudasset. assets. listSpeechPhraseSets</code></p>
<p><code>cloudasset. assets. listSqladminBackupRuns</code></p>
<p><code>cloudasset. assets. listSqladminInstances</code></p>
<p><code>cloudasset. assets. listStorageBuckets</code></p>
<p><code>cloudasset.assets.listTpuNodes</code></p>
<p><code>cloudasset. assets. listVpcaccessConnector</code></p>
<p><code>cloudasset. assets. queryAccessPolicy</code></p>
<p><code>cloudasset. assets. queryIamPolicy</code></p>
<p><code>cloudasset. assets. queryOSInventories</code></p>
<p><code>cloudasset. assets. queryResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudasset. othercloudconnections. get</code></p>
<p><code>cloudasset. othercloudconnections. list</code></p>
<p><code>cloudasset. othercloudconnections. verify</code></p>
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudsecuritycompliance. auditReports. get</code></p>
<p><code>cloudsecuritycompliance. auditReports. list</code></p>
<p><code>cloudsecuritycompliance. billingSettings. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. cmEnrollments. get</code></p>
<p><code>cloudsecuritycompliance. controlComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. controlReports. get</code></p>
<p><code>cloudsecuritycompliance. controls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. controls. get</code></li>
<li><code>cloudsecuritycompliance. controls. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. findingSummaries. list</code></p>
<p><code>cloudsecuritycompliance. findings. list</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. get</code></p>
<p><code>cloudsecuritycompliance. frameworkAudits. list</code></p>
<p><code>cloudsecuritycompliance. frameworkComplianceReports.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. aggregate</code></li>
<li><code>cloudsecuritycompliance. frameworkComplianceReports. get</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworkComplianceSummaries. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>cloudsecuritycompliance. locations. get</code></p>
<p><code>cloudsecuritycompliance. locations. list</code></p>
<p><code>cloudsecuritycompliance. operations. get</code></p>
<p><code>cloudsecuritycompliance. operations. list</code></p>
<p><code>cloudsecuritycompliance. resourceEnrollmentStatuses.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. get</code></li>
<li><code>cloudsecuritycompliance. resourceEnrollmentStatuses. list</code></li>
</ul>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config. deploymentgrouprevisions.*</code></p>
<ul>
<li><code>config. deploymentgrouprevisions. get</code></li>
<li><code>config. deploymentgrouprevisions. list</code></li>
</ul>
<p><code>config.deploymentgroups.get</code></p>
<p><code>config.deploymentgroups.list</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>config.resources.*</code></p>
<ul>
<li><code>config.resources.get</code></li>
<li><code>config.resources.list</code></li>
</ul>
<p><code>config.revisions.get</code></p>
<p><code>config.revisions.list</code></p>
<p><code>config.terraformversions.*</code></p>
<ul>
<li><code>config.terraformversions.get</code></li>
<li><code>config.terraformversions.list</code></li>
</ul>
<p><code>container.clusters.list</code></p>
<p><code>designcenter. applicationTemplateRevisions. get</code></p>
<p><code>designcenter. applicationTemplateRevisions. list</code></p>
<p><code>designcenter. applicationTemplates. get</code></p>
<p><code>designcenter. applicationTemplates. list</code></p>
<p><code>designcenter.applications.get</code></p>
<p><code>designcenter.applications.list</code></p>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.get</code></p>
<p><code>designcenter.components.list</code></p>
<p><code>designcenter.connections.get</code></p>
<p><code>designcenter.connections.list</code></p>
<p><code>designcenter.locations.*</code></p>
<ul>
<li><code>designcenter.locations.get</code></li>
<li><code>designcenter.locations.list</code></li>
</ul>
<p><code>designcenter.operations.get</code></p>
<p><code>designcenter.operations.list</code></p>
<p><code>designcenter. sharedTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. sharedTemplateRevisions. get</code></li>
<li><code>designcenter. sharedTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter.sharedTemplates.*</code></p>
<ul>
<li><code>designcenter. sharedTemplates. get</code></li>
<li><code>designcenter. sharedTemplates. list</code></li>
</ul>
<p><code>designcenter.shares.get</code></p>
<p><code>designcenter.shares.list</code></p>
<p><code>designcenter.spaces.get</code></p>
<p><code>designcenter. spaces. getIamPolicy</code></p>
<p><code>designcenter.spaces.list</code></p>
<p><code>developerconnect. deploymentEvents.*</code></p>
<ul>
<li><code>developerconnect. deploymentEvents. get</code></li>
<li><code>developerconnect. deploymentEvents. list</code></li>
</ul>
<p><code>developerconnect. insightsConfigs. get</code></p>
<p><code>developerconnect. insightsConfigs. list</code></p>
<p><code>developerconnect.locations.*</code></p>
<ul>
<li><code>developerconnect.locations.get</code></li>
<li><code>developerconnect. locations. list</code></li>
</ul>
<p><code>developerconnect. operations. get</code></p>
<p><code>developerconnect. operations. list</code></p>
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
<p><code>monitoring.timeSeries.list</code></p>
<p><code>monitoring. uptimeCheckConfigs. get</code></p>
<p><code>monitoring. uptimeCheckConfigs. list</code></p>
<p><code>opsconfigmonitoring. resourceMetadata. list</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. get</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. list</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. get</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. get</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. list</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. get</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. list</code></p>
<p><code>recommender. alloydbInstanceSecurityInsights. get</code></p>
<p><code>recommender. alloydbInstanceSecurityInsights. list</code></p>
<p><code>recommender. alloydbInstanceSecurityRecommendations. get</code></p>
<p><code>recommender. alloydbInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. appengineVersionCostInsights. get</code></p>
<p><code>recommender. appengineVersionCostInsights. list</code></p>
<p><code>recommender. appengineVersionCostRecommendations. get</code></p>
<p><code>recommender. appengineVersionCostRecommendations. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsInsights. get</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsInsights. list</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsRecommendations. get</code></p>
<p><code>recommender. bigqueryCapacityCommitmentsRecommendations. list</code></p>
<p><code>recommender. bigqueryMaterializedViewInsights. get</code></p>
<p><code>recommender. bigqueryMaterializedViewInsights. list</code></p>
<p><code>recommender. bigqueryMaterializedViewRecommendations. get</code></p>
<p><code>recommender. bigqueryMaterializedViewRecommendations. list</code></p>
<p><code>recommender. bigqueryPartitionClusterRecommendations. get</code></p>
<p><code>recommender. bigqueryPartitionClusterRecommendations. list</code></p>
<p><code>recommender. bigqueryTableStatsInsights. get</code></p>
<p><code>recommender. bigqueryTableStatsInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceInsights. get</code></p>
<p><code>recommender. bigtableClusterPerformanceInsights. list</code></p>
<p><code>recommender. bigtableClusterPerformanceRecommendations. get</code></p>
<p><code>recommender. bigtableClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender. cloudCostGeneralInsights. get</code></p>
<p><code>recommender. cloudCostGeneralInsights. list</code></p>
<p><code>recommender. cloudCostGeneralRecommendations. get</code></p>
<p><code>recommender. cloudCostGeneralRecommendations. list</code></p>
<p><code>recommender. cloudDeprecationGeneralInsights. get</code></p>
<p><code>recommender. cloudDeprecationGeneralInsights. list</code></p>
<p><code>recommender. cloudDeprecationGeneralRecommendations. get</code></p>
<p><code>recommender. cloudDeprecationGeneralRecommendations. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceInsights. list</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. get</code></p>
<p><code>recommender. cloudFunctionsPerformanceRecommendations. list</code></p>
<p><code>recommender. cloudManageabilityGeneralInsights. get</code></p>
<p><code>recommender. cloudManageabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudManageabilityGeneralRecommendations. get</code></p>
<p><code>recommender. cloudManageabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudPerformanceGeneralInsights. get</code></p>
<p><code>recommender. cloudPerformanceGeneralInsights. list</code></p>
<p><code>recommender. cloudPerformanceGeneralRecommendations. get</code></p>
<p><code>recommender. cloudPerformanceGeneralRecommendations. list</code></p>
<p><code>recommender. cloudRecentChangeInsights. get</code></p>
<p><code>recommender. cloudRecentChangeInsights. list</code></p>
<p><code>recommender. cloudRecentChangeRecommendations. get</code></p>
<p><code>recommender. cloudRecentChangeRecommendations. list</code></p>
<p><code>recommender. cloudRecentChangeRecommenderConfig. get</code></p>
<p><code>recommender. cloudReliabilityGeneralInsights. get</code></p>
<p><code>recommender. cloudReliabilityGeneralInsights. list</code></p>
<p><code>recommender. cloudReliabilityGeneralRecommendations. get</code></p>
<p><code>recommender. cloudReliabilityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudSecurityGeneralInsights. get</code></p>
<p><code>recommender. cloudSecurityGeneralInsights. list</code></p>
<p><code>recommender. cloudSecurityGeneralRecommendations. get</code></p>
<p><code>recommender. cloudSecurityGeneralRecommendations. list</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlIdleInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceActivityInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceActivityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceCpuUsageInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceDiskUsageTrendInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceMemoryUsageInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOomProbabilityInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceOomProbabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. get</code></p>
<p><code>recommender. cloudsqlInstanceOutOfDiskRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceInsights. get</code></p>
<p><code>recommender. cloudsqlInstancePerformanceInsights. list</code></p>
<p><code>recommender. cloudsqlInstancePerformanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlInstancePerformanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityRecommendations. get</code></p>
<p><code>recommender. cloudsqlInstanceReliabilityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceSecurityInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceSecurityRecommendations. get</code></p>
<p><code>recommender. cloudsqlInstanceSecurityRecommendations. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedCpuUsageInsights. list</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. get</code></p>
<p><code>recommender. cloudsqlInstanceUnderprovisionedMemoryUsageInsights. list</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlOverprovisionedInstanceRecommendations. list</code></p>
<p><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. get</code></p>
<p><code>recommender. cloudsqlUnderProvisionedInstanceRecommendations. list</code></p>
<p><code>recommender. commitmentUtilizationInsights. get</code></p>
<p><code>recommender. commitmentUtilizationInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceInsights. get</code></p>
<p><code>recommender. computeAddressIdleResourceInsights. list</code></p>
<p><code>recommender. computeAddressIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeAddressIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeDiskIdleResourceInsights. get</code></p>
<p><code>recommender. computeDiskIdleResourceInsights. list</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeDiskIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeFirewallInsightTypeConfigs. get</code></p>
<p><code>recommender. computeFirewallInsights. get</code></p>
<p><code>recommender. computeFirewallInsights. list</code></p>
<p><code>recommender. computeIdleResourceInsights. get</code></p>
<p><code>recommender. computeIdleResourceInsights. list</code></p>
<p><code>recommender. computeIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeIdleResourceRecommenderConfig. get</code></p>
<p><code>recommender. computeImageIdleResourceInsights. get</code></p>
<p><code>recommender. computeImageIdleResourceInsights. list</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeImageIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceCpuUsageInsights. get</code></p>
<p><code>recommender. computeInstanceCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsagePredictionInsights. get</code></p>
<p><code>recommender. computeInstanceCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceCpuUsageTrendInsights. get</code></p>
<p><code>recommender. computeInstanceCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageInsights. get</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsagePredictionInsights. get</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageTrendInsights. get</code></p>
<p><code>recommender. computeInstanceGroupManagerCpuUsageTrendInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. get</code></p>
<p><code>recommender. computeInstanceGroupManagerMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsageInsights. get</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsagePredictionInsights. get</code></p>
<p><code>recommender. computeInstanceGroupManagerMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. get</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommendations. list</code></p>
<p><code>recommender. computeInstanceIdleResourceRecommenderConfig. get</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. get</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommendations. list</code></p>
<p><code>recommender. computeInstanceMachineTypeRecommenderConfig. get</code></p>
<p><code>recommender. computeInstanceMemoryUsageInsights. get</code></p>
<p><code>recommender. computeInstanceMemoryUsageInsights. list</code></p>
<p><code>recommender. computeInstanceMemoryUsagePredictionInsights. get</code></p>
<p><code>recommender. computeInstanceMemoryUsagePredictionInsights. list</code></p>
<p><code>recommender. computeInstanceNetworkThroughputInsights. get</code></p>
<p><code>recommender. computeInstanceNetworkThroughputInsights. list</code></p>
<p><code>recommender. containerDiagnosisInsights. get</code></p>
<p><code>recommender. containerDiagnosisInsights. list</code></p>
<p><code>recommender. containerDiagnosisRecommendations. get</code></p>
<p><code>recommender. containerDiagnosisRecommendations. list</code></p>
<p><code>recommender.costInsights.get</code></p>
<p><code>recommender.costInsights.list</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. get</code></p>
<p><code>recommender. dataflowDiagnosticsInsights. list</code></p>
<p><code>recommender. errorReportingInsights. get</code></p>
<p><code>recommender. errorReportingInsights. list</code></p>
<p><code>recommender. errorReportingRecommendations. get</code></p>
<p><code>recommender. errorReportingRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesInsights. get</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesInsights. list</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesRecommendations. get</code></p>
<p><code>recommender. firestoreDatabaseFirebaseRulesRecommendations. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityInsights. get</code></p>
<p><code>recommender. firestoreDatabaseReliabilityInsights. list</code></p>
<p><code>recommender. firestoreDatabaseReliabilityRecommendations. get</code></p>
<p><code>recommender. firestoreDatabaseReliabilityRecommendations. list</code></p>
<p><code>recommender. gmpGuidedExperienceInsights. get</code></p>
<p><code>recommender. gmpGuidedExperienceInsights. list</code></p>
<p><code>recommender. gmpGuidedExperienceRecommendations. get</code></p>
<p><code>recommender. gmpGuidedExperienceRecommendations. list</code></p>
<p><code>recommender. gmpProjectManagementInsights. get</code></p>
<p><code>recommender. gmpProjectManagementInsights. list</code></p>
<p><code>recommender. gmpProjectManagementRecommendations. get</code></p>
<p><code>recommender. gmpProjectManagementRecommendations. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsInsights. get</code></p>
<p><code>recommender. gmpProjectProductSuggestionsInsights. list</code></p>
<p><code>recommender. gmpProjectProductSuggestionsRecommendations. get</code></p>
<p><code>recommender. gmpProjectProductSuggestionsRecommendations. list</code></p>
<p><code>recommender. iamPolicyChangeRiskInsights. get</code></p>
<p><code>recommender. iamPolicyChangeRiskInsights. list</code></p>
<p><code>recommender. iamPolicyChangeRiskRecommendations. get</code></p>
<p><code>recommender. iamPolicyChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamPolicyInsights. get</code></p>
<p><code>recommender. iamPolicyInsights. list</code></p>
<p><code>recommender. iamPolicyLateralMovementInsights. get</code></p>
<p><code>recommender. iamPolicyLateralMovementInsights. list</code></p>
<p><code>recommender. iamPolicyRecommendations. get</code></p>
<p><code>recommender. iamPolicyRecommendations. list</code></p>
<p><code>recommender. iamPolicyRecommenderConfig. get</code></p>
<p><code>recommender. iamServiceAccountChangeRiskInsights. get</code></p>
<p><code>recommender. iamServiceAccountChangeRiskInsights. list</code></p>
<p><code>recommender. iamServiceAccountChangeRiskRecommendations. get</code></p>
<p><code>recommender. iamServiceAccountChangeRiskRecommendations. list</code></p>
<p><code>recommender. iamServiceAccountInsights. get</code></p>
<p><code>recommender. iamServiceAccountInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>recommender. loggingProductSuggestionContainerInsights. get</code></p>
<p><code>recommender. loggingProductSuggestionContainerInsights. list</code></p>
<p><code>recommender. loggingProductSuggestionContainerRecommendations. get</code></p>
<p><code>recommender. loggingProductSuggestionContainerRecommendations. list</code></p>
<p><code>recommender. memorystoreManageabilityInsights. get</code></p>
<p><code>recommender. memorystoreManageabilityInsights. list</code></p>
<p><code>recommender. memorystoreManageabilityRecommendations. get</code></p>
<p><code>recommender. memorystoreManageabilityRecommendations. list</code></p>
<p><code>recommender. memorystorePerformanceInsights. get</code></p>
<p><code>recommender. memorystorePerformanceInsights. list</code></p>
<p><code>recommender. memorystorePerformanceRecommendations. get</code></p>
<p><code>recommender. memorystorePerformanceRecommendations. list</code></p>
<p><code>recommender. memorystoreReliabilityInsights. get</code></p>
<p><code>recommender. memorystoreReliabilityInsights. list</code></p>
<p><code>recommender. memorystoreReliabilityRecommendations. get</code></p>
<p><code>recommender. memorystoreReliabilityRecommendations. list</code></p>
<p><code>recommender. memorystoreUtilizationInsights. get</code></p>
<p><code>recommender. memorystoreUtilizationInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeInsights. get</code></p>
<p><code>recommender. monitoringProductSuggestionComputeInsights. list</code></p>
<p><code>recommender. monitoringProductSuggestionComputeRecommendations. get</code></p>
<p><code>recommender. monitoringProductSuggestionComputeRecommendations. list</code></p>
<p><code>recommender. networkAnalyzerCloudSqlInsights. get</code></p>
<p><code>recommender. networkAnalyzerCloudSqlInsights. list</code></p>
<p><code>recommender. networkAnalyzerDynamicRouteInsights. get</code></p>
<p><code>recommender. networkAnalyzerDynamicRouteInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. get</code></p>
<p><code>recommender. networkAnalyzerGkeConnectivityInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. get</code></p>
<p><code>recommender. networkAnalyzerGkeIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerGkeServiceAccountInsights. get</code></p>
<p><code>recommender. networkAnalyzerGkeServiceAccountInsights. list</code></p>
<p><code>recommender. networkAnalyzerIpAddressInsights. get</code></p>
<p><code>recommender. networkAnalyzerIpAddressInsights. list</code></p>
<p><code>recommender. networkAnalyzerLoadBalancerInsights. get</code></p>
<p><code>recommender. networkAnalyzerLoadBalancerInsights. list</code></p>
<p><code>recommender. networkAnalyzerVpcConnectivityInsights. get</code></p>
<p><code>recommender. networkAnalyzerVpcConnectivityInsights. list</code></p>
<p><code>recommender. orgPolicyInsights. get</code></p>
<p><code>recommender. orgPolicyInsights. list</code></p>
<p><code>recommender. orgPolicyRecommendations. get</code></p>
<p><code>recommender. orgPolicyRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskInsights. get</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskRecommendations. get</code></p>
<p><code>recommender. resourcemanagerProjectChangeRiskRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationInsightTypeConfigs. get</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationInsights. get</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationInsights. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. get</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommendations. list</code></p>
<p><code>recommender. resourcemanagerProjectUtilizationRecommenderConfigs. get</code></p>
<p><code>recommender. resourcemanagerServiceLimitInsights. get</code></p>
<p><code>recommender. resourcemanagerServiceLimitInsights. list</code></p>
<p><code>recommender. resourcemanagerServiceLimitRecommendations. get</code></p>
<p><code>recommender. resourcemanagerServiceLimitRecommendations. list</code></p>
<p><code>recommender. runServiceCostInsights. get</code></p>
<p><code>recommender. runServiceCostInsights. list</code></p>
<p><code>recommender. runServiceCostRecommendations. get</code></p>
<p><code>recommender. runServiceCostRecommendations. list</code></p>
<p><code>recommender. runServiceIdentityInsights. get</code></p>
<p><code>recommender. runServiceIdentityInsights. list</code></p>
<p><code>recommender. runServiceIdentityRecommendations. get</code></p>
<p><code>recommender. runServiceIdentityRecommendations. list</code></p>
<p><code>recommender. runServicePerformanceInsights. get</code></p>
<p><code>recommender. runServicePerformanceInsights. list</code></p>
<p><code>recommender. runServicePerformanceRecommendations. get</code></p>
<p><code>recommender. runServicePerformanceRecommendations. list</code></p>
<p><code>recommender. runServiceSecurityInsights. get</code></p>
<p><code>recommender. runServiceSecurityInsights. list</code></p>
<p><code>recommender. runServiceSecurityRecommendations. get</code></p>
<p><code>recommender. runServiceSecurityRecommendations. list</code></p>
<p><code>recommender. spannerDatabaseSecurityInsights. get</code></p>
<p><code>recommender. spannerDatabaseSecurityInsights. list</code></p>
<p><code>recommender. spannerDatabaseSecurityRecommendations. get</code></p>
<p><code>recommender. spannerDatabaseSecurityRecommendations. list</code></p>
<p><code>recommender. spannerProjectReliabilityInsights. get</code></p>
<p><code>recommender. spannerProjectReliabilityInsights. list</code></p>
<p><code>recommender. spannerProjectReliabilityRecommendations. get</code></p>
<p><code>recommender. spannerProjectReliabilityRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentInsights. get</code></p>
<p><code>recommender. spendBasedCommitmentInsights. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. get</code></p>
<p><code>recommender. spendBasedCommitmentRecommendations. list</code></p>
<p><code>recommender. spendBasedCommitmentRecommenderConfig. get</code></p>
<p><code>recommender. storageBucketSoftDeleteInsights. get</code></p>
<p><code>recommender. storageBucketSoftDeleteInsights. list</code></p>
<p><code>recommender. storageBucketSoftDeleteRecommendations. get</code></p>
<p><code>recommender. storageBucketSoftDeleteRecommendations. list</code></p>
<p><code>recommender. usageCommitmentRecommendations. get</code></p>
<p><code>recommender. usageCommitmentRecommendations. list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicehealth.*</code></p>
<ul>
<li><code>servicehealth.artifacts.get</code></li>
<li><code>servicehealth.artifacts.list</code></li>
<li><code>servicehealth.events.get</code></li>
<li><code>servicehealth.events.list</code></li>
<li><code>servicehealth.locations.get</code></li>
<li><code>servicehealth.locations.list</code></li>
<li><code>servicehealth. organizationEvents. get</code></li>
<li><code>servicehealth. organizationEvents. list</code></li>
<li><code>servicehealth. organizationImpacts. get</code></li>
<li><code>servicehealth. organizationImpacts. list</code></li>
<li><code>servicehealth.statuses.get</code></li>
</ul>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
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
<td><code>apphub.applications.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.applications.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.applications.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub. applications. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.applications.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub. applications. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.applications.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.boundaries.attach</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.boundaries.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub.boundaries.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.discoveredServices.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.discoveredServices.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub. discoveredServices. register</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.discoveredWorkloads.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub. discoveredWorkloads. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub. discoveredWorkloads. register</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub. extendedMetadataSchemas. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub. extendedMetadataSchemas. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationViewer">Application Viewer</a> ( <code>roles/ designcenter.applicationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub. serviceProjectAttachments. attach</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub. serviceProjectAttachments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub. serviceProjectAttachments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub. serviceProjectAttachments. detach</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub. serviceProjectAttachments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub. serviceProjectAttachments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.admin">Application Design Center Admin</a> ( <code>roles/ designcenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationAdmin">Application Admin</a> ( <code>roles/ designcenter.applicationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.applicationEditor">Application Editor</a> ( <code>roles/ designcenter.applicationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.user">Application Design Center User</a> ( <code>roles/ designcenter.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub. serviceProjectAttachments. lookup</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.services.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.services.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>apphub.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.services.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.workloads.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/designcenter#designcenter.serviceAgent">DesignCenter Service Agent</a> ( <code>roles/ designcenter.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/saasservicemgmt#saasservicemgmt.serviceAgent">SaaS Service Management Service Agent</a> ( <code>roles/ saasservicemgmt.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.workloads.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>apphub.workloads.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>apphub.workloads.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.viewer">App Hub Viewer</a> ( <code>roles/ apphub.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.appManagementViewer">App Management Viewer</a> ( <code>roles/ apphub.appManagementViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code>roles/ cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/developerconnect#developerconnect.serviceAgent">Developer Connect Service Agent</a> ( <code>roles/ developerconnect.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>apphub.workloads.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.admin">App Hub Admin</a> ( <code>roles/ apphub.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apphub#apphub.editor">App Hub Editor</a> ( <code>roles/ apphub.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
