---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph
title: Enterprise Knowledge Graph roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Enterprise Knowledge Graph. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Enterprise Knowledge Graph roles

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
<td><h4 id="enterpriseknowledgegraph.admin" class="role-title add-link" data-text="Enterprise Knowledge Graph Admin Beta" tabindex="-1">Enterprise Knowledge Graph Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p>Administrator of Enterprise Knowledge Graph resources</p></td>
<td><p><code dir="ltr" translate="no">enterpriseknowledgegraph.*</code></p>
<ul>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  search</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  cancel</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  create</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  delete</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  get</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="enterpriseknowledgegraph.editor" class="role-title add-link" data-text="Enterprise Knowledge Graph Editor Beta" tabindex="-1">Enterprise Knowledge Graph Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p>Editor of Enterprise Knowledge Graph resources</p></td>
<td><p><code dir="ltr" translate="no">enterpriseknowledgegraph.*</code></p>
<ul>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  search</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  cancel</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  create</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  delete</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  get</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="enterpriseknowledgegraph.viewer" class="role-title add-link" data-text="Enterprise Knowledge Graph Viewer Beta" tabindex="-1">Enterprise Knowledge Graph Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p>Viewer of Enterprise Knowledge Graph resources</p></td>
<td><p><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  get</code></p>
<p><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></p>
<p><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.*</code></p>
<ul>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  lookup</code></li>
<li><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  search</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="enterpriseknowledgegraph.serviceAgent" class="role-title add-link" data-text="Enterprise Knowledge Graph Service Agent" tabindex="-1">Enterprise Knowledge Graph Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  enterpriseknowledgegraph.serviceAgent</code> )</p>
<p>Gives Enterprise Knowledge Graph Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.readsessions.create</code></p>
<p><code dir="ltr" translate="no">bigquery.readsessions.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.update</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.updateData</code></p>
<p><code dir="ltr" translate="no">dataform.folders.create</code></p>
<p><code dir="ltr" translate="no">dataform.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataform.locations.get</code></li>
<li><code dir="ltr" translate="no">dataform.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataform.repositories.create</code></p>
<p><code dir="ltr" translate="no">dataform.repositories.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Enterprise Knowledge Graph permissions

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
<td><h4 id="enterpriseknowledgegraph.cloudKnowledgeGraphEntities.lookup" class="permission-name add-link" data-text="enterpriseknowledgegraph.cloudKnowledgeGraphEntities.lookup" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  lookup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="enterpriseknowledgegraph.cloudKnowledgeGraphEntities.search" class="permission-name add-link" data-text="enterpriseknowledgegraph.cloudKnowledgeGraphEntities.search" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  cloudKnowledgeGraphEntities.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="enterpriseknowledgegraph.entityReconciliationJobs.cancel" class="permission-name add-link" data-text="enterpriseknowledgegraph.entityReconciliationJobs.cancel" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="enterpriseknowledgegraph.entityReconciliationJobs.create" class="permission-name add-link" data-text="enterpriseknowledgegraph.entityReconciliationJobs.create" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="enterpriseknowledgegraph.entityReconciliationJobs.delete" class="permission-name add-link" data-text="enterpriseknowledgegraph.entityReconciliationJobs.delete" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="enterpriseknowledgegraph.entityReconciliationJobs.get" class="permission-name add-link" data-text="enterpriseknowledgegraph.entityReconciliationJobs.get" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="enterpriseknowledgegraph.entityReconciliationJobs.list" class="permission-name add-link" data-text="enterpriseknowledgegraph.entityReconciliationJobs.list" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  entityReconciliationJobs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="enterpriseknowledgegraph.publicKnowledgeGraphEntities.lookup" class="permission-name add-link" data-text="enterpriseknowledgegraph.publicKnowledgeGraphEntities.lookup" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  lookup</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="enterpriseknowledgegraph.publicKnowledgeGraphEntities.search" class="permission-name add-link" data-text="enterpriseknowledgegraph.publicKnowledgeGraphEntities.search" tabindex="-1"><code dir="ltr" translate="no">enterpriseknowledgegraph.  publicKnowledgeGraphEntities.  search</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin">Enterprise Knowledge Graph Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor">Enterprise Knowledge Graph Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer">Enterprise Knowledge Graph Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  enterpriseknowledgegraph.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
