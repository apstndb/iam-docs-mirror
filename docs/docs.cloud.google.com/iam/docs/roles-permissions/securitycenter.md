---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/securitycenter
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter
title: Security Command Center roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Security Command Center. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Security Command Center roles

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
<td><h4 id="securitycenter.admin" class="role-title add-link" data-text="Security Center Admin" tabindex="-1">Security Center Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p>Admin(super user) access to security center</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">aiplatform.artifacts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredoss.config.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.customers.create</code></li>
<li><code dir="ltr" translate="no">assuredoss.locations.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.locations.list</code></li>
<li><code dir="ltr" translate="no">assuredoss.metadata.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.metadata.list</code></li>
<li><code dir="ltr" translate="no">assuredoss.operations.cancel</code></li>
<li><code dir="ltr" translate="no">assuredoss.operations.delete</code></li>
<li><code dir="ltr" translate="no">assuredoss.operations.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">auditmanager.auditReports.*</code></p>
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
<p><code dir="ltr" translate="no">auditmanager.findings.list</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchEnrichmentResourceOwners</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  generate</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  auditReports.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  auditScopeReports.  generate</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  billingSettings.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  update</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlPredictions.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  update</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cmEnrollments.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  cmEnrollments.  update</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controlComplianceSummaries.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controlReports.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  controls.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  findingSummaries.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  findings.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkAudits.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceReports.  aggregate</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceReports.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkComplianceSummaries.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  update</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  update</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  enrollResource</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  locations.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  operations.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecuritycompliance.  resourceEnrollmentStatuses.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsecurityscanner.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  crawledurls.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  getSummary</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  stop</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.scans.get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.scans.run</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">dlp.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  create</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  update</code></li>
<li><code dir="ltr" translate="no">dlp.charts.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
<li><code dir="ltr" translate="no">dlp.connections.create</code></li>
<li><code dir="ltr" translate="no">dlp.connections.delete</code></li>
<li><code dir="ltr" translate="no">dlp.connections.get</code></li>
<li><code dir="ltr" translate="no">dlp.connections.list</code></li>
<li><code dir="ltr" translate="no">dlp.connections.search</code></li>
<li><code dir="ltr" translate="no">dlp.connections.update</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.update</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.create</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.get</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.list</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></li>
<li><code dir="ltr" translate="no">dlp.inspectFindings.list</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.update</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.list</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.update</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.list</code></li>
<li><code dir="ltr" translate="no">dlp.kms.encrypt</code></li>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.create</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.delete</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.update</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.update</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dspm.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dspm.  locations.  computeAggregation</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDataGovernanceAnalytics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDspmGovernedProjects</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchGovernedResourceMetrics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchLineageConnections</code></li>
<li><code dir="ltr" translate="no">dspm.locations.get</code></li>
<li><code dir="ltr" translate="no">dspm.locations.list</code></li>
<li><code dir="ltr" translate="no">dspm.operations.cancel</code></li>
<li><code dir="ltr" translate="no">dspm.operations.delete</code></li>
<li><code dir="ltr" translate="no">dspm.operations.get</code></li>
<li><code dir="ltr" translate="no">dspm.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iam.serviceAccountKeys.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.create</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">modelarmor.floorSettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.  floorSettings.  computeEffectiveFloorSetting</code></li>
<li><code dir="ltr" translate="no">modelarmor.floorSettings.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.  floorSettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.locations.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">modelarmor.templates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">modelarmor.templates.create</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.delete</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.get</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.list</code></li>
<li><code dir="ltr" translate="no">modelarmor.templates.update</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeInput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeOutput</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToSanitizeUserPrompt</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeModelResponse</code></li>
<li><code dir="ltr" translate="no">modelarmor.  templates.  useToStreamSanitizeUserPrompt</code></li>
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
<p><code dir="ltr" translate="no">opsconfigmonitoring.  resourceMetadata.  list</code></p>
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.create</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.update</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.assets.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.assets.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></li>
<li><code dir="ltr" translate="no">securitycenter.  assets.  runDiscovery</code></li>
<li><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  billingtier.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  exposurepathexplan.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findingexternalsystems.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  bulkMuteUpdate</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.export</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setMute</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setState</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setWorkflowState</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findingsecuritymarks.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.mute</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.riskreports.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  riskreports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  test</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.simulations.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.sources.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  sources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securitycenter.sources.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  sources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securitycenter.sources.update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  update</code></li>
<li><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.adminEditor" class="role-title add-link" data-text="Security Center Admin Editor" tabindex="-1">Security Center Admin Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p>Admin Read-write access to security center</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">aiplatform.artifacts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.config.get</code></p>
<p><code dir="ltr" translate="no">assuredoss.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredoss.locations.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredoss.metadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredoss.metadata.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.metadata.list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredoss.operations.get</code></p>
<p><code dir="ltr" translate="no">assuredoss.operations.list</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchEnrichmentResourceOwners</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
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
<p><code dir="ltr" translate="no">cloudsecurityscanner.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  crawledurls.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  getSummary</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  stop</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  create</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  delete</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.scans.get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.scans.run</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dspm.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dspm.  locations.  computeAggregation</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDataGovernanceAnalytics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDspmGovernedProjects</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchGovernedResourceMetrics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchLineageConnections</code></li>
<li><code dir="ltr" translate="no">dspm.locations.get</code></li>
<li><code dir="ltr" translate="no">dspm.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dspm.operations.get</code></p>
<p><code dir="ltr" translate="no">dspm.operations.list</code></p>
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
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.assets.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.assets.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></li>
<li><code dir="ltr" translate="no">securitycenter.  assets.  runDiscovery</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></li>
</ul>
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
<p><code dir="ltr" translate="no">securitycenter.  exposurepathexplan.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findingexternalsystems.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  findings.  bulkMuteUpdate</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.export</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setMute</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setState</code></li>
<li><code dir="ltr" translate="no">securitycenter.  findings.  setWorkflowState</code></li>
<li><code dir="ltr" translate="no">securitycenter.findings.update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  findingsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.issues.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.mute</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.muteconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  test</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.simulations.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
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
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p>
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
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.adminViewer" class="role-title add-link" data-text="Security Center Admin Viewer" tabindex="-1">Security Center Admin Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Admin Read access to security center</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">aiplatform.artifacts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  attachments.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  dockerimages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  dockerimages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.files.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.locations.get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  mavenartifacts.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.npmpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  npmpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.packages.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.packages.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectconfigs.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  pythonpackages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  get</code></li>
<li><code dir="ltr" translate="no">artifactregistry.  pythonpackages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  exportArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  readViaVirtualRepository</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.rules.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.tags.list</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.versions.list</code></p>
<p><code dir="ltr" translate="no">assuredoss.config.get</code></p>
<p><code dir="ltr" translate="no">assuredoss.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredoss.locations.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredoss.metadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">assuredoss.metadata.get</code></li>
<li><code dir="ltr" translate="no">assuredoss.metadata.list</code></li>
</ul>
<p><code dir="ltr" translate="no">assuredoss.operations.get</code></p>
<p><code dir="ltr" translate="no">assuredoss.operations.list</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchEnrichmentResourceOwners</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
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
<p><code dir="ltr" translate="no">cloudsecurityscanner.  crawledurls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.results.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  get</code></li>
<li><code dir="ltr" translate="no">cloudsecurityscanner.  results.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  getSummary</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scanruns.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.scans.get</code></p>
<p><code dir="ltr" translate="no">cloudsecurityscanner.  scans.  list</code></p>
<p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">dspm.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dspm.  locations.  computeAggregation</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDataGovernanceAnalytics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchDspmGovernedProjects</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchGovernedResourceMetrics</code></li>
<li><code dir="ltr" translate="no">dspm.  locations.  fetchLineageConnections</code></li>
<li><code dir="ltr" translate="no">dspm.locations.get</code></li>
<li><code dir="ltr" translate="no">dspm.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dspm.operations.get</code></p>
<p><code dir="ltr" translate="no">dspm.operations.list</code></p>
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
<p><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.get</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.list</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></p>
<p><code dir="ltr" translate="no">pubsub.schemas.validate</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.get</code></p>
<p><code dir="ltr" translate="no">pubsub.snapshots.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">pubsub.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.get</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.list</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
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
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  test</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.simulations.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
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
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  get</code></li>
<li><code dir="ltr" translate="no">securityposture.  postureTemplates.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.list</code></p>
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
<p><code dir="ltr" translate="no">stackdriver.  resourceMetadata.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.assetSecurityMarksWriter" class="role-title add-link" data-text="Security Center Asset Security Marks Writer" tabindex="-1">Security Center Asset Security Marks Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.assetSecurityMarksWriter</code> )</p>
<p>Write access to asset security marks</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.assetsDiscoveryRunner" class="role-title add-link" data-text="Security Center Assets Discovery Runner" tabindex="-1">Security Center Assets Discovery Runner</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.assetsDiscoveryRunner</code> )</p>
<p>Run asset discovery access to assets</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  assets.  runDiscovery</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.assetsViewer" class="role-title add-link" data-text="Security Center Assets Viewer" tabindex="-1">Security Center Assets Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p>Read access to assets</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  exportIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryAccessPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryOSInventories</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchEnrichmentResourceOwners</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.attackPathsViewer" class="role-title add-link" data-text="Security Center Attack Paths Reader" tabindex="-1">Security Center Attack Paths Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.attackPathsViewer</code> )</p>
<p>Read access to security center attack paths</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  exposurepathexplan.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.bigQueryExportsEditor" class="role-title add-link" data-text="Security Center BigQuery Exports Editor" tabindex="-1">Security Center BigQuery Exports Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p>Read-Write access to security center BigQuery Exports</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.findings.export</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.bigQueryExportsViewer" class="role-title add-link" data-text="Security Center BigQuery Exports Viewer" tabindex="-1">Security Center BigQuery Exports Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p>Read access to security center BigQuery Exports</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.complianceReportsViewer" class="role-title add-link" data-text="Security Center Compliance Reports Viewer Beta" tabindex="-1">Security Center Compliance Reports Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.complianceReportsViewer</code> )</p>
<p>Read access to security center compliance reports</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.complianceSnapshotsViewer" class="role-title add-link" data-text="Security Center Compliance Snapshots Viewer Beta" tabindex="-1">Security Center Compliance Snapshots Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.complianceSnapshotsViewer</code> )</p>
<p>Read access to security center compliance snapshots</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.externalSystemsEditor" class="role-title add-link" data-text="Security Center External Systems Editor" tabindex="-1">Security Center External Systems Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.externalSystemsEditor</code> )</p>
<p>Write access to security center external systems</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findingexternalsystems.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingSecurityMarksWriter" class="role-title add-link" data-text="Security Center Finding Security Marks Writer" tabindex="-1">Security Center Finding Security Marks Writer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingSecurityMarksWriter</code> )</p>
<p>Write access to finding security marks</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findingsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findingsBulkMuteEditor" class="role-title add-link" data-text="Security Center Findings Bulk Mute Editor" tabindex="-1">Security Center Findings Bulk Mute Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsBulkMuteEditor</code> )</p>
<p>Ability to mute findings in bulk</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findings.  bulkMuteUpdate</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingsEditor" class="role-title add-link" data-text="Security Center Findings Editor" tabindex="-1">Security Center Findings Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p>Read-write access to findings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  bulkMuteUpdate</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  setMute</code></p>
<p><code dir="ltr" translate="no">securitycenter.  findings.  setState</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.update</code></p>
<p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.issues.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.mute</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findingsMuteSetter" class="role-title add-link" data-text="Security Center Findings Mute Setter" tabindex="-1">Security Center Findings Mute Setter</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsMuteSetter</code> )</p>
<p>Set mute access to findings</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findings.  setMute</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingsStateSetter" class="role-title add-link" data-text="Security Center Findings State Setter" tabindex="-1">Security Center Findings State Setter</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsStateSetter</code> )</p>
<p>Set state access to findings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findings.  setState</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findingsViewer" class="role-title add-link" data-text="Security Center Findings Viewer" tabindex="-1">Security Center Findings Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Read access to findings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></p>
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
<p><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingsWorkflowStateSetter" class="role-title add-link" data-text="Security Center Findings Workflow State Setter Beta" tabindex="-1">Security Center Findings Workflow State Setter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.findingsWorkflowStateSetter</code> )</p>
<p>Set workflow state access to findings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  findings.  setWorkflowState</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.issuesEditor" class="role-title add-link" data-text="Security Center Issues Editor" tabindex="-1">Security Center Issues Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p>Write access to security center issues</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.issues.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.issues.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.group</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></li>
<li><code dir="ltr" translate="no">securitycenter.issues.mute</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.issuesViewer" class="role-title add-link" data-text="Security Center Issues Viewer" tabindex="-1">Security Center Issues Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Read access to security center issues</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.graphs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.graphs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.graphs.query</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.issues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.group</code></p>
<p><code dir="ltr" translate="no">securitycenter.issues.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.muteConfigsEditor" class="role-title add-link" data-text="Security Center Mute Configurations Editor" tabindex="-1">Security Center Mute Configurations Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p>Read-Write access to security center mute configurations</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.muteconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.muteConfigsViewer" class="role-title add-link" data-text="Security Center Mute Configurations Viewer" tabindex="-1">Security Center Mute Configurations Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.muteConfigsViewer</code> )</p>
<p>Read access to security center mute configurations</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.notificationConfigEditor" class="role-title add-link" data-text="Security Center Notification Configurations Editor" tabindex="-1">Security Center Notification Configurations Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p>Write access to notification configurations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  notificationconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.notificationConfigViewer" class="role-title add-link" data-text="Security Center Notification Configurations Viewer" tabindex="-1">Security Center Notification Configurations Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.notificationConfigViewer</code> )</p>
<p>Read access to notification configurations</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.resourceValueConfigsEditor" class="role-title add-link" data-text="Security Center Resource Value Configurations Editor" tabindex="-1">Security Center Resource Value Configurations Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p>
<p>Read-Write access to security center resource value configurations</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.resourceValueConfigsViewer" class="role-title add-link" data-text="Security Center Resource Value Configurations Viewer" tabindex="-1">Security Center Resource Value Configurations Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsViewer</code> )</p>
<p>Read access to security center resource value configurations</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.riskReportsViewer" class="role-title add-link" data-text="Security Center Risk Reports Viewer" tabindex="-1">Security Center Risk Reports Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.riskReportsViewer</code> )</p>
<p>Read access to security center risk reports</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.riskreports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.riskreports.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  riskreports.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityHealthAnalyticsCustomModulesTester" class="role-title add-link" data-text="Security Health Analytics Custom Modules Tester" tabindex="-1">Security Health Analytics Custom Modules Tester</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p>
<p>Test access to Security Health Analytics Custom Modules</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  test</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.settingsAdmin" class="role-title add-link" data-text="Security Center Settings Admin" tabindex="-1">Security Center Settings Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p>Admin(super user) access to security center settings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  billingtier.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.findings.export</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.muteconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  create</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.settingsEditor" class="role-title add-link" data-text="Security Center Settings Editor" tabindex="-1">Security Center Settings Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p>Read-Write access to security center settings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  billingtier.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.findings.export</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.muteconfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securitycentersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  create</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  billingMetadata.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveEventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  eventThreatDetectionCustomModules.  validate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  locations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  operations.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  migrate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  activate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkActivationOperation</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkEligibility</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  checkOnboardingStatus</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  generateServiceAccounts</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityCommandCenter.  update</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  test</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.settingsViewer" class="role-title add-link" data-text="Security Center Settings Viewer" tabindex="-1">Security Center Settings Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Read access to security center settings</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></p>
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
<p><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></p>
<p><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></p>
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
<tr class="odd">
<td><h4 id="securitycenter.simulationsViewer" class="role-title add-link" data-text="Security Center Simulations Reader" tabindex="-1">Security Center Simulations Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.simulationsViewer</code> )</p>
<p>Read access to security center simulations</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.simulations.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.sourcesAdmin" class="role-title add-link" data-text="Security Center Sources Admin" tabindex="-1">Security Center Sources Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p>Admin access to sources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.sources.get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  sources.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">securitycenter.sources.list</code></li>
<li><code dir="ltr" translate="no">securitycenter.  sources.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">securitycenter.sources.update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.sourcesEditor" class="role-title add-link" data-text="Security Center Sources Editor" tabindex="-1">Security Center Sources Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p>Read-write access to sources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Organization</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.sourcesViewer" class="role-title add-link" data-text="Security Center Sources Viewer" tabindex="-1">Security Center Sources Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.sourcesViewer</code> )</p>
<p>Read access to sources</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.valuedResourcesViewer" class="role-title add-link" data-text="Security Center Valued Resources Reader" tabindex="-1">Security Center Valued Resources Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.valuedResourcesViewer</code> )</p>
<p>Read access to security center valued resources</p></td>
<td><p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p></td>
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
<td><h4 id="securitycenter.attackSurfaceManagementScannerServiceAgent" class="role-title add-link" data-text="Attack Surface Management Scanner Service Agent" tabindex="-1">Attack Surface Management Scanner Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.attackSurfaceManagementScannerServiceAgent</code> )</p>
<p>Gives Mandiant Attack Surface Management the ability to scan Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">apigateway.apiconfigs.get</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.automationServiceAgent" class="role-title add-link" data-text="Security Center Automation Service Agent" tabindex="-1">Security Center Automation Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.automationServiceAgent</code> )</p>
<p>Security Center automation service agent can configure GCP resources to enable security scanning.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudasset.feeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudasset.feeds.create</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.delete</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.get</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.list</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.folders.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.folders.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.controlServiceAgent" class="role-title add-link" data-text="Security Center Control Service Agent" tabindex="-1">Security Center Control Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</p>
<p>Security Center Control service agent can monitor and configure GCP resources and import security findings.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.feeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudasset.feeds.create</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.delete</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.get</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.list</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.simulations.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.integrationExecutorServiceAgent" class="role-title add-link" data-text="Security Center Integration Executor Service Agent" tabindex="-1">Security Center Integration Executor Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.integrationExecutorServiceAgent</code> )</p>
<p>Gives Security Center access to execute Integrations.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">integrations.  securityExecutions.  cancel</code></p>
<p><code dir="ltr" translate="no">integrations.  securityExecutions.  list</code></p>
<p><code dir="ltr" translate="no">integrations.  securityIntegrations.  invoke</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.notificationServiceAgent" class="role-title add-link" data-text="Security Center Notification Service Agent" tabindex="-1">Security Center Notification Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.notificationServiceAgent</code> )</p>
<p>Security Center service agent can publish notifications to Pub/Sub topics.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">pubsub.topics.publish</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityHealthAnalyticsServiceAgent" class="role-title add-link" data-text="Security Health Analytics Service Agent" tabindex="-1">Security Health Analytics Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</p>
<p>Security Health Analytics service agent can scan GCP resource metadata to find security vulnerabilities.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.feeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudasset.feeds.create</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.delete</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.get</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.list</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
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
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityResponseServiceAgent" class="role-title add-link" data-text="Google Cloud Security Response Service Agent" tabindex="-1">Google Cloud Security Response Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.securityResponseServiceAgent</code> )</p>
<p>Gives Playbook Runner permissions to execute all Google authored Playbooks. This role will keep evolving as we add more playbooks</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteAccessConfig</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.publish</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.serviceAgent" class="role-title add-link" data-text="Security Center Service Agent" tabindex="-1">Security Center Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</p>
<p>Security Center service agent can scan GCP resources and import security scans.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">binaryauthorization.policy.get</code></p>
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
<p><code dir="ltr" translate="no">cloudasset.feeds.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudasset.feeds.create</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.delete</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.get</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.list</code></li>
<li><code dir="ltr" translate="no">cloudasset.feeds.update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  list</code></p>
<p><code dir="ltr" translate="no">cloudasset.  othercloudconnections.  verify</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.list</code></p>
<p><code dir="ltr" translate="no">compute.disks.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.get</code></p>
<p><code dir="ltr" translate="no">iam.denypolicies.list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPoolProviders.  list</code></p>
<p><code dir="ltr" translate="no">iam.googleapis.  com/workloadIdentityPools.  list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">monitoring.alertPolicies.list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.assets.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.findings.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></p>
<p><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></p>
<p><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></p>
<p><code dir="ltr" translate="no">securitycenter.simulations.get</code></p>
<p><code dir="ltr" translate="no">securitycenter.sources.list</code></p>
<p><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></li>
<li><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  delete</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  list</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  simulate</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  update</code></p>
<p><code dir="ltr" translate="no">serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></li>
<li><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.disable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.list</code></p></td>
</tr>
</tbody>
</table>

