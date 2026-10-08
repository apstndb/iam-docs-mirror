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
<td>Cloud Hub Operator <sup>Beta</sup>
<p>( <code>roles/ cloudhub.operator</code> )</p>
<p>Allows users to view and interact with Cloud Hub.</p></td>
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
<p><code>apptopology.*</code></p>
<ul>
<li><code>apptopology. applicationTopologies. generate</code></li>
<li><code>apptopology. devOpsDomainTopologies. generate</code></li>
<li><code>apptopology. discoveredResourcesTopologies. generate</code></li>
<li><code>apptopology.domains.get</code></li>
<li><code>apptopology.domains.list</code></li>
<li><code>apptopology.locations.get</code></li>
<li><code>apptopology.locations.list</code></li>
<li><code>apptopology.operations.get</code></li>
<li><code>apptopology.operations.list</code></li>
<li><code>apptopology.schemas.get</code></li>
<li><code>apptopology. securityDomainTopologies. generate</code></li>
<li><code>apptopology. sreDomainTopologies. generate</code></li>
<li><code>apptopology.topologyViews.get</code></li>
<li><code>apptopology.topologyViews.list</code></li>
</ul>
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
<p><code>billing.resourceCosts.get</code></p>
<p><code>capacityplanner. capacityPlans. get</code></p>
<p><code>capacityplanner. capacityPlans. list</code></p>
<p><code>capacityplanner.forecasts.list</code></p>
<p><code>capacityplanner.operations.get</code></p>
<p><code>capacityplanner. planAlertInsights. list</code></p>
<p><code>capacityplanner. usageAlertInsights. list</code></p>
<p><code>capacityplanner. usageHistories.*</code></p>
<ul>
<li><code>capacityplanner. usageHistories. list</code></li>
<li><code>capacityplanner. usageHistories. summarize</code></li>
</ul>
<p><code>cloudasset.assets.*</code></p>
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
<p><code>cloudnotifications. activities. list</code></p>
<p><code>cloudquotas.quotas.get</code></p>
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
<p><code>cloudsupport.properties.get</code></p>
<p><code>cloudsupport.techCases.get</code></p>
<p><code>cloudsupport.techCases.list</code></p>
<p><code>compute.futureReservations.get</code></p>
<p><code>compute. futureReservations. list</code></p>
<p><code>compute.reservations.get</code></p>
<p><code>compute.reservations.list</code></p>
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
<p><code>errorreporting. applications. list</code></p>
<p><code>errorreporting. errorEvents. list</code></p>
<p><code>errorreporting. groupMetadata. get</code></p>
<p><code>errorreporting.groups.list</code></p>
<p><code>logging.buckets.get</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>logging.exclusions.get</code></p>
<p><code>logging.exclusions.list</code></p>
<p><code>logging.links.get</code></p>
<p><code>logging.links.list</code></p>
<p><code>logging.locations.*</code></p>
<ul>
<li><code>logging.locations.get</code></li>
<li><code>logging.locations.list</code></li>
</ul>
<p><code>logging.logEntries.list</code></p>
<p><code>logging.logMetrics.get</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>logging.logScopes.get</code></p>
<p><code>logging.logScopes.list</code></p>
<p><code>logging.logServiceIndexes.list</code></p>
<p><code>logging.logServices.list</code></p>
<p><code>logging.logs.list</code></p>
<p><code>logging.notificationRules.get</code></p>
<p><code>logging.notificationRules.list</code></p>
<p><code>logging.operations.get</code></p>
<p><code>logging.operations.list</code></p>
<p><code>logging.queries.getShared</code></p>
<p><code>logging.queries.listShared</code></p>
<p><code>logging.queries.usePrivate</code></p>
<p><code>logging.settings.get</code></p>
<p><code>logging.sinks.get</code></p>
<p><code>logging.sinks.list</code></p>
<p><code>logging.usage.get</code></p>
<p><code>logging.views.get</code></p>
<p><code>logging.views.getIamPolicy</code></p>
<p><code>logging.views.list</code></p>
<p><code>maintenance.*</code></p>
<ul>
<li><code>maintenance.locations.get</code></li>
<li><code>maintenance.locations.list</code></li>
<li><code>maintenance. resourceMaintenances. get</code></li>
<li><code>maintenance. resourceMaintenances. list</code></li>
</ul>
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
<p><code>observability.scopes.get</code></p>
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
<p><code>recommender. costRecommendations.*</code></p>
<ul>
<li><code>recommender. costRecommendations. listAll</code></li>
<li><code>recommender. costRecommendations. summarizeAll</code></li>
</ul>
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
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>securitycenter.assets.group</code></p>
<p><code>securitycenter.assets.list</code></p>
<p><code>securitycenter. assets. listAssetPropertyNames</code></p>
<p><code>securitycenter. attackpaths. list</code></p>
<p><code>securitycenter. complianceReports. aggregate</code></p>
<p><code>securitycenter. compliancesnapshots. list</code></p>
<p><code>securitycenter. exposurepathexplan. get</code></p>
<p><code>securitycenter. findingexplanations. get</code></p>
<p><code>securitycenter.findings.group</code></p>
<p><code>securitycenter.findings.list</code></p>
<p><code>securitycenter. findings. listFindingPropertyNames</code></p>
<p><code>securitycenter.graphs.*</code></p>
<ul>
<li><code>securitycenter.graphs.get</code></li>
<li><code>securitycenter.graphs.query</code></li>
</ul>
<p><code>securitycenter.issues.get</code></p>
<p><code>securitycenter.issues.group</code></p>
<p><code>securitycenter.issues.list</code></p>
<p><code>securitycenter. issues. listFilterValues</code></p>
<p><code>securitycenter.issues.retrieve</code></p>
<p><code>securitycenter.issues.search</code></p>
<p><code>securitycenter. issues. searchImpactedResources</code></p>
<p><code>securitycenter.sources.get</code></p>
<p><code>securitycenter.sources.list</code></p>
<p><code>securitycenter. userinterfacemetadata. get</code></p>
<p><code>securitycenter. vulnerabilitysnapshots. list</code></p>
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
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.quotas.get</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
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

## Cloud Hub permissions

There are no IAM permissions for this service.
