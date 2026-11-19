---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads
title: Assured Workloads roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Assured Workloads. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Assured Workloads roles

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
<td>Assured Workloads Administrator
<p>( <code>roles/ assuredworkloads.admin</code> )</p>
<p>Grants full access to Assured Workloads resources, CRM resources - project/folder and Organization Policy administration</p></td>
<td><p><code>accesscontextmanager. policies. create</code></p>
<p><code>accesscontextmanager. policies. delete</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. create</code></p>
<p><code>accesscontextmanager. servicePerimeters. delete</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. update</code></p>
<p><code>assuredworkloads.*</code></p>
<ul>
<li><code>assuredworkloads. dbControlComplianceSummaries. list</code></li>
<li><code>assuredworkloads. dbFindingSummaries. list</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. aggregate</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. get</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></li>
<li><code>assuredworkloads. operations. get</code></li>
<li><code>assuredworkloads. operations. list</code></li>
<li><code>assuredworkloads.updates.list</code></li>
<li><code>assuredworkloads. updates. update</code></li>
<li><code>assuredworkloads. violations. get</code></li>
<li><code>assuredworkloads. violations. list</code></li>
<li><code>assuredworkloads. violations. update</code></li>
<li><code>assuredworkloads. workload. create</code></li>
<li><code>assuredworkloads. workload. delete</code></li>
<li><code>assuredworkloads.workload.get</code></li>
<li><code>assuredworkloads.workload.list</code></li>
<li><code>assuredworkloads. workload. update</code></li>
</ul>
<p><code>axt.labels.set</code></p>
<p><code>bigquery.config.update</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. cloudControlPredictions. create</code></li>
<li><code>cloudsecuritycompliance. cloudControlPredictions. get</code></li>
<li><code>cloudsecuritycompliance. cloudControlPredictions. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. cloudControls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. cloudControls. create</code></li>
<li><code>cloudsecuritycompliance. cloudControls. delete</code></li>
<li><code>cloudsecuritycompliance. cloudControls. get</code></li>
<li><code>cloudsecuritycompliance. cloudControls. list</code></li>
<li><code>cloudsecuritycompliance. cloudControls. update</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworks.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworks. create</code></li>
<li><code>cloudsecuritycompliance. frameworks. delete</code></li>
<li><code>cloudsecuritycompliance. frameworks. get</code></li>
<li><code>cloudsecuritycompliance. frameworks. list</code></li>
<li><code>cloudsecuritycompliance. frameworks. update</code></li>
</ul>
<p><code>logging.settings.update</code></p>
<p><code>orgpolicy.policies.*</code></p>
<ul>
<li><code>orgpolicy.policies.create</code></li>
<li><code>orgpolicy.policies.delete</code></li>
<li><code>orgpolicy.policies.list</code></li>
<li><code>orgpolicy.policies.update</code></li>
</ul>
<p><code>orgpolicy.policy.*</code></p>
<ul>
<li><code>orgpolicy.policy.get</code></li>
<li><code>orgpolicy.policy.set</code></li>
</ul>
<p><code>resourcemanager.folders.create</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. projects. create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Assured Workloads Editor
<p>( <code>roles/ assuredworkloads.editor</code> )</p>
<p>Grants read, write access to Assured Workloads resources, CRM resources - project/folder and Organization Policy administration</p></td>
<td><p><code>accesscontextmanager. policies. create</code></p>
<p><code>accesscontextmanager. policies. delete</code></p>
<p><code>accesscontextmanager. policies. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. create</code></p>
<p><code>accesscontextmanager. servicePerimeters. delete</code></p>
<p><code>accesscontextmanager. servicePerimeters. get</code></p>
<p><code>accesscontextmanager. servicePerimeters. update</code></p>
<p><code>assuredworkloads.*</code></p>
<ul>
<li><code>assuredworkloads. dbControlComplianceSummaries. list</code></li>
<li><code>assuredworkloads. dbFindingSummaries. list</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. aggregate</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. get</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></li>
<li><code>assuredworkloads. operations. get</code></li>
<li><code>assuredworkloads. operations. list</code></li>
<li><code>assuredworkloads.updates.list</code></li>
<li><code>assuredworkloads. updates. update</code></li>
<li><code>assuredworkloads. violations. get</code></li>
<li><code>assuredworkloads. violations. list</code></li>
<li><code>assuredworkloads. violations. update</code></li>
<li><code>assuredworkloads. workload. create</code></li>
<li><code>assuredworkloads. workload. delete</code></li>
<li><code>assuredworkloads.workload.get</code></li>
<li><code>assuredworkloads.workload.list</code></li>
<li><code>assuredworkloads. workload. update</code></li>
</ul>
<p><code>axt.labels.set</code></p>
<p><code>bigquery.config.update</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. cloudControlPredictions. create</code></li>
<li><code>cloudsecuritycompliance. cloudControlPredictions. get</code></li>
<li><code>cloudsecuritycompliance. cloudControlPredictions. list</code></li>
</ul>
<p><code>cloudsecuritycompliance. cloudControls.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. cloudControls. create</code></li>
<li><code>cloudsecuritycompliance. cloudControls. delete</code></li>
<li><code>cloudsecuritycompliance. cloudControls. get</code></li>
<li><code>cloudsecuritycompliance. cloudControls. list</code></li>
<li><code>cloudsecuritycompliance. cloudControls. update</code></li>
</ul>
<p><code>cloudsecuritycompliance. frameworks.*</code></p>
<ul>
<li><code>cloudsecuritycompliance. frameworks. create</code></li>
<li><code>cloudsecuritycompliance. frameworks. delete</code></li>
<li><code>cloudsecuritycompliance. frameworks. get</code></li>
<li><code>cloudsecuritycompliance. frameworks. list</code></li>
<li><code>cloudsecuritycompliance. frameworks. update</code></li>
</ul>
<p><code>logging.settings.update</code></p>
<p><code>orgpolicy.policies.*</code></p>
<ul>
<li><code>orgpolicy.policies.create</code></li>
<li><code>orgpolicy.policies.delete</code></li>
<li><code>orgpolicy.policies.list</code></li>
<li><code>orgpolicy.policies.update</code></li>
</ul>
<p><code>orgpolicy.policy.*</code></p>
<ul>
<li><code>orgpolicy.policy.get</code></li>
<li><code>orgpolicy.policy.set</code></li>
</ul>
<p><code>resourcemanager.folders.create</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. projects. create</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Assured Workloads Viewer
<p>( <code>roles/ assuredworkloads.viewer</code> )</p>
<p>Viewer role for Assured Workloads</p></td>
<td><p><code>assuredworkloads. dbControlComplianceSummaries. list</code></p>
<p><code>assuredworkloads. dbFindingSummaries. list</code></p>
<p><code>assuredworkloads. dbFrameworkComplianceReports.*</code></p>
<ul>
<li><code>assuredworkloads. dbFrameworkComplianceReports. aggregate</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. get</code></li>
</ul>
<p><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></p>
<p><code>assuredworkloads.operations.*</code></p>
<ul>
<li><code>assuredworkloads. operations. get</code></li>
<li><code>assuredworkloads. operations. list</code></li>
</ul>
<p><code>assuredworkloads.updates.list</code></p>
<p><code>assuredworkloads. violations. get</code></p>
<p><code>assuredworkloads. violations. list</code></p>
<p><code>assuredworkloads.workload.get</code></p>
<p><code>assuredworkloads.workload.list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Assured Workloads Reader
<p>( <code>roles/ assuredworkloads.reader</code> )</p>
<p>Grants read access to all Assured Workloads resources and CRM resources - project/folder</p></td>
<td><p><code>assuredworkloads. dbControlComplianceSummaries. list</code></p>
<p><code>assuredworkloads. dbFindingSummaries. list</code></p>
<p><code>assuredworkloads. dbFrameworkComplianceReports.*</code></p>
<ul>
<li><code>assuredworkloads. dbFrameworkComplianceReports. aggregate</code></li>
<li><code>assuredworkloads. dbFrameworkComplianceReports. get</code></li>
</ul>
<p><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></p>
<p><code>assuredworkloads.operations.*</code></p>
<ul>
<li><code>assuredworkloads. operations. get</code></li>
<li><code>assuredworkloads. operations. list</code></li>
</ul>
<p><code>assuredworkloads.updates.list</code></p>
<p><code>assuredworkloads. violations. get</code></p>
<p><code>assuredworkloads. violations. list</code></p>
<p><code>assuredworkloads.workload.get</code></p>
<p><code>assuredworkloads.workload.list</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlPredictions. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>cloudsecuritycompliance. frameworks. list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Assured Workloads Monitoring Service Agent
<p>( <code>roles/ assuredworkloads.monitoringServiceAgent</code> )</p>
<p>Gives the Assured Workloads service account access to create CAIS feed and monitor Assured Workloads.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>accessapproval.settings.get</code></p>
<p><code>aiplatform.customJobs.get</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform.datasets.get</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform.endpoints.get</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform.featurestores.get</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. get</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.metadataStores.get</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform.models.get</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. get</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform.tensorboards.get</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. get</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. list</code></p>
<p><code>axt.labels.get</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>binaryauthorization.policy.get</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>cloudasset. assets. exportIamPolicy</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudasset.feeds.*</code></p>
<ul>
<li><code>cloudasset.feeds.create</code></li>
<li><code>cloudasset.feeds.delete</code></li>
<li><code>cloudasset.feeds.get</code></li>
<li><code>cloudasset.feeds.list</code></li>
<li><code>cloudasset.feeds.update</code></li>
</ul>
<p><code>cloudkms.cryptoKeys.get</code></p>
<p><code>cloudkms.cryptoKeys.list</code></p>
<p><code>cloudkms.keyRings.list</code></p>
<p><code>cloudsecurityscanner.scans.get</code></p>
<p><code>cloudsecurityscanner. scans. list</code></p>
<p><code>cloudsql.instances.connect</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.instances.list</code></p>
<p><code>cloudsql.users.list</code></p>
<p><code>compute.autoscalers.list</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.firewallPolicies.list</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute. instanceGroupManagers. list</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.managedRulesets.*</code></p>
<ul>
<li><code>compute.managedRulesets.get</code></li>
<li><code>compute.managedRulesets.list</code></li>
</ul>
<p><code>compute.networks.list</code></p>
<p><code>compute.regionSslPolicies.list</code></p>
<p><code>compute. regionTargetHttpProxies. list</code></p>
<p><code>compute.regionUrlMaps.list</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.securityPolicies.list</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute.sslPolicies.list</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.zones.list</code></p>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>discoveryengine.dataStores.get</code></p>
<p><code>discoveryengine. dataStores. list</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.tableDataProfiles.get</code></p>
<p><code>dlp.tableDataProfiles.list</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>iam.serviceAccountKeys.list</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getIamPolicy</code></p>
<p><code>logging.buckets.list</code></p>
<p><code>logging.logMetrics.list</code></p>
<p><code>monitoring.alertPolicies.list</code></p>
<p><code>notebooks.instances.get</code></p>
<p><code>notebooks.instances.list</code></p>
<p><code>orgpolicy.constraints.list</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>privateca.certificates.list</code></p>
<p><code>resourcemanager.folders.get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager.folders.list</code></p>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager. hierarchyNodes. listTagBindings</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagHolds.list</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>secretmanager.secrets.list</code></p>
<p><code>securesourcemanager. sshkeys. listAny</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.list</code></p></td>
</tr>
<tr class="even">
<td>Assured Workloads Service Agent
<p>( <code>roles/ assuredworkloads.serviceAgent</code> )</p>
<p>Gives the Assured Workloads service account access to create KMS keyrings and keys, monitor Assured Workloads and read Organization Policies.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudkms.cryptoKeys.create</code></p>
<p><code>cloudkms.keyRings.create</code></p>
<p><code>orgpolicy.policies.list</code></p>
<p><code>orgpolicy.policy.get</code></p>
<p><code>serviceusage. catalogs. listMembers</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.listApis</code></p>
<p><code>serviceusage. services. listDependentServices</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Assured Workloads permissions

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
<td><code>assuredworkloads. dbControlComplianceSummaries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. dbFindingSummaries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. dbFrameworkComplianceReports. aggregate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. dbFrameworkComplianceReports. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. dbFrameworkComplianceSummaries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. operations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. operations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads.updates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. updates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. violations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringServiceAgent">Cloud Controls Partner Monitoring Service Agent</a> ( <code>roles/ cloudcontrolspartner.monitoringServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. violations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringServiceAgent">Cloud Controls Partner Monitoring Service Agent</a> ( <code>roles/ cloudcontrolspartner.monitoringServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. violations. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. workload. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads. workload. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads.workload.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>assuredworkloads.workload.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.viewer">Assured Workloads Viewer</a> ( <code>roles/ assuredworkloads.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.reader">Assured Workloads Reader</a> ( <code>roles/ assuredworkloads.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>assuredworkloads. workload. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.admin">Assured Workloads Administrator</a> ( <code>roles/ assuredworkloads.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/assuredworkloads#assuredworkloads.editor">Assured Workloads Editor</a> ( <code>roles/ assuredworkloads.editor</code> )</p></td>
</tr>
</tbody>
</table>
