---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist
title: Gemini Cloud Assist roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Gemini Cloud Assist. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Gemini Cloud Assist roles

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
<td>Gemini Cloud Assist Admin <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.admin</code> )</p>
<p>Grants the ability to administer Gemini Cloud Assist chat.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>appoptimize.locations.*</code></p>
<ul>
<li><code>appoptimize.locations.get</code></li>
<li><code>appoptimize.locations.list</code></li>
</ul>
<p><code>cloudaicompanion. dataSharingWithGoogleSettings.*</code></p>
<ul>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. create</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. delete</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. get</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. list</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. update</code></li>
</ul>
<p><code>cloudaicompanion. geminiGcpEnablementSettings.*</code></p>
<ul>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. create</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. delete</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. get</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. update</code></li>
</ul>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsCreate</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsDelete</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsGet</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsList</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsUpdate</code></p>
<p><code>cloudaicompanion.topics.create</code></p>
<p><code>cloudaicompanion.topics.delete</code></p>
<p><code>cloudaicompanion.topics.get</code></p>
<p><code>cloudaicompanion. topics. setIamPolicy</code></p>
<p><code>cloudaicompanion.topics.update</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
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
<p><code>designcenter. applicationTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. applicationTemplates.*</code></p>
<ul>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
</ul>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.*</code></p>
<ul>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
</ul>
<p><code>designcenter.connections.*</code></p>
<ul>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
</ul>
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
<p><code>geminicloudassist. agents. invoke</code></p>
<p><code>geminicloudassist. investigationRevisions. delete</code></p>
<p><code>geminicloudassist. investigationRevisions. get</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. delete</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist. investigations. setIamPolicy</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>mcp.tools.call</code></p>
<p><code>monitoring. alertPolicies. create</code></p>
<p><code>monitoring. alertPolicies. update</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage. multipartUploads. listParts</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Gemini Cloud Assist Editor <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.editor</code> )</p>
<p>Grants the ability to edit Gemini Cloud Assist chat.</p></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>appoptimize.locations.*</code></p>
<ul>
<li><code>appoptimize.locations.get</code></li>
<li><code>appoptimize.locations.list</code></li>
</ul>
<p><code>cloudaicompanion. dataSharingWithGoogleSettings.*</code></p>
<ul>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. create</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. delete</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. get</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. list</code></li>
<li><code>cloudaicompanion. dataSharingWithGoogleSettings. update</code></li>
</ul>
<p><code>cloudaicompanion. geminiGcpEnablementSettings.*</code></p>
<ul>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. create</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. delete</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. get</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></li>
<li><code>cloudaicompanion. geminiGcpEnablementSettings. update</code></li>
</ul>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsCreate</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsDelete</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsGet</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsList</code></p>
<p><code>cloudaicompanion. settingBindings. geminiGcpEnablementSettingsUpdate</code></p>
<p><code>cloudaicompanion.topics.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
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
<p><code>designcenter. applicationTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. applicationTemplates.*</code></p>
<ul>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
</ul>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.*</code></p>
<ul>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
</ul>
<p><code>designcenter.connections.*</code></p>
<ul>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
</ul>
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
<p><code>geminicloudassist. agents. invoke</code></p>
<p><code>geminicloudassist. investigationRevisions. delete</code></p>
<p><code>geminicloudassist. investigationRevisions. get</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. delete</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>mcp.tools.call</code></p>
<p><code>monitoring. alertPolicies. create</code></p>
<p><code>monitoring. alertPolicies. update</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage. multipartUploads. listParts</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Cloud Assist Investigation Owner <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p>Grants full administrative access to Gemini Cloud Assist investigations, except the ability to create a new investigation.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Investigation</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigationRevisions.*</code></p>
<ul>
<li><code>geminicloudassist. investigationRevisions. create</code></li>
<li><code>geminicloudassist. investigationRevisions. delete</code></li>
<li><code>geminicloudassist. investigationRevisions. get</code></li>
<li><code>geminicloudassist. investigationRevisions. list</code></li>
<li><code>geminicloudassist. investigationRevisions. run</code></li>
</ul>
<p><code>geminicloudassist. investigations. delete</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist. investigations. setIamPolicy</code></p>
<p><code>geminicloudassist. investigations. update</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>Gemini Cloud Assist User <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.user</code> )</p>
<p>Grants the ability to use Gemini Cloud Assist chat and create investigations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>apphub.applications.create</code></p>
<p><code>apphub.applications.delete</code></p>
<p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.applications.update</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>apphub. serviceProjectAttachments. list</code></p>
<p><code>appoptimize.locations.*</code></p>
<ul>
<li><code>appoptimize.locations.get</code></li>
<li><code>appoptimize.locations.list</code></li>
</ul>
<p><code>cloudaicompanion.companions.*</code></p>
<ul>
<li><code>cloudaicompanion. companions. generateChat</code></li>
<li><code>cloudaicompanion. companions. generateCode</code></li>
</ul>
<p><code>cloudaicompanion. entitlements. get</code></p>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. get</code></p>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></p>
<p><code>cloudaicompanion.instances.*</code></p>
<ul>
<li><code>cloudaicompanion. instances. completeCode</code></li>
<li><code>cloudaicompanion. instances. completeTask</code></li>
<li><code>cloudaicompanion. instances. exportMetrics</code></li>
<li><code>cloudaicompanion. instances. generateCode</code></li>
<li><code>cloudaicompanion. instances. generateText</code></li>
<li><code>cloudaicompanion. instances. queryEffectiveSetting</code></li>
<li><code>cloudaicompanion. instances. queryEffectiveSettingBindings</code></li>
</ul>
<p><code>cloudaicompanion. licenses. selfAssign</code></p>
<p><code>cloudaicompanion.topics.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudbuild.builds.list</code></p>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.export</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
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
<p><code>designcenter. applicationTemplateRevisions.*</code></p>
<ul>
<li><code>designcenter. applicationTemplateRevisions. delete</code></li>
<li><code>designcenter. applicationTemplateRevisions. get</code></li>
<li><code>designcenter. applicationTemplateRevisions. list</code></li>
</ul>
<p><code>designcenter. applicationTemplates.*</code></p>
<ul>
<li><code>designcenter. applicationTemplates. create</code></li>
<li><code>designcenter. applicationTemplates. delete</code></li>
<li><code>designcenter. applicationTemplates. get</code></li>
<li><code>designcenter. applicationTemplates. list</code></li>
<li><code>designcenter. applicationTemplates. update</code></li>
</ul>
<p><code>designcenter.applications.*</code></p>
<ul>
<li><code>designcenter. applications. create</code></li>
<li><code>designcenter. applications. delete</code></li>
<li><code>designcenter.applications.get</code></li>
<li><code>designcenter.applications.list</code></li>
<li><code>designcenter. applications. update</code></li>
</ul>
<p><code>designcenter. catalogTemplateRevisions. get</code></p>
<p><code>designcenter. catalogTemplateRevisions. list</code></p>
<p><code>designcenter. catalogTemplates. get</code></p>
<p><code>designcenter. catalogTemplates. list</code></p>
<p><code>designcenter.catalogs.get</code></p>
<p><code>designcenter.catalogs.list</code></p>
<p><code>designcenter.components.*</code></p>
<ul>
<li><code>designcenter.components.create</code></li>
<li><code>designcenter.components.delete</code></li>
<li><code>designcenter.components.get</code></li>
<li><code>designcenter.components.list</code></li>
<li><code>designcenter.components.update</code></li>
</ul>
<p><code>designcenter.connections.*</code></p>
<ul>
<li><code>designcenter. connections. create</code></li>
<li><code>designcenter. connections. delete</code></li>
<li><code>designcenter.connections.get</code></li>
<li><code>designcenter.connections.list</code></li>
<li><code>designcenter. connections. update</code></li>
</ul>
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
<p><code>geminicloudassist. agents. invoke</code></p>
<p><code>geminicloudassist. instances. explain</code></p>
<p><code>geminicloudassist. investigations. create</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>mcp.tools.call</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.multipartUploads.list</code></p>
<p><code>storage. multipartUploads. listParts</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Cloud Assist Viewer <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.viewer</code> )</p>
<p>Grants the ability to view Gemini Cloud Assist chat and create investigations.</p></td>
<td><p><code>apphub.applications.get</code></p>
<p><code>apphub.applications.list</code></p>
<p><code>apphub.locations.*</code></p>
<ul>
<li><code>apphub.locations.get</code></li>
<li><code>apphub.locations.list</code></li>
</ul>
<p><code>appoptimize.locations.*</code></p>
<ul>
<li><code>appoptimize.locations.get</code></li>
<li><code>appoptimize.locations.list</code></li>
</ul>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. get</code></p>
<p><code>cloudaicompanion. geminiGcpEnablementSettings. list</code></p>
<p><code>config.automigrationconfig.get</code></p>
<p><code>config.deployments.get</code></p>
<p><code>config. deployments. getIamPolicy</code></p>
<p><code>config.deployments.list</code></p>
<p><code>config.locations.*</code></p>
<ul>
<li><code>config.locations.get</code></li>
<li><code>config.locations.list</code></li>
</ul>
<p><code>config.operations.get</code></p>
<p><code>config.operations.list</code></p>
<p><code>config.previews.get</code></p>
<p><code>config.previews.list</code></p>
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
<p><code>geminicloudassist. investigationRevisions. get</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td>Gemini Cloud Assist Investigation Admin <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p>Grants full administrative access to Gemini Cloud Assist investigations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Investigation</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigationRevisions.*</code></p>
<ul>
<li><code>geminicloudassist. investigationRevisions. create</code></li>
<li><code>geminicloudassist. investigationRevisions. delete</code></li>
<li><code>geminicloudassist. investigationRevisions. get</code></li>
<li><code>geminicloudassist. investigationRevisions. list</code></li>
<li><code>geminicloudassist. investigationRevisions. run</code></li>
</ul>
<p><code>geminicloudassist. investigations.*</code></p>
<ul>
<li><code>geminicloudassist. investigations. create</code></li>
<li><code>geminicloudassist. investigations. delete</code></li>
<li><code>geminicloudassist. investigations. get</code></li>
<li><code>geminicloudassist. investigations. getIamPolicy</code></li>
<li><code>geminicloudassist. investigations. list</code></li>
<li><code>geminicloudassist. investigations. setIamPolicy</code></li>
<li><code>geminicloudassist. investigations. update</code></li>
</ul>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist.operations.*</code></p>
<ul>
<li><code>geminicloudassist. operations. cancel</code></li>
<li><code>geminicloudassist. operations. delete</code></li>
<li><code>geminicloudassist. operations. get</code></li>
<li><code>geminicloudassist. operations. list</code></li>
</ul>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Cloud Assist Investigation Creator <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p>Grants the ability to create a new Cloud Assist investigation, list existing investigations that you have permission to view, and check the status of investigations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigations. create</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>Gemini Cloud Assist Investigation Editor <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p>Grants the ability to list, view, edit, and run existing Gemini Cloud Assist investigations. The ability to create or delete an investigation is granted separately.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Investigation</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigationRevisions. create</code></p>
<p><code>geminicloudassist. investigationRevisions. get</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigationRevisions. run</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist. investigations. update</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="odd">
<td>Gemini Cloud Assist Investigation User <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p>Grants the ability to list existing investigations that you have permission to view and check the status of investigations. Access to individual investigations must be granted separately.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>Gemini Cloud Assist Investigation Viewer <sup>Beta</sup>
<p>( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p>Grants read-only access to existing Gemini Cloud Assist investigations, including revision information and IAM policy information for investigations.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Investigation</li>
</ul></td>
<td><p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudaicompanion. instances. queryEffectiveSetting</code></p>
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
<p><code>geminicloudassist. investigationRevisions. get</code></p>
<p><code>geminicloudassist. investigationRevisions. list</code></p>
<p><code>geminicloudassist. investigations. get</code></p>
<p><code>geminicloudassist. investigations. getIamPolicy</code></p>
<p><code>geminicloudassist. investigations. list</code></p>
<p><code>geminicloudassist.locations.*</code></p>
<ul>
<li><code>geminicloudassist. locations. get</code></li>
<li><code>geminicloudassist. locations. list</code></li>
</ul>
<p><code>geminicloudassist. operations. get</code></p>
<p><code>geminicloudassist. operations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Gemini Cloud Assist permissions

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
<td><code>geminicloudassist. agents. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioUser">BigQuery Studio User</a> ( <code>roles/ bigquery.studioUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.user">Gemini for Google Cloud User</a> ( <code>roles/ cloudaicompanion.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.user">Discovery Engine User</a> ( <code>roles/ discoveryengine.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.codeToolsUser">Gemini Code Assist Tools User</a> ( <code>roles/ cloudaicompanion.codeToolsUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudaicompanion#cloudaicompanion.individualUser">Gemini for Google Cloud individual User</a> ( <code>roles/ cloudaicompanion.individualUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.agentspaceUser">Gemini Enterprise User</a> ( <code>roles/ discoveryengine.agentspaceUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.podcastApiUser">Podcast API User</a> ( <code>roles/ discoveryengine.podcastApiUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.dataScientist">Data Scientist</a> ( <code>roles/ iam.dataScientist</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. instances. explain</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigationRevisions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigationRevisions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigationRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigationRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigationRevisions. run</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigations. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigations. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. investigations. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. investigations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.admin">Gemini Cloud Assist Admin</a> ( <code>roles/ geminicloudassist.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.editor">Gemini Cloud Assist Editor</a> ( <code>roles/ geminicloudassist.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.viewer">Gemini Cloud Assist Viewer</a> ( <code>roles/ geminicloudassist.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.serviceAgent">Chronicle Service Agent</a> ( <code>roles/ chronicle.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. operations. cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. operations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>geminicloudassist. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>geminicloudassist. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationOwner">Gemini Cloud Assist Investigation Owner</a> ( <code>roles/ geminicloudassist.investigationOwner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.user">Gemini Cloud Assist User</a> ( <code>roles/ geminicloudassist.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationAdmin">Gemini Cloud Assist Investigation Admin</a> ( <code>roles/ geminicloudassist.investigationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationCreator">Gemini Cloud Assist Investigation Creator</a> ( <code>roles/ geminicloudassist.investigationCreator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationEditor">Gemini Cloud Assist Investigation Editor</a> ( <code>roles/ geminicloudassist.investigationEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationUser">Gemini Cloud Assist Investigation User</a> ( <code>roles/ geminicloudassist.investigationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/geminicloudassist#geminicloudassist.investigationViewer">Gemini Cloud Assist Investigation Viewer</a> ( <code>roles/ geminicloudassist.investigationViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
