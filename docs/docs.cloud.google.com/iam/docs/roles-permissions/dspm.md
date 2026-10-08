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
<td>Data Security Posture Management Admin
<p>( <code>roles/ dspm.admin</code> )</p>
<p>Full access to Data Security Posture Management resources.</p></td>
<td><p><code>dspm.*</code></p>
<ul>
<li><code>dspm. locations. computeAggregation</code></li>
<li><code>dspm. locations. fetchDataGovernanceAnalytics</code></li>
<li><code>dspm. locations. fetchDspmGovernedProjects</code></li>
<li><code>dspm. locations. fetchGovernedResourceMetrics</code></li>
<li><code>dspm. locations. fetchLineageConnections</code></li>
<li><code>dspm.locations.get</code></li>
<li><code>dspm.locations.list</code></li>
<li><code>dspm.operations.cancel</code></li>
<li><code>dspm.operations.delete</code></li>
<li><code>dspm.operations.get</code></li>
<li><code>dspm.operations.list</code></li>
</ul>
<p><code>resourcemanager. organizations. get</code></p></td>
</tr>
<tr class="even">
<td>Data Security Posture Management Viewer
<p>( <code>roles/ dspm.viewer</code> )</p>
<p>Readonly access to Data Security Posture Management resources.</p></td>
<td><p><code>dspm.locations.*</code></p>
<ul>
<li><code>dspm. locations. computeAggregation</code></li>
<li><code>dspm. locations. fetchDataGovernanceAnalytics</code></li>
<li><code>dspm. locations. fetchDspmGovernedProjects</code></li>
<li><code>dspm. locations. fetchGovernedResourceMetrics</code></li>
<li><code>dspm. locations. fetchLineageConnections</code></li>
<li><code>dspm.locations.get</code></li>
<li><code>dspm.locations.list</code></li>
</ul>
<p><code>dspm.operations.get</code></p>
<p><code>dspm.operations.list</code></p>
<p><code>resourcemanager. organizations. get</code></p></td>
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
<td>DSPM Service Agent
<p>( <code>roles/ dspm.serviceAgent</code> )</p>
<p>Gives DSPM Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.artifacts.list</code></p>
<p><code>aiplatform.contexts.list</code></p>
<p><code>aiplatform.dataItems.list</code></p>
<p><code>aiplatform.datasets.get</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform.executions.list</code></p>
<p><code>aiplatform. metadataSchemas. list</code></p>
<p><code>aiplatform. modelEvaluations. list</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>aiplatform.tuningJobs.list</code></p>
<p><code>bigquery. datasets. createTagBinding</code></p>
<p><code>bigquery. datasets. deleteTagBinding</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery. tables. createTagBinding</code></p>
<p><code>bigquery. tables. deleteTagBinding</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset.assets.listResource</code></p>
<p><code>cloudasset. assets. queryResource</code></p>
<p><code>cloudasset. assets. searchAllResources</code></p>
<p><code>cloudasset.feeds.create</code></p>
<p><code>cloudasset.feeds.delete</code></p>
<p><code>cloudasset.feeds.get</code></p>
<p><code>cloudasset.feeds.update</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. create</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. delete</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. get</code></p>
<p><code>cloudsecuritycompliance. cloudControlDeployments. list</code></p>
<p><code>cloudsecuritycompliance. cloudControls. get</code></p>
<p><code>cloudsecuritycompliance. cloudControls. list</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. create</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. delete</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. get</code></p>
<p><code>cloudsecuritycompliance. frameworkDeployments. list</code></p>
<p><code>cloudsecuritycompliance. frameworks. get</code></p>
<p><code>resourcemanager. folders. getIamPolicy</code></p>
<p><code>resourcemanager. hierarchyNodes.*</code></p>
<ul>
<li><code>resourcemanager. hierarchyNodes. createTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></li>
<li><code>resourcemanager. hierarchyNodes. listTagBindings</code></li>
</ul>
<p><code>resourcemanager. organizations. getIamPolicy</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager.tagKeys.create</code></p>
<p><code>resourcemanager.tagKeys.delete</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager. tagKeys. getIamPolicy</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager.tagKeys.update</code></p>
<p><code>resourcemanager. tagValueBindings.*</code></p>
<ul>
<li><code>resourcemanager. tagValueBindings. create</code></li>
<li><code>resourcemanager. tagValueBindings. delete</code></li>
</ul>
<p><code>resourcemanager. tagValues. create</code></p>
<p><code>resourcemanager. tagValues. delete</code></p>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager. tagValues. getIamPolicy</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>resourcemanager. tagValues. update</code></p>
<p><code>securitycenter. securityhealthanalyticssettings.*</code></p>
<ul>
<li><code>securitycenter. securityhealthanalyticssettings. calculate</code></li>
<li><code>securitycenter. securityhealthanalyticssettings. get</code></li>
<li><code>securitycenter. securityhealthanalyticssettings. update</code></li>
</ul>
<p><code>securitycentermanagement. effectiveSecurityHealthAnalyticsCustomModules. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. get</code></p>
<p><code>securitycentermanagement. securityCenterServices. update</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. create</code></p>
<p><code>securitycentermanagement. securityHealthAnalyticsCustomModules. get</code></p>
<p><code>securityposture.operations.get</code></p>
<p><code>securityposture. postureDeployments. create</code></p>
<p><code>securityposture. postureDeployments. delete</code></p>
<p><code>securityposture. postureDeployments. get</code></p>
<p><code>securityposture. postureDeployments. list</code></p>
<p><code>securityposture. postures. create</code></p>
<p><code>securityposture.postures.get</code></p>
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
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage. buckets. createTagBinding</code></p>
<p><code>storage. buckets. deleteTagBinding</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage. intelligenceConfigs. get</code></p></td>
</tr>
</tbody>
</table>

## Data Security Posture Management permissions

| Permission                                      | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
|-------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `dspm. locations. computeAggregation`           | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm. locations. fetchDataGovernanceAnalytics` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm. locations. fetchDspmGovernedProjects`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm. locations. fetchGovernedResourceMetrics` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm. locations. fetchLineageConnections`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm.locations.get`                            | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm.locations.list`                           | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) |
| `dspm.operations.cancel`                        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `dspm.operations.delete`                        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `dspm.operations.get`                           | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` )                                                                                                                                                                                                                                                                          |
| `dspm.operations.list`                          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Data Security Posture Management Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.admin) ( `roles/ dspm.admin` ) [Data Security Posture Management Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/dspm#dspm.viewer) ( `roles/ dspm.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Center Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin) ( `roles/ securitycenter.admin` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Security Center Admin Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor) ( `roles/ securitycenter.adminEditor` ) [Security Center Admin Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer) ( `roles/ securitycenter.adminViewer` ) |
