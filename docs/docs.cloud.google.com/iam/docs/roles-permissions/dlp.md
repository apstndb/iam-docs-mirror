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
<td><h4 id="dlp.admin" class="role-title add-link" data-text="DLP Administrator" tabindex="-1">DLP Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p>Administer DLP including jobs and templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.*</code></p>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.editor" class="role-title add-link" data-text="DLP Editor" tabindex="-1">DLP Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p>Editor role for DLP</p></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  create</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.connections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.connections.create</code></li>
<li><code dir="ltr" translate="no">dlp.connections.delete</code></li>
<li><code dir="ltr" translate="no">dlp.connections.get</code></li>
<li><code dir="ltr" translate="no">dlp.connections.list</code></li>
<li><code dir="ltr" translate="no">dlp.connections.search</code></li>
<li><code dir="ltr" translate="no">dlp.connections.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.estimates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.estimates.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.create</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.get</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.jobTriggers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.jobTriggers.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.list</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.create</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.delete</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.subscriptions.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.user" class="role-title add-link" data-text="DLP User" tabindex="-1">DLP User</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.user</code> )</p>
<p>Inspect, Redact, and De-identify Content</p></td>
<td><p><code dir="ltr" translate="no">dlp.kms.encrypt</code></p>
<p><code dir="ltr" translate="no">dlp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.viewer" class="role-title add-link" data-text="DLP Viewer" tabindex="-1">DLP Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p>Viewer role for DLP</p></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.connections.get</code></p>
<p><code dir="ltr" translate="no">dlp.connections.list</code></p>
<p><code dir="ltr" translate="no">dlp.connections.search</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.estimates.get</code></p>
<p><code dir="ltr" translate="no">dlp.estimates.list</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p>
<p><code dir="ltr" translate="no">dlp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p>
<p><code dir="ltr" translate="no">dlp.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">dlp.subscriptions.list</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.analyzeRiskTemplatesEditor" class="role-title add-link" data-text="DLP Analyze Risk Templates Editor" tabindex="-1">DLP Analyze Risk Templates Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p>Edit DLP analyze risk templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  create</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.analyzeRiskTemplatesReader" class="role-title add-link" data-text="DLP Analyze Risk Templates Reader" tabindex="-1">DLP Analyze Risk Templates Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesReader</code> )</p>
<p>Read DLP analyze risk templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.columnDataProfilesReader" class="role-title add-link" data-text="DLP Column Data Profiles Reader" tabindex="-1">DLP Column Data Profiles Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.columnDataProfilesReader</code> )</p>
<p>Read DLP column profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.connectionsAdmin" class="role-title add-link" data-text="DLP Connections Admin" tabindex="-1">DLP Connections Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p>Manage DLP Connections.</p></td>
<td><p><code dir="ltr" translate="no">dlp.connections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.connections.create</code></li>
<li><code dir="ltr" translate="no">dlp.connections.delete</code></li>
<li><code dir="ltr" translate="no">dlp.connections.get</code></li>
<li><code dir="ltr" translate="no">dlp.connections.list</code></li>
<li><code dir="ltr" translate="no">dlp.connections.search</code></li>
<li><code dir="ltr" translate="no">dlp.connections.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.connectionsReader" class="role-title add-link" data-text="DLP Connections Viewer" tabindex="-1">DLP Connections Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.connectionsReader</code> )</p>
<p>View DLP Connections.</p></td>
<td><p><code dir="ltr" translate="no">dlp.connections.get</code></p>
<p><code dir="ltr" translate="no">dlp.connections.list</code></p>
<p><code dir="ltr" translate="no">dlp.connections.search</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.dataProfilesAdmin" class="role-title add-link" data-text="DLP Data Profiles Admin" tabindex="-1">DLP Data Profiles Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p>Manage DLP profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.columnDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.dataProfilesReader" class="role-title add-link" data-text="DLP Data Profiles Reader" tabindex="-1">DLP Data Profiles Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p>Read DLP profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.charts.get</code></p>
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
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.deidentifyTemplatesEditor" class="role-title add-link" data-text="DLP De-identify Templates Editor" tabindex="-1">DLP De-identify Templates Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p>Edit DLP de-identify templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.deidentifyTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.deidentifyTemplates.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.deidentifyTemplatesReader" class="role-title add-link" data-text="DLP De-identify Templates Reader" tabindex="-1">DLP De-identify Templates Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesReader</code> )</p>
<p>Read DLP de-identify templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.estimatesAdmin" class="role-title add-link" data-text="DLP Cost Estimation" tabindex="-1">DLP Cost Estimation</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p>Manage DLP Cost Estimates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.estimates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.estimates.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.create</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.get</code></li>
<li><code dir="ltr" translate="no">dlp.estimates.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.fileStoreProfilesAdmin" class="role-title add-link" data-text="DLP File Store Data Profiles Admin" tabindex="-1">DLP File Store Data Profiles Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.fileStoreProfilesAdmin</code> )</p>
<p>Manage DLP file store profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.fileStoreProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.fileStoreProfilesReader" class="role-title add-link" data-text="DLP File Store Data Profiles Reader" tabindex="-1">DLP File Store Data Profiles Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.fileStoreProfilesReader</code> )</p>
<p>Read DLP file store profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.charts.get</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.inspectFindingsReader" class="role-title add-link" data-text="DLP Inspect Findings Reader" tabindex="-1">DLP Inspect Findings Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.inspectFindingsReader</code> )</p>
<p>Read DLP stored findings.</p></td>
<td><p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.inspectTemplatesEditor" class="role-title add-link" data-text="DLP Inspect Templates Editor" tabindex="-1">DLP Inspect Templates Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p>Edit DLP inspect templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.inspectTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.create</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.delete</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></li>
<li><code dir="ltr" translate="no">dlp.inspectTemplates.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.inspectTemplatesReader" class="role-title add-link" data-text="DLP Inspect Templates Reader" tabindex="-1">DLP Inspect Templates Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.inspectTemplatesReader</code> )</p>
<p>Read DLP inspect templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobTriggersEditor" class="role-title add-link" data-text="DLP Job Triggers Editor" tabindex="-1">DLP Job Triggers Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p>Edit job triggers configurations.</p></td>
<td><p><code dir="ltr" translate="no">dlp.jobTriggers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.jobTriggers.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.list</code></li>
<li><code dir="ltr" translate="no">dlp.jobTriggers.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobTriggersReader" class="role-title add-link" data-text="DLP Job Triggers Reader" tabindex="-1">DLP Job Triggers Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.jobTriggersReader</code> )</p>
<p>Read job triggers.</p></td>
<td><p><code dir="ltr" translate="no">dlp.jobTriggers.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobsEditor" class="role-title add-link" data-text="DLP Jobs Editor" tabindex="-1">DLP Jobs Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p>Edit and create jobs</p></td>
<td><p><code dir="ltr" translate="no">dlp.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.kms.encrypt</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobsReader" class="role-title add-link" data-text="DLP Jobs Reader" tabindex="-1">DLP Jobs Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.jobsReader</code> )</p>
<p>Read jobs</p></td>
<td><p><code dir="ltr" translate="no">dlp.jobs.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.orgdriver" class="role-title add-link" data-text="DLP Organization Data Profiles Driver" tabindex="-1">DLP Organization Data Profiles Driver</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p>Permissions needed by the DLP service account to generate data profiles within an organization or folder.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Folder</li>
</ul></td>
<td><p><code dir="ltr" translate="no">aiplatform.agentExamples.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.agentExamples.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotationSpecs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.cacheConfigs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.consents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  contexts.  queryContextLineageSubgraph</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasetVersions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  datasetVersions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  queryDeployedModels</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeviceDebugInfo.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationItems.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationItems.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  exampleStores.  readExample</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  executions.  queryExecutionInputsAndOutputs</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureMonitors.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitors.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViewSyncs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  fetchFeatureValues</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  searchNearestEntities</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.humanInTheLoops.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  humanInTheLoops.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  indexEndpoints.  queryVectors</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memoryRevisions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  memoryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataSchemas.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  metadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  searchStatsAnomalies</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitors.  searchModelMonitoringAlerts</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitors.  searchModelMonitoringStats</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasTrialDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.nasTrialDetails.get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  nasTrialDetails.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.operations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.query</code></p>
<p><code dir="ltr" translate="no">aiplatform.  ragEngineConfigs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  query</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicyEngine.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessionEvents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.specialistPools.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  update</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboardRuns.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardRuns.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  batchRead</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  read</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.get</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.export</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.get</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.connect</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.locations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.users.get</code></p>
<p><code dir="ltr" translate="no">alloydb.users.list</code></p>
<p><code dir="ltr" translate="no">alloydb.users.login</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.bireservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.listAll</code></p>
<p><code dir="ltr" translate="no">bigquery.  jobs.  listExecutionMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  search</code></p>
<p><code dir="ltr" translate="no">bigquery.reservationGroups.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.use</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.savedqueries.get</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.replicateData</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.transfers.get</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
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
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  fineGrainedGet</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.migrationJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.getData</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.run</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.update</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
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
<p><code dir="ltr" translate="no">dns.policies.createTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.backups.createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.backups.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.instances.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">redis.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.projectDataProfilesReader" class="role-title add-link" data-text="DLP Project Data Profiles Reader" tabindex="-1">DLP Project Data Profiles Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.projectDataProfilesReader</code> )</p>
<p>Read DLP project profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.projectDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.projectdriver" class="role-title add-link" data-text="DLP Project Data Profiles Driver" tabindex="-1">DLP Project Data Profiles Driver</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Permissions needed by the DLP service account to generate data profiles within a project.</p></td>
<td><p><code dir="ltr" translate="no">aiplatform.agentExamples.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.agentExamples.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.agents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotationSpecs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  annotationSpecs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.annotations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.apps.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.artifacts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  batchPredictionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.cacheConfigs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.cachedContents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.consents.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.contexts.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  contexts.  queryContextLineageSubgraph</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.customJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.dataItems.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  dataLabelingJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasetVersions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  datasetVersions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.datasets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  deploymentResourcePools.  queryDeployedModels</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeploymentJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  edgeDeviceDebugInfo.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.edgeDevices.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.endpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.entityTypes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationItems.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  evaluationItems.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationRuns.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.evaluationSets.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.exampleStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  exampleStores.  readExample</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.executions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  executions.  queryExecutionInputsAndOutputs</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.extensions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureGroups.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitorJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureMonitors.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureMonitors.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureOnlineStores.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViewSyncs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  featureViewSyncs.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  fetchFeatureValues</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featureViews.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  featureViews.  searchNearestEntities</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.features.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.featurestores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.humanInTheLoops.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  humanInTheLoops.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  hyperparameterTuningJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexEndpoints.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  indexEndpoints.  queryVectors</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.indexes.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.locations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.memories.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.memoryRevisions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  memoryRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataSchemas.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  metadataSchemas.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.metadataStores.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelDeploymentMonitoringJobs.  searchStatsAnomalies</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluationSlices.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelEvaluations.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitoringJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.modelMonitors.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitors.  searchModelMonitoringAlerts</code></p>
<p><code dir="ltr" translate="no">aiplatform.  modelMonitors.  searchModelMonitoringStats</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.models.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.nasTrialDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.nasTrialDetails.get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  nasTrialDetails.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookExecutionJobs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimeTemplates.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  notebookRuntimes.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  onlineEvaluators.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.operations.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  persistentResources.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.pipelineJobs.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  get</code></li>
<li><code dir="ltr" translate="no">aiplatform.  provisionedThroughputRevisions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  provisionedThroughputs.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragCorpora.query</code></p>
<p><code dir="ltr" translate="no">aiplatform.  ragEngineConfigs.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.ragFiles.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngineRuntimeRevisions.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  reasoningEngines.  query</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  sandboxEnvironments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.schedules.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicies.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  semanticGovernancePolicyEngine.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessionEvents.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.sessions.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.specialistPools.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  specialistPools.  update</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.studies.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardExperiments.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboardRuns.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardRuns.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  batchRead</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  tensorboardTimeSeries.  read</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tensorboards.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  get</code></p>
<p><code dir="ltr" translate="no">aiplatform.  trainingPipelines.  list</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.trials.list</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.get</code></p>
<p><code dir="ltr" translate="no">aiplatform.tuningJobs.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.get</code></p>
<p><code dir="ltr" translate="no">alloydb.backups.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  backups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.export</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  generateClientCertificate</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.get</code></p>
<p><code dir="ltr" translate="no">alloydb.clusters.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">alloydb.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.get</code></p>
<p><code dir="ltr" translate="no">alloydb.databases.list</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.connect</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">alloydb.  instances.  executeSqlReadOnly</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.get</code></p>
<p><code dir="ltr" translate="no">alloydb.instances.list</code></p>
<p><code dir="ltr" translate="no">alloydb.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.locations.get</code></li>
<li><code dir="ltr" translate="no">alloydb.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.operations.get</code></p>
<p><code dir="ltr" translate="no">alloydb.operations.list</code></p>
<p><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.*</code></p>
<ul>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  get</code></li>
<li><code dir="ltr" translate="no">alloydb.  supportedDatabaseFlags.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">alloydb.users.get</code></p>
<p><code dir="ltr" translate="no">alloydb.users.list</code></p>
<p><code dir="ltr" translate="no">alloydb.users.login</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  apis.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apigateway.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.apis.createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.apis.listTagBindings</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">apihub.  deployments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  backupVaults.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">backupdr.  managementServers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appConnectors.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">beyondcorp.  appGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.bireservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  get</code></p>
<p><code dir="ltr" translate="no">bigquery.  capacityCommitments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.connections.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.list</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.listAll</code></p>
<p><code dir="ltr" translate="no">bigquery.  jobs.  listExecutionMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationAssignments.  search</code></p>
<p><code dir="ltr" translate="no">bigquery.reservationGroups.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservationGroups.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.get</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  reservations.  listFailoverDatasets</code></p>
<p><code dir="ltr" translate="no">bigquery.reservations.use</code></p>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.savedqueries.get</code></p>
<p><code dir="ltr" translate="no">bigquery.savedqueries.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.replicateData</code></p>
<p><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateTag</code></p>
<p><code dir="ltr" translate="no">bigquery.transfers.get</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  authorizedViews.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">bigtable.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudaicompanion.  entitlements.  get</code></p>
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
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  deliveryPipelines.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">clouddeploy.  targets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.keyHandles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.create</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.get</code></li>
<li><code dir="ltr" translate="no">cloudkms.keyHandles.list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudkms.  keyRings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudkms.operations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  projects.  showEffectiveAutokeyConfig</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.connect</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.executeSql</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">cloudsql.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.login</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">composer.  environments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  commitments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.disks.createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.disks.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  disks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.disks.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  externalVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  futureReservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalAddresses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  globalNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  images.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  images.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.images.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  instantSnapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  licenses.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  machineImages.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEdgeSecurityServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  packetMirrorings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  publicDelegatedPrefixes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendBuckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionFirewallPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSecurityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  reservations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  routers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  routes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.routes.listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  securityPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  serviceAttachments.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  sslPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  storagePools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetGrpcProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetInstances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetSslProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetVpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnGateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  vpnTunnels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">container.  clusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  fineGrainedGet</code></p>
<p><code dir="ltr" translate="no">datacatalog.entries.updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  entryGroups.  updateTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></p>
<p><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datafusion.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datamigration.  connectionProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  connectionProfiles.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.migrationJobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  migrationJobs.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">datamigration.  privateConnections.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">datamigration.  privateConnections.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.cancel</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.create</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.delete</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.get</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.getData</code></p>
<p><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.list</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.run</code></p>
<p><code dir="ltr" translate="no">dataplex.datascans.update</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.entries.update</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  connectionProfiles.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">datastream.  streams.  listTagBindings</code></p>
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
<p><code dir="ltr" translate="no">dns.policies.createTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">domains.  registrations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channelConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">eventarc.  triggers.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.backups.createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.backups.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.backups.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">file.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">file.instances.listTagBindings</code></p>
<p><code dir="ltr" translate="no">file.snapshots.*</code></p>
<ul>
<li><code dir="ltr" translate="no">file.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">file.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">file.snapshots.listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkemulticloud.  attachedClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  bareMetalClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareAdminClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">gkeonprem.  vmwareClusters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.roles.createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.roles.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.roles.listTagBindings</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">krmapihosting.  krmApiHosts.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  channels.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  inputs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">livestream.  pools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">logging.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">managedidentities.  domains.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">memcache.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  federations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">metastore.  services.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  alertPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">monitoring.  dashboards.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  hubs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  spokes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkmanagement.  connectivitytests.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">networkservices.  endpointConfigSelectors.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  gateways.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  gateways.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  httpFilters.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">networkservices.  meshes.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  caPools.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">privateca.  certificateTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></p>
<p><code dir="ltr" translate="no">pubsub.topics.updateTag</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterPerformanceRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  alloydbClusterReliabilityRecommendations.  list</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  get</code></p>
<p><code dir="ltr" translate="no">recommender.  cloudAssetInsights.  list</code></p>
<p><code dir="ltr" translate="no">recommender.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.locations.get</code></li>
<li><code dir="ltr" translate="no">recommender.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">redis.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">redis.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagKeys.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  create</code></li>
<li><code dir="ltr" translate="no">resourcemanager.  tagValueBindings.  delete</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.tagValues.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.jobs.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.jobs.listTagBindings</code></p>
<p><code dir="ltr" translate="no">run.services.createTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">run.services.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">run.services.listTagBindings</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">secretmanager.  secrets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">spanner.  instances.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">storage.folders.get</code></p>
<p><code dir="ltr" translate="no">storage.folders.list</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.get</code></p>
<p><code dir="ltr" translate="no">storage.managedFolders.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobTemplates.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">transcoder.  jobs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPeerings.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  networkPolicies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateClouds.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  privateConnections.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">vmwareengine.  vmwareEngineNetworks.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workflows.  workflows.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  createTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  deleteTagBinding</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">workstations.  workstationClusters.  listTagBindings</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.reader" class="role-title add-link" data-text="DLP Reader" tabindex="-1">DLP Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p>Read DLP entities, such as jobs and templates.</p></td>
<td><p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectFindings.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobTriggers.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.get</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.list</code></p>
<p><code dir="ltr" translate="no">dlp.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.locations.get</code></li>
<li><code dir="ltr" translate="no">dlp.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.storedInfoTypesEditor" class="role-title add-link" data-text="DLP Stored InfoTypes Editor" tabindex="-1">DLP Stored InfoTypes Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p>
<p>Edit DLP stored info types.</p></td>
<td><p><code dir="ltr" translate="no">dlp.storedInfoTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.create</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.delete</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></li>
<li><code dir="ltr" translate="no">dlp.storedInfoTypes.update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.storedInfoTypesReader" class="role-title add-link" data-text="DLP Stored InfoTypes Reader" tabindex="-1">DLP Stored InfoTypes Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.storedInfoTypesReader</code> )</p>
<p>Read DLP stored info types.</p></td>
<td><p><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></p>
<p><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.subscriptionsAdmin" class="role-title add-link" data-text="DLP Subscription Admin" tabindex="-1">DLP Subscription Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p>
<p>Manage DLP subscriptions.</p></td>
<td><p><code dir="ltr" translate="no">dlp.subscriptions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.subscriptions.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">dlp.subscriptions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.subscriptionsReader" class="role-title add-link" data-text="DLP Subscription Viewer" tabindex="-1">DLP Subscription Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.subscriptionsReader</code> )</p>
<p>View DLP subscriptions.</p></td>
<td><p><code dir="ltr" translate="no">dlp.subscriptions.get</code></p>
<p><code dir="ltr" translate="no">dlp.subscriptions.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.tableDataProfilesAdmin" class="role-title add-link" data-text="DLP Table Data Profiles Admin" tabindex="-1">DLP Table Data Profiles Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.tableDataProfilesAdmin</code> )</p>
<p>Manage DLP table profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.tableDataProfiles.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.delete</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></li>
<li><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.tableDataProfilesReader" class="role-title add-link" data-text="DLP Table Data Profiles Reader" tabindex="-1">DLP Table Data Profiles Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.tableDataProfilesReader</code> )</p>
<p>Read DLP table profiles.</p></td>
<td><p><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></p>
<p><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></p></td>
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
<td><h4 id="dlp.serviceAgent" class="role-title add-link" data-text="DLP API Service Agent" tabindex="-1">DLP API Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</p>
<p>Gives the Cloud DLP API service agent permissions for BigQuery, Cloud Storage, Datastore, Pub/Sub, and Cloud KMS.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">appengine.applications.get</code></p>
<p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.attach</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.create</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.delete</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.list</code></p>
<p><code dir="ltr" translate="no">bigquery.  dataPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.dataPolicies.update</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.datasets.create</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.get</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.link</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listSharedDatasetUsage</code></li>
<li><code dir="ltr" translate="no">bigquery.  datasets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.update</code></li>
<li><code dir="ltr" translate="no">bigquery.datasets.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.update</code></p>
<p><code dir="ltr" translate="no">bigquery.models.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.models.create</code></li>
<li><code dir="ltr" translate="no">bigquery.models.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.models.export</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.getMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.list</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateMetadata</code></li>
<li><code dir="ltr" translate="no">bigquery.models.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.readsessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.readsessions.create</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.readsessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.routines.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.routines.create</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.get</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.list</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.update</code></li>
<li><code dir="ltr" translate="no">bigquery.routines.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  create</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">bigquery.rowAccessPolicies.get</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  list</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">bigquery.  rowAccessPolicies.  update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquery.tables.create</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.delete</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.deleteSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.export</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.get</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.list</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.replicateData</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  restoreSnapshot</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setCategory</code></li>
<li><code dir="ltr" translate="no">bigquery.  tables.  setColumnDataPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.update</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateData</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateIndex</code></li>
<li><code dir="ltr" translate="no">bigquery.tables.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudaicompanion.  instances.  completeTask</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllIamPolicies</code></p>
<p><code dir="ltr" translate="no">cloudkms.  cryptoKeyVersions.  useToDecrypt</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.locations.list</code></p>
<p><code dir="ltr" translate="no">databasesconsole.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">databasesconsole.locations.get</code></li>
<li><code dir="ltr" translate="no">databasesconsole.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  create</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  delete</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  search</code></p>
<p><code dir="ltr" translate="no">databasesconsole.  studioQueries.  update</code></p>
<p><code dir="ltr" translate="no">datacatalog.  categories.  fineGrainedGet</code></p>
<p><code dir="ltr" translate="no">datacatalog.  migrationConfig.  get</code></p>
<p><code dir="ltr" translate="no">datacatalog.tagTemplates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  create</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.get</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  getTag</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">datacatalog.  tagTemplates.  update</code></li>
<li><code dir="ltr" translate="no">datacatalog.tagTemplates.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">dataplex.aspectTypes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.create</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.get</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.list</code></li>
<li><code dir="ltr" translate="no">dataplex.  aspectTypes.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.update</code></li>
<li><code dir="ltr" translate="no">dataplex.aspectTypes.use</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.datascans.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataplex.datascans.cancel</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.create</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.delete</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.get</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.getData</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.list</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.run</code></li>
<li><code dir="ltr" translate="no">dataplex.  datascans.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataplex.datascans.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataplex.entries.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.get</code></p>
<p><code dir="ltr" translate="no">dataplex.operations.list</code></p>
<p><code dir="ltr" translate="no">dataplex.projects.search</code></p>
<p><code dir="ltr" translate="no">datastore.databases.get</code></p>
<p><code dir="ltr" translate="no">datastore.  databases.  getMetadata</code></p>
<p><code dir="ltr" translate="no">datastore.databases.list</code></p>
<p><code dir="ltr" translate="no">datastore.entities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.entities.allocateIds</code></li>
<li><code dir="ltr" translate="no">datastore.entities.create</code></li>
<li><code dir="ltr" translate="no">datastore.entities.delete</code></li>
<li><code dir="ltr" translate="no">datastore.entities.get</code></li>
<li><code dir="ltr" translate="no">datastore.entities.list</code></li>
<li><code dir="ltr" translate="no">datastore.entities.update</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.namespaces.get</code></li>
<li><code dir="ltr" translate="no">datastore.namespaces.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datastore.schemas.list</code></p>
<p><code dir="ltr" translate="no">datastore.statistics.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datastore.statistics.get</code></li>
<li><code dir="ltr" translate="no">datastore.statistics.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></p>
<p><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></p>
<p><code dir="ltr" translate="no">dlp.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dlp.jobs.cancel</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.create</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.delete</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.get</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.hybridInspect</code></li>
<li><code dir="ltr" translate="no">dlp.jobs.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dlp.kms.encrypt</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.timeSeries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.timeSeries.create</code></li>
<li><code dir="ltr" translate="no">monitoring.timeSeries.list</code></li>
</ul>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">pubsub.*</code></p>
<ul>
<li><code dir="ltr" translate="no">pubsub.  messageTransforms.  validate</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.attach</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.commit</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.create</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.get</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.list</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.listRevisions</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.rollback</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.schemas.validate</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.create</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.get</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.  snapshots.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.seek</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.snapshots.update</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.consume</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.create</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.get</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.  subscriptions.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.subscriptions.update</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  attachSubscription</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.create</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.createTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.delete</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  detachSubscription</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.get</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.list</code></li>
<li><code dir="ltr" translate="no">pubsub.  topics.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.listTagBindings</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.publish</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.update</code></li>
<li><code dir="ltr" translate="no">pubsub.topics.updateTag</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  iamPolicyInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  iamPolicyRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteInsights.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  get</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  list</code></li>
<li><code dir="ltr" translate="no">recommender.  storageBucketSoftDeleteRecommendations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  hierarchyNodes.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
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
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p>
<p><code dir="ltr" translate="no">storage.anywhereCaches.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.anywhereCaches.create</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.disable</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.get</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.list</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.pause</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.resume</code></li>
<li><code dir="ltr" translate="no">storage.anywhereCaches.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.bucketOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  bucketOperations.  cancel</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.get</code></li>
<li><code dir="ltr" translate="no">storage.bucketOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.buckets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.buckets.create</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.buckets.delete</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  enableObjectRetention</code></li>
<li><code dir="ltr" translate="no">storage.buckets.get</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.getIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  getObjectInsights</code></li>
<li><code dir="ltr" translate="no">storage.buckets.list</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">storage.buckets.relocate</code></li>
<li><code dir="ltr" translate="no">storage.buckets.restore</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.buckets.setIpFilter</code></li>
<li><code dir="ltr" translate="no">storage.buckets.update</code></li>
<li><code dir="ltr" translate="no">storage.  buckets.  viewIntelligenceDetails</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.featureConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.featureConfigs.create</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.delete</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.get</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.list</code></li>
<li><code dir="ltr" translate="no">storage.featureConfigs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.folders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.folders.create</code></li>
<li><code dir="ltr" translate="no">storage.folders.delete</code></li>
<li><code dir="ltr" translate="no">storage.folders.get</code></li>
<li><code dir="ltr" translate="no">storage.folders.list</code></li>
<li><code dir="ltr" translate="no">storage.folders.rename</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.intelligenceConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storage.  intelligenceConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.managedFolders.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.managedFolders.create</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.delete</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.get</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.managedFolders.list</code></li>
<li><code dir="ltr" translate="no">storage.  managedFolders.  setIamPolicy</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.multipartUploads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.multipartUploads.abort</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  create</code></li>
<li><code dir="ltr" translate="no">storage.multipartUploads.list</code></li>
<li><code dir="ltr" translate="no">storage.  multipartUploads.  listParts</code></li>
</ul>
<p><code dir="ltr" translate="no">storage.objects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storage.objects.create</code></li>
<li><code dir="ltr" translate="no">storage.objects.createContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.delete</code></li>
<li><code dir="ltr" translate="no">storage.objects.deleteContext</code></li>
<li><code dir="ltr" translate="no">storage.objects.get</code></li>
<li><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.list</code></li>
<li><code dir="ltr" translate="no">storage.objects.move</code></li>
<li><code dir="ltr" translate="no">storage.  objects.  overrideUnlockedRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.restore</code></li>
<li><code dir="ltr" translate="no">storage.objects.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">storage.objects.setRetention</code></li>
<li><code dir="ltr" translate="no">storage.objects.update</code></li>
<li><code dir="ltr" translate="no">storage.objects.updateContext</code></li>
</ul>
<p><code dir="ltr" translate="no">storagebatchoperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  bucketOperations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  create</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  jobs.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  locations.  list</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  get</code></li>
<li><code dir="ltr" translate="no">storagebatchoperations.  operations.  list</code></li>
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
<td><h4 id="dlp.analyzeRiskTemplates.create" class="permission-name add-link" data-text="dlp.analyzeRiskTemplates.create" tabindex="-1"><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.analyzeRiskTemplates.delete" class="permission-name add-link" data-text="dlp.analyzeRiskTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.analyzeRiskTemplates.get" class="permission-name add-link" data-text="dlp.analyzeRiskTemplates.get" tabindex="-1"><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesReader">DLP Analyze Risk Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.analyzeRiskTemplates.list" class="permission-name add-link" data-text="dlp.analyzeRiskTemplates.list" tabindex="-1"><code dir="ltr" translate="no">dlp.analyzeRiskTemplates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesReader">DLP Analyze Risk Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.analyzeRiskTemplates.update" class="permission-name add-link" data-text="dlp.analyzeRiskTemplates.update" tabindex="-1"><code dir="ltr" translate="no">dlp.  analyzeRiskTemplates.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.analyzeRiskTemplatesEditor">DLP Analyze Risk Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.analyzeRiskTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.charts.get" class="permission-name add-link" data-text="dlp.charts.get" tabindex="-1"><code dir="ltr" translate="no">dlp.charts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.columnDataProfiles.get" class="permission-name add-link" data-text="dlp.columnDataProfiles.get" tabindex="-1"><code dir="ltr" translate="no">dlp.columnDataProfiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.columnDataProfilesReader">DLP Column Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.columnDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.columnDataProfiles.list" class="permission-name add-link" data-text="dlp.columnDataProfiles.list" tabindex="-1"><code dir="ltr" translate="no">dlp.columnDataProfiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.columnDataProfilesReader">DLP Column Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.columnDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.connections.create" class="permission-name add-link" data-text="dlp.connections.create" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.connections.delete" class="permission-name add-link" data-text="dlp.connections.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.connections.get" class="permission-name add-link" data-text="dlp.connections.get" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.connections.list" class="permission-name add-link" data-text="dlp.connections.list" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.connections.search" class="permission-name add-link" data-text="dlp.connections.search" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsReader">DLP Connections Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.connections.update" class="permission-name add-link" data-text="dlp.connections.update" tabindex="-1"><code dir="ltr" translate="no">dlp.connections.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.connectionsAdmin">DLP Connections Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.connectionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.deidentifyTemplates.create" class="permission-name add-link" data-text="dlp.deidentifyTemplates.create" tabindex="-1"><code dir="ltr" translate="no">dlp.deidentifyTemplates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.deidentifyTemplates.delete" class="permission-name add-link" data-text="dlp.deidentifyTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.deidentifyTemplates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.deidentifyTemplates.get" class="permission-name add-link" data-text="dlp.deidentifyTemplates.get" tabindex="-1"><code dir="ltr" translate="no">dlp.deidentifyTemplates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesReader">DLP De-identify Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.deidentifyTemplates.list" class="permission-name add-link" data-text="dlp.deidentifyTemplates.list" tabindex="-1"><code dir="ltr" translate="no">dlp.deidentifyTemplates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesReader">DLP De-identify Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.deidentifyTemplates.update" class="permission-name add-link" data-text="dlp.deidentifyTemplates.update" tabindex="-1"><code dir="ltr" translate="no">dlp.deidentifyTemplates.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.deidentifyTemplatesEditor">DLP De-identify Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.deidentifyTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.estimates.cancel" class="permission-name add-link" data-text="dlp.estimates.cancel" tabindex="-1"><code dir="ltr" translate="no">dlp.estimates.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.estimates.create" class="permission-name add-link" data-text="dlp.estimates.create" tabindex="-1"><code dir="ltr" translate="no">dlp.estimates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.estimates.delete" class="permission-name add-link" data-text="dlp.estimates.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.estimates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.estimates.get" class="permission-name add-link" data-text="dlp.estimates.get" tabindex="-1"><code dir="ltr" translate="no">dlp.estimates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.estimates.list" class="permission-name add-link" data-text="dlp.estimates.list" tabindex="-1"><code dir="ltr" translate="no">dlp.estimates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.estimatesAdmin">DLP Cost Estimation</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.estimatesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.fileStoreProfiles.delete" class="permission-name add-link" data-text="dlp.fileStoreProfiles.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.fileStoreProfiles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.fileStoreProfiles.get" class="permission-name add-link" data-text="dlp.fileStoreProfiles.get" tabindex="-1"><code dir="ltr" translate="no">dlp.fileStoreProfiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.fileStoreProfiles.list" class="permission-name add-link" data-text="dlp.fileStoreProfiles.list" tabindex="-1"><code dir="ltr" translate="no">dlp.fileStoreProfiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesAdmin">DLP File Store Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.fileStoreProfilesReader">DLP File Store Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.fileStoreProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.inspectFindings.list" class="permission-name add-link" data-text="dlp.inspectFindings.list" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectFindings.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectFindingsReader">DLP Inspect Findings Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectFindingsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.inspectTemplates.create" class="permission-name add-link" data-text="dlp.inspectTemplates.create" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectTemplates.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.inspectTemplates.delete" class="permission-name add-link" data-text="dlp.inspectTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectTemplates.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.inspectTemplates.get" class="permission-name add-link" data-text="dlp.inspectTemplates.get" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectTemplates.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesReader">DLP Inspect Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.inspectTemplates.list" class="permission-name add-link" data-text="dlp.inspectTemplates.list" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectTemplates.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesReader">DLP Inspect Templates Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dialogflow#dialogflow.serviceAgent">Dialogflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dialogflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.inspectTemplates.update" class="permission-name add-link" data-text="dlp.inspectTemplates.update" tabindex="-1"><code dir="ltr" translate="no">dlp.inspectTemplates.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.inspectTemplatesEditor">DLP Inspect Templates Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.inspectTemplatesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobTriggers.create" class="permission-name add-link" data-text="dlp.jobTriggers.create" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobTriggers.delete" class="permission-name add-link" data-text="dlp.jobTriggers.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobTriggers.get" class="permission-name add-link" data-text="dlp.jobTriggers.get" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersReader">DLP Job Triggers Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobTriggers.hybridInspect" class="permission-name add-link" data-text="dlp.jobTriggers.hybridInspect" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.hybridInspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobTriggers.list" class="permission-name add-link" data-text="dlp.jobTriggers.list" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersReader">DLP Job Triggers Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobTriggers.update" class="permission-name add-link" data-text="dlp.jobTriggers.update" tabindex="-1"><code dir="ltr" translate="no">dlp.jobTriggers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobTriggersEditor">DLP Job Triggers Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobTriggersEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobs.cancel" class="permission-name add-link" data-text="dlp.jobs.cancel" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobs.create" class="permission-name add-link" data-text="dlp.jobs.create" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobs.delete" class="permission-name add-link" data-text="dlp.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobs.get" class="permission-name add-link" data-text="dlp.jobs.get" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsReader">DLP Jobs Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.jobs.hybridInspect" class="permission-name add-link" data-text="dlp.jobs.hybridInspect" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.hybridInspect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.jobs.list" class="permission-name add-link" data-text="dlp.jobs.list" tabindex="-1"><code dir="ltr" translate="no">dlp.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsReader">DLP Jobs Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.kms.encrypt" class="permission-name add-link" data-text="dlp.kms.encrypt" tabindex="-1"><code dir="ltr" translate="no">dlp.kms.encrypt</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.jobsEditor">DLP Jobs Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.jobsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.serviceAgent">DLP API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.locations.get" class="permission-name add-link" data-text="dlp.locations.get" tabindex="-1"><code dir="ltr" translate="no">dlp.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.locations.list" class="permission-name add-link" data-text="dlp.locations.list" tabindex="-1"><code dir="ltr" translate="no">dlp.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.user">DLP User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/ces#ces.serviceAgent">Customer Engagement Suite Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  ces.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenterinsights#contactcenterinsights.serviceAgent">Contact Center AI Insights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenterinsights.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.projectDataProfiles.get" class="permission-name add-link" data-text="dlp.projectDataProfiles.get" tabindex="-1"><code dir="ltr" translate="no">dlp.projectDataProfiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectDataProfilesReader">DLP Project Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.projectDataProfiles.list" class="permission-name add-link" data-text="dlp.projectDataProfiles.list" tabindex="-1"><code dir="ltr" translate="no">dlp.projectDataProfiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectDataProfilesReader">DLP Project Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.storedInfoTypes.create" class="permission-name add-link" data-text="dlp.storedInfoTypes.create" tabindex="-1"><code dir="ltr" translate="no">dlp.storedInfoTypes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.storedInfoTypes.delete" class="permission-name add-link" data-text="dlp.storedInfoTypes.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.storedInfoTypes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.storedInfoTypes.get" class="permission-name add-link" data-text="dlp.storedInfoTypes.get" tabindex="-1"><code dir="ltr" translate="no">dlp.storedInfoTypes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesReader">DLP Stored InfoTypes Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dlp.storedInfoTypes.list" class="permission-name add-link" data-text="dlp.storedInfoTypes.list" tabindex="-1"><code dir="ltr" translate="no">dlp.storedInfoTypes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.reader">DLP Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesReader">DLP Stored InfoTypes Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/modelarmor#modelarmor.serviceAgent">Model Armor Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  modelarmor.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.storedInfoTypes.update" class="permission-name add-link" data-text="dlp.storedInfoTypes.update" tabindex="-1"><code dir="ltr" translate="no">dlp.storedInfoTypes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.storedInfoTypesEditor">DLP Stored InfoTypes Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.storedInfoTypesEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.subscriptions.cancel" class="permission-name add-link" data-text="dlp.subscriptions.cancel" tabindex="-1"><code dir="ltr" translate="no">dlp.subscriptions.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.subscriptions.create" class="permission-name add-link" data-text="dlp.subscriptions.create" tabindex="-1"><code dir="ltr" translate="no">dlp.subscriptions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.subscriptions.get" class="permission-name add-link" data-text="dlp.subscriptions.get" tabindex="-1"><code dir="ltr" translate="no">dlp.subscriptions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsReader">DLP Subscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.subscriptions.list" class="permission-name add-link" data-text="dlp.subscriptions.list" tabindex="-1"><code dir="ltr" translate="no">dlp.subscriptions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsReader">DLP Subscription Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.subscriptions.update" class="permission-name add-link" data-text="dlp.subscriptions.update" tabindex="-1"><code dir="ltr" translate="no">dlp.subscriptions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.subscriptionsAdmin">DLP Subscription Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.subscriptionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.tableDataProfiles.delete" class="permission-name add-link" data-text="dlp.tableDataProfiles.delete" tabindex="-1"><code dir="ltr" translate="no">dlp.tableDataProfiles.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.tableDataProfilesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dlp.tableDataProfiles.get" class="permission-name add-link" data-text="dlp.tableDataProfiles.get" tabindex="-1"><code dir="ltr" translate="no">dlp.tableDataProfiles.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.tableDataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesReader">DLP Table Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.tableDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudsecuritycompliance.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="dlp.tableDataProfiles.list" class="permission-name add-link" data-text="dlp.tableDataProfiles.list" tabindex="-1"><code dir="ltr" translate="no">dlp.tableDataProfiles.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.admin">DLP Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.editor">DLP Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.viewer">DLP Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.admin">Security Center Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesAdmin">DLP Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.dataProfilesReader">DLP Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.dataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesAdmin">DLP Table Data Profiles Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.tableDataProfilesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.tableDataProfilesReader">DLP Table Data Profiles Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.tableDataProfilesReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminEditor">Security Center Admin Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.adminViewer">Security Center Admin Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.adminViewer</code> )</p></td>
</tr>
</tbody>
</table>
