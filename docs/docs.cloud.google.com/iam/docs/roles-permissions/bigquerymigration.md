---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration
title: BigQuery Migration API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Migration API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Migration API roles

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
<td>Bigquerymigration Admin
<p>( <code>roles/ bigquerymigration.admin</code> )</p>
<p>Admin role for bigquerymigration</p></td>
<td><p><code>bigquerymigration.*</code></p>
<ul>
<li><code>bigquerymigration.subtasks.get</code></li>
<li><code>bigquerymigration. subtasks. list</code></li>
<li><code>bigquerymigration. translation. translate</code></li>
<li><code>bigquerymigration. workflows. create</code></li>
<li><code>bigquerymigration. workflows. delete</code></li>
<li><code>bigquerymigration. workflows. enableAiOutputTypes</code></li>
<li><code>bigquerymigration. workflows. enableLineageOutputTypes</code></li>
<li><code>bigquerymigration. workflows. enableOutputTypePermissions</code></li>
<li><code>bigquerymigration. workflows. get</code></li>
<li><code>bigquerymigration. workflows. list</code></li>
<li><code>bigquerymigration. workflows. orchestrateTask</code></li>
<li><code>bigquerymigration. workflows. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>MigrationWorkflow Editor
<p>( <code>roles/ bigquerymigration.editor</code> )</p>
<p>Editor of EDW migration workflows.</p></td>
<td><p><code>bigquerymigration.subtasks.*</code></p>
<ul>
<li><code>bigquerymigration.subtasks.get</code></li>
<li><code>bigquerymigration. subtasks. list</code></li>
</ul>
<p><code>bigquerymigration. workflows. create</code></p>
<p><code>bigquerymigration. workflows. delete</code></p>
<p><code>bigquerymigration. workflows. enableAiOutputTypes</code></p>
<p><code>bigquerymigration. workflows. enableLineageOutputTypes</code></p>
<p><code>bigquerymigration. workflows. enableOutputTypePermissions</code></p>
<p><code>bigquerymigration. workflows. get</code></p>
<p><code>bigquerymigration. workflows. list</code></p>
<p><code>bigquerymigration. workflows. update</code></p></td>
</tr>
<tr class="odd">
<td>MigrationWorkflow Viewer
<p>( <code>roles/ bigquerymigration.viewer</code> )</p>
<p>Viewer of EDW migration MigrationWorkflow.</p></td>
<td><p><code>bigquerymigration.subtasks.*</code></p>
<ul>
<li><code>bigquerymigration.subtasks.get</code></li>
<li><code>bigquerymigration. subtasks. list</code></li>
</ul>
<p><code>bigquerymigration. workflows. get</code></p>
<p><code>bigquerymigration. workflows. list</code></p></td>
</tr>
<tr class="even">
<td>Migration Management Editor <sup>Beta</sup>
<p>( <code>roles/ bigquerymigration.migrationEditor</code> )</p>
<p>Admin of EDW migrations.</p></td>
<td></td>
</tr>
<tr class="odd">
<td>Migration Management Viewer <sup>Beta</sup>
<p>( <code>roles/ bigquerymigration.migrationViewer</code> )</p>
<p>Viewer of EDW migrations.</p></td>
<td></td>
</tr>
<tr class="even">
<td>Task Orchestrator
<p>( <code>roles/ bigquerymigration.orchestrator</code> )</p>
<p>Orchestrator of EDW migration tasks.</p></td>
<td><p><code>bigquerymigration. workflows. orchestrateTask</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td>Migration Translation User
<p>( <code>roles/ bigquerymigration.translationUser</code> )</p>
<p>User of EDW migration interactive SQL translation service.</p></td>
<td><p><code>bigquerymigration. translation. translate</code></p></td>
</tr>
<tr class="even">
<td>Task Worker
<p>( <code>roles/ bigquerymigration.worker</code> )</p>
<p>Worker that executes EDW migration subtasks.</p></td>
<td><p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
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
<td>BigQuery Migration Service Agent
<p>( <code>roles/ bigquerymigration.serviceAgent</code> )</p>
<p>Access required for the BigQuery Migration Service to perform data discovery, metadata registration, and manage data transfers.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Migration API permissions

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
<td><code>bigquerymigration.subtasks.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code>roles/ bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. subtasks. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code>roles/ bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>bigquerymigration. translation. translate</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code>roles/ bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code>roles/ bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code>roles/ bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.translationUser">Migration Translation User</a> ( <code>roles/ bigquerymigration.translationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code>roles/ iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code>roles/ dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code>roles/ dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. workflows. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>bigquerymigration. workflows. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. workflows. enableAiOutputTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>bigquerymigration. workflows. enableLineageOutputTypes</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. workflows. enableOutputTypePermissions</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>bigquerymigration. workflows. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code>roles/ bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. workflows. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code>roles/ bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>bigquerymigration. workflows. orchestrateTask</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.orchestrator">Task Orchestrator</a> ( <code>roles/ bigquerymigration.orchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><code>bigquerymigration. workflows. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code>roles/ bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code>roles/ bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
