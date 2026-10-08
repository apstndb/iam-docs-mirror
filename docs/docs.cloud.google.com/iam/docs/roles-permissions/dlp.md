---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dlp
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dlp
title: Sensitive Data Protection roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Sensitive Data Protection. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Sensitive Data Protection roles

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
<td>DLP Administrator
<p>( <code>roles/ dlp.admin</code> )</p>
<p>Administer DLP including jobs and templates.</p></td>
<td><p><code>dlp.*</code></p>
<ul>
<li><code>dlp. analyzeRiskTemplates. create</code></li>
<li><code>dlp. analyzeRiskTemplates. delete</code></li>
<li><code>dlp.analyzeRiskTemplates.get</code></li>
<li><code>dlp.analyzeRiskTemplates.list</code></li>
<li><code>dlp. analyzeRiskTemplates. update</code></li>
<li><code>dlp.charts.get</code></li>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
<li><code>dlp.connections.create</code></li>
<li><code>dlp.connections.delete</code></li>
<li><code>dlp.connections.get</code></li>
<li><code>dlp.connections.list</code></li>
<li><code>dlp.connections.search</code></li>
<li><code>dlp.connections.update</code></li>
<li><code>dlp.contentPolicies.apply</code></li>
<li><code>dlp.contentPolicies.create</code></li>
<li><code>dlp.contentPolicies.delete</code></li>
<li><code>dlp.contentPolicies.get</code></li>
<li><code>dlp.contentPolicies.list</code></li>
<li><code>dlp.contentPolicies.update</code></li>
<li><code>dlp.deidentifyTemplates.create</code></li>
<li><code>dlp.deidentifyTemplates.delete</code></li>
<li><code>dlp.deidentifyTemplates.get</code></li>
<li><code>dlp.deidentifyTemplates.list</code></li>
<li><code>dlp.deidentifyTemplates.update</code></li>
<li><code>dlp.estimates.cancel</code></li>
<li><code>dlp.estimates.create</code></li>
<li><code>dlp.estimates.delete</code></li>
<li><code>dlp.estimates.get</code></li>
<li><code>dlp.estimates.list</code></li>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
<li><code>dlp.inspectFindings.list</code></li>
<li><code>dlp.inspectTemplates.create</code></li>
<li><code>dlp.inspectTemplates.delete</code></li>
<li><code>dlp.inspectTemplates.get</code></li>
<li><code>dlp.inspectTemplates.list</code></li>
<li><code>dlp.inspectTemplates.update</code></li>
<li><code>dlp.jobTriggers.create</code></li>
<li><code>dlp.jobTriggers.delete</code></li>
<li><code>dlp.jobTriggers.get</code></li>
<li><code>dlp.jobTriggers.hybridInspect</code></li>
<li><code>dlp.jobTriggers.list</code></li>
<li><code>dlp.jobTriggers.update</code></li>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
<li><code>dlp.kms.encrypt</code></li>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
<li><code>dlp.storedInfoTypes.create</code></li>
<li><code>dlp.storedInfoTypes.delete</code></li>
<li><code>dlp.storedInfoTypes.get</code></li>
<li><code>dlp.storedInfoTypes.list</code></li>
<li><code>dlp.storedInfoTypes.update</code></li>
<li><code>dlp.subscriptions.cancel</code></li>
<li><code>dlp.subscriptions.create</code></li>
<li><code>dlp.subscriptions.get</code></li>
<li><code>dlp.subscriptions.list</code></li>
<li><code>dlp.subscriptions.update</code></li>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>DLP Editor
<p>( <code>roles/ dlp.editor</code> )</p>
<p>Editor role for DLP</p></td>
<td><p><code>dlp.analyzeRiskTemplates.*</code></p>
<ul>
<li><code>dlp. analyzeRiskTemplates. create</code></li>
<li><code>dlp. analyzeRiskTemplates. delete</code></li>
<li><code>dlp.analyzeRiskTemplates.get</code></li>
<li><code>dlp.analyzeRiskTemplates.list</code></li>
<li><code>dlp. analyzeRiskTemplates. update</code></li>
</ul>
<p><code>dlp.charts.get</code></p>
<p><code>dlp.columnDataProfiles.*</code></p>
<ul>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
</ul>
<p><code>dlp.connections.*</code></p>
<ul>
<li><code>dlp.connections.create</code></li>
<li><code>dlp.connections.delete</code></li>
<li><code>dlp.connections.get</code></li>
<li><code>dlp.connections.list</code></li>
<li><code>dlp.connections.search</code></li>
<li><code>dlp.connections.update</code></li>
</ul>
<p><code>dlp.contentPolicies.*</code></p>
<ul>
<li><code>dlp.contentPolicies.apply</code></li>
<li><code>dlp.contentPolicies.create</code></li>
<li><code>dlp.contentPolicies.delete</code></li>
<li><code>dlp.contentPolicies.get</code></li>
<li><code>dlp.contentPolicies.list</code></li>
<li><code>dlp.contentPolicies.update</code></li>
</ul>
<p><code>dlp.deidentifyTemplates.*</code></p>
<ul>
<li><code>dlp.deidentifyTemplates.create</code></li>
<li><code>dlp.deidentifyTemplates.delete</code></li>
<li><code>dlp.deidentifyTemplates.get</code></li>
<li><code>dlp.deidentifyTemplates.list</code></li>
<li><code>dlp.deidentifyTemplates.update</code></li>
</ul>
<p><code>dlp.estimates.*</code></p>
<ul>
<li><code>dlp.estimates.cancel</code></li>
<li><code>dlp.estimates.create</code></li>
<li><code>dlp.estimates.delete</code></li>
<li><code>dlp.estimates.get</code></li>
<li><code>dlp.estimates.list</code></li>
</ul>
<p><code>dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
</ul>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.*</code></p>
<ul>
<li><code>dlp.inspectTemplates.create</code></li>
<li><code>dlp.inspectTemplates.delete</code></li>
<li><code>dlp.inspectTemplates.get</code></li>
<li><code>dlp.inspectTemplates.list</code></li>
<li><code>dlp.inspectTemplates.update</code></li>
</ul>
<p><code>dlp.jobTriggers.*</code></p>
<ul>
<li><code>dlp.jobTriggers.create</code></li>
<li><code>dlp.jobTriggers.delete</code></li>
<li><code>dlp.jobTriggers.get</code></li>
<li><code>dlp.jobTriggers.hybridInspect</code></li>
<li><code>dlp.jobTriggers.list</code></li>
<li><code>dlp.jobTriggers.update</code></li>
</ul>
<p><code>dlp.jobs.*</code></p>
<ul>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
</ul>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>dlp.projectDataProfiles.*</code></p>
<ul>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
</ul>
<p><code>dlp.storedInfoTypes.*</code></p>
<ul>
<li><code>dlp.storedInfoTypes.create</code></li>
<li><code>dlp.storedInfoTypes.delete</code></li>
<li><code>dlp.storedInfoTypes.get</code></li>
<li><code>dlp.storedInfoTypes.list</code></li>
<li><code>dlp.storedInfoTypes.update</code></li>
</ul>
<p><code>dlp.subscriptions.*</code></p>
<ul>
<li><code>dlp.subscriptions.cancel</code></li>
<li><code>dlp.subscriptions.create</code></li>
<li><code>dlp.subscriptions.get</code></li>
<li><code>dlp.subscriptions.list</code></li>
<li><code>dlp.subscriptions.update</code></li>
</ul>
<p><code>dlp.tableDataProfiles.*</code></p>
<ul>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP User
<p>( <code>roles/ dlp.user</code> )</p>
<p>Inspect, Redact, and De-identify Content</p></td>
<td><p><code>dlp.contentPolicies.apply</code></p>
<p><code>dlp.kms.encrypt</code></p>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td>DLP Viewer
<p>( <code>roles/ dlp.viewer</code> )</p>
<p>Viewer role for DLP</p></td>
<td><p><code>dlp.analyzeRiskTemplates.get</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.charts.get</code></p>
<p><code>dlp.columnDataProfiles.*</code></p>
<ul>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
</ul>
<p><code>dlp.connections.get</code></p>
<p><code>dlp.connections.list</code></p>
<p><code>dlp.connections.search</code></p>
<p><code>dlp.contentPolicies.get</code></p>
<p><code>dlp.contentPolicies.list</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.estimates.get</code></p>
<p><code>dlp.estimates.list</code></p>
<p><code>dlp.fileStoreProfiles.get</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.get</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.get</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>dlp.projectDataProfiles.*</code></p>
<ul>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
</ul>
<p><code>dlp.storedInfoTypes.get</code></p>
<p><code>dlp.storedInfoTypes.list</code></p>
<p><code>dlp.subscriptions.get</code></p>
<p><code>dlp.subscriptions.list</code></p>
<p><code>dlp.tableDataProfiles.get</code></p>
<p><code>dlp.tableDataProfiles.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Analyze Risk Templates Editor
<p>( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p>Edit DLP analyze risk templates.</p></td>
<td><p><code>dlp.analyzeRiskTemplates.*</code></p>
<ul>
<li><code>dlp. analyzeRiskTemplates. create</code></li>
<li><code>dlp. analyzeRiskTemplates. delete</code></li>
<li><code>dlp.analyzeRiskTemplates.get</code></li>
<li><code>dlp.analyzeRiskTemplates.list</code></li>
<li><code>dlp. analyzeRiskTemplates. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Analyze Risk Templates Reader
<p>( <code>roles/ dlp.analyzeRiskTemplatesReader</code> )</p>
<p>Read DLP analyze risk templates.</p></td>
<td><p><code>dlp.analyzeRiskTemplates.get</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Column Data Profiles Reader
<p>( <code>roles/ dlp.columnDataProfilesReader</code> )</p>
<p>Read DLP column profiles.</p></td>
<td><p><code>dlp.columnDataProfiles.*</code></p>
<ul>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Connections Admin
<p>( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p>Manage DLP Connections.</p></td>
<td><p><code>dlp.connections.*</code></p>
<ul>
<li><code>dlp.connections.create</code></li>
<li><code>dlp.connections.delete</code></li>
<li><code>dlp.connections.get</code></li>
<li><code>dlp.connections.list</code></li>
<li><code>dlp.connections.search</code></li>
<li><code>dlp.connections.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Connections Viewer
<p>( <code>roles/ dlp.connectionsReader</code> )</p>
<p>View DLP Connections.</p></td>
<td><p><code>dlp.connections.get</code></p>
<p><code>dlp.connections.list</code></p>
<p><code>dlp.connections.search</code></p></td>
</tr>
<tr class="even">
<td>DLP Content Policies Consumer
<p>( <code>roles/ dlp.contentPoliciesConsumer</code> )</p>
<p>Apply content policies.</p></td>
<td><p><code>dlp.contentPolicies.apply</code></p>
<p><code>dlp.contentPolicies.get</code></p></td>
</tr>
<tr class="odd">
<td>DLP Content Policies Editor
<p>( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p>Edit DLP content policies.</p></td>
<td><p><code>dlp.contentPolicies.*</code></p>
<ul>
<li><code>dlp.contentPolicies.apply</code></li>
<li><code>dlp.contentPolicies.create</code></li>
<li><code>dlp.contentPolicies.delete</code></li>
<li><code>dlp.contentPolicies.get</code></li>
<li><code>dlp.contentPolicies.list</code></li>
<li><code>dlp.contentPolicies.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Content Policies Reader
<p>( <code>roles/ dlp.contentPoliciesReader</code> )</p>
<p>Read DLP content policies.</p></td>
<td><p><code>dlp.contentPolicies.get</code></p>
<p><code>dlp.contentPolicies.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Data Profiles Admin
<p>( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p>Manage DLP profiles.</p></td>
<td><p><code>dlp.charts.get</code></p>
<p><code>dlp.columnDataProfiles.*</code></p>
<ul>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
</ul>
<p><code>dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
</ul>
<p><code>dlp.projectDataProfiles.*</code></p>
<ul>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
</ul>
<p><code>dlp.tableDataProfiles.*</code></p>
<ul>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Data Profiles Reader
<p>( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p>Read DLP profiles.</p></td>
<td><p><code>dlp.charts.get</code></p>
<p><code>dlp.columnDataProfiles.*</code></p>
<ul>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
</ul>
<p><code>dlp.fileStoreProfiles.get</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p>
<p><code>dlp.projectDataProfiles.*</code></p>
<ul>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
</ul>
<p><code>dlp.tableDataProfiles.get</code></p>
<p><code>dlp.tableDataProfiles.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP De-identify Templates Editor
<p>( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p>Edit DLP de-identify templates.</p></td>
<td><p><code>dlp.deidentifyTemplates.*</code></p>
<ul>
<li><code>dlp.deidentifyTemplates.create</code></li>
<li><code>dlp.deidentifyTemplates.delete</code></li>
<li><code>dlp.deidentifyTemplates.get</code></li>
<li><code>dlp.deidentifyTemplates.list</code></li>
<li><code>dlp.deidentifyTemplates.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP De-identify Templates Reader
<p>( <code>roles/ dlp.deidentifyTemplatesReader</code> )</p>
<p>Read DLP de-identify templates.</p></td>
<td><p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Cost Estimation
<p>( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p>Manage DLP Cost Estimates.</p></td>
<td><p><code>dlp.estimates.*</code></p>
<ul>
<li><code>dlp.estimates.cancel</code></li>
<li><code>dlp.estimates.create</code></li>
<li><code>dlp.estimates.delete</code></li>
<li><code>dlp.estimates.get</code></li>
<li><code>dlp.estimates.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP File Store Data Profiles Admin
<p>( <code>roles/ dlp.fileStoreProfilesAdmin</code> )</p>
<p>Manage DLP file store profiles.</p></td>
<td><p><code>dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>DLP File Store Data Profiles Reader
<p>( <code>roles/ dlp.fileStoreProfilesReader</code> )</p>
<p>Read DLP file store profiles.</p></td>
<td><p><code>dlp.charts.get</code></p>
<p><code>dlp.fileStoreProfiles.get</code></p>
<p><code>dlp.fileStoreProfiles.list</code></p></td>
</tr>
<tr class="even">
<td>DLP Inspect Findings Reader
<p>( <code>roles/ dlp.inspectFindingsReader</code> )</p>
<p>Read DLP stored findings.</p></td>
<td><p><code>dlp.inspectFindings.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Inspect Templates Editor
<p>( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p>Edit DLP inspect templates.</p></td>
<td><p><code>dlp.inspectTemplates.*</code></p>
<ul>
<li><code>dlp.inspectTemplates.create</code></li>
<li><code>dlp.inspectTemplates.delete</code></li>
<li><code>dlp.inspectTemplates.get</code></li>
<li><code>dlp.inspectTemplates.list</code></li>
<li><code>dlp.inspectTemplates.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Inspect Templates Reader
<p>( <code>roles/ dlp.inspectTemplatesReader</code> )</p>
<p>Read DLP inspect templates.</p></td>
<td><p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Job Triggers Editor
<p>( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p>Edit job triggers configurations.</p></td>
<td><p><code>dlp.jobTriggers.*</code></p>
<ul>
<li><code>dlp.jobTriggers.create</code></li>
<li><code>dlp.jobTriggers.delete</code></li>
<li><code>dlp.jobTriggers.get</code></li>
<li><code>dlp.jobTriggers.hybridInspect</code></li>
<li><code>dlp.jobTriggers.list</code></li>
<li><code>dlp.jobTriggers.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Job Triggers Reader
<p>( <code>roles/ dlp.jobTriggersReader</code> )</p>
<p>Read job triggers.</p></td>
<td><p><code>dlp.jobTriggers.get</code></p>
<p><code>dlp.jobTriggers.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Jobs Editor
<p>( <code>roles/ dlp.jobsEditor</code> )</p>
<p>Edit and create jobs</p></td>
<td><p><code>dlp.jobs.*</code></p>
<ul>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
</ul>
<p><code>dlp.kms.encrypt</code></p></td>
</tr>
<tr class="even">
<td>DLP Jobs Reader
<p>( <code>roles/ dlp.jobsReader</code> )</p>
<p>Read jobs</p></td>
<td><p><code>dlp.jobs.get</code></p>
<p><code>dlp.jobs.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Organization Data Profiles Driver
<p>( <code>roles/ dlp.orgdriver</code> )</p>
<p>Permissions needed by the DLP service account to generate data profiles within an organization or folder.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code>aiplatform. agentAnomalyDetectionScopes. get</code></p>
<p><code>aiplatform. agentAnomalyDetectionScopes. list</code></p>
<p><code>aiplatform.agentExamples.get</code></p>
<p><code>aiplatform.agentExamples.list</code></p>
<p><code>aiplatform.agents.get</code></p>
<p><code>aiplatform.agents.list</code></p>
<p><code>aiplatform. analyzedInvocations.*</code></p>
<ul>
<li><code>aiplatform. analyzedInvocations. get</code></li>
<li><code>aiplatform. analyzedInvocations. list</code></li>
</ul>
<p><code>aiplatform.analyzedSessions.*</code></p>
<ul>
<li><code>aiplatform. analyzedSessions. aggregate</code></li>
<li><code>aiplatform. analyzedSessions. get</code></li>
<li><code>aiplatform. analyzedSessions. list</code></li>
</ul>
<p><code>aiplatform.annotationSpecs.get</code></p>
<p><code>aiplatform. annotationSpecs. list</code></p>
<p><code>aiplatform.annotations.get</code></p>
<p><code>aiplatform.annotations.list</code></p>
<p><code>aiplatform.apps.get</code></p>
<p><code>aiplatform.apps.list</code></p>
<p><code>aiplatform.artifacts.get</code></p>
<p><code>aiplatform.artifacts.list</code></p>
<p><code>aiplatform. batchPredictionJobs. get</code></p>
<p><code>aiplatform. batchPredictionJobs. list</code></p>
<p><code>aiplatform.cacheConfigs.get</code></p>
<p><code>aiplatform.cachedContents.get</code></p>
<p><code>aiplatform.cachedContents.list</code></p>
<p><code>aiplatform.consents.get</code></p>
<p><code>aiplatform.contexts.get</code></p>
<p><code>aiplatform.contexts.list</code></p>
<p><code>aiplatform. contexts. queryContextLineageSubgraph</code></p>
<p><code>aiplatform.customJobs.get</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform.dataItems.get</code></p>
<p><code>aiplatform.dataItems.list</code></p>
<p><code>aiplatform. dataLabelingJobs. get</code></p>
<p><code>aiplatform. dataLabelingJobs. list</code></p>
<p><code>aiplatform.datasetVersions.get</code></p>
<p><code>aiplatform. datasetVersions. list</code></p>
<p><code>aiplatform.datasets.get</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform. deploymentResourcePools. get</code></p>
<p><code>aiplatform. deploymentResourcePools. list</code></p>
<p><code>aiplatform. deploymentResourcePools. queryDeployedModels</code></p>
<p><code>aiplatform. edgeDeploymentJobs. get</code></p>
<p><code>aiplatform. edgeDeploymentJobs. list</code></p>
<p><code>aiplatform. edgeDeviceDebugInfo. get</code></p>
<p><code>aiplatform.edgeDevices.get</code></p>
<p><code>aiplatform.edgeDevices.list</code></p>
<p><code>aiplatform.endpoints.get</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform.entityTypes.get</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform. evaluationExperiments. get</code></p>
<p><code>aiplatform. evaluationExperiments. list</code></p>
<p><code>aiplatform.evaluationItems.get</code></p>
<p><code>aiplatform. evaluationItems. list</code></p>
<p><code>aiplatform. evaluationMetrics. get</code></p>
<p><code>aiplatform. evaluationMetrics. list</code></p>
<p><code>aiplatform.evaluationRuns.get</code></p>
<p><code>aiplatform.evaluationRuns.list</code></p>
<p><code>aiplatform.evaluationSets.get</code></p>
<p><code>aiplatform.evaluationSets.list</code></p>
<p><code>aiplatform.exampleStores.get</code></p>
<p><code>aiplatform.exampleStores.list</code></p>
<p><code>aiplatform. exampleStores. readExample</code></p>
<p><code>aiplatform.executions.get</code></p>
<p><code>aiplatform.executions.list</code></p>
<p><code>aiplatform. executions. queryExecutionInputsAndOutputs</code></p>
<p><code>aiplatform.extensions.get</code></p>
<p><code>aiplatform.extensions.list</code></p>
<p><code>aiplatform.featureGroups.get</code></p>
<p><code>aiplatform.featureGroups.list</code></p>
<p><code>aiplatform. featureMonitorJobs. get</code></p>
<p><code>aiplatform. featureMonitorJobs. list</code></p>
<p><code>aiplatform.featureMonitors.get</code></p>
<p><code>aiplatform. featureMonitors. list</code></p>
<p><code>aiplatform. featureOnlineStores. get</code></p>
<p><code>aiplatform. featureOnlineStores. list</code></p>
<p><code>aiplatform.featureViewSyncs.*</code></p>
<ul>
<li><code>aiplatform. featureViewSyncs. get</code></li>
<li><code>aiplatform. featureViewSyncs. list</code></li>
</ul>
<p><code>aiplatform. featureViews. fetchFeatureValues</code></p>
<p><code>aiplatform.featureViews.get</code></p>
<p><code>aiplatform.featureViews.list</code></p>
<p><code>aiplatform. featureViews. searchNearestEntities</code></p>
<p><code>aiplatform.features.get</code></p>
<p><code>aiplatform.features.list</code></p>
<p><code>aiplatform.featurestores.get</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform.humanInTheLoops.get</code></p>
<p><code>aiplatform. humanInTheLoops. list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. get</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.indexEndpoints.get</code></p>
<p><code>aiplatform.indexEndpoints.list</code></p>
<p><code>aiplatform. indexEndpoints. queryVectors</code></p>
<p><code>aiplatform.indexes.get</code></p>
<p><code>aiplatform.indexes.list</code></p>
<p><code>aiplatform.interactions.get</code></p>
<p><code>aiplatform.interactions.list</code></p>
<p><code>aiplatform.locations.get</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>aiplatform.memories.get</code></p>
<p><code>aiplatform.memories.list</code></p>
<p><code>aiplatform.memoryRevisions.get</code></p>
<p><code>aiplatform. memoryRevisions. list</code></p>
<p><code>aiplatform.metadataSchemas.get</code></p>
<p><code>aiplatform. metadataSchemas. list</code></p>
<p><code>aiplatform.metadataStores.get</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. get</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. searchStatsAnomalies</code></p>
<p><code>aiplatform. modelEvaluationSlices. get</code></p>
<p><code>aiplatform. modelEvaluationSlices. list</code></p>
<p><code>aiplatform. modelEvaluations. get</code></p>
<p><code>aiplatform. modelEvaluations. list</code></p>
<p><code>aiplatform. modelMonitoringJobs. get</code></p>
<p><code>aiplatform. modelMonitoringJobs. list</code></p>
<p><code>aiplatform.modelMonitors.get</code></p>
<p><code>aiplatform.modelMonitors.list</code></p>
<p><code>aiplatform. modelMonitors. searchModelMonitoringAlerts</code></p>
<p><code>aiplatform. modelMonitors. searchModelMonitoringStats</code></p>
<p><code>aiplatform.models.get</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform.monitoredAgents.get</code></p>
<p><code>aiplatform. monitoredAgents. list</code></p>
<p><code>aiplatform.nasJobs.get</code></p>
<p><code>aiplatform.nasJobs.list</code></p>
<p><code>aiplatform.nasTrialDetails.*</code></p>
<ul>
<li><code>aiplatform.nasTrialDetails.get</code></li>
<li><code>aiplatform. nasTrialDetails. list</code></li>
</ul>
<p><code>aiplatform. notebookExecutionJobs. get</code></p>
<p><code>aiplatform. notebookExecutionJobs. list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. get</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform. notebookRuntimes. get</code></p>
<p><code>aiplatform. notebookRuntimes. list</code></p>
<p><code>aiplatform. onlineEvaluators. get</code></p>
<p><code>aiplatform. onlineEvaluators. list</code></p>
<p><code>aiplatform.operations.list</code></p>
<p><code>aiplatform. persistentResources. get</code></p>
<p><code>aiplatform. persistentResources. list</code></p>
<p><code>aiplatform.pipelineJobs.get</code></p>
<p><code>aiplatform.pipelineJobs.list</code></p>
<p><code>aiplatform. provisionedThroughputRevisions.*</code></p>
<ul>
<li><code>aiplatform. provisionedThroughputRevisions. get</code></li>
<li><code>aiplatform. provisionedThroughputRevisions. list</code></li>
</ul>
<p><code>aiplatform. provisionedThroughputs. get</code></p>
<p><code>aiplatform. provisionedThroughputs. list</code></p>
<p><code>aiplatform.ragCorpora.get</code></p>
<p><code>aiplatform.ragCorpora.list</code></p>
<p><code>aiplatform.ragCorpora.query</code></p>
<p><code>aiplatform. ragEngineConfigs. get</code></p>
<p><code>aiplatform.ragFiles.get</code></p>
<p><code>aiplatform.ragFiles.list</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. get</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. list</code></p>
<p><code>aiplatform. reasoningEngines. get</code></p>
<p><code>aiplatform. reasoningEngines. list</code></p>
<p><code>aiplatform. reasoningEngines. query</code></p>
<p><code>aiplatform. sandboxEnvironments. get</code></p>
<p><code>aiplatform. sandboxEnvironments. list</code></p>
<p><code>aiplatform.schedules.get</code></p>
<p><code>aiplatform.schedules.list</code></p>
<p><code>aiplatform. semanticGovernancePolicies. get</code></p>
<p><code>aiplatform. semanticGovernancePolicies. list</code></p>
<p><code>aiplatform. semanticGovernancePolicyEngine. get</code></p>
<p><code>aiplatform.sessionEvents.list</code></p>
<p><code>aiplatform.sessions.get</code></p>
<p><code>aiplatform.sessions.list</code></p>
<p><code>aiplatform.specialistPools.get</code></p>
<p><code>aiplatform. specialistPools. list</code></p>
<p><code>aiplatform. specialistPools. update</code></p>
<p><code>aiplatform.studies.get</code></p>
<p><code>aiplatform.studies.list</code></p>
<p><code>aiplatform.tasks.get</code></p>
<p><code>aiplatform.tasks.list</code></p>
<p><code>aiplatform. tensorboardExperiments. get</code></p>
<p><code>aiplatform. tensorboardExperiments. list</code></p>
<p><code>aiplatform.tensorboardRuns.get</code></p>
<p><code>aiplatform. tensorboardRuns. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. batchRead</code></p>
<p><code>aiplatform. tensorboardTimeSeries. get</code></p>
<p><code>aiplatform. tensorboardTimeSeries. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. read</code></p>
<p><code>aiplatform.tensorboards.get</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. get</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>aiplatform.trials.get</code></p>
<p><code>aiplatform.trials.list</code></p>
<p><code>aiplatform.tuningJobs.get</code></p>
<p><code>aiplatform.tuningJobs.list</code></p>
<p><code>alloydb. backups. createTagBinding</code></p>
<p><code>alloydb. backups. deleteTagBinding</code></p>
<p><code>alloydb.backups.get</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb. backups. listEffectiveTags</code></p>
<p><code>alloydb. backups. listTagBindings</code></p>
<p><code>alloydb. clusters. createTagBinding</code></p>
<p><code>alloydb. clusters. deleteTagBinding</code></p>
<p><code>alloydb.clusters.export</code></p>
<p><code>alloydb. clusters. generateClientCertificate</code></p>
<p><code>alloydb.clusters.get</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb. clusters. listEffectiveTags</code></p>
<p><code>alloydb. clusters. listTagBindings</code></p>
<p><code>alloydb.databases.get</code></p>
<p><code>alloydb.databases.list</code></p>
<p><code>alloydb.instances.connect</code></p>
<p><code>alloydb.instances.executeSql</code></p>
<p><code>alloydb. instances. executeSqlReadOnly</code></p>
<p><code>alloydb.instances.get</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>alloydb.locations.*</code></p>
<ul>
<li><code>alloydb.locations.get</code></li>
<li><code>alloydb.locations.list</code></li>
</ul>
<p><code>alloydb.operations.get</code></p>
<p><code>alloydb.operations.list</code></p>
<p><code>alloydb. supportedDatabaseFlags.*</code></p>
<ul>
<li><code>alloydb. supportedDatabaseFlags. get</code></li>
<li><code>alloydb. supportedDatabaseFlags. list</code></li>
</ul>
<p><code>alloydb.users.get</code></p>
<p><code>alloydb.users.list</code></p>
<p><code>alloydb.users.login</code></p>
<p><code>apigateway. apis. createTagBinding</code></p>
<p><code>apigateway. apis. deleteTagBinding</code></p>
<p><code>apigateway. apis. listEffectiveTags</code></p>
<p><code>apigateway. apis. listTagBindings</code></p>
<p><code>apigateway. gateways. createTagBinding</code></p>
<p><code>apigateway. gateways. deleteTagBinding</code></p>
<p><code>apigateway. gateways. listEffectiveTags</code></p>
<p><code>apigateway. gateways. listTagBindings</code></p>
<p><code>apihub.apis.createTagBinding</code></p>
<p><code>apihub.apis.deleteTagBinding</code></p>
<p><code>apihub.apis.listEffectiveTags</code></p>
<p><code>apihub.apis.listTagBindings</code></p>
<p><code>apihub. deployments. createTagBinding</code></p>
<p><code>apihub. deployments. deleteTagBinding</code></p>
<p><code>apihub. deployments. listEffectiveTags</code></p>
<p><code>apihub. deployments. listTagBindings</code></p>
<p><code>artifactregistry. repositories. createTagBinding</code></p>
<p><code>artifactregistry. repositories. deleteTagBinding</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>backupdr. backupVaults. createTagBinding</code></p>
<p><code>backupdr. backupVaults. deleteTagBinding</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. managementServers. createTagBinding</code></p>
<p><code>backupdr. managementServers. deleteTagBinding</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>beyondcorp. appConnections. createTagBinding</code></p>
<p><code>beyondcorp. appConnections. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnections. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnections. listTagBindings</code></p>
<p><code>beyondcorp. appConnectors. createTagBinding</code></p>
<p><code>beyondcorp. appConnectors. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnectors. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnectors. listTagBindings</code></p>
<p><code>beyondcorp. appGateways. createTagBinding</code></p>
<p><code>beyondcorp. appGateways. deleteTagBinding</code></p>
<p><code>beyondcorp. appGateways. listEffectiveTags</code></p>
<p><code>beyondcorp. appGateways. listTagBindings</code></p>
<p><code>bigquery.bireservations.get</code></p>
<p><code>bigquery. capacityCommitments. get</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery.config.get</code></p>
<p><code>bigquery.connections.updateTag</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery. datasets. createTagBinding</code></p>
<p><code>bigquery. datasets. deleteTagBinding</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.jobs.listAll</code></p>
<p><code>bigquery. jobs. listExecutionMetadata</code></p>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery. reservationAssignments. list</code></p>
<p><code>bigquery. reservationAssignments. search</code></p>
<p><code>bigquery.reservationGroups.get</code></p>
<p><code>bigquery. reservationGroups. list</code></p>
<p><code>bigquery.reservations.get</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery. reservations. listFailoverDatasets</code></p>
<p><code>bigquery.reservations.use</code></p>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery.savedqueries.get</code></p>
<p><code>bigquery.savedqueries.list</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.createIndex</code></p>
<p><code>bigquery.tables.createSnapshot</code></p>
<p><code>bigquery. tables. createTagBinding</code></p>
<p><code>bigquery.tables.delete</code></p>
<p><code>bigquery.tables.deleteIndex</code></p>
<p><code>bigquery. tables. deleteTagBinding</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>bigquery.tables.replicateData</code></p>
<p><code>bigquery. tables. restoreSnapshot</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>bigquery.tables.updateIndex</code></p>
<p><code>bigquery.tables.updateTag</code></p>
<p><code>bigquery.transfers.get</code></p>
<p><code>bigquerymigration. translation. translate</code></p>
<p><code>bigtable. authorizedViews. createTagBinding</code></p>
<p><code>bigtable. authorizedViews. deleteTagBinding</code></p>
<p><code>bigtable. authorizedViews. listEffectiveTags</code></p>
<p><code>bigtable. authorizedViews. listTagBindings</code></p>
<p><code>bigtable. instances. createTagBinding</code></p>
<p><code>bigtable. instances. deleteTagBinding</code></p>
<p><code>bigtable. instances. listEffectiveTags</code></p>
<p><code>bigtable. instances. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. createTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. createTagBinding</code></p>
<p><code>certificatemanager. certmapentries. deleteTagBinding</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. createTagBinding</code></p>
<p><code>certificatemanager. certmaps. deleteTagBinding</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certs. createTagBinding</code></p>
<p><code>certificatemanager. certs. deleteTagBinding</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. createTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. trustconfigs. createTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>cloudaicompanion. entitlements. get</code></p>
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
<p><code>cloudasset.savedqueries.get</code></p>
<p><code>cloudasset.savedqueries.list</code></p>
<p><code>clouddeploy. deliveryPipelines. createTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. deleteTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. listEffectiveTags</code></p>
<p><code>clouddeploy. deliveryPipelines. listTagBindings</code></p>
<p><code>clouddeploy. targets. createTagBinding</code></p>
<p><code>clouddeploy. targets. deleteTagBinding</code></p>
<p><code>clouddeploy. targets. listEffectiveTags</code></p>
<p><code>clouddeploy. targets. listTagBindings</code></p>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms. keyRings. createTagBinding</code></p>
<p><code>cloudkms. keyRings. deleteTagBinding</code></p>
<p><code>cloudkms. keyRings. listEffectiveTags</code></p>
<p><code>cloudkms. keyRings. listTagBindings</code></p>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>cloudsql.instances.connect</code></p>
<p><code>cloudsql. instances. createTagBinding</code></p>
<p><code>cloudsql. instances. deleteTagBinding</code></p>
<p><code>cloudsql.instances.executeSql</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql. instances. listEffectiveTags</code></p>
<p><code>cloudsql. instances. listTagBindings</code></p>
<p><code>cloudsql.instances.login</code></p>
<p><code>composer. environments. createTagBinding</code></p>
<p><code>composer. environments. deleteTagBinding</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>compute. addresses. createTagBinding</code></p>
<p><code>compute. addresses. deleteTagBinding</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute. backendBuckets. createTagBinding</code></p>
<p><code>compute. backendBuckets. deleteTagBinding</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute. backendServices. createTagBinding</code></p>
<p><code>compute. backendServices. deleteTagBinding</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute. commitments. createTagBinding</code></p>
<p><code>compute. commitments. deleteTagBinding</code></p>
<p><code>compute. commitments. listEffectiveTags</code></p>
<p><code>compute. commitments. listTagBindings</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.deleteTagBinding</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. createTagBinding</code></p>
<p><code>compute. externalVpnGateways. deleteTagBinding</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute. firewallPolicies. createTagBinding</code></p>
<p><code>compute. firewallPolicies. deleteTagBinding</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute. firewalls. createTagBinding</code></p>
<p><code>compute. firewalls. deleteTagBinding</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute. forwardingRules. createTagBinding</code></p>
<p><code>compute. forwardingRules. deleteTagBinding</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute. futureReservations. createTagBinding</code></p>
<p><code>compute. futureReservations. deleteTagBinding</code></p>
<p><code>compute. futureReservations. listEffectiveTags</code></p>
<p><code>compute. futureReservations. listTagBindings</code></p>
<p><code>compute. globalAddresses. createTagBinding</code></p>
<p><code>compute. globalAddresses. deleteTagBinding</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. createTagBinding</code></p>
<p><code>compute. globalForwardingRules. deleteTagBinding</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. globalNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. healthChecks. createTagBinding</code></p>
<p><code>compute. healthChecks. deleteTagBinding</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute. httpHealthChecks. createTagBinding</code></p>
<p><code>compute. httpHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute. httpsHealthChecks. createTagBinding</code></p>
<p><code>compute. httpsHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute. images. createTagBinding</code></p>
<p><code>compute. images. deleteTagBinding</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. createTagBinding</code></p>
<p><code>compute. instanceGroupManagers. deleteTagBinding</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute. instanceGroups. createTagBinding</code></p>
<p><code>compute. instanceGroups. deleteTagBinding</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute. instances. deleteTagBinding</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instantSnapshots. createTagBinding</code></p>
<p><code>compute. instantSnapshots. deleteTagBinding</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. interconnectAttachments. createTagBinding</code></p>
<p><code>compute. interconnectAttachments. deleteTagBinding</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute. interconnects. createTagBinding</code></p>
<p><code>compute. interconnects. deleteTagBinding</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute. licenses. createTagBinding</code></p>
<p><code>compute. licenses. deleteTagBinding</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute. machineImages. createTagBinding</code></p>
<p><code>compute. machineImages. deleteTagBinding</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. networkAttachments. createTagBinding</code></p>
<p><code>compute. networkAttachments. deleteTagBinding</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEdgeSecurityServices. createTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. deleteTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. listEffectiveTags</code></p>
<p><code>compute. networkEdgeSecurityServices. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups. createTagBinding</code></p>
<p><code>compute. networkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. networkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. networkEndpointGroups. listTagBindings</code></p>
<p><code>compute. networks. createTagBinding</code></p>
<p><code>compute. networks. deleteTagBinding</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute. packetMirrorings. createTagBinding</code></p>
<p><code>compute. packetMirrorings. deleteTagBinding</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. createTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. deleteTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. regionBackendBuckets. createTagBinding</code></p>
<p><code>compute. regionBackendBuckets. deleteTagBinding</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. createTagBinding</code></p>
<p><code>compute. regionBackendServices. deleteTagBinding</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. createTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. deleteTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionHealthChecks. createTagBinding</code></p>
<p><code>compute. regionHealthChecks. deleteTagBinding</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. regionNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. createTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSslCertificates. createTagBinding</code></p>
<p><code>compute. regionSslCertificates. deleteTagBinding</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute. regionSslPolicies. createTagBinding</code></p>
<p><code>compute. regionSslPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute. regionUrlMaps. createTagBinding</code></p>
<p><code>compute. regionUrlMaps. deleteTagBinding</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute. reservations. createTagBinding</code></p>
<p><code>compute. reservations. deleteTagBinding</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute. routers. createTagBinding</code></p>
<p><code>compute. routers. deleteTagBinding</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute. routes. createTagBinding</code></p>
<p><code>compute. routes. deleteTagBinding</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute. securityPolicies. createTagBinding</code></p>
<p><code>compute. securityPolicies. deleteTagBinding</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute. serviceAttachments. createTagBinding</code></p>
<p><code>compute. serviceAttachments. deleteTagBinding</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute. snapshots. createTagBinding</code></p>
<p><code>compute. snapshots. deleteTagBinding</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute. sslCertificates. createTagBinding</code></p>
<p><code>compute. sslCertificates. deleteTagBinding</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute. sslPolicies. createTagBinding</code></p>
<p><code>compute. sslPolicies. deleteTagBinding</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute. storagePools. createTagBinding</code></p>
<p><code>compute. storagePools. deleteTagBinding</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute. subnetworks. createTagBinding</code></p>
<p><code>compute. subnetworks. deleteTagBinding</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute. targetGrpcProxies. createTagBinding</code></p>
<p><code>compute. targetGrpcProxies. deleteTagBinding</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute. targetHttpProxies. createTagBinding</code></p>
<p><code>compute. targetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute. targetHttpsProxies. createTagBinding</code></p>
<p><code>compute. targetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute. targetInstances. createTagBinding</code></p>
<p><code>compute. targetInstances. deleteTagBinding</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute. targetPools. createTagBinding</code></p>
<p><code>compute. targetPools. deleteTagBinding</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute. targetSslProxies. createTagBinding</code></p>
<p><code>compute. targetSslProxies. deleteTagBinding</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute. targetTcpProxies. createTagBinding</code></p>
<p><code>compute. targetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute. targetVpnGateways. createTagBinding</code></p>
<p><code>compute. targetVpnGateways. deleteTagBinding</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute. urlMaps. createTagBinding</code></p>
<p><code>compute. urlMaps. deleteTagBinding</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute. vpnGateways. createTagBinding</code></p>
<p><code>compute. vpnGateways. deleteTagBinding</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute. vpnTunnels. createTagBinding</code></p>
<p><code>compute. vpnTunnels. deleteTagBinding</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>config. deploymentgroups. createTagBinding</code></p>
<p><code>config. deploymentgroups. deleteTagBinding</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config. deployments. createTagBinding</code></p>
<p><code>config. deployments. deleteTagBinding</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config. previews. createTagBinding</code></p>
<p><code>config. previews. deleteTagBinding</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>container. clusters. createTagBinding</code></p>
<p><code>container. clusters. deleteTagBinding</code></p>
<p><code>container. clusters. listEffectiveTags</code></p>
<p><code>container. clusters. listTagBindings</code></p>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries. search</code></p>
<p><code>datacatalog. categories. fineGrainedGet</code></p>
<p><code>datacatalog.entries.updateTag</code></p>
<p><code>datacatalog. entryGroups. updateTag</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog. tagTemplates. create</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>datacatalog.tagTemplates.use</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>datafusion. instances. createTagBinding</code></p>
<p><code>datafusion. instances. deleteTagBinding</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datamigration. connectionprofiles. createTagBinding</code></p>
<p><code>datamigration. connectionprofiles. deleteTagBinding</code></p>
<p><code>datamigration. connectionprofiles. listEffectiveTags</code></p>
<p><code>datamigration. connectionprofiles. listTagBindings</code></p>
<p><code>datamigration. migrationjobs. createTagBinding</code></p>
<p><code>datamigration. migrationjobs. deleteTagBinding</code></p>
<p><code>datamigration. migrationjobs. listEffectiveTags</code></p>
<p><code>datamigration. migrationjobs. listTagBindings</code></p>
<p><code>datamigration. privateconnections. createTagBinding</code></p>
<p><code>datamigration. privateconnections. deleteTagBinding</code></p>
<p><code>datamigration. privateconnections. listEffectiveTags</code></p>
<p><code>datamigration. privateconnections. listTagBindings</code></p>
<p><code>dataplex.aspectTypes.create</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.datascans.cancel</code></p>
<p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.delete</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.getData</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.datascans.run</code></p>
<p><code>dataplex.datascans.update</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.update</code></p>
<p><code>dataplex. entryGroups. createTagBinding</code></p>
<p><code>dataplex. entryGroups. deleteTagBinding</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryTypes. createTagBinding</code></p>
<p><code>dataplex. entryTypes. deleteTagBinding</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.governanceRules.*</code></p>
<ul>
<li><code>dataplex. governanceRules. createTagBinding</code></li>
<li><code>dataplex. governanceRules. deleteTagBinding</code></li>
<li><code>dataplex. governanceRules. listEffectiveTags</code></li>
<li><code>dataplex. governanceRules. listTagBindings</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>datastore. databases. createTagBinding</code></p>
<p><code>datastore. databases. deleteTagBinding</code></p>
<p><code>datastore. databases. listEffectiveTags</code></p>
<p><code>datastore. databases. listTagBindings</code></p>
<p><code>datastream. connectionProfiles. createTagBinding</code></p>
<p><code>datastream. connectionProfiles. deleteTagBinding</code></p>
<p><code>datastream. connectionProfiles. listEffectiveTags</code></p>
<p><code>datastream. connectionProfiles. listTagBindings</code></p>
<p><code>datastream. privateConnections. createTagBinding</code></p>
<p><code>datastream. privateConnections. deleteTagBinding</code></p>
<p><code>datastream. privateConnections. listEffectiveTags</code></p>
<p><code>datastream. privateConnections. listTagBindings</code></p>
<p><code>datastream. streams. createTagBinding</code></p>
<p><code>datastream. streams. deleteTagBinding</code></p>
<p><code>datastream. streams. listEffectiveTags</code></p>
<p><code>datastream. streams. listTagBindings</code></p>
<p><code>dlp.*</code></p>
<ul>
<li><code>dlp. analyzeRiskTemplates. create</code></li>
<li><code>dlp. analyzeRiskTemplates. delete</code></li>
<li><code>dlp.analyzeRiskTemplates.get</code></li>
<li><code>dlp.analyzeRiskTemplates.list</code></li>
<li><code>dlp. analyzeRiskTemplates. update</code></li>
<li><code>dlp.charts.get</code></li>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
<li><code>dlp.connections.create</code></li>
<li><code>dlp.connections.delete</code></li>
<li><code>dlp.connections.get</code></li>
<li><code>dlp.connections.list</code></li>
<li><code>dlp.connections.search</code></li>
<li><code>dlp.connections.update</code></li>
<li><code>dlp.contentPolicies.apply</code></li>
<li><code>dlp.contentPolicies.create</code></li>
<li><code>dlp.contentPolicies.delete</code></li>
<li><code>dlp.contentPolicies.get</code></li>
<li><code>dlp.contentPolicies.list</code></li>
<li><code>dlp.contentPolicies.update</code></li>
<li><code>dlp.deidentifyTemplates.create</code></li>
<li><code>dlp.deidentifyTemplates.delete</code></li>
<li><code>dlp.deidentifyTemplates.get</code></li>
<li><code>dlp.deidentifyTemplates.list</code></li>
<li><code>dlp.deidentifyTemplates.update</code></li>
<li><code>dlp.estimates.cancel</code></li>
<li><code>dlp.estimates.create</code></li>
<li><code>dlp.estimates.delete</code></li>
<li><code>dlp.estimates.get</code></li>
<li><code>dlp.estimates.list</code></li>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
<li><code>dlp.inspectFindings.list</code></li>
<li><code>dlp.inspectTemplates.create</code></li>
<li><code>dlp.inspectTemplates.delete</code></li>
<li><code>dlp.inspectTemplates.get</code></li>
<li><code>dlp.inspectTemplates.list</code></li>
<li><code>dlp.inspectTemplates.update</code></li>
<li><code>dlp.jobTriggers.create</code></li>
<li><code>dlp.jobTriggers.delete</code></li>
<li><code>dlp.jobTriggers.get</code></li>
<li><code>dlp.jobTriggers.hybridInspect</code></li>
<li><code>dlp.jobTriggers.list</code></li>
<li><code>dlp.jobTriggers.update</code></li>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
<li><code>dlp.kms.encrypt</code></li>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
<li><code>dlp.storedInfoTypes.create</code></li>
<li><code>dlp.storedInfoTypes.delete</code></li>
<li><code>dlp.storedInfoTypes.get</code></li>
<li><code>dlp.storedInfoTypes.list</code></li>
<li><code>dlp.storedInfoTypes.update</code></li>
<li><code>dlp.subscriptions.cancel</code></li>
<li><code>dlp.subscriptions.create</code></li>
<li><code>dlp.subscriptions.get</code></li>
<li><code>dlp.subscriptions.list</code></li>
<li><code>dlp.subscriptions.update</code></li>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul>
<p><code>dns.policies.createTagBinding</code></p>
<p><code>dns.policies.deleteTagBinding</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>domains. registrations. createTagBinding</code></p>
<p><code>domains. registrations. deleteTagBinding</code></p>
<p><code>domains. registrations. listEffectiveTags</code></p>
<p><code>domains. registrations. listTagBindings</code></p>
<p><code>eventarc. channelConnections. createTagBinding</code></p>
<p><code>eventarc. channelConnections. deleteTagBinding</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channels. createTagBinding</code></p>
<p><code>eventarc. channels. deleteTagBinding</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc. triggers. createTagBinding</code></p>
<p><code>eventarc. triggers. deleteTagBinding</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>file.backups.createTagBinding</code></p>
<p><code>file.backups.deleteTagBinding</code></p>
<p><code>file.backups.listEffectiveTags</code></p>
<p><code>file.backups.listTagBindings</code></p>
<p><code>file. instances. createTagBinding</code></p>
<p><code>file. instances. deleteTagBinding</code></p>
<p><code>file. instances. listEffectiveTags</code></p>
<p><code>file.instances.listTagBindings</code></p>
<p><code>file.snapshots.*</code></p>
<ul>
<li><code>file. snapshots. createTagBinding</code></li>
<li><code>file. snapshots. deleteTagBinding</code></li>
<li><code>file. snapshots. listEffectiveTags</code></li>
<li><code>file.snapshots.listTagBindings</code></li>
</ul>
<p><code>financialservices. v1instances. createTagBinding</code></p>
<p><code>financialservices. v1instances. deleteTagBinding</code></p>
<p><code>financialservices. v1instances. listEffectiveTags</code></p>
<p><code>financialservices. v1instances. listTagBindings</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>gkemulticloud. attachedClusters. createTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. deleteTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareClusters. listTagBindings</code></p>
<p><code>iam.roles.createTagBinding</code></p>
<p><code>iam.roles.deleteTagBinding</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam. serviceAccounts. createTagBinding</code></p>
<p><code>iam. serviceAccounts. deleteTagBinding</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>krmapihosting. krmApiHosts. createTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. deleteTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>livestream. channels. createTagBinding</code></p>
<p><code>livestream. channels. deleteTagBinding</code></p>
<p><code>livestream. channels. listEffectiveTags</code></p>
<p><code>livestream. channels. listTagBindings</code></p>
<p><code>livestream. inputs. createTagBinding</code></p>
<p><code>livestream. inputs. deleteTagBinding</code></p>
<p><code>livestream. inputs. listEffectiveTags</code></p>
<p><code>livestream. inputs. listTagBindings</code></p>
<p><code>livestream. pools. createTagBinding</code></p>
<p><code>livestream. pools. deleteTagBinding</code></p>
<p><code>livestream. pools. listEffectiveTags</code></p>
<p><code>livestream. pools. listTagBindings</code></p>
<p><code>logging. buckets. createTagBinding</code></p>
<p><code>logging. buckets. deleteTagBinding</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>looker. instances. createTagBinding</code></p>
<p><code>looker. instances. deleteTagBinding</code></p>
<p><code>looker. instances. listEffectiveTags</code></p>
<p><code>looker. instances. listTagBindings</code></p>
<p><code>managedidentities. domains. createTagBinding</code></p>
<p><code>managedidentities. domains. deleteTagBinding</code></p>
<p><code>managedidentities. domains. listEffectiveTags</code></p>
<p><code>managedidentities. domains. listTagBindings</code></p>
<p><code>memcache. instances. createTagBinding</code></p>
<p><code>memcache. instances. deleteTagBinding</code></p>
<p><code>memcache. instances. listEffectiveTags</code></p>
<p><code>memcache. instances. listTagBindings</code></p>
<p><code>metastore. federations. createTagBinding</code></p>
<p><code>metastore. federations. deleteTagBinding</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore. services. createTagBinding</code></p>
<p><code>metastore. services. deleteTagBinding</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>monitoring. alertPolicies. createTagBinding</code></p>
<p><code>monitoring. alertPolicies. deleteTagBinding</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring. dashboards. createTagBinding</code></p>
<p><code>monitoring. dashboards. deleteTagBinding</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>networkconnectivity. hubs. createTagBinding</code></p>
<p><code>networkconnectivity. hubs. deleteTagBinding</code></p>
<p><code>networkconnectivity. hubs. listEffectiveTags</code></p>
<p><code>networkconnectivity. hubs. listTagBindings</code></p>
<p><code>networkconnectivity. spokes. createTagBinding</code></p>
<p><code>networkconnectivity. spokes. deleteTagBinding</code></p>
<p><code>networkconnectivity. spokes. listEffectiveTags</code></p>
<p><code>networkconnectivity. spokes. listTagBindings</code></p>
<p><code>networkmanagement. connectivitytests. createTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. deleteTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networksecurity. authorizationPolicies. createTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. authorizationPolicies. listTagBindings</code></p>
<p><code>networksecurity. clientTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. clientTlsPolicies. listTagBindings</code></p>
<p><code>networksecurity. serverTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. serverTlsPolicies. listTagBindings</code></p>
<p><code>networkservices. endpointConfigSelectors.*</code></p>
<ul>
<li><code>networkservices. endpointConfigSelectors. createTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. deleteTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></li>
<li><code>networkservices. endpointConfigSelectors. listTagBindings</code></li>
</ul>
<p><code>networkservices. gateways. createTagBinding</code></p>
<p><code>networkservices. gateways. deleteTagBinding</code></p>
<p><code>networkservices. gateways. listEffectiveTags</code></p>
<p><code>networkservices. gateways. listTagBindings</code></p>
<p><code>networkservices. httpFilters. createTagBinding</code></p>
<p><code>networkservices. httpFilters. deleteTagBinding</code></p>
<p><code>networkservices. httpFilters. listEffectiveTags</code></p>
<p><code>networkservices. httpFilters. listTagBindings</code></p>
<p><code>networkservices. meshes. createTagBinding</code></p>
<p><code>networkservices. meshes. deleteTagBinding</code></p>
<p><code>networkservices. meshes. listEffectiveTags</code></p>
<p><code>networkservices. meshes. listTagBindings</code></p>
<p><code>notebooks. instances. createTagBinding</code></p>
<p><code>notebooks. instances. deleteTagBinding</code></p>
<p><code>notebooks. instances. listEffectiveTags</code></p>
<p><code>notebooks. instances. listTagBindings</code></p>
<p><code>parametermanager. parameters. createTagBinding</code></p>
<p><code>parametermanager. parameters. deleteTagBinding</code></p>
<p><code>parametermanager. parameters. listEffectiveTags</code></p>
<p><code>parametermanager. parameters. listTagBindings</code></p>
<p><code>privateca. caPools. createTagBinding</code></p>
<p><code>privateca. caPools. deleteTagBinding</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. createTagBinding</code></p>
<p><code>privateca. certificateTemplates. deleteTagBinding</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>pubsub. snapshots. createTagBinding</code></p>
<p><code>pubsub. snapshots. deleteTagBinding</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub. subscriptions. createTagBinding</code></p>
<p><code>pubsub. subscriptions. deleteTagBinding</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.topics.createTagBinding</code></p>
<p><code>pubsub.topics.deleteTagBinding</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>recaptchaenterprise. keys. createTagBinding</code></p>
<p><code>recaptchaenterprise. keys. deleteTagBinding</code></p>
<p><code>recaptchaenterprise. keys. listEffectiveTags</code></p>
<p><code>recaptchaenterprise. keys. listTagBindings</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. get</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. list</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. get</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. get</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. list</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. get</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>redis. clusters. createTagBinding</code></p>
<p><code>redis. clusters. deleteTagBinding</code></p>
<p><code>redis. clusters. listEffectiveTags</code></p>
<p><code>redis.clusters.listTagBindings</code></p>
<p><code>redis. instances. createTagBinding</code></p>
<p><code>redis. instances. deleteTagBinding</code></p>
<p><code>redis. instances. listEffectiveTags</code></p>
<p><code>redis. instances. listTagBindings</code></p>
<p><code>resourcemanager. hierarchyNodes.*</code></p>
<ul>
<li><code>resourcemanager. hierarchyNodes. createTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></li>
<li><code>resourcemanager. hierarchyNodes. listTagBindings</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager. tagValueBindings.*</code></p>
<ul>
<li><code>resourcemanager. tagValueBindings. create</code></li>
<li><code>resourcemanager. tagValueBindings. delete</code></li>
</ul>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>run.jobs.createTagBinding</code></p>
<p><code>run.jobs.deleteTagBinding</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.services.createTagBinding</code></p>
<p><code>run.services.deleteTagBinding</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>secretmanager. secrets. createTagBinding</code></p>
<p><code>secretmanager. secrets. deleteTagBinding</code></p>
<p><code>secretmanager. secrets. listEffectiveTags</code></p>
<p><code>secretmanager. secrets. listTagBindings</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>spanner. instances. createTagBinding</code></p>
<p><code>spanner. instances. deleteTagBinding</code></p>
<p><code>spanner. instances. listEffectiveTags</code></p>
<p><code>spanner. instances. listTagBindings</code></p>
<p><code>storage. buckets. createTagBinding</code></p>
<p><code>storage. buckets. deleteTagBinding</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p>
<p><code>tpu.nodes.createTagBinding</code></p>
<p><code>tpu.nodes.deleteTagBinding</code></p>
<p><code>tpu.nodes.listEffectiveTags</code></p>
<p><code>tpu.nodes.listTagBindings</code></p>
<p><code>transcoder. jobTemplates. createTagBinding</code></p>
<p><code>transcoder. jobTemplates. deleteTagBinding</code></p>
<p><code>transcoder. jobTemplates. listEffectiveTags</code></p>
<p><code>transcoder. jobTemplates. listTagBindings</code></p>
<p><code>transcoder. jobs. createTagBinding</code></p>
<p><code>transcoder. jobs. deleteTagBinding</code></p>
<p><code>transcoder. jobs. listEffectiveTags</code></p>
<p><code>transcoder. jobs. listTagBindings</code></p>
<p><code>videostitcher. cdnKeys. createTagBinding</code></p>
<p><code>videostitcher. cdnKeys. deleteTagBinding</code></p>
<p><code>videostitcher. cdnKeys. listEffectiveTags</code></p>
<p><code>videostitcher. cdnKeys. listTagBindings</code></p>
<p><code>videostitcher. liveConfigs. createTagBinding</code></p>
<p><code>videostitcher. liveConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. liveConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. liveConfigs. listTagBindings</code></p>
<p><code>videostitcher. slates. createTagBinding</code></p>
<p><code>videostitcher. slates. deleteTagBinding</code></p>
<p><code>videostitcher. slates. listEffectiveTags</code></p>
<p><code>videostitcher. slates. listTagBindings</code></p>
<p><code>videostitcher. vodConfigs. createTagBinding</code></p>
<p><code>videostitcher. vodConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. vodConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. vodConfigs. listTagBindings</code></p>
<p><code>vmmigration. groups. createTagBinding</code></p>
<p><code>vmmigration. groups. deleteTagBinding</code></p>
<p><code>vmmigration. groups. listEffectiveTags</code></p>
<p><code>vmmigration. groups. listTagBindings</code></p>
<p><code>vmmigration. sources. createTagBinding</code></p>
<p><code>vmmigration. sources. deleteTagBinding</code></p>
<p><code>vmmigration. sources. listEffectiveTags</code></p>
<p><code>vmmigration. sources. listTagBindings</code></p>
<p><code>vmwareengine. networkPeerings. createTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. createTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. createTagBinding</code></p>
<p><code>vmwareengine. privateClouds. deleteTagBinding</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. createTagBinding</code></p>
<p><code>vmwareengine. privateConnections. deleteTagBinding</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p>
<p><code>workflows. workflows. createTagBinding</code></p>
<p><code>workflows. workflows. deleteTagBinding</code></p>
<p><code>workflows. workflows. listEffectiveTags</code></p>
<p><code>workflows. workflows. listTagBindings</code></p>
<p><code>workstations. workstationClusters. createTagBinding</code></p>
<p><code>workstations. workstationClusters. deleteTagBinding</code></p>
<p><code>workstations. workstationClusters. listEffectiveTags</code></p>
<p><code>workstations. workstationClusters. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>DLP Project Data Profiles Reader
<p>( <code>roles/ dlp.projectDataProfilesReader</code> )</p>
<p>Read DLP project profiles.</p></td>
<td><p><code>dlp.projectDataProfiles.*</code></p>
<ul>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>DLP Project Data Profiles Driver
<p>( <code>roles/ dlp.projectdriver</code> )</p>
<p>Permissions needed by the DLP service account to generate data profiles within a project.</p></td>
<td><p><code>aiplatform. agentAnomalyDetectionScopes. get</code></p>
<p><code>aiplatform. agentAnomalyDetectionScopes. list</code></p>
<p><code>aiplatform.agentExamples.get</code></p>
<p><code>aiplatform.agentExamples.list</code></p>
<p><code>aiplatform.agents.get</code></p>
<p><code>aiplatform.agents.list</code></p>
<p><code>aiplatform. analyzedInvocations.*</code></p>
<ul>
<li><code>aiplatform. analyzedInvocations. get</code></li>
<li><code>aiplatform. analyzedInvocations. list</code></li>
</ul>
<p><code>aiplatform.analyzedSessions.*</code></p>
<ul>
<li><code>aiplatform. analyzedSessions. aggregate</code></li>
<li><code>aiplatform. analyzedSessions. get</code></li>
<li><code>aiplatform. analyzedSessions. list</code></li>
</ul>
<p><code>aiplatform.annotationSpecs.get</code></p>
<p><code>aiplatform. annotationSpecs. list</code></p>
<p><code>aiplatform.annotations.get</code></p>
<p><code>aiplatform.annotations.list</code></p>
<p><code>aiplatform.apps.get</code></p>
<p><code>aiplatform.apps.list</code></p>
<p><code>aiplatform.artifacts.get</code></p>
<p><code>aiplatform.artifacts.list</code></p>
<p><code>aiplatform. batchPredictionJobs. get</code></p>
<p><code>aiplatform. batchPredictionJobs. list</code></p>
<p><code>aiplatform.cacheConfigs.get</code></p>
<p><code>aiplatform.cachedContents.get</code></p>
<p><code>aiplatform.cachedContents.list</code></p>
<p><code>aiplatform.consents.get</code></p>
<p><code>aiplatform.contexts.get</code></p>
<p><code>aiplatform.contexts.list</code></p>
<p><code>aiplatform. contexts. queryContextLineageSubgraph</code></p>
<p><code>aiplatform.customJobs.get</code></p>
<p><code>aiplatform.customJobs.list</code></p>
<p><code>aiplatform.dataItems.get</code></p>
<p><code>aiplatform.dataItems.list</code></p>
<p><code>aiplatform. dataLabelingJobs. get</code></p>
<p><code>aiplatform. dataLabelingJobs. list</code></p>
<p><code>aiplatform.datasetVersions.get</code></p>
<p><code>aiplatform. datasetVersions. list</code></p>
<p><code>aiplatform.datasets.get</code></p>
<p><code>aiplatform.datasets.list</code></p>
<p><code>aiplatform. deploymentResourcePools. get</code></p>
<p><code>aiplatform. deploymentResourcePools. list</code></p>
<p><code>aiplatform. deploymentResourcePools. queryDeployedModels</code></p>
<p><code>aiplatform. edgeDeploymentJobs. get</code></p>
<p><code>aiplatform. edgeDeploymentJobs. list</code></p>
<p><code>aiplatform. edgeDeviceDebugInfo. get</code></p>
<p><code>aiplatform.edgeDevices.get</code></p>
<p><code>aiplatform.edgeDevices.list</code></p>
<p><code>aiplatform.endpoints.get</code></p>
<p><code>aiplatform.endpoints.list</code></p>
<p><code>aiplatform.entityTypes.get</code></p>
<p><code>aiplatform.entityTypes.list</code></p>
<p><code>aiplatform. evaluationExperiments. get</code></p>
<p><code>aiplatform. evaluationExperiments. list</code></p>
<p><code>aiplatform.evaluationItems.get</code></p>
<p><code>aiplatform. evaluationItems. list</code></p>
<p><code>aiplatform. evaluationMetrics. get</code></p>
<p><code>aiplatform. evaluationMetrics. list</code></p>
<p><code>aiplatform.evaluationRuns.get</code></p>
<p><code>aiplatform.evaluationRuns.list</code></p>
<p><code>aiplatform.evaluationSets.get</code></p>
<p><code>aiplatform.evaluationSets.list</code></p>
<p><code>aiplatform.exampleStores.get</code></p>
<p><code>aiplatform.exampleStores.list</code></p>
<p><code>aiplatform. exampleStores. readExample</code></p>
<p><code>aiplatform.executions.get</code></p>
<p><code>aiplatform.executions.list</code></p>
<p><code>aiplatform. executions. queryExecutionInputsAndOutputs</code></p>
<p><code>aiplatform.extensions.get</code></p>
<p><code>aiplatform.extensions.list</code></p>
<p><code>aiplatform.featureGroups.get</code></p>
<p><code>aiplatform.featureGroups.list</code></p>
<p><code>aiplatform. featureMonitorJobs. get</code></p>
<p><code>aiplatform. featureMonitorJobs. list</code></p>
<p><code>aiplatform.featureMonitors.get</code></p>
<p><code>aiplatform. featureMonitors. list</code></p>
<p><code>aiplatform. featureOnlineStores. get</code></p>
<p><code>aiplatform. featureOnlineStores. list</code></p>
<p><code>aiplatform.featureViewSyncs.*</code></p>
<ul>
<li><code>aiplatform. featureViewSyncs. get</code></li>
<li><code>aiplatform. featureViewSyncs. list</code></li>
</ul>
<p><code>aiplatform. featureViews. fetchFeatureValues</code></p>
<p><code>aiplatform.featureViews.get</code></p>
<p><code>aiplatform.featureViews.list</code></p>
<p><code>aiplatform. featureViews. searchNearestEntities</code></p>
<p><code>aiplatform.features.get</code></p>
<p><code>aiplatform.features.list</code></p>
<p><code>aiplatform.featurestores.get</code></p>
<p><code>aiplatform.featurestores.list</code></p>
<p><code>aiplatform.humanInTheLoops.get</code></p>
<p><code>aiplatform. humanInTheLoops. list</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. get</code></p>
<p><code>aiplatform. hyperparameterTuningJobs. list</code></p>
<p><code>aiplatform.indexEndpoints.get</code></p>
<p><code>aiplatform.indexEndpoints.list</code></p>
<p><code>aiplatform. indexEndpoints. queryVectors</code></p>
<p><code>aiplatform.indexes.get</code></p>
<p><code>aiplatform.indexes.list</code></p>
<p><code>aiplatform.interactions.get</code></p>
<p><code>aiplatform.interactions.list</code></p>
<p><code>aiplatform.locations.get</code></p>
<p><code>aiplatform.locations.list</code></p>
<p><code>aiplatform.memories.get</code></p>
<p><code>aiplatform.memories.list</code></p>
<p><code>aiplatform.memoryRevisions.get</code></p>
<p><code>aiplatform. memoryRevisions. list</code></p>
<p><code>aiplatform.metadataSchemas.get</code></p>
<p><code>aiplatform. metadataSchemas. list</code></p>
<p><code>aiplatform.metadataStores.get</code></p>
<p><code>aiplatform.metadataStores.list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. get</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. list</code></p>
<p><code>aiplatform. modelDeploymentMonitoringJobs. searchStatsAnomalies</code></p>
<p><code>aiplatform. modelEvaluationSlices. get</code></p>
<p><code>aiplatform. modelEvaluationSlices. list</code></p>
<p><code>aiplatform. modelEvaluations. get</code></p>
<p><code>aiplatform. modelEvaluations. list</code></p>
<p><code>aiplatform. modelMonitoringJobs. get</code></p>
<p><code>aiplatform. modelMonitoringJobs. list</code></p>
<p><code>aiplatform.modelMonitors.get</code></p>
<p><code>aiplatform.modelMonitors.list</code></p>
<p><code>aiplatform. modelMonitors. searchModelMonitoringAlerts</code></p>
<p><code>aiplatform. modelMonitors. searchModelMonitoringStats</code></p>
<p><code>aiplatform.models.get</code></p>
<p><code>aiplatform.models.list</code></p>
<p><code>aiplatform.monitoredAgents.get</code></p>
<p><code>aiplatform. monitoredAgents. list</code></p>
<p><code>aiplatform.nasJobs.get</code></p>
<p><code>aiplatform.nasJobs.list</code></p>
<p><code>aiplatform.nasTrialDetails.*</code></p>
<ul>
<li><code>aiplatform.nasTrialDetails.get</code></li>
<li><code>aiplatform. nasTrialDetails. list</code></li>
</ul>
<p><code>aiplatform. notebookExecutionJobs. get</code></p>
<p><code>aiplatform. notebookExecutionJobs. list</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. get</code></p>
<p><code>aiplatform. notebookRuntimeTemplates. list</code></p>
<p><code>aiplatform. notebookRuntimes. get</code></p>
<p><code>aiplatform. notebookRuntimes. list</code></p>
<p><code>aiplatform. onlineEvaluators. get</code></p>
<p><code>aiplatform. onlineEvaluators. list</code></p>
<p><code>aiplatform.operations.list</code></p>
<p><code>aiplatform. persistentResources. get</code></p>
<p><code>aiplatform. persistentResources. list</code></p>
<p><code>aiplatform.pipelineJobs.get</code></p>
<p><code>aiplatform.pipelineJobs.list</code></p>
<p><code>aiplatform. provisionedThroughputRevisions.*</code></p>
<ul>
<li><code>aiplatform. provisionedThroughputRevisions. get</code></li>
<li><code>aiplatform. provisionedThroughputRevisions. list</code></li>
</ul>
<p><code>aiplatform. provisionedThroughputs. get</code></p>
<p><code>aiplatform. provisionedThroughputs. list</code></p>
<p><code>aiplatform.ragCorpora.get</code></p>
<p><code>aiplatform.ragCorpora.list</code></p>
<p><code>aiplatform.ragCorpora.query</code></p>
<p><code>aiplatform. ragEngineConfigs. get</code></p>
<p><code>aiplatform.ragFiles.get</code></p>
<p><code>aiplatform.ragFiles.list</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. get</code></p>
<p><code>aiplatform. reasoningEngineRuntimeRevisions. list</code></p>
<p><code>aiplatform. reasoningEngines. get</code></p>
<p><code>aiplatform. reasoningEngines. list</code></p>
<p><code>aiplatform. reasoningEngines. query</code></p>
<p><code>aiplatform. sandboxEnvironments. get</code></p>
<p><code>aiplatform. sandboxEnvironments. list</code></p>
<p><code>aiplatform.schedules.get</code></p>
<p><code>aiplatform.schedules.list</code></p>
<p><code>aiplatform. semanticGovernancePolicies. get</code></p>
<p><code>aiplatform. semanticGovernancePolicies. list</code></p>
<p><code>aiplatform. semanticGovernancePolicyEngine. get</code></p>
<p><code>aiplatform.sessionEvents.list</code></p>
<p><code>aiplatform.sessions.get</code></p>
<p><code>aiplatform.sessions.list</code></p>
<p><code>aiplatform.specialistPools.get</code></p>
<p><code>aiplatform. specialistPools. list</code></p>
<p><code>aiplatform. specialistPools. update</code></p>
<p><code>aiplatform.studies.get</code></p>
<p><code>aiplatform.studies.list</code></p>
<p><code>aiplatform.tasks.get</code></p>
<p><code>aiplatform.tasks.list</code></p>
<p><code>aiplatform. tensorboardExperiments. get</code></p>
<p><code>aiplatform. tensorboardExperiments. list</code></p>
<p><code>aiplatform.tensorboardRuns.get</code></p>
<p><code>aiplatform. tensorboardRuns. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. batchRead</code></p>
<p><code>aiplatform. tensorboardTimeSeries. get</code></p>
<p><code>aiplatform. tensorboardTimeSeries. list</code></p>
<p><code>aiplatform. tensorboardTimeSeries. read</code></p>
<p><code>aiplatform.tensorboards.get</code></p>
<p><code>aiplatform.tensorboards.list</code></p>
<p><code>aiplatform. trainingPipelines. get</code></p>
<p><code>aiplatform. trainingPipelines. list</code></p>
<p><code>aiplatform.trials.get</code></p>
<p><code>aiplatform.trials.list</code></p>
<p><code>aiplatform.tuningJobs.get</code></p>
<p><code>aiplatform.tuningJobs.list</code></p>
<p><code>alloydb. backups. createTagBinding</code></p>
<p><code>alloydb. backups. deleteTagBinding</code></p>
<p><code>alloydb.backups.get</code></p>
<p><code>alloydb.backups.list</code></p>
<p><code>alloydb. backups. listEffectiveTags</code></p>
<p><code>alloydb. backups. listTagBindings</code></p>
<p><code>alloydb. clusters. createTagBinding</code></p>
<p><code>alloydb. clusters. deleteTagBinding</code></p>
<p><code>alloydb.clusters.export</code></p>
<p><code>alloydb. clusters. generateClientCertificate</code></p>
<p><code>alloydb.clusters.get</code></p>
<p><code>alloydb.clusters.list</code></p>
<p><code>alloydb. clusters. listEffectiveTags</code></p>
<p><code>alloydb. clusters. listTagBindings</code></p>
<p><code>alloydb.databases.get</code></p>
<p><code>alloydb.databases.list</code></p>
<p><code>alloydb.instances.connect</code></p>
<p><code>alloydb.instances.executeSql</code></p>
<p><code>alloydb. instances. executeSqlReadOnly</code></p>
<p><code>alloydb.instances.get</code></p>
<p><code>alloydb.instances.list</code></p>
<p><code>alloydb.locations.*</code></p>
<ul>
<li><code>alloydb.locations.get</code></li>
<li><code>alloydb.locations.list</code></li>
</ul>
<p><code>alloydb.operations.get</code></p>
<p><code>alloydb.operations.list</code></p>
<p><code>alloydb. supportedDatabaseFlags.*</code></p>
<ul>
<li><code>alloydb. supportedDatabaseFlags. get</code></li>
<li><code>alloydb. supportedDatabaseFlags. list</code></li>
</ul>
<p><code>alloydb.users.get</code></p>
<p><code>alloydb.users.list</code></p>
<p><code>alloydb.users.login</code></p>
<p><code>apigateway. apis. createTagBinding</code></p>
<p><code>apigateway. apis. deleteTagBinding</code></p>
<p><code>apigateway. apis. listEffectiveTags</code></p>
<p><code>apigateway. apis. listTagBindings</code></p>
<p><code>apigateway. gateways. createTagBinding</code></p>
<p><code>apigateway. gateways. deleteTagBinding</code></p>
<p><code>apigateway. gateways. listEffectiveTags</code></p>
<p><code>apigateway. gateways. listTagBindings</code></p>
<p><code>apihub.apis.createTagBinding</code></p>
<p><code>apihub.apis.deleteTagBinding</code></p>
<p><code>apihub.apis.listEffectiveTags</code></p>
<p><code>apihub.apis.listTagBindings</code></p>
<p><code>apihub. deployments. createTagBinding</code></p>
<p><code>apihub. deployments. deleteTagBinding</code></p>
<p><code>apihub. deployments. listEffectiveTags</code></p>
<p><code>apihub. deployments. listTagBindings</code></p>
<p><code>artifactregistry. repositories. createTagBinding</code></p>
<p><code>artifactregistry. repositories. deleteTagBinding</code></p>
<p><code>artifactregistry. repositories. listEffectiveTags</code></p>
<p><code>artifactregistry. repositories. listTagBindings</code></p>
<p><code>backupdr. backupVaults. createTagBinding</code></p>
<p><code>backupdr. backupVaults. deleteTagBinding</code></p>
<p><code>backupdr. backupVaults. listEffectiveTags</code></p>
<p><code>backupdr. backupVaults. listTagBindings</code></p>
<p><code>backupdr. managementServers. createTagBinding</code></p>
<p><code>backupdr. managementServers. deleteTagBinding</code></p>
<p><code>backupdr. managementServers. listEffectiveTags</code></p>
<p><code>backupdr. managementServers. listTagBindings</code></p>
<p><code>beyondcorp. appConnections. createTagBinding</code></p>
<p><code>beyondcorp. appConnections. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnections. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnections. listTagBindings</code></p>
<p><code>beyondcorp. appConnectors. createTagBinding</code></p>
<p><code>beyondcorp. appConnectors. deleteTagBinding</code></p>
<p><code>beyondcorp. appConnectors. listEffectiveTags</code></p>
<p><code>beyondcorp. appConnectors. listTagBindings</code></p>
<p><code>beyondcorp. appGateways. createTagBinding</code></p>
<p><code>beyondcorp. appGateways. deleteTagBinding</code></p>
<p><code>beyondcorp. appGateways. listEffectiveTags</code></p>
<p><code>beyondcorp. appGateways. listTagBindings</code></p>
<p><code>bigquery.bireservations.get</code></p>
<p><code>bigquery. capacityCommitments. get</code></p>
<p><code>bigquery. capacityCommitments. list</code></p>
<p><code>bigquery.config.get</code></p>
<p><code>bigquery.connections.updateTag</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery. datasets. createTagBinding</code></p>
<p><code>bigquery. datasets. deleteTagBinding</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.datasets.getIamPolicy</code></p>
<p><code>bigquery. datasets. listEffectiveTags</code></p>
<p><code>bigquery. datasets. listTagBindings</code></p>
<p><code>bigquery.datasets.updateTag</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.jobs.list</code></p>
<p><code>bigquery.jobs.listAll</code></p>
<p><code>bigquery. jobs. listExecutionMetadata</code></p>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery. reservationAssignments. list</code></p>
<p><code>bigquery. reservationAssignments. search</code></p>
<p><code>bigquery.reservationGroups.get</code></p>
<p><code>bigquery. reservationGroups. list</code></p>
<p><code>bigquery.reservations.get</code></p>
<p><code>bigquery.reservations.list</code></p>
<p><code>bigquery. reservations. listFailoverDatasets</code></p>
<p><code>bigquery.reservations.use</code></p>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery.savedqueries.get</code></p>
<p><code>bigquery.savedqueries.list</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.createIndex</code></p>
<p><code>bigquery.tables.createSnapshot</code></p>
<p><code>bigquery. tables. createTagBinding</code></p>
<p><code>bigquery.tables.delete</code></p>
<p><code>bigquery.tables.deleteIndex</code></p>
<p><code>bigquery. tables. deleteTagBinding</code></p>
<p><code>bigquery.tables.export</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.getIamPolicy</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery. tables. listEffectiveTags</code></p>
<p><code>bigquery. tables. listTagBindings</code></p>
<p><code>bigquery.tables.replicateData</code></p>
<p><code>bigquery. tables. restoreSnapshot</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>bigquery.tables.updateIndex</code></p>
<p><code>bigquery.tables.updateTag</code></p>
<p><code>bigquery.transfers.get</code></p>
<p><code>bigquerymigration. translation. translate</code></p>
<p><code>bigtable. authorizedViews. createTagBinding</code></p>
<p><code>bigtable. authorizedViews. deleteTagBinding</code></p>
<p><code>bigtable. authorizedViews. listEffectiveTags</code></p>
<p><code>bigtable. authorizedViews. listTagBindings</code></p>
<p><code>bigtable. instances. createTagBinding</code></p>
<p><code>bigtable. instances. deleteTagBinding</code></p>
<p><code>bigtable. instances. listEffectiveTags</code></p>
<p><code>bigtable. instances. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. createTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. createTagBinding</code></p>
<p><code>certificatemanager. certmapentries. deleteTagBinding</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. createTagBinding</code></p>
<p><code>certificatemanager. certmaps. deleteTagBinding</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certs. createTagBinding</code></p>
<p><code>certificatemanager. certs. deleteTagBinding</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. createTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. deleteTagBinding</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. trustconfigs. createTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. deleteTagBinding</code></p>
<p><code>certificatemanager. trustconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. trustconfigs. listTagBindings</code></p>
<p><code>cloudaicompanion. entitlements. get</code></p>
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
<p><code>cloudasset.savedqueries.get</code></p>
<p><code>cloudasset.savedqueries.list</code></p>
<p><code>clouddeploy. deliveryPipelines. createTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. deleteTagBinding</code></p>
<p><code>clouddeploy. deliveryPipelines. listEffectiveTags</code></p>
<p><code>clouddeploy. deliveryPipelines. listTagBindings</code></p>
<p><code>clouddeploy. targets. createTagBinding</code></p>
<p><code>clouddeploy. targets. deleteTagBinding</code></p>
<p><code>clouddeploy. targets. listEffectiveTags</code></p>
<p><code>clouddeploy. targets. listTagBindings</code></p>
<p><code>cloudkms.keyHandles.*</code></p>
<ul>
<li><code>cloudkms.keyHandles.create</code></li>
<li><code>cloudkms.keyHandles.get</code></li>
<li><code>cloudkms.keyHandles.list</code></li>
</ul>
<p><code>cloudkms. keyRings. createTagBinding</code></p>
<p><code>cloudkms. keyRings. deleteTagBinding</code></p>
<p><code>cloudkms. keyRings. listEffectiveTags</code></p>
<p><code>cloudkms. keyRings. listTagBindings</code></p>
<p><code>cloudkms.operations.get</code></p>
<p><code>cloudkms. projects. showEffectiveAutokeyConfig</code></p>
<p><code>cloudsql.instances.connect</code></p>
<p><code>cloudsql. instances. createTagBinding</code></p>
<p><code>cloudsql. instances. deleteTagBinding</code></p>
<p><code>cloudsql.instances.executeSql</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql. instances. listEffectiveTags</code></p>
<p><code>cloudsql. instances. listTagBindings</code></p>
<p><code>cloudsql.instances.login</code></p>
<p><code>composer. environments. createTagBinding</code></p>
<p><code>composer. environments. deleteTagBinding</code></p>
<p><code>composer. environments. listEffectiveTags</code></p>
<p><code>composer. environments. listTagBindings</code></p>
<p><code>compute. addresses. createTagBinding</code></p>
<p><code>compute. addresses. deleteTagBinding</code></p>
<p><code>compute. addresses. listEffectiveTags</code></p>
<p><code>compute. addresses. listTagBindings</code></p>
<p><code>compute. backendBuckets. createTagBinding</code></p>
<p><code>compute. backendBuckets. deleteTagBinding</code></p>
<p><code>compute. backendBuckets. listEffectiveTags</code></p>
<p><code>compute. backendBuckets. listTagBindings</code></p>
<p><code>compute. backendServices. createTagBinding</code></p>
<p><code>compute. backendServices. deleteTagBinding</code></p>
<p><code>compute. backendServices. listEffectiveTags</code></p>
<p><code>compute. backendServices. listTagBindings</code></p>
<p><code>compute. commitments. createTagBinding</code></p>
<p><code>compute. commitments. deleteTagBinding</code></p>
<p><code>compute. commitments. listEffectiveTags</code></p>
<p><code>compute. commitments. listTagBindings</code></p>
<p><code>compute.disks.createTagBinding</code></p>
<p><code>compute.disks.deleteTagBinding</code></p>
<p><code>compute. disks. listEffectiveTags</code></p>
<p><code>compute.disks.listTagBindings</code></p>
<p><code>compute. externalVpnGateways. createTagBinding</code></p>
<p><code>compute. externalVpnGateways. deleteTagBinding</code></p>
<p><code>compute. externalVpnGateways. listEffectiveTags</code></p>
<p><code>compute. externalVpnGateways. listTagBindings</code></p>
<p><code>compute. firewallPolicies. createTagBinding</code></p>
<p><code>compute. firewallPolicies. deleteTagBinding</code></p>
<p><code>compute. firewallPolicies. listEffectiveTags</code></p>
<p><code>compute. firewallPolicies. listTagBindings</code></p>
<p><code>compute. firewalls. createTagBinding</code></p>
<p><code>compute. firewalls. deleteTagBinding</code></p>
<p><code>compute. firewalls. listEffectiveTags</code></p>
<p><code>compute. firewalls. listTagBindings</code></p>
<p><code>compute. forwardingRules. createTagBinding</code></p>
<p><code>compute. forwardingRules. deleteTagBinding</code></p>
<p><code>compute. forwardingRules. listEffectiveTags</code></p>
<p><code>compute. forwardingRules. listTagBindings</code></p>
<p><code>compute. futureReservations. createTagBinding</code></p>
<p><code>compute. futureReservations. deleteTagBinding</code></p>
<p><code>compute. futureReservations. listEffectiveTags</code></p>
<p><code>compute. futureReservations. listTagBindings</code></p>
<p><code>compute. globalAddresses. createTagBinding</code></p>
<p><code>compute. globalAddresses. deleteTagBinding</code></p>
<p><code>compute. globalAddresses. listEffectiveTags</code></p>
<p><code>compute. globalAddresses. listTagBindings</code></p>
<p><code>compute. globalForwardingRules. createTagBinding</code></p>
<p><code>compute. globalForwardingRules. deleteTagBinding</code></p>
<p><code>compute. globalForwardingRules. listEffectiveTags</code></p>
<p><code>compute. globalForwardingRules. listTagBindings</code></p>
<p><code>compute. globalNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. globalNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. globalNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. healthChecks. createTagBinding</code></p>
<p><code>compute. healthChecks. deleteTagBinding</code></p>
<p><code>compute. healthChecks. listEffectiveTags</code></p>
<p><code>compute. healthChecks. listTagBindings</code></p>
<p><code>compute. httpHealthChecks. createTagBinding</code></p>
<p><code>compute. httpHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpHealthChecks. listTagBindings</code></p>
<p><code>compute. httpsHealthChecks. createTagBinding</code></p>
<p><code>compute. httpsHealthChecks. deleteTagBinding</code></p>
<p><code>compute. httpsHealthChecks. listEffectiveTags</code></p>
<p><code>compute. httpsHealthChecks. listTagBindings</code></p>
<p><code>compute. images. createTagBinding</code></p>
<p><code>compute. images. deleteTagBinding</code></p>
<p><code>compute. images. listEffectiveTags</code></p>
<p><code>compute.images.listTagBindings</code></p>
<p><code>compute. instanceGroupManagers. createTagBinding</code></p>
<p><code>compute. instanceGroupManagers. deleteTagBinding</code></p>
<p><code>compute. instanceGroupManagers. listEffectiveTags</code></p>
<p><code>compute. instanceGroupManagers. listTagBindings</code></p>
<p><code>compute. instanceGroups. createTagBinding</code></p>
<p><code>compute. instanceGroups. deleteTagBinding</code></p>
<p><code>compute. instanceGroups. listEffectiveTags</code></p>
<p><code>compute. instanceGroups. listTagBindings</code></p>
<p><code>compute. instances. createTagBinding</code></p>
<p><code>compute. instances. deleteTagBinding</code></p>
<p><code>compute. instances. listEffectiveTags</code></p>
<p><code>compute. instances. listTagBindings</code></p>
<p><code>compute. instantSnapshots. createTagBinding</code></p>
<p><code>compute. instantSnapshots. deleteTagBinding</code></p>
<p><code>compute. instantSnapshots. listEffectiveTags</code></p>
<p><code>compute. instantSnapshots. listTagBindings</code></p>
<p><code>compute. interconnectAttachments. createTagBinding</code></p>
<p><code>compute. interconnectAttachments. deleteTagBinding</code></p>
<p><code>compute. interconnectAttachments. listEffectiveTags</code></p>
<p><code>compute. interconnectAttachments. listTagBindings</code></p>
<p><code>compute. interconnects. createTagBinding</code></p>
<p><code>compute. interconnects. deleteTagBinding</code></p>
<p><code>compute. interconnects. listEffectiveTags</code></p>
<p><code>compute. interconnects. listTagBindings</code></p>
<p><code>compute. licenses. createTagBinding</code></p>
<p><code>compute. licenses. deleteTagBinding</code></p>
<p><code>compute. licenses. listEffectiveTags</code></p>
<p><code>compute. licenses. listTagBindings</code></p>
<p><code>compute. machineImages. createTagBinding</code></p>
<p><code>compute. machineImages. deleteTagBinding</code></p>
<p><code>compute. machineImages. listEffectiveTags</code></p>
<p><code>compute. machineImages. listTagBindings</code></p>
<p><code>compute. networkAttachments. createTagBinding</code></p>
<p><code>compute. networkAttachments. deleteTagBinding</code></p>
<p><code>compute. networkAttachments. listEffectiveTags</code></p>
<p><code>compute. networkAttachments. listTagBindings</code></p>
<p><code>compute. networkEdgeSecurityServices. createTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. deleteTagBinding</code></p>
<p><code>compute. networkEdgeSecurityServices. listEffectiveTags</code></p>
<p><code>compute. networkEdgeSecurityServices. listTagBindings</code></p>
<p><code>compute. networkEndpointGroups. createTagBinding</code></p>
<p><code>compute. networkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. networkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. networkEndpointGroups. listTagBindings</code></p>
<p><code>compute. networks. createTagBinding</code></p>
<p><code>compute. networks. deleteTagBinding</code></p>
<p><code>compute. networks. listEffectiveTags</code></p>
<p><code>compute. networks. listTagBindings</code></p>
<p><code>compute. packetMirrorings. createTagBinding</code></p>
<p><code>compute. packetMirrorings. deleteTagBinding</code></p>
<p><code>compute. packetMirrorings. listEffectiveTags</code></p>
<p><code>compute. packetMirrorings. listTagBindings</code></p>
<p><code>compute. publicDelegatedPrefixes. createTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. deleteTagBinding</code></p>
<p><code>compute. publicDelegatedPrefixes. listEffectiveTags</code></p>
<p><code>compute. publicDelegatedPrefixes. listTagBindings</code></p>
<p><code>compute. regionBackendBuckets. createTagBinding</code></p>
<p><code>compute. regionBackendBuckets. deleteTagBinding</code></p>
<p><code>compute. regionBackendBuckets. listEffectiveTags</code></p>
<p><code>compute. regionBackendBuckets. listTagBindings</code></p>
<p><code>compute. regionBackendServices. createTagBinding</code></p>
<p><code>compute. regionBackendServices. deleteTagBinding</code></p>
<p><code>compute. regionBackendServices. listEffectiveTags</code></p>
<p><code>compute. regionBackendServices. listTagBindings</code></p>
<p><code>compute. regionFirewallPolicies. createTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. deleteTagBinding</code></p>
<p><code>compute. regionFirewallPolicies. listEffectiveTags</code></p>
<p><code>compute. regionFirewallPolicies. listTagBindings</code></p>
<p><code>compute. regionHealthChecks. createTagBinding</code></p>
<p><code>compute. regionHealthChecks. deleteTagBinding</code></p>
<p><code>compute. regionHealthChecks. listEffectiveTags</code></p>
<p><code>compute. regionHealthChecks. listTagBindings</code></p>
<p><code>compute. regionNetworkEndpointGroups. createTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. deleteTagBinding</code></p>
<p><code>compute. regionNetworkEndpointGroups. listEffectiveTags</code></p>
<p><code>compute. regionNetworkEndpointGroups. listTagBindings</code></p>
<p><code>compute. regionSecurityPolicies. createTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSecurityPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSecurityPolicies. listTagBindings</code></p>
<p><code>compute. regionSslCertificates. createTagBinding</code></p>
<p><code>compute. regionSslCertificates. deleteTagBinding</code></p>
<p><code>compute. regionSslCertificates. listEffectiveTags</code></p>
<p><code>compute. regionSslCertificates. listTagBindings</code></p>
<p><code>compute. regionSslPolicies. createTagBinding</code></p>
<p><code>compute. regionSslPolicies. deleteTagBinding</code></p>
<p><code>compute. regionSslPolicies. listEffectiveTags</code></p>
<p><code>compute. regionSslPolicies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetHttpsProxies. createTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetHttpsProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. createTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute. regionUrlMaps. createTagBinding</code></p>
<p><code>compute. regionUrlMaps. deleteTagBinding</code></p>
<p><code>compute. regionUrlMaps. listEffectiveTags</code></p>
<p><code>compute. regionUrlMaps. listTagBindings</code></p>
<p><code>compute. reservations. createTagBinding</code></p>
<p><code>compute. reservations. deleteTagBinding</code></p>
<p><code>compute. reservations. listEffectiveTags</code></p>
<p><code>compute. reservations. listTagBindings</code></p>
<p><code>compute. routers. createTagBinding</code></p>
<p><code>compute. routers. deleteTagBinding</code></p>
<p><code>compute. routers. listEffectiveTags</code></p>
<p><code>compute. routers. listTagBindings</code></p>
<p><code>compute. routes. createTagBinding</code></p>
<p><code>compute. routes. deleteTagBinding</code></p>
<p><code>compute. routes. listEffectiveTags</code></p>
<p><code>compute.routes.listTagBindings</code></p>
<p><code>compute. securityPolicies. createTagBinding</code></p>
<p><code>compute. securityPolicies. deleteTagBinding</code></p>
<p><code>compute. securityPolicies. listEffectiveTags</code></p>
<p><code>compute. securityPolicies. listTagBindings</code></p>
<p><code>compute. serviceAttachments. createTagBinding</code></p>
<p><code>compute. serviceAttachments. deleteTagBinding</code></p>
<p><code>compute. serviceAttachments. listEffectiveTags</code></p>
<p><code>compute. serviceAttachments. listTagBindings</code></p>
<p><code>compute. snapshots. createTagBinding</code></p>
<p><code>compute. snapshots. deleteTagBinding</code></p>
<p><code>compute. snapshots. listEffectiveTags</code></p>
<p><code>compute. snapshots. listTagBindings</code></p>
<p><code>compute. sslCertificates. createTagBinding</code></p>
<p><code>compute. sslCertificates. deleteTagBinding</code></p>
<p><code>compute. sslCertificates. listEffectiveTags</code></p>
<p><code>compute. sslCertificates. listTagBindings</code></p>
<p><code>compute. sslPolicies. createTagBinding</code></p>
<p><code>compute. sslPolicies. deleteTagBinding</code></p>
<p><code>compute. sslPolicies. listEffectiveTags</code></p>
<p><code>compute. sslPolicies. listTagBindings</code></p>
<p><code>compute. storagePools. createTagBinding</code></p>
<p><code>compute. storagePools. deleteTagBinding</code></p>
<p><code>compute. storagePools. listEffectiveTags</code></p>
<p><code>compute. storagePools. listTagBindings</code></p>
<p><code>compute. subnetworks. createTagBinding</code></p>
<p><code>compute. subnetworks. deleteTagBinding</code></p>
<p><code>compute. subnetworks. listEffectiveTags</code></p>
<p><code>compute. subnetworks. listTagBindings</code></p>
<p><code>compute. targetGrpcProxies. createTagBinding</code></p>
<p><code>compute. targetGrpcProxies. deleteTagBinding</code></p>
<p><code>compute. targetGrpcProxies. listEffectiveTags</code></p>
<p><code>compute. targetGrpcProxies. listTagBindings</code></p>
<p><code>compute. targetHttpProxies. createTagBinding</code></p>
<p><code>compute. targetHttpProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpProxies. listTagBindings</code></p>
<p><code>compute. targetHttpsProxies. createTagBinding</code></p>
<p><code>compute. targetHttpsProxies. deleteTagBinding</code></p>
<p><code>compute. targetHttpsProxies. listEffectiveTags</code></p>
<p><code>compute. targetHttpsProxies. listTagBindings</code></p>
<p><code>compute. targetInstances. createTagBinding</code></p>
<p><code>compute. targetInstances. deleteTagBinding</code></p>
<p><code>compute. targetInstances. listEffectiveTags</code></p>
<p><code>compute. targetInstances. listTagBindings</code></p>
<p><code>compute. targetPools. createTagBinding</code></p>
<p><code>compute. targetPools. deleteTagBinding</code></p>
<p><code>compute. targetPools. listEffectiveTags</code></p>
<p><code>compute. targetPools. listTagBindings</code></p>
<p><code>compute. targetSslProxies. createTagBinding</code></p>
<p><code>compute. targetSslProxies. deleteTagBinding</code></p>
<p><code>compute. targetSslProxies. listEffectiveTags</code></p>
<p><code>compute. targetSslProxies. listTagBindings</code></p>
<p><code>compute. targetTcpProxies. createTagBinding</code></p>
<p><code>compute. targetTcpProxies. deleteTagBinding</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute. targetVpnGateways. createTagBinding</code></p>
<p><code>compute. targetVpnGateways. deleteTagBinding</code></p>
<p><code>compute. targetVpnGateways. listEffectiveTags</code></p>
<p><code>compute. targetVpnGateways. listTagBindings</code></p>
<p><code>compute. urlMaps. createTagBinding</code></p>
<p><code>compute. urlMaps. deleteTagBinding</code></p>
<p><code>compute. urlMaps. listEffectiveTags</code></p>
<p><code>compute. urlMaps. listTagBindings</code></p>
<p><code>compute. vpnGateways. createTagBinding</code></p>
<p><code>compute. vpnGateways. deleteTagBinding</code></p>
<p><code>compute. vpnGateways. listEffectiveTags</code></p>
<p><code>compute. vpnGateways. listTagBindings</code></p>
<p><code>compute. vpnTunnels. createTagBinding</code></p>
<p><code>compute. vpnTunnels. deleteTagBinding</code></p>
<p><code>compute. vpnTunnels. listEffectiveTags</code></p>
<p><code>compute. vpnTunnels. listTagBindings</code></p>
<p><code>config. deploymentgroups. createTagBinding</code></p>
<p><code>config. deploymentgroups. deleteTagBinding</code></p>
<p><code>config. deploymentgroups. listEffectiveTags</code></p>
<p><code>config. deploymentgroups. listTagBindings</code></p>
<p><code>config. deployments. createTagBinding</code></p>
<p><code>config. deployments. deleteTagBinding</code></p>
<p><code>config. deployments. listEffectiveTags</code></p>
<p><code>config. deployments. listTagBindings</code></p>
<p><code>config. previews. createTagBinding</code></p>
<p><code>config. previews. deleteTagBinding</code></p>
<p><code>config. previews. listEffectiveTags</code></p>
<p><code>config. previews. listTagBindings</code></p>
<p><code>container. clusters. createTagBinding</code></p>
<p><code>container. clusters. deleteTagBinding</code></p>
<p><code>container. clusters. listEffectiveTags</code></p>
<p><code>container. clusters. listTagBindings</code></p>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries. search</code></p>
<p><code>datacatalog. categories. fineGrainedGet</code></p>
<p><code>datacatalog.entries.updateTag</code></p>
<p><code>datacatalog. entryGroups. updateTag</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog. tagTemplates. create</code></p>
<p><code>datacatalog.tagTemplates.get</code></p>
<p><code>datacatalog. tagTemplates. getTag</code></p>
<p><code>datacatalog.tagTemplates.use</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform. repositories. createTagBinding</code></p>
<p><code>dataform. repositories. deleteTagBinding</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataform. repositories. listEffectiveTags</code></p>
<p><code>dataform. repositories. listTagBindings</code></p>
<p><code>datafusion. instances. createTagBinding</code></p>
<p><code>datafusion. instances. deleteTagBinding</code></p>
<p><code>datafusion. instances. listEffectiveTags</code></p>
<p><code>datafusion. instances. listTagBindings</code></p>
<p><code>datamigration. connectionprofiles. createTagBinding</code></p>
<p><code>datamigration. connectionprofiles. deleteTagBinding</code></p>
<p><code>datamigration. connectionprofiles. listEffectiveTags</code></p>
<p><code>datamigration. connectionprofiles. listTagBindings</code></p>
<p><code>datamigration. migrationjobs. createTagBinding</code></p>
<p><code>datamigration. migrationjobs. deleteTagBinding</code></p>
<p><code>datamigration. migrationjobs. listEffectiveTags</code></p>
<p><code>datamigration. migrationjobs. listTagBindings</code></p>
<p><code>datamigration. privateconnections. createTagBinding</code></p>
<p><code>datamigration. privateconnections. deleteTagBinding</code></p>
<p><code>datamigration. privateconnections. listEffectiveTags</code></p>
<p><code>datamigration. privateconnections. listTagBindings</code></p>
<p><code>dataplex.aspectTypes.create</code></p>
<p><code>dataplex.aspectTypes.get</code></p>
<p><code>dataplex.aspectTypes.list</code></p>
<p><code>dataplex.aspectTypes.use</code></p>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.datascans.cancel</code></p>
<p><code>dataplex.datascans.create</code></p>
<p><code>dataplex.datascans.delete</code></p>
<p><code>dataplex.datascans.get</code></p>
<p><code>dataplex.datascans.getData</code></p>
<p><code>dataplex. datascans. getIamPolicy</code></p>
<p><code>dataplex.datascans.list</code></p>
<p><code>dataplex.datascans.run</code></p>
<p><code>dataplex.datascans.update</code></p>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.entries.update</code></p>
<p><code>dataplex. entryGroups. createTagBinding</code></p>
<p><code>dataplex. entryGroups. deleteTagBinding</code></p>
<p><code>dataplex. entryGroups. listEffectiveTags</code></p>
<p><code>dataplex. entryGroups. listTagBindings</code></p>
<p><code>dataplex. entryTypes. createTagBinding</code></p>
<p><code>dataplex. entryTypes. deleteTagBinding</code></p>
<p><code>dataplex. entryTypes. listEffectiveTags</code></p>
<p><code>dataplex. entryTypes. listTagBindings</code></p>
<p><code>dataplex.governanceRules.*</code></p>
<ul>
<li><code>dataplex. governanceRules. createTagBinding</code></li>
<li><code>dataplex. governanceRules. deleteTagBinding</code></li>
<li><code>dataplex. governanceRules. listEffectiveTags</code></li>
<li><code>dataplex. governanceRules. listTagBindings</code></li>
</ul>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>datastore. databases. createTagBinding</code></p>
<p><code>datastore. databases. deleteTagBinding</code></p>
<p><code>datastore. databases. listEffectiveTags</code></p>
<p><code>datastore. databases. listTagBindings</code></p>
<p><code>datastream. connectionProfiles. createTagBinding</code></p>
<p><code>datastream. connectionProfiles. deleteTagBinding</code></p>
<p><code>datastream. connectionProfiles. listEffectiveTags</code></p>
<p><code>datastream. connectionProfiles. listTagBindings</code></p>
<p><code>datastream. privateConnections. createTagBinding</code></p>
<p><code>datastream. privateConnections. deleteTagBinding</code></p>
<p><code>datastream. privateConnections. listEffectiveTags</code></p>
<p><code>datastream. privateConnections. listTagBindings</code></p>
<p><code>datastream. streams. createTagBinding</code></p>
<p><code>datastream. streams. deleteTagBinding</code></p>
<p><code>datastream. streams. listEffectiveTags</code></p>
<p><code>datastream. streams. listTagBindings</code></p>
<p><code>dlp.*</code></p>
<ul>
<li><code>dlp. analyzeRiskTemplates. create</code></li>
<li><code>dlp. analyzeRiskTemplates. delete</code></li>
<li><code>dlp.analyzeRiskTemplates.get</code></li>
<li><code>dlp.analyzeRiskTemplates.list</code></li>
<li><code>dlp. analyzeRiskTemplates. update</code></li>
<li><code>dlp.charts.get</code></li>
<li><code>dlp.columnDataProfiles.get</code></li>
<li><code>dlp.columnDataProfiles.list</code></li>
<li><code>dlp.connections.create</code></li>
<li><code>dlp.connections.delete</code></li>
<li><code>dlp.connections.get</code></li>
<li><code>dlp.connections.list</code></li>
<li><code>dlp.connections.search</code></li>
<li><code>dlp.connections.update</code></li>
<li><code>dlp.contentPolicies.apply</code></li>
<li><code>dlp.contentPolicies.create</code></li>
<li><code>dlp.contentPolicies.delete</code></li>
<li><code>dlp.contentPolicies.get</code></li>
<li><code>dlp.contentPolicies.list</code></li>
<li><code>dlp.contentPolicies.update</code></li>
<li><code>dlp.deidentifyTemplates.create</code></li>
<li><code>dlp.deidentifyTemplates.delete</code></li>
<li><code>dlp.deidentifyTemplates.get</code></li>
<li><code>dlp.deidentifyTemplates.list</code></li>
<li><code>dlp.deidentifyTemplates.update</code></li>
<li><code>dlp.estimates.cancel</code></li>
<li><code>dlp.estimates.create</code></li>
<li><code>dlp.estimates.delete</code></li>
<li><code>dlp.estimates.get</code></li>
<li><code>dlp.estimates.list</code></li>
<li><code>dlp.fileStoreProfiles.delete</code></li>
<li><code>dlp.fileStoreProfiles.get</code></li>
<li><code>dlp.fileStoreProfiles.list</code></li>
<li><code>dlp.inspectFindings.list</code></li>
<li><code>dlp.inspectTemplates.create</code></li>
<li><code>dlp.inspectTemplates.delete</code></li>
<li><code>dlp.inspectTemplates.get</code></li>
<li><code>dlp.inspectTemplates.list</code></li>
<li><code>dlp.inspectTemplates.update</code></li>
<li><code>dlp.jobTriggers.create</code></li>
<li><code>dlp.jobTriggers.delete</code></li>
<li><code>dlp.jobTriggers.get</code></li>
<li><code>dlp.jobTriggers.hybridInspect</code></li>
<li><code>dlp.jobTriggers.list</code></li>
<li><code>dlp.jobTriggers.update</code></li>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
<li><code>dlp.kms.encrypt</code></li>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
<li><code>dlp.projectDataProfiles.get</code></li>
<li><code>dlp.projectDataProfiles.list</code></li>
<li><code>dlp.storedInfoTypes.create</code></li>
<li><code>dlp.storedInfoTypes.delete</code></li>
<li><code>dlp.storedInfoTypes.get</code></li>
<li><code>dlp.storedInfoTypes.list</code></li>
<li><code>dlp.storedInfoTypes.update</code></li>
<li><code>dlp.subscriptions.cancel</code></li>
<li><code>dlp.subscriptions.create</code></li>
<li><code>dlp.subscriptions.get</code></li>
<li><code>dlp.subscriptions.list</code></li>
<li><code>dlp.subscriptions.update</code></li>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul>
<p><code>dns.policies.createTagBinding</code></p>
<p><code>dns.policies.deleteTagBinding</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>domains. registrations. createTagBinding</code></p>
<p><code>domains. registrations. deleteTagBinding</code></p>
<p><code>domains. registrations. listEffectiveTags</code></p>
<p><code>domains. registrations. listTagBindings</code></p>
<p><code>eventarc. channelConnections. createTagBinding</code></p>
<p><code>eventarc. channelConnections. deleteTagBinding</code></p>
<p><code>eventarc. channelConnections. listEffectiveTags</code></p>
<p><code>eventarc. channelConnections. listTagBindings</code></p>
<p><code>eventarc. channels. createTagBinding</code></p>
<p><code>eventarc. channels. deleteTagBinding</code></p>
<p><code>eventarc. channels. listEffectiveTags</code></p>
<p><code>eventarc. channels. listTagBindings</code></p>
<p><code>eventarc. triggers. createTagBinding</code></p>
<p><code>eventarc. triggers. deleteTagBinding</code></p>
<p><code>eventarc. triggers. listEffectiveTags</code></p>
<p><code>eventarc. triggers. listTagBindings</code></p>
<p><code>file.backups.createTagBinding</code></p>
<p><code>file.backups.deleteTagBinding</code></p>
<p><code>file.backups.listEffectiveTags</code></p>
<p><code>file.backups.listTagBindings</code></p>
<p><code>file. instances. createTagBinding</code></p>
<p><code>file. instances. deleteTagBinding</code></p>
<p><code>file. instances. listEffectiveTags</code></p>
<p><code>file.instances.listTagBindings</code></p>
<p><code>file.snapshots.*</code></p>
<ul>
<li><code>file. snapshots. createTagBinding</code></li>
<li><code>file. snapshots. deleteTagBinding</code></li>
<li><code>file. snapshots. listEffectiveTags</code></li>
<li><code>file.snapshots.listTagBindings</code></li>
</ul>
<p><code>financialservices. v1instances. createTagBinding</code></p>
<p><code>financialservices. v1instances. deleteTagBinding</code></p>
<p><code>financialservices. v1instances. listEffectiveTags</code></p>
<p><code>financialservices. v1instances. listTagBindings</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>gkemulticloud. attachedClusters. createTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. deleteTagBinding</code></p>
<p><code>gkemulticloud. attachedClusters. listEffectiveTags</code></p>
<p><code>gkemulticloud. attachedClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. bareMetalClusters. createTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. bareMetalClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. bareMetalClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareAdminClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareAdminClusters. listTagBindings</code></p>
<p><code>gkeonprem. vmwareClusters. createTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. deleteTagBinding</code></p>
<p><code>gkeonprem. vmwareClusters. listEffectiveTags</code></p>
<p><code>gkeonprem. vmwareClusters. listTagBindings</code></p>
<p><code>iam.roles.createTagBinding</code></p>
<p><code>iam.roles.deleteTagBinding</code></p>
<p><code>iam.roles.listEffectiveTags</code></p>
<p><code>iam.roles.listTagBindings</code></p>
<p><code>iam. serviceAccounts. createTagBinding</code></p>
<p><code>iam. serviceAccounts. deleteTagBinding</code></p>
<p><code>iam. serviceAccounts. listEffectiveTags</code></p>
<p><code>iam. serviceAccounts. listTagBindings</code></p>
<p><code>krmapihosting. krmApiHosts. createTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. deleteTagBinding</code></p>
<p><code>krmapihosting. krmApiHosts. listEffectiveTags</code></p>
<p><code>krmapihosting. krmApiHosts. listTagBindings</code></p>
<p><code>livestream. channels. createTagBinding</code></p>
<p><code>livestream. channels. deleteTagBinding</code></p>
<p><code>livestream. channels. listEffectiveTags</code></p>
<p><code>livestream. channels. listTagBindings</code></p>
<p><code>livestream. inputs. createTagBinding</code></p>
<p><code>livestream. inputs. deleteTagBinding</code></p>
<p><code>livestream. inputs. listEffectiveTags</code></p>
<p><code>livestream. inputs. listTagBindings</code></p>
<p><code>livestream. pools. createTagBinding</code></p>
<p><code>livestream. pools. deleteTagBinding</code></p>
<p><code>livestream. pools. listEffectiveTags</code></p>
<p><code>livestream. pools. listTagBindings</code></p>
<p><code>logging. buckets. createTagBinding</code></p>
<p><code>logging. buckets. deleteTagBinding</code></p>
<p><code>logging. buckets. listEffectiveTags</code></p>
<p><code>logging. buckets. listTagBindings</code></p>
<p><code>looker. instances. createTagBinding</code></p>
<p><code>looker. instances. deleteTagBinding</code></p>
<p><code>looker. instances. listEffectiveTags</code></p>
<p><code>looker. instances. listTagBindings</code></p>
<p><code>managedidentities. domains. createTagBinding</code></p>
<p><code>managedidentities. domains. deleteTagBinding</code></p>
<p><code>managedidentities. domains. listEffectiveTags</code></p>
<p><code>managedidentities. domains. listTagBindings</code></p>
<p><code>memcache. instances. createTagBinding</code></p>
<p><code>memcache. instances. deleteTagBinding</code></p>
<p><code>memcache. instances. listEffectiveTags</code></p>
<p><code>memcache. instances. listTagBindings</code></p>
<p><code>metastore. federations. createTagBinding</code></p>
<p><code>metastore. federations. deleteTagBinding</code></p>
<p><code>metastore. federations. listEffectiveTags</code></p>
<p><code>metastore. federations. listTagBindings</code></p>
<p><code>metastore. services. createTagBinding</code></p>
<p><code>metastore. services. deleteTagBinding</code></p>
<p><code>metastore. services. listEffectiveTags</code></p>
<p><code>metastore. services. listTagBindings</code></p>
<p><code>monitoring. alertPolicies. createTagBinding</code></p>
<p><code>monitoring. alertPolicies. deleteTagBinding</code></p>
<p><code>monitoring. alertPolicies. listEffectiveTags</code></p>
<p><code>monitoring. alertPolicies. listTagBindings</code></p>
<p><code>monitoring. dashboards. createTagBinding</code></p>
<p><code>monitoring. dashboards. deleteTagBinding</code></p>
<p><code>monitoring. dashboards. listEffectiveTags</code></p>
<p><code>monitoring. dashboards. listTagBindings</code></p>
<p><code>monitoring.timeSeries.create</code></p>
<p><code>networkconnectivity. hubs. createTagBinding</code></p>
<p><code>networkconnectivity. hubs. deleteTagBinding</code></p>
<p><code>networkconnectivity. hubs. listEffectiveTags</code></p>
<p><code>networkconnectivity. hubs. listTagBindings</code></p>
<p><code>networkconnectivity. spokes. createTagBinding</code></p>
<p><code>networkconnectivity. spokes. deleteTagBinding</code></p>
<p><code>networkconnectivity. spokes. listEffectiveTags</code></p>
<p><code>networkconnectivity. spokes. listTagBindings</code></p>
<p><code>networkmanagement. connectivitytests. createTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. deleteTagBinding</code></p>
<p><code>networkmanagement. connectivitytests. listEffectiveTags</code></p>
<p><code>networkmanagement. connectivitytests. listTagBindings</code></p>
<p><code>networksecurity. authorizationPolicies. createTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. authorizationPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. authorizationPolicies. listTagBindings</code></p>
<p><code>networksecurity. clientTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. clientTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. clientTlsPolicies. listTagBindings</code></p>
<p><code>networksecurity. serverTlsPolicies. createTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. deleteTagBinding</code></p>
<p><code>networksecurity. serverTlsPolicies. listEffectiveTags</code></p>
<p><code>networksecurity. serverTlsPolicies. listTagBindings</code></p>
<p><code>networkservices. endpointConfigSelectors.*</code></p>
<ul>
<li><code>networkservices. endpointConfigSelectors. createTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. deleteTagBinding</code></li>
<li><code>networkservices. endpointConfigSelectors. listEffectiveTags</code></li>
<li><code>networkservices. endpointConfigSelectors. listTagBindings</code></li>
</ul>
<p><code>networkservices. gateways. createTagBinding</code></p>
<p><code>networkservices. gateways. deleteTagBinding</code></p>
<p><code>networkservices. gateways. listEffectiveTags</code></p>
<p><code>networkservices. gateways. listTagBindings</code></p>
<p><code>networkservices. httpFilters. createTagBinding</code></p>
<p><code>networkservices. httpFilters. deleteTagBinding</code></p>
<p><code>networkservices. httpFilters. listEffectiveTags</code></p>
<p><code>networkservices. httpFilters. listTagBindings</code></p>
<p><code>networkservices. meshes. createTagBinding</code></p>
<p><code>networkservices. meshes. deleteTagBinding</code></p>
<p><code>networkservices. meshes. listEffectiveTags</code></p>
<p><code>networkservices. meshes. listTagBindings</code></p>
<p><code>notebooks. instances. createTagBinding</code></p>
<p><code>notebooks. instances. deleteTagBinding</code></p>
<p><code>notebooks. instances. listEffectiveTags</code></p>
<p><code>notebooks. instances. listTagBindings</code></p>
<p><code>parametermanager. parameters. createTagBinding</code></p>
<p><code>parametermanager. parameters. deleteTagBinding</code></p>
<p><code>parametermanager. parameters. listEffectiveTags</code></p>
<p><code>parametermanager. parameters. listTagBindings</code></p>
<p><code>privateca. caPools. createTagBinding</code></p>
<p><code>privateca. caPools. deleteTagBinding</code></p>
<p><code>privateca. caPools. listEffectiveTags</code></p>
<p><code>privateca. caPools. listTagBindings</code></p>
<p><code>privateca. certificateTemplates. createTagBinding</code></p>
<p><code>privateca. certificateTemplates. deleteTagBinding</code></p>
<p><code>privateca. certificateTemplates. listEffectiveTags</code></p>
<p><code>privateca. certificateTemplates. listTagBindings</code></p>
<p><code>pubsub. snapshots. createTagBinding</code></p>
<p><code>pubsub. snapshots. deleteTagBinding</code></p>
<p><code>pubsub. snapshots. listEffectiveTags</code></p>
<p><code>pubsub. snapshots. listTagBindings</code></p>
<p><code>pubsub. subscriptions. createTagBinding</code></p>
<p><code>pubsub. subscriptions. deleteTagBinding</code></p>
<p><code>pubsub. subscriptions. listEffectiveTags</code></p>
<p><code>pubsub. subscriptions. listTagBindings</code></p>
<p><code>pubsub.topics.createTagBinding</code></p>
<p><code>pubsub.topics.deleteTagBinding</code></p>
<p><code>pubsub. topics. listEffectiveTags</code></p>
<p><code>pubsub.topics.listTagBindings</code></p>
<p><code>pubsub.topics.updateTag</code></p>
<p><code>recaptchaenterprise. keys. createTagBinding</code></p>
<p><code>recaptchaenterprise. keys. deleteTagBinding</code></p>
<p><code>recaptchaenterprise. keys. listEffectiveTags</code></p>
<p><code>recaptchaenterprise. keys. listTagBindings</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. get</code></p>
<p><code>recommender. alloydbClusterPerformanceInsights. list</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. get</code></p>
<p><code>recommender. alloydbClusterPerformanceRecommendations. list</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. get</code></p>
<p><code>recommender. alloydbClusterReliabilityInsights. list</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. get</code></p>
<p><code>recommender. alloydbClusterReliabilityRecommendations. list</code></p>
<p><code>recommender. cloudAssetInsights. get</code></p>
<p><code>recommender. cloudAssetInsights. list</code></p>
<p><code>recommender.locations.*</code></p>
<ul>
<li><code>recommender.locations.get</code></li>
<li><code>recommender.locations.list</code></li>
</ul>
<p><code>redis. clusters. createTagBinding</code></p>
<p><code>redis. clusters. deleteTagBinding</code></p>
<p><code>redis. clusters. listEffectiveTags</code></p>
<p><code>redis.clusters.listTagBindings</code></p>
<p><code>redis. instances. createTagBinding</code></p>
<p><code>redis. instances. deleteTagBinding</code></p>
<p><code>redis. instances. listEffectiveTags</code></p>
<p><code>redis. instances. listTagBindings</code></p>
<p><code>resourcemanager. hierarchyNodes.*</code></p>
<ul>
<li><code>resourcemanager. hierarchyNodes. createTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. deleteTagBinding</code></li>
<li><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></li>
<li><code>resourcemanager. hierarchyNodes. listTagBindings</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>resourcemanager.tagKeys.get</code></p>
<p><code>resourcemanager.tagKeys.list</code></p>
<p><code>resourcemanager. tagValueBindings.*</code></p>
<ul>
<li><code>resourcemanager. tagValueBindings. create</code></li>
<li><code>resourcemanager. tagValueBindings. delete</code></li>
</ul>
<p><code>resourcemanager.tagValues.get</code></p>
<p><code>resourcemanager.tagValues.list</code></p>
<p><code>run.jobs.createTagBinding</code></p>
<p><code>run.jobs.deleteTagBinding</code></p>
<p><code>run.jobs.listEffectiveTags</code></p>
<p><code>run.jobs.listTagBindings</code></p>
<p><code>run.services.createTagBinding</code></p>
<p><code>run.services.deleteTagBinding</code></p>
<p><code>run.services.listEffectiveTags</code></p>
<p><code>run.services.listTagBindings</code></p>
<p><code>secretmanager. secrets. createTagBinding</code></p>
<p><code>secretmanager. secrets. deleteTagBinding</code></p>
<p><code>secretmanager. secrets. listEffectiveTags</code></p>
<p><code>secretmanager. secrets. listTagBindings</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>spanner. instances. createTagBinding</code></p>
<p><code>spanner. instances. deleteTagBinding</code></p>
<p><code>spanner. instances. listEffectiveTags</code></p>
<p><code>spanner. instances. listTagBindings</code></p>
<p><code>storage. buckets. createTagBinding</code></p>
<p><code>storage. buckets. deleteTagBinding</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage. buckets. listEffectiveTags</code></p>
<p><code>storage. buckets. listTagBindings</code></p>
<p><code>storage.folders.get</code></p>
<p><code>storage.folders.list</code></p>
<p><code>storage.managedFolders.get</code></p>
<p><code>storage.managedFolders.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p>
<p><code>tpu.nodes.createTagBinding</code></p>
<p><code>tpu.nodes.deleteTagBinding</code></p>
<p><code>tpu.nodes.listEffectiveTags</code></p>
<p><code>tpu.nodes.listTagBindings</code></p>
<p><code>transcoder. jobTemplates. createTagBinding</code></p>
<p><code>transcoder. jobTemplates. deleteTagBinding</code></p>
<p><code>transcoder. jobTemplates. listEffectiveTags</code></p>
<p><code>transcoder. jobTemplates. listTagBindings</code></p>
<p><code>transcoder. jobs. createTagBinding</code></p>
<p><code>transcoder. jobs. deleteTagBinding</code></p>
<p><code>transcoder. jobs. listEffectiveTags</code></p>
<p><code>transcoder. jobs. listTagBindings</code></p>
<p><code>videostitcher. cdnKeys. createTagBinding</code></p>
<p><code>videostitcher. cdnKeys. deleteTagBinding</code></p>
<p><code>videostitcher. cdnKeys. listEffectiveTags</code></p>
<p><code>videostitcher. cdnKeys. listTagBindings</code></p>
<p><code>videostitcher. liveConfigs. createTagBinding</code></p>
<p><code>videostitcher. liveConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. liveConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. liveConfigs. listTagBindings</code></p>
<p><code>videostitcher. slates. createTagBinding</code></p>
<p><code>videostitcher. slates. deleteTagBinding</code></p>
<p><code>videostitcher. slates. listEffectiveTags</code></p>
<p><code>videostitcher. slates. listTagBindings</code></p>
<p><code>videostitcher. vodConfigs. createTagBinding</code></p>
<p><code>videostitcher. vodConfigs. deleteTagBinding</code></p>
<p><code>videostitcher. vodConfigs. listEffectiveTags</code></p>
<p><code>videostitcher. vodConfigs. listTagBindings</code></p>
<p><code>vmmigration. groups. createTagBinding</code></p>
<p><code>vmmigration. groups. deleteTagBinding</code></p>
<p><code>vmmigration. groups. listEffectiveTags</code></p>
<p><code>vmmigration. groups. listTagBindings</code></p>
<p><code>vmmigration. sources. createTagBinding</code></p>
<p><code>vmmigration. sources. deleteTagBinding</code></p>
<p><code>vmmigration. sources. listEffectiveTags</code></p>
<p><code>vmmigration. sources. listTagBindings</code></p>
<p><code>vmwareengine. networkPeerings. createTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPeerings. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPeerings. listTagBindings</code></p>
<p><code>vmwareengine. networkPolicies. createTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. deleteTagBinding</code></p>
<p><code>vmwareengine. networkPolicies. listEffectiveTags</code></p>
<p><code>vmwareengine. networkPolicies. listTagBindings</code></p>
<p><code>vmwareengine. privateClouds. createTagBinding</code></p>
<p><code>vmwareengine. privateClouds. deleteTagBinding</code></p>
<p><code>vmwareengine. privateClouds. listEffectiveTags</code></p>
<p><code>vmwareengine. privateClouds. listTagBindings</code></p>
<p><code>vmwareengine. privateConnections. createTagBinding</code></p>
<p><code>vmwareengine. privateConnections. deleteTagBinding</code></p>
<p><code>vmwareengine. privateConnections. listEffectiveTags</code></p>
<p><code>vmwareengine. privateConnections. listTagBindings</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. createTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. deleteTagBinding</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listEffectiveTags</code></p>
<p><code>vmwareengine. vmwareEngineNetworks. listTagBindings</code></p>
<p><code>workflows. workflows. createTagBinding</code></p>
<p><code>workflows. workflows. deleteTagBinding</code></p>
<p><code>workflows. workflows. listEffectiveTags</code></p>
<p><code>workflows. workflows. listTagBindings</code></p>
<p><code>workstations. workstationClusters. createTagBinding</code></p>
<p><code>workstations. workstationClusters. deleteTagBinding</code></p>
<p><code>workstations. workstationClusters. listEffectiveTags</code></p>
<p><code>workstations. workstationClusters. listTagBindings</code></p></td>
</tr>
<tr class="even">
<td>DLP Reader
<p>( <code>roles/ dlp.reader</code> )</p>
<p>Read DLP entities, such as jobs and templates.</p></td>
<td><p><code>dlp.analyzeRiskTemplates.get</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.contentPolicies.get</code></p>
<p><code>dlp.contentPolicies.list</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectFindings.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobTriggers.get</code></p>
<p><code>dlp.jobTriggers.list</code></p>
<p><code>dlp.jobs.get</code></p>
<p><code>dlp.jobs.list</code></p>
<p><code>dlp.locations.*</code></p>
<ul>
<li><code>dlp.locations.get</code></li>
<li><code>dlp.locations.list</code></li>
</ul>
<p><code>dlp.storedInfoTypes.get</code></p>
<p><code>dlp.storedInfoTypes.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Stored InfoTypes Editor
<p>( <code>roles/ dlp.storedInfoTypesEditor</code> )</p>
<p>Edit DLP stored info types.</p></td>
<td><p><code>dlp.storedInfoTypes.*</code></p>
<ul>
<li><code>dlp.storedInfoTypes.create</code></li>
<li><code>dlp.storedInfoTypes.delete</code></li>
<li><code>dlp.storedInfoTypes.get</code></li>
<li><code>dlp.storedInfoTypes.list</code></li>
<li><code>dlp.storedInfoTypes.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Stored InfoTypes Reader
<p>( <code>roles/ dlp.storedInfoTypesReader</code> )</p>
<p>Read DLP stored info types.</p></td>
<td><p><code>dlp.storedInfoTypes.get</code></p>
<p><code>dlp.storedInfoTypes.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Subscription Admin
<p>( <code>roles/ dlp.subscriptionsAdmin</code> )</p>
<p>Manage DLP subscriptions.</p></td>
<td><p><code>dlp.subscriptions.*</code></p>
<ul>
<li><code>dlp.subscriptions.cancel</code></li>
<li><code>dlp.subscriptions.create</code></li>
<li><code>dlp.subscriptions.get</code></li>
<li><code>dlp.subscriptions.list</code></li>
<li><code>dlp.subscriptions.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DLP Subscription Viewer
<p>( <code>roles/ dlp.subscriptionsReader</code> )</p>
<p>View DLP subscriptions.</p></td>
<td><p><code>dlp.subscriptions.get</code></p>
<p><code>dlp.subscriptions.list</code></p></td>
</tr>
<tr class="odd">
<td>DLP Table Data Profiles Admin
<p>( <code>roles/ dlp.tableDataProfilesAdmin</code> )</p>
<p>Manage DLP table profiles.</p></td>
<td><p><code>dlp.tableDataProfiles.*</code></p>
<ul>
<li><code>dlp.tableDataProfiles.delete</code></li>
<li><code>dlp.tableDataProfiles.get</code></li>
<li><code>dlp.tableDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>DLP Table Data Profiles Reader
<p>( <code>roles/ dlp.tableDataProfilesReader</code> )</p>
<p>Read DLP table profiles.</p></td>
<td><p><code>dlp.tableDataProfiles.get</code></p>
<p><code>dlp.tableDataProfiles.list</code></p></td>
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
<td>DLP API Service Agent
<p>( <code>roles/ dlp.serviceAgent</code> )</p>
<p>Gives the Cloud DLP API service agent permissions for BigQuery, Cloud Storage, Datastore, Pub/Sub, and Cloud KMS.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>aiplatform.endpoints.predict</code></p>
<p><code>appengine.applications.get</code></p>
<p><code>bigquery.config.get</code></p>
<p><code>bigquery.dataPolicies.attach</code></p>
<p><code>bigquery.dataPolicies.create</code></p>
<p><code>bigquery.dataPolicies.delete</code></p>
<p><code>bigquery.dataPolicies.get</code></p>
<p><code>bigquery. dataPolicies. getIamPolicy</code></p>
<p><code>bigquery.dataPolicies.list</code></p>
<p><code>bigquery. dataPolicies. setIamPolicy</code></p>
<p><code>bigquery.dataPolicies.update</code></p>
<p><code>bigquery.datasets.*</code></p>
<ul>
<li><code>bigquery.datasets.create</code></li>
<li><code>bigquery. datasets. createTagBinding</code></li>
<li><code>bigquery.datasets.delete</code></li>
<li><code>bigquery. datasets. deleteTagBinding</code></li>
<li><code>bigquery.datasets.get</code></li>
<li><code>bigquery.datasets.getIamPolicy</code></li>
<li><code>bigquery.datasets.link</code></li>
<li><code>bigquery. datasets. listEffectiveTags</code></li>
<li><code>bigquery. datasets. listSharedDatasetUsage</code></li>
<li><code>bigquery. datasets. listTagBindings</code></li>
<li><code>bigquery.datasets.setIamPolicy</code></li>
<li><code>bigquery.datasets.update</code></li>
<li><code>bigquery.datasets.updateTag</code></li>
</ul>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.jobs.get</code></p>
<p><code>bigquery.jobs.update</code></p>
<p><code>bigquery.models.*</code></p>
<ul>
<li><code>bigquery.models.create</code></li>
<li><code>bigquery.models.delete</code></li>
<li><code>bigquery.models.export</code></li>
<li><code>bigquery.models.getData</code></li>
<li><code>bigquery.models.getMetadata</code></li>
<li><code>bigquery.models.list</code></li>
<li><code>bigquery.models.updateData</code></li>
<li><code>bigquery.models.updateMetadata</code></li>
<li><code>bigquery.models.updateTag</code></li>
</ul>
<p><code>bigquery.propertyGraphs.*</code></p>
<ul>
<li><code>bigquery.propertyGraphs.create</code></li>
<li><code>bigquery.propertyGraphs.delete</code></li>
<li><code>bigquery.propertyGraphs.get</code></li>
<li><code>bigquery.propertyGraphs.list</code></li>
<li><code>bigquery.propertyGraphs.update</code></li>
</ul>
<p><code>bigquery.readsessions.*</code></p>
<ul>
<li><code>bigquery.readsessions.create</code></li>
<li><code>bigquery.readsessions.getData</code></li>
<li><code>bigquery.readsessions.update</code></li>
</ul>
<p><code>bigquery.routines.*</code></p>
<ul>
<li><code>bigquery.routines.create</code></li>
<li><code>bigquery.routines.delete</code></li>
<li><code>bigquery.routines.get</code></li>
<li><code>bigquery.routines.list</code></li>
<li><code>bigquery.routines.update</code></li>
<li><code>bigquery.routines.updateTag</code></li>
</ul>
<p><code>bigquery. rowAccessPolicies. create</code></p>
<p><code>bigquery. rowAccessPolicies. delete</code></p>
<p><code>bigquery.rowAccessPolicies.get</code></p>
<p><code>bigquery. rowAccessPolicies. getIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. list</code></p>
<p><code>bigquery. rowAccessPolicies. setIamPolicy</code></p>
<p><code>bigquery. rowAccessPolicies. update</code></p>
<p><code>bigquery.tables.*</code></p>
<ul>
<li><code>bigquery.tables.create</code></li>
<li><code>bigquery.tables.createIndex</code></li>
<li><code>bigquery.tables.createSnapshot</code></li>
<li><code>bigquery. tables. createTagBinding</code></li>
<li><code>bigquery.tables.delete</code></li>
<li><code>bigquery.tables.deleteIndex</code></li>
<li><code>bigquery.tables.deleteSnapshot</code></li>
<li><code>bigquery. tables. deleteTagBinding</code></li>
<li><code>bigquery.tables.export</code></li>
<li><code>bigquery.tables.get</code></li>
<li><code>bigquery.tables.getData</code></li>
<li><code>bigquery.tables.getIamPolicy</code></li>
<li><code>bigquery.tables.list</code></li>
<li><code>bigquery. tables. listEffectiveTags</code></li>
<li><code>bigquery. tables. listTagBindings</code></li>
<li><code>bigquery.tables.replicateData</code></li>
<li><code>bigquery. tables. restoreSnapshot</code></li>
<li><code>bigquery.tables.setCategory</code></li>
<li><code>bigquery. tables. setColumnDataPolicy</code></li>
<li><code>bigquery.tables.setIamPolicy</code></li>
<li><code>bigquery.tables.update</code></li>
<li><code>bigquery.tables.updateData</code></li>
<li><code>bigquery.tables.updateIndex</code></li>
<li><code>bigquery.tables.updateTag</code></li>
</ul>
<p><code>cloudaicompanion. instances. completeTask</code></p>
<p><code>cloudasset. assets. analyzeIamPolicy</code></p>
<p><code>cloudasset. assets. exportResource</code></p>
<p><code>cloudasset. assets. searchAllIamPolicies</code></p>
<p><code>cloudkms. cryptoKeyVersions. useToDecrypt</code></p>
<p><code>cloudkms.locations.get</code></p>
<p><code>cloudkms.locations.list</code></p>
<p><code>databasesconsole.locations.*</code></p>
<ul>
<li><code>databasesconsole.locations.get</code></li>
<li><code>databasesconsole. locations. list</code></li>
</ul>
<p><code>databasesconsole. studioQueries. create</code></p>
<p><code>databasesconsole. studioQueries. delete</code></p>
<p><code>databasesconsole. studioQueries. search</code></p>
<p><code>databasesconsole. studioQueries. update</code></p>
<p><code>datacatalog. categories. fineGrainedGet</code></p>
<p><code>datacatalog. migrationConfig. get</code></p>
<p><code>datacatalog.tagTemplates.*</code></p>
<ul>
<li><code>datacatalog. tagTemplates. create</code></li>
<li><code>datacatalog. tagTemplates. delete</code></li>
<li><code>datacatalog.tagTemplates.get</code></li>
<li><code>datacatalog. tagTemplates. getIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. getTag</code></li>
<li><code>datacatalog. tagTemplates. setIamPolicy</code></li>
<li><code>datacatalog. tagTemplates. update</code></li>
<li><code>datacatalog.tagTemplates.use</code></li>
</ul>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>dataplex.aspectTypes.*</code></p>
<ul>
<li><code>dataplex.aspectTypes.create</code></li>
<li><code>dataplex.aspectTypes.delete</code></li>
<li><code>dataplex.aspectTypes.get</code></li>
<li><code>dataplex. aspectTypes. getIamPolicy</code></li>
<li><code>dataplex.aspectTypes.list</code></li>
<li><code>dataplex. aspectTypes. setIamPolicy</code></li>
<li><code>dataplex.aspectTypes.update</code></li>
<li><code>dataplex.aspectTypes.use</code></li>
</ul>
<p><code>dataplex.dataDomains.discover</code></p>
<p><code>dataplex.datascans.*</code></p>
<ul>
<li><code>dataplex.datascans.cancel</code></li>
<li><code>dataplex.datascans.create</code></li>
<li><code>dataplex.datascans.delete</code></li>
<li><code>dataplex.datascans.get</code></li>
<li><code>dataplex.datascans.getData</code></li>
<li><code>dataplex. datascans. getIamPolicy</code></li>
<li><code>dataplex.datascans.list</code></li>
<li><code>dataplex.datascans.run</code></li>
<li><code>dataplex. datascans. setIamPolicy</code></li>
<li><code>dataplex.datascans.update</code></li>
</ul>
<p><code>dataplex.entries.get</code></p>
<p><code>dataplex.operations.get</code></p>
<p><code>dataplex.operations.list</code></p>
<p><code>dataplex.projects.search</code></p>
<p><code>datastore.databases.get</code></p>
<p><code>datastore. databases. getMetadata</code></p>
<p><code>datastore.databases.list</code></p>
<p><code>datastore.entities.*</code></p>
<ul>
<li><code>datastore.entities.allocateIds</code></li>
<li><code>datastore.entities.create</code></li>
<li><code>datastore.entities.delete</code></li>
<li><code>datastore.entities.get</code></li>
<li><code>datastore.entities.list</code></li>
<li><code>datastore.entities.update</code></li>
</ul>
<p><code>datastore.namespaces.*</code></p>
<ul>
<li><code>datastore.namespaces.get</code></li>
<li><code>datastore.namespaces.list</code></li>
</ul>
<p><code>datastore.schemas.list</code></p>
<p><code>datastore.statistics.*</code></p>
<ul>
<li><code>datastore.statistics.get</code></li>
<li><code>datastore.statistics.list</code></li>
</ul>
<p><code>dlp.analyzeRiskTemplates.get</code></p>
<p><code>dlp.analyzeRiskTemplates.list</code></p>
<p><code>dlp.deidentifyTemplates.get</code></p>
<p><code>dlp.deidentifyTemplates.list</code></p>
<p><code>dlp.inspectTemplates.get</code></p>
<p><code>dlp.inspectTemplates.list</code></p>
<p><code>dlp.jobs.*</code></p>
<ul>
<li><code>dlp.jobs.cancel</code></li>
<li><code>dlp.jobs.create</code></li>
<li><code>dlp.jobs.delete</code></li>
<li><code>dlp.jobs.get</code></li>
<li><code>dlp.jobs.hybridInspect</code></li>
<li><code>dlp.jobs.list</code></li>
</ul>
<p><code>dlp.kms.encrypt</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>monitoring.dashboards.get</code></p>
<p><code>monitoring.dashboards.list</code></p>
<p><code>monitoring.groups.get</code></p>
<p><code>monitoring.groups.list</code></p>
<p><code>monitoring. metricDescriptors. list</code></p>
<p><code>monitoring. monitoredResourceDescriptors.*</code></p>
<ul>
<li><code>monitoring. monitoredResourceDescriptors. get</code></li>
<li><code>monitoring. monitoredResourceDescriptors. list</code></li>
</ul>
<p><code>monitoring.timeSeries.*</code></p>
<ul>
<li><code>monitoring.timeSeries.create</code></li>
<li><code>monitoring.timeSeries.list</code></li>
</ul>
<p><code>orgpolicy.policy.get</code></p>
<p><code>pubsub.*</code></p>
<ul>
<li><code>pubsub. messageTransforms. validate</code></li>
<li><code>pubsub.schemas.attach</code></li>
<li><code>pubsub.schemas.commit</code></li>
<li><code>pubsub.schemas.create</code></li>
<li><code>pubsub.schemas.delete</code></li>
<li><code>pubsub.schemas.get</code></li>
<li><code>pubsub.schemas.getIamPolicy</code></li>
<li><code>pubsub.schemas.list</code></li>
<li><code>pubsub.schemas.listRevisions</code></li>
<li><code>pubsub.schemas.rollback</code></li>
<li><code>pubsub.schemas.setIamPolicy</code></li>
<li><code>pubsub.schemas.validate</code></li>
<li><code>pubsub.snapshots.create</code></li>
<li><code>pubsub. snapshots. createTagBinding</code></li>
<li><code>pubsub.snapshots.delete</code></li>
<li><code>pubsub. snapshots. deleteTagBinding</code></li>
<li><code>pubsub.snapshots.get</code></li>
<li><code>pubsub.snapshots.getIamPolicy</code></li>
<li><code>pubsub.snapshots.list</code></li>
<li><code>pubsub. snapshots. listEffectiveTags</code></li>
<li><code>pubsub. snapshots. listTagBindings</code></li>
<li><code>pubsub.snapshots.seek</code></li>
<li><code>pubsub.snapshots.setIamPolicy</code></li>
<li><code>pubsub.snapshots.update</code></li>
<li><code>pubsub.subscriptions.consume</code></li>
<li><code>pubsub.subscriptions.create</code></li>
<li><code>pubsub. subscriptions. createTagBinding</code></li>
<li><code>pubsub.subscriptions.delete</code></li>
<li><code>pubsub. subscriptions. deleteTagBinding</code></li>
<li><code>pubsub.subscriptions.get</code></li>
<li><code>pubsub. subscriptions. getIamPolicy</code></li>
<li><code>pubsub.subscriptions.list</code></li>
<li><code>pubsub. subscriptions. listEffectiveTags</code></li>
<li><code>pubsub. subscriptions. listTagBindings</code></li>
<li><code>pubsub. subscriptions. setIamPolicy</code></li>
<li><code>pubsub.subscriptions.update</code></li>
<li><code>pubsub. topics. attachSubscription</code></li>
<li><code>pubsub.topics.create</code></li>
<li><code>pubsub.topics.createTagBinding</code></li>
<li><code>pubsub.topics.delete</code></li>
<li><code>pubsub.topics.deleteTagBinding</code></li>
<li><code>pubsub. topics. detachSubscription</code></li>
<li><code>pubsub.topics.get</code></li>
<li><code>pubsub.topics.getIamPolicy</code></li>
<li><code>pubsub.topics.list</code></li>
<li><code>pubsub. topics. listEffectiveTags</code></li>
<li><code>pubsub.topics.listTagBindings</code></li>
<li><code>pubsub.topics.publish</code></li>
<li><code>pubsub.topics.setIamPolicy</code></li>
<li><code>pubsub.topics.update</code></li>
<li><code>pubsub.topics.updateTag</code></li>
</ul>
<p><code>recommender. iamPolicyInsights.*</code></p>
<ul>
<li><code>recommender. iamPolicyInsights. get</code></li>
<li><code>recommender. iamPolicyInsights. list</code></li>
<li><code>recommender. iamPolicyInsights. update</code></li>
</ul>
<p><code>recommender. iamPolicyRecommendations.*</code></p>
<ul>
<li><code>recommender. iamPolicyRecommendations. get</code></li>
<li><code>recommender. iamPolicyRecommendations. list</code></li>
<li><code>recommender. iamPolicyRecommendations. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteInsights. get</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. list</code></li>
<li><code>recommender. storageBucketSoftDeleteInsights. update</code></li>
</ul>
<p><code>recommender. storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code>recommender. storageBucketSoftDeleteRecommendations. get</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. list</code></li>
<li><code>recommender. storageBucketSoftDeleteRecommendations. update</code></li>
</ul>
<p><code>resourcemanager. hierarchyNodes. listEffectiveTags</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
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
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>stackdriver.projects.get</code></p>
<p><code>stackdriver. resourceMetadata. list</code></p>
<p><code>storage.anywhereCaches.*</code></p>
<ul>
<li><code>storage.anywhereCaches.create</code></li>
<li><code>storage.anywhereCaches.disable</code></li>
<li><code>storage.anywhereCaches.get</code></li>
<li><code>storage.anywhereCaches.list</code></li>
<li><code>storage.anywhereCaches.pause</code></li>
<li><code>storage.anywhereCaches.resume</code></li>
<li><code>storage.anywhereCaches.update</code></li>
</ul>
<p><code>storage.bucketOperations.*</code></p>
<ul>
<li><code>storage. bucketOperations. cancel</code></li>
<li><code>storage.bucketOperations.get</code></li>
<li><code>storage.bucketOperations.list</code></li>
</ul>
<p><code>storage.buckets.*</code></p>
<ul>
<li><code>storage.buckets.create</code></li>
<li><code>storage. buckets. createTagBinding</code></li>
<li><code>storage.buckets.delete</code></li>
<li><code>storage. buckets. deleteTagBinding</code></li>
<li><code>storage. buckets. enableObjectRetention</code></li>
<li><code>storage.buckets.get</code></li>
<li><code>storage.buckets.getIamPolicy</code></li>
<li><code>storage.buckets.getIpFilter</code></li>
<li><code>storage. buckets. getObjectInsights</code></li>
<li><code>storage.buckets.list</code></li>
<li><code>storage. buckets. listEffectiveTags</code></li>
<li><code>storage. buckets. listTagBindings</code></li>
<li><code>storage.buckets.relocate</code></li>
<li><code>storage.buckets.restore</code></li>
<li><code>storage.buckets.setIamPolicy</code></li>
<li><code>storage.buckets.setIpFilter</code></li>
<li><code>storage.buckets.update</code></li>
<li><code>storage. buckets. viewIntelligenceDetails</code></li>
<li><code>storage. buckets. viewSecurityIntelligenceDetails</code></li>
</ul>
<p><code>storage.featureConfigs.*</code></p>
<ul>
<li><code>storage.featureConfigs.create</code></li>
<li><code>storage.featureConfigs.delete</code></li>
<li><code>storage.featureConfigs.get</code></li>
<li><code>storage.featureConfigs.list</code></li>
<li><code>storage.featureConfigs.update</code></li>
</ul>
<p><code>storage.folders.*</code></p>
<ul>
<li><code>storage.folders.create</code></li>
<li><code>storage.folders.delete</code></li>
<li><code>storage.folders.get</code></li>
<li><code>storage.folders.list</code></li>
<li><code>storage.folders.rename</code></li>
</ul>
<p><code>storage.intelligenceConfigs.*</code></p>
<ul>
<li><code>storage. intelligenceConfigs. get</code></li>
<li><code>storage. intelligenceConfigs. update</code></li>
</ul>
<p><code>storage.managedFolders.*</code></p>
<ul>
<li><code>storage.managedFolders.create</code></li>
<li><code>storage.managedFolders.delete</code></li>
<li><code>storage.managedFolders.get</code></li>
<li><code>storage. managedFolders. getIamPolicy</code></li>
<li><code>storage.managedFolders.list</code></li>
<li><code>storage. managedFolders. setIamPolicy</code></li>
<li><code>storage.managedFolders.update</code></li>
</ul>
<p><code>storage.multipartUploads.*</code></p>
<ul>
<li><code>storage.multipartUploads.abort</code></li>
<li><code>storage. multipartUploads. create</code></li>
<li><code>storage.multipartUploads.list</code></li>
<li><code>storage. multipartUploads. listParts</code></li>
</ul>
<p><code>storage.objects.*</code></p>
<ul>
<li><code>storage.objects.create</code></li>
<li><code>storage.objects.createContext</code></li>
<li><code>storage.objects.delete</code></li>
<li><code>storage.objects.deleteContext</code></li>
<li><code>storage.objects.get</code></li>
<li><code>storage.objects.getIamPolicy</code></li>
<li><code>storage.objects.list</code></li>
<li><code>storage.objects.move</code></li>
<li><code>storage. objects. overrideUnlockedRetention</code></li>
<li><code>storage.objects.restore</code></li>
<li><code>storage.objects.setIamPolicy</code></li>
<li><code>storage.objects.setRetention</code></li>
<li><code>storage.objects.update</code></li>
<li><code>storage.objects.updateContext</code></li>
</ul>
<p><code>storagebatchoperations.*</code></p>
<ul>
<li><code>storagebatchoperations. bucketOperations. get</code></li>
<li><code>storagebatchoperations. bucketOperations. list</code></li>
<li><code>storagebatchoperations. jobs. cancel</code></li>
<li><code>storagebatchoperations. jobs. create</code></li>
<li><code>storagebatchoperations. jobs. delete</code></li>
<li><code>storagebatchoperations. jobs. get</code></li>
<li><code>storagebatchoperations. jobs. list</code></li>
<li><code>storagebatchoperations. locations. get</code></li>
<li><code>storagebatchoperations. locations. list</code></li>
<li><code>storagebatchoperations. operations. cancel</code></li>
<li><code>storagebatchoperations. operations. delete</code></li>
<li><code>storagebatchoperations. operations. get</code></li>
<li><code>storagebatchoperations. operations. list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Sensitive Data Protection permissions

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
<td><code>dlp. analyzeRiskTemplates. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp. analyzeRiskTemplates. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.analyzeRiskTemplates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesReader">DLP Analyze Risk Templates Reader</a> ( <code>roles/ dlp.analyzeRiskTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.analyzeRiskTemplates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesReader">DLP Analyze Risk Templates Reader</a> ( <code>roles/ dlp.analyzeRiskTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp. analyzeRiskTemplates. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code>roles/ dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.charts.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code>roles/ dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.columnDataProfiles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.columnDataProfilesReader">DLP Column Data Profiles Reader</a> ( <code>roles/ dlp.columnDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.columnDataProfiles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.columnDataProfilesReader">DLP Column Data Profiles Reader</a> ( <code>roles/ dlp.columnDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.connections.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.connections.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.connections.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code>roles/ dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.connections.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code>roles/ dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.connections.search</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code>roles/ dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.connections.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code>roles/ dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.contentPolicies.apply</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code>roles/ dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesConsumer">DLP Content Policies Consumer</a> ( <code>roles/ dlp.contentPoliciesConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.contentPolicies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.contentPolicies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.contentPolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesConsumer">DLP Content Policies Consumer</a> ( <code>roles/ dlp.contentPoliciesConsumer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesReader">DLP Content Policies Reader</a> ( <code>roles/ dlp.contentPoliciesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.contentPolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesReader">DLP Content Policies Reader</a> ( <code>roles/ dlp.contentPoliciesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.contentPolicies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.contentPoliciesEditor">DLP Content Policies Editor</a> ( <code>roles/ dlp.contentPoliciesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.deidentifyTemplates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.deidentifyTemplates.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.deidentifyTemplates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesReader">DLP De-identify Templates Reader</a> ( <code>roles/ dlp.deidentifyTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.deidentifyTemplates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesReader">DLP De-identify Templates Reader</a> ( <code>roles/ dlp.deidentifyTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.deidentifyTemplates.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code>roles/ dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.estimates.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.estimates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.estimates.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.estimates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.estimates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code>roles/ dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.fileStoreProfiles.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code>roles/ dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.fileStoreProfiles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code>roles/ dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code>roles/ dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.fileStoreProfiles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code>roles/ dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code>roles/ dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.inspectFindings.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectFindingsReader">DLP Inspect Findings Reader</a> ( <code>roles/ dlp.inspectFindingsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.inspectTemplates.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.inspectTemplates.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.inspectTemplates.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesReader">DLP Inspect Templates Reader</a> ( <code>roles/ dlp.inspectTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.inspectTemplates.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesReader">DLP Inspect Templates Reader</a> ( <code>roles/ dlp.inspectTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code>roles/ dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.inspectTemplates.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code>roles/ dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.jobTriggers.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.jobTriggers.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.jobTriggers.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersReader">DLP Job Triggers Reader</a> ( <code>roles/ dlp.jobTriggersReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.jobTriggers.hybridInspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.jobTriggers.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersReader">DLP Job Triggers Reader</a> ( <code>roles/ dlp.jobTriggersReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.jobTriggers.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code>roles/ dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.jobs.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.jobs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.jobs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.jobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsReader">DLP Jobs Reader</a> ( <code>roles/ dlp.jobsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.jobs.hybridInspect</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.jobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsReader">DLP Jobs Reader</a> ( <code>roles/ dlp.jobsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.kms.encrypt</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code>roles/ dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code>roles/ dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code>roles/ dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code>roles/ dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code>roles/ dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code>roles/ ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code>roles/ contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.projectDataProfiles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectDataProfilesReader">DLP Project Data Profiles Reader</a> ( <code>roles/ dlp.projectDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.projectDataProfiles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectDataProfilesReader">DLP Project Data Profiles Reader</a> ( <code>roles/ dlp.projectDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.storedInfoTypes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code>roles/ dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.storedInfoTypes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code>roles/ dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.storedInfoTypes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code>roles/ dlp.storedInfoTypesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesReader">DLP Stored InfoTypes Reader</a> ( <code>roles/ dlp.storedInfoTypesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dlp.storedInfoTypes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code>roles/ dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code>roles/ dlp.storedInfoTypesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesReader">DLP Stored InfoTypes Reader</a> ( <code>roles/ dlp.storedInfoTypesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code>roles/ modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.storedInfoTypes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code>roles/ dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.subscriptions.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.subscriptions.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.subscriptions.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsReader">DLP Subscription Viewer</a> ( <code>roles/ dlp.subscriptionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.subscriptions.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsReader">DLP Subscription Viewer</a> ( <code>roles/ dlp.subscriptionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.subscriptions.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code>roles/ dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>dlp.tableDataProfiles.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code>roles/ dlp.tableDataProfilesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dlp.tableDataProfiles.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code>roles/ dlp.tableDataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesReader">DLP Table Data Profiles Reader</a> ( <code>roles/ dlp.tableDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dlp.tableDataProfiles.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code>roles/ dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code>roles/ dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code>roles/ dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code>roles/ securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code>roles/ dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code>roles/ dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code>roles/ dlp.tableDataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesReader">DLP Table Data Profiles Reader</a> ( <code>roles/ dlp.tableDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code>roles/ securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code>roles/ securitycenter.adminViewer</code> )</p></td>
</tr>
</tbody>
</table>
