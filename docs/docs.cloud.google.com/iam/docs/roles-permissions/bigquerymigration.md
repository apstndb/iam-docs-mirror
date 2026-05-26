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
<td><h4 id="bigquerymigration.admin" class="role-title add-link" data-text="Bigquerymigration Admin" tabindex="-1">Bigquerymigration Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p>Admin role for bigquerymigration</p></td>
<td><p><code dir="ltr" translate="no">bigquerymigration.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquerymigration.subtasks.get</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  create</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  delete</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableAiOutputTypes</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableLineageOutputTypes</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableOutputTypePermissions</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  get</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  orchestrateTask</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  workflows.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.editor" class="role-title add-link" data-text="MigrationWorkflow Editor" tabindex="-1">MigrationWorkflow Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p>
<p>Editor of EDW migration workflows.</p></td>
<td><p><code dir="ltr" translate="no">bigquerymigration.subtasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquerymigration.subtasks.get</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  create</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  delete</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableAiOutputTypes</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableLineageOutputTypes</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableOutputTypePermissions</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  get</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.viewer" class="role-title add-link" data-text="MigrationWorkflow Viewer" tabindex="-1">MigrationWorkflow Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.viewer</code> )</p>
<p>Viewer of EDW migration MigrationWorkflow.</p></td>
<td><p><code dir="ltr" translate="no">bigquerymigration.subtasks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">bigquerymigration.subtasks.get</code></li>
<li><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  get</code></p>
<p><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.orchestrator" class="role-title add-link" data-text="Task Orchestrator" tabindex="-1">Task Orchestrator</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.orchestrator</code> )</p>
<p>Orchestrator of EDW migration tasks.</p></td>
<td><p><code dir="ltr" translate="no">bigquerymigration.  workflows.  orchestrateTask</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.translationUser" class="role-title add-link" data-text="Migration Translation User" tabindex="-1">Migration Translation User</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.translationUser</code> )</p>
<p>User of EDW migration interactive SQL translation service.</p></td>
<td><p><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.worker" class="role-title add-link" data-text="Task Worker" tabindex="-1">Task Worker</h4>
<p>( <code dir="ltr" translate="no">roles/  bigquerymigration.worker</code> )</p>
<p>Worker that executes EDW migration subtasks.</p></td>
<td><p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
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
<td><h4 id="bigquerymigration.subtasks.get" class="permission-name add-link" data-text="bigquerymigration.subtasks.get" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.subtasks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.subtasks.list" class="permission-name add-link" data-text="bigquerymigration.subtasks.list" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  subtasks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.translation.translate" class="permission-name add-link" data-text="bigquerymigration.translation.translate" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  translation.  translate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.admin">BigQuery Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.studioAdmin">BigQuery Studio Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.studioAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquery#bigquery.user">BigQuery User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquery.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.translationUser">Migration Translation User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.translationUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprep#dataprep.serviceAgent">Dataprep Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprep.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.workflows.create" class="permission-name add-link" data-text="bigquerymigration.workflows.create" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.workflows.delete" class="permission-name add-link" data-text="bigquerymigration.workflows.delete" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.workflows.enableAiOutputTypes" class="permission-name add-link" data-text="bigquerymigration.workflows.enableAiOutputTypes" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableAiOutputTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.workflows.enableLineageOutputTypes" class="permission-name add-link" data-text="bigquerymigration.workflows.enableLineageOutputTypes" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableLineageOutputTypes</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.workflows.enableOutputTypePermissions" class="permission-name add-link" data-text="bigquerymigration.workflows.enableOutputTypePermissions" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  enableOutputTypePermissions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.workflows.get" class="permission-name add-link" data-text="bigquerymigration.workflows.get" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.workflows.list" class="permission-name add-link" data-text="bigquerymigration.workflows.list" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.viewer">MigrationWorkflow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="bigquerymigration.workflows.orchestrateTask" class="permission-name add-link" data-text="bigquerymigration.workflows.orchestrateTask" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  orchestrateTask</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.orchestrator">Task Orchestrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.orchestrator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="bigquerymigration.workflows.update" class="permission-name add-link" data-text="bigquerymigration.workflows.update" tabindex="-1"><code dir="ltr" translate="no">bigquerymigration.  workflows.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.admin">Bigquerymigration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerymigration#bigquerymigration.editor">MigrationWorkflow Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  bigquerymigration.editor</code> )</p></td>
</tr>
</tbody>
</table>
