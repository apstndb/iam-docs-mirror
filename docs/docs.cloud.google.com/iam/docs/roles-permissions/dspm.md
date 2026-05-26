---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dspm
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dspm
title: Data Security Posture Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Data Security Posture Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Data Security Posture Management roles

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
<td><h4 id="dspm.admin" class="role-title add-link" data-text="Data Security Posture Management Admin" tabindex="-1">Data Security Posture Management Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p>Full access to Data Security Posture Management resources.</p></td>
<td><p><code dir="ltr" translate="no">dspm.*</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.viewer" class="role-title add-link" data-text="Data Security Posture Management Viewer" tabindex="-1">Data Security Posture Management Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p>Readonly access to Data Security Posture Management resources.</p></td>
<td><p><code dir="ltr" translate="no">dspm.locations.*</code></p>
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
<td><h4 id="dspm.serviceAgent" class="role-title add-link" data-text="DSPM Service Agent" tabindex="-1">DSPM Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dspm.serviceAgent</code> )</p>
<p>Gives DSPM Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  metadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  queryResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.create</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.delete</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.get</code></p>
<p><code dir="ltr" translate="no">cloudasset.feeds.update</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  create</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  delete</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControlDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  cloudControls.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  create</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  delete</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  get</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworkDeployments.  list</code></p>
<p><code dir="ltr" translate="no">cloudsecuritycompliance.  frameworks.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  folders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagKeys.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  create</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  delete</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValues.  update</code></p>
<p><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  calculate</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  get</code></li>
<li><code dir="ltr" translate="no">securitycenter.  securityhealthanalyticssettings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">securitycentermanagement.  effectiveSecurityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  get</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityCenterServices.  update</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  create</code></p>
<p><code dir="ltr" translate="no">securitycentermanagement.  securityHealthAnalyticsCustomModules.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.operations.get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  create</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  delete</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  get</code></p>
<p><code dir="ltr" translate="no">securityposture.  postureDeployments.  list</code></p>
<p><code dir="ltr" translate="no">securityposture.  postures.  create</code></p>
<p><code dir="ltr" translate="no">securityposture.postures.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></p></td>
</tr>
</tbody>
</table>

## Data Security Posture Management permissions

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
<td><h4 id="dspm.locations.computeAggregation" class="permission-name add-link" data-text="dspm.locations.computeAggregation" tabindex="-1"><code dir="ltr" translate="no">dspm.  locations.  computeAggregation</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.locations.fetchDataGovernanceAnalytics" class="permission-name add-link" data-text="dspm.locations.fetchDataGovernanceAnalytics" tabindex="-1"><code dir="ltr" translate="no">dspm.  locations.  fetchDataGovernanceAnalytics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dspm.locations.fetchDspmGovernedProjects" class="permission-name add-link" data-text="dspm.locations.fetchDspmGovernedProjects" tabindex="-1"><code dir="ltr" translate="no">dspm.  locations.  fetchDspmGovernedProjects</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.locations.fetchGovernedResourceMetrics" class="permission-name add-link" data-text="dspm.locations.fetchGovernedResourceMetrics" tabindex="-1"><code dir="ltr" translate="no">dspm.  locations.  fetchGovernedResourceMetrics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dspm.locations.fetchLineageConnections" class="permission-name add-link" data-text="dspm.locations.fetchLineageConnections" tabindex="-1"><code dir="ltr" translate="no">dspm.  locations.  fetchLineageConnections</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.locations.get" class="permission-name add-link" data-text="dspm.locations.get" tabindex="-1"><code dir="ltr" translate="no">dspm.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dspm.locations.list" class="permission-name add-link" data-text="dspm.locations.list" tabindex="-1"><code dir="ltr" translate="no">dspm.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.operations.cancel" class="permission-name add-link" data-text="dspm.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">dspm.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dspm.operations.delete" class="permission-name add-link" data-text="dspm.operations.delete" tabindex="-1"><code dir="ltr" translate="no">dspm.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dspm.operations.get" class="permission-name add-link" data-text="dspm.operations.get" tabindex="-1"><code dir="ltr" translate="no">dspm.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dspm.operations.list" class="permission-name add-link" data-text="dspm.operations.list" tabindex="-1"><code dir="ltr" translate="no">dspm.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin">Data Security Posture Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer">Data Security Posture Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dspm.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
</tbody>
</table>