## Security Command Center permissions

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
<td><h4 id="securitycenter.assets.group" class="permission-name add-link" data-text="securitycenter.assets.group" tabindex="-1"><code dir="ltr" translate="no">securitycenter.assets.group</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.assets.list" class="permission-name add-link" data-text="securitycenter.assets.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.assets.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.assets.listAssetPropertyNames" class="permission-name add-link" data-text="securitycenter.assets.listAssetPropertyNames" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  assets.  listAssetPropertyNames</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.assets.runDiscovery" class="permission-name add-link" data-text="securitycenter.assets.runDiscovery" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  assets.  runDiscovery</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsDiscoveryRunner">Security Center Assets Discovery Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsDiscoveryRunner</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.assetsecuritymarks.update" class="permission-name add-link" data-text="securitycenter.assetsecuritymarks.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  assetsecuritymarks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetSecurityMarksWriter">Security Center Asset Security Marks Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetSecurityMarksWriter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.attackpaths.list" class="permission-name add-link" data-text="securitycenter.attackpaths.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  attackpaths.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackPathsViewer">Security Center Attack Paths Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.attackPathsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.bigQueryExports.create" class="permission-name add-link" data-text="securitycenter.bigQueryExports.create" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.bigQueryExports.delete" class="permission-name add-link" data-text="securitycenter.bigQueryExports.delete" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.bigQueryExports.get" class="permission-name add-link" data-text="securitycenter.bigQueryExports.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.bigQueryExports.list" class="permission-name add-link" data-text="securitycenter.bigQueryExports.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsViewer">Security Center BigQuery Exports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.bigQueryExports.update" class="permission-name add-link" data-text="securitycenter.bigQueryExports.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  bigQueryExports.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.billingtier.update" class="permission-name add-link" data-text="securitycenter.billingtier.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  billingtier.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.complianceReports.aggregate" class="permission-name add-link" data-text="securitycenter.complianceReports.aggregate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  complianceReports.  aggregate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.complianceReportsViewer">Security Center Compliance Reports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.complianceReportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.complianceSnapshotsViewer">Security Center Compliance Snapshots Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.complianceSnapshotsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.compliancesnapshots.list" class="permission-name add-link" data-text="securitycenter.compliancesnapshots.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  compliancesnapshots.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.complianceSnapshotsViewer">Security Center Compliance Snapshots Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.complianceSnapshotsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.containerthreatdetectionsettings.calculate" class="permission-name add-link" data-text="securitycenter.containerthreatdetectionsettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.containerthreatdetectionsettings.get" class="permission-name add-link" data-text="securitycenter.containerthreatdetectionsettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.containerthreatdetectionsettings.update" class="permission-name add-link" data-text="securitycenter.containerthreatdetectionsettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  containerthreatdetectionsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.effectivesecurityhealthanalyticscustommodules.get" class="permission-name add-link" data-text="securitycenter.effectivesecurityhealthanalyticscustommodules.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.effectivesecurityhealthanalyticscustommodules.list" class="permission-name add-link" data-text="securitycenter.effectivesecurityhealthanalyticscustommodules.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  effectivesecurityhealthanalyticscustommodules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.eventthreatdetectionsettings.calculate" class="permission-name add-link" data-text="securitycenter.eventthreatdetectionsettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.eventthreatdetectionsettings.get" class="permission-name add-link" data-text="securitycenter.eventthreatdetectionsettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.eventthreatdetectionsettings.update" class="permission-name add-link" data-text="securitycenter.eventthreatdetectionsettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  eventthreatdetectionsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.exposurepathexplan.get" class="permission-name add-link" data-text="securitycenter.exposurepathexplan.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  exposurepathexplan.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackPathsViewer">Security Center Attack Paths Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.attackPathsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findingexplanations.get" class="permission-name add-link" data-text="securitycenter.findingexplanations.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findingexplanations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingexternalsystems.update" class="permission-name add-link" data-text="securitycenter.findingexternalsystems.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findingexternalsystems.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.externalSystemsEditor">Security Center External Systems Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.externalSystemsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findings.bulkMuteUpdate" class="permission-name add-link" data-text="securitycenter.findings.bulkMuteUpdate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findings.  bulkMuteUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsBulkMuteEditor">Security Center Findings Bulk Mute Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsBulkMuteEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findings.export" class="permission-name add-link" data-text="securitycenter.findings.export" tabindex="-1"><code dir="ltr" translate="no">securitycenter.findings.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.bigQueryExportsEditor">Security Center BigQuery Exports Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.bigQueryExportsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findings.group" class="permission-name add-link" data-text="securitycenter.findings.group" tabindex="-1"><code dir="ltr" translate="no">securitycenter.findings.group</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findings.list" class="permission-name add-link" data-text="securitycenter.findings.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.findings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityResponseServiceAgent">Google Cloud Security Response Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityResponseServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findings.listFindingPropertyNames" class="permission-name add-link" data-text="securitycenter.findings.listFindingPropertyNames" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findings.  listFindingPropertyNames</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findings.setMute" class="permission-name add-link" data-text="securitycenter.findings.setMute" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findings.  setMute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsMuteSetter">Security Center Findings Mute Setter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsMuteSetter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findings.setState" class="permission-name add-link" data-text="securitycenter.findings.setState" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findings.  setState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsStateSetter">Security Center Findings State Setter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsStateSetter</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findings.setWorkflowState" class="permission-name add-link" data-text="securitycenter.findings.setWorkflowState" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findings.  setWorkflowState</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsWorkflowStateSetter">Security Center Findings Workflow State Setter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsWorkflowStateSetter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.findings.update" class="permission-name add-link" data-text="securitycenter.findings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.findings.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.findingsecuritymarks.update" class="permission-name add-link" data-text="securitycenter.findingsecuritymarks.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  findingsecuritymarks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingSecurityMarksWriter">Security Center Finding Security Marks Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingSecurityMarksWriter</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.graphs.get" class="permission-name add-link" data-text="securitycenter.graphs.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.graphs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.graphs.query" class="permission-name add-link" data-text="securitycenter.graphs.query" tabindex="-1"><code dir="ltr" translate="no">securitycenter.graphs.query</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.integratedvulnerabilityscannersettings.calculate" class="permission-name add-link" data-text="securitycenter.integratedvulnerabilityscannersettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.integratedvulnerabilityscannersettings.get" class="permission-name add-link" data-text="securitycenter.integratedvulnerabilityscannersettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.integratedvulnerabilityscannersettings.update" class="permission-name add-link" data-text="securitycenter.integratedvulnerabilityscannersettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  integratedvulnerabilityscannersettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.issues.get" class="permission-name add-link" data-text="securitycenter.issues.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.issues.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.issues.group" class="permission-name add-link" data-text="securitycenter.issues.group" tabindex="-1"><code dir="ltr" translate="no">securitycenter.issues.group</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.issues.list" class="permission-name add-link" data-text="securitycenter.issues.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.issues.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.issues.listFilterValues" class="permission-name add-link" data-text="securitycenter.issues.listFilterValues" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  issues.  listFilterValues</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesViewer">Security Center Issues Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.issues.mute" class="permission-name add-link" data-text="securitycenter.issues.mute" tabindex="-1"><code dir="ltr" translate="no">securitycenter.issues.mute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.issuesEditor">Security Center Issues Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.issuesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.muteconfigs.create" class="permission-name add-link" data-text="securitycenter.muteconfigs.create" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  muteconfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsEditor">Security Center Mute Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.muteconfigs.delete" class="permission-name add-link" data-text="securitycenter.muteconfigs.delete" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  muteconfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsEditor">Security Center Mute Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.muteconfigs.get" class="permission-name add-link" data-text="securitycenter.muteconfigs.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.muteconfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsEditor">Security Center Mute Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsViewer">Security Center Mute Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.muteconfigs.list" class="permission-name add-link" data-text="securitycenter.muteconfigs.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  muteconfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsEditor">Security Center Mute Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsViewer">Security Center Mute Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.muteconfigs.update" class="permission-name add-link" data-text="securitycenter.muteconfigs.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  muteconfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.muteConfigsEditor">Security Center Mute Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.muteConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.notificationconfig.create" class="permission-name add-link" data-text="securitycenter.notificationconfig.create" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  notificationconfig.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.notificationconfig.delete" class="permission-name add-link" data-text="securitycenter.notificationconfig.delete" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  notificationconfig.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.notificationconfig.get" class="permission-name add-link" data-text="securitycenter.notificationconfig.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  notificationconfig.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigViewer">Security Center Notification Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.notificationconfig.list" class="permission-name add-link" data-text="securitycenter.notificationconfig.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  notificationconfig.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigViewer">Security Center Notification Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.notificationconfig.update" class="permission-name add-link" data-text="securitycenter.notificationconfig.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  notificationconfig.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.organizationsettings.get" class="permission-name add-link" data-text="securitycenter.organizationsettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  organizationsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsServiceAgent">Security Health Analytics Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.organizationsettings.update" class="permission-name add-link" data-text="securitycenter.organizationsettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  organizationsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.rapidvulnerabilitydetectionsettings.calculate" class="permission-name add-link" data-text="securitycenter.rapidvulnerabilitydetectionsettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.rapidvulnerabilitydetectionsettings.get" class="permission-name add-link" data-text="securitycenter.rapidvulnerabilitydetectionsettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.rapidvulnerabilitydetectionsettings.update" class="permission-name add-link" data-text="securitycenter.rapidvulnerabilitydetectionsettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  rapidvulnerabilitydetectionsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.resourcevalueconfigs.create" class="permission-name add-link" data-text="securitycenter.resourcevalueconfigs.create" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.resourcevalueconfigs.delete" class="permission-name add-link" data-text="securitycenter.resourcevalueconfigs.delete" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.resourcevalueconfigs.get" class="permission-name add-link" data-text="securitycenter.resourcevalueconfigs.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsViewer">Security Center Resource Value Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.resourcevalueconfigs.list" class="permission-name add-link" data-text="securitycenter.resourcevalueconfigs.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsViewer">Security Center Resource Value Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.resourcevalueconfigs.update" class="permission-name add-link" data-text="securitycenter.resourcevalueconfigs.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  resourcevalueconfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.resourceValueConfigsEditor">Security Center Resource Value Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.resourceValueConfigsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.riskreports.get" class="permission-name add-link" data-text="securitycenter.riskreports.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.riskreports.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.riskReportsViewer">Security Center Risk Reports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.riskReportsViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.riskreports.list" class="permission-name add-link" data-text="securitycenter.riskreports.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  riskreports.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.riskReportsViewer">Security Center Risk Reports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.riskReportsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securitycentersettings.get" class="permission-name add-link" data-text="securitycenter.securitycentersettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.editor">Securitycentermanagement Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.viewer">Security Center Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsViewer">Security Center Management Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securitycentersettings.update" class="permission-name add-link" data-text="securitycenter.securitycentersettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securitycentersettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.admin">Security Center Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycentermanagement#securitycentermanagement.settingsEditor">Security Center Management Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycentermanagement.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.create" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.create" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.delete" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.delete" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.get" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.list" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.simulate" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.simulate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  simulate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.test" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.test" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  test</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.securityHealthAnalyticsCustomModulesTester">Security Health Analytics Custom Modules Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.securityHealthAnalyticsCustomModulesTester</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityhealthanalyticscustommodules.update" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticscustommodules.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticscustommodules.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityhealthanalyticssettings.calculate" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticssettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.securityhealthanalyticssettings.get" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticssettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.securityhealthanalyticssettings.update" class="permission-name add-link" data-text="securitycenter.securityhealthanalyticssettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.admin">Security Posture Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securityposture#securityposture.postureDeployer">Security Posture Deployer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securityposture.postureDeployer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.serviceAgent">DSPM Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.simulations.get" class="permission-name add-link" data-text="securitycenter.simulations.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.simulations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.simulationsViewer">Security Center Simulations Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.simulationsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.sources.get" class="permission-name add-link" data-text="securitycenter.sources.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.sources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesViewer">Security Center Sources Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.sources.getIamPolicy" class="permission-name add-link" data-text="securitycenter.sources.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  sources.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.sources.list" class="permission-name add-link" data-text="securitycenter.sources.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.sources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesViewer">Security Center Sources Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarServiceAgent">Chronicle SOAR Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.sources.setIamPolicy" class="permission-name add-link" data-text="securitycenter.sources.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  sources.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.sources.update" class="permission-name add-link" data-text="securitycenter.sources.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.sources.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.serviceAgent">Secured Landing Zone Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.subscription.get" class="permission-name add-link" data-text="securitycenter.subscription.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  subscription.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.userinterfacemetadata.get" class="permission-name add-link" data-text="securitycenter.userinterfacemetadata.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  userinterfacemetadata.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamAdmin">IAM Recommender Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/recommender#recommender.iamViewer">IAM Recommender Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  recommender.iamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetSecurityMarksWriter">Security Center Asset Security Marks Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetSecurityMarksWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsDiscoveryRunner">Security Center Assets Discovery Runner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsDiscoveryRunner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.assetsViewer">Security Center Assets Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.assetsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingSecurityMarksWriter">Security Center Finding Security Marks Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingSecurityMarksWriter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsStateSetter">Security Center Findings State Setter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsStateSetter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsWorkflowStateSetter">Security Center Findings Workflow State Setter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsWorkflowStateSetter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigEditor">Security Center Notification Configurations Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.notificationConfigViewer">Security Center Notification Configurations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.notificationConfigViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.riskReportsViewer">Security Center Risk Reports Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.riskReportsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesAdmin">Security Center Sources Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesEditor">Security Center Sources Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.sourcesViewer">Security Center Sources Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.sourcesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.valuedresources.list" class="permission-name add-link" data-text="securitycenter.valuedresources.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  valuedresources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.admin">Chronicle API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarAdmin">Chronicle SOAR Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarThreatManager">Chronicle SOAR Threat Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarThreatManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/chronicle#chronicle.soarVulnerabilityManager">Chronicle SOAR Vulnerability Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  chronicle.soarVulnerabilityManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.valuedResourcesViewer">Security Center Valued Resources Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.valuedResourcesViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.virtualmachinethreatdetectionsettings.calculate" class="permission-name add-link" data-text="securitycenter.virtualmachinethreatdetectionsettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.virtualmachinethreatdetectionsettings.get" class="permission-name add-link" data-text="securitycenter.virtualmachinethreatdetectionsettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.virtualmachinethreatdetectionsettings.update" class="permission-name add-link" data-text="securitycenter.virtualmachinethreatdetectionsettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  virtualmachinethreatdetectionsettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.vulnerabilitysnapshots.list" class="permission-name add-link" data-text="securitycenter.vulnerabilitysnapshots.list" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  vulnerabilitysnapshots.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsEditor">Security Center Findings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.findingsViewer">Security Center Findings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.findingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.websecurityscannersettings.calculate" class="permission-name add-link" data-text="securitycenter.websecurityscannersettings.calculate" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  calculate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="securitycenter.websecurityscannersettings.get" class="permission-name add-link" data-text="securitycenter.websecurityscannersettings.get" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsViewer">Security Center Settings Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riskmanager#riskmanager.serviceAgent">Risk Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riskmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="securitycenter.websecurityscannersettings.update" class="permission-name add-link" data-text="securitycenter.websecurityscannersettings.update" tabindex="-1"><code dir="ltr" translate="no">securitycenter.  websecurityscannersettings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsAdmin">Security Center Settings Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.settingsEditor">Security Center Settings Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.settingsEditor</code> )</p></td>
</tr>
</tbody>
</table>
