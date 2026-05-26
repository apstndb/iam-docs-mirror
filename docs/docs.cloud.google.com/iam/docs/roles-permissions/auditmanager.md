---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/auditmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager
title: Audit Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Audit Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Audit Manager roles

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
<td><h4 id="auditmanager.admin" class="role-title add-link" data-text="Audit Manager Admin Beta" tabindex="-1">Audit Manager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p>Full access to Audit Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">auditmanager.auditReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  auditReports.  generate</code></li>
<li><code dir="ltr" translate="no">auditmanager.auditReports.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.auditReports.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.auditSchedules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  create</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.  auditScopeReports.  generate</code></p>
<p><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.controlReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.controls.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.findings.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.findings.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  locations.  enrollResource</code></li>
<li><code dir="ltr" translate="no">auditmanager.locations.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.locations.list</code></li>
</ul>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.auditor" class="role-title add-link" data-text="Audit Manager Auditor Beta" tabindex="-1">Audit Manager Auditor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p>Allows creating and viewing an audit report.</p></td>
<td><p><code dir="ltr" translate="no">auditmanager.auditReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  auditReports.  generate</code></li>
<li><code dir="ltr" translate="no">auditmanager.auditReports.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.auditReports.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.auditSchedules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  create</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></li>
<li><code dir="ltr" translate="no">auditmanager.  auditSchedules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.  auditScopeReports.  generate</code></p>
<p><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.controlReports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.controls.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.findings.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.findings.list</code></li>
</ul>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.ccfAdmin" class="role-title add-link" data-text="Custom Compliance Framework Admin Beta" tabindex="-1">Custom Compliance Framework Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p>Full access to Custom Compliance Framework resources.</p></td>
<td><p><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  create</code></li>
<li><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  delete</code></li>
<li><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  get</code></li>
<li><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  list</code></li>
<li><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.locations.get</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.ccfViewer" class="role-title add-link" data-text="Custom Compliance Framework Viewer Beta" tabindex="-1">Custom Compliance Framework Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p>Allows viewing Custom Compliance Framework resources.</p></td>
<td><p><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  get</code></p>
<p><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  list</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.get</code></p>
<p><code dir="ltr" translate="no">auditmanager.locations.list</code></p>
<p><code dir="ltr" translate="no">auditmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">auditmanager.operations.get</code></li>
<li><code dir="ltr" translate="no">auditmanager.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
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
<td><h4 id="auditmanager.serviceAgent" class="role-title add-link" data-text="Audit Manager Auditing Service Agent" tabindex="-1">Audit Manager Auditing Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</p>
<p>Grants Audit Manager Service Agent access to various list/get rpcs of products to perform an audit.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">accessapproval.settings.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  list</code></p>
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
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.cryptoKeys.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyRings.list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.scans.get</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.list</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.firewallPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  list</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.securityPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.sslPolicies.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetSslProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">compute.vpnGateways.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.list</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.list</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">logging.buckets.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.constraints.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">privateca.certificates.list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagHolds.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">secretmanager.secrets.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  contentsecuritypolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivemcppolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.mcppolicy.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p></td>
</tr>
</tbody>
</table>

## Audit Manager permissions

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
<td><h4 id="auditmanager.auditReports.generate" class="permission-name add-link" data-text="auditmanager.auditReports.generate" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditReports.  generate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.auditReports.get" class="permission-name add-link" data-text="auditmanager.auditReports.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.auditReports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.auditReports.list" class="permission-name add-link" data-text="auditmanager.auditReports.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.auditReports.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.auditSchedules.create" class="permission-name add-link" data-text="auditmanager.auditSchedules.create" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditSchedules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.auditSchedules.get" class="permission-name add-link" data-text="auditmanager.auditSchedules.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditSchedules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.auditSchedules.list" class="permission-name add-link" data-text="auditmanager.auditSchedules.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditSchedules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.auditSchedules.update" class="permission-name add-link" data-text="auditmanager.auditSchedules.update" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditSchedules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.auditScopeReports.generate" class="permission-name add-link" data-text="auditmanager.auditScopeReports.generate" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  auditScopeReports.  generate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.billingSettings.get" class="permission-name add-link" data-text="auditmanager.billingSettings.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  billingSettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.controlReports.get" class="permission-name add-link" data-text="auditmanager.controlReports.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  controlReports.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.controlReports.list" class="permission-name add-link" data-text="auditmanager.controlReports.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  controlReports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.controls.list" class="permission-name add-link" data-text="auditmanager.controls.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.controls.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.customComplianceFrameworks.create" class="permission-name add-link" data-text="auditmanager.customComplianceFrameworks.create" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.customComplianceFrameworks.delete" class="permission-name add-link" data-text="auditmanager.customComplianceFrameworks.delete" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.customComplianceFrameworks.get" class="permission-name add-link" data-text="auditmanager.customComplianceFrameworks.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.customComplianceFrameworks.list" class="permission-name add-link" data-text="auditmanager.customComplianceFrameworks.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.customComplianceFrameworks.update" class="permission-name add-link" data-text="auditmanager.customComplianceFrameworks.update" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  customComplianceFrameworks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.findings.get" class="permission-name add-link" data-text="auditmanager.findings.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.findings.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.findings.list" class="permission-name add-link" data-text="auditmanager.findings.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.findings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.locations.enrollResource" class="permission-name add-link" data-text="auditmanager.locations.enrollResource" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  locations.  enrollResource</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.locations.get" class="permission-name add-link" data-text="auditmanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.locations.list" class="permission-name add-link" data-text="auditmanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.operations.get" class="permission-name add-link" data-text="auditmanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.operations.list" class="permission-name add-link" data-text="auditmanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfAdmin">Custom Compliance Framework Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.ccfViewer">Custom Compliance Framework Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.ccfViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="auditmanager.resourceEnrollmentStatuses.get" class="permission-name add-link" data-text="auditmanager.resourceEnrollmentStatuses.get" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="auditmanager.resourceEnrollmentStatuses.list" class="permission-name add-link" data-text="auditmanager.resourceEnrollmentStatuses.list" tabindex="-1"><code dir="ltr" translate="no">auditmanager.  resourceEnrollmentStatuses.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.admin">Audit Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.admin">Compliance Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.viewer">Compliance Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.auditor">Audit Manager Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.auditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
</tbody>
</table>
