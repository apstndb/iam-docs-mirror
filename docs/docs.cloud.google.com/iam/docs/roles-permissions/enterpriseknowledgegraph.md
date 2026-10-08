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
<td>Enterprise Knowledge Graph Admin <sup>Beta</sup>
<p>( <code>roles/ enterpriseknowledgegraph.admin</code> )</p>
<p>Administrator of Enterprise Knowledge Graph resources</p></td>
<td><p><code>enterpriseknowledgegraph.*</code></p>
<ul>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. search</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. cancel</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. create</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. delete</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. get</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. list</code></li>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. search</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Enterprise Knowledge Graph Editor <sup>Beta</sup>
<p>( <code>roles/ enterpriseknowledgegraph.editor</code> )</p>
<p>Editor of Enterprise Knowledge Graph resources</p></td>
<td><p><code>enterpriseknowledgegraph.*</code></p>
<ul>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. search</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. cancel</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. create</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. delete</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. get</code></li>
<li><code>enterpriseknowledgegraph. entityReconciliationJobs. list</code></li>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. search</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Enterprise Knowledge Graph Viewer <sup>Beta</sup>
<p>( <code>roles/ enterpriseknowledgegraph.viewer</code> )</p>
<p>Viewer of Enterprise Knowledge Graph resources</p></td>
<td><p><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities.*</code></p>
<ul>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. cloudKnowledgeGraphEntities. search</code></li>
</ul>
<p><code>enterpriseknowledgegraph. entityReconciliationJobs. get</code></p>
<p><code>enterpriseknowledgegraph. entityReconciliationJobs. list</code></p>
<p><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities.*</code></p>
<ul>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. lookup</code></li>
<li><code>enterpriseknowledgegraph. publicKnowledgeGraphEntities. search</code></li>
</ul>
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
<td>Enterprise Knowledge Graph Service Agent
<p>( <code>roles/ enterpriseknowledgegraph.serviceAgent</code> )</p>
<p>Gives Enterprise Knowledge Graph Service Account access to consumer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>bigquery.config.get</code></p>
<p><code>bigquery.datasets.create</code></p>
<p><code>bigquery.datasets.get</code></p>
<p><code>bigquery.jobs.create</code></p>
<p><code>bigquery.readsessions.create</code></p>
<p><code>bigquery.readsessions.getData</code></p>
<p><code>bigquery.tables.create</code></p>
<p><code>bigquery.tables.get</code></p>
<p><code>bigquery.tables.getData</code></p>
<p><code>bigquery.tables.list</code></p>
<p><code>bigquery.tables.update</code></p>
<p><code>bigquery.tables.updateData</code></p>
<p><code>dataform.folders.create</code></p>
<p><code>dataform.locations.*</code></p>
<ul>
<li><code>dataform.locations.get</code></li>
<li><code>dataform.locations.list</code></li>
</ul>
<p><code>dataform.repositories.create</code></p>
<p><code>dataform.repositories.list</code></p>
<p><code>geminidataanalytics. locations. chat</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Enterprise Knowledge Graph permissions

| Permission                                                       | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `enterpriseknowledgegraph. cloudKnowledgeGraphEntities. lookup`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `enterpriseknowledgegraph. cloudKnowledgeGraphEntities. search`  | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `enterpriseknowledgegraph. entityReconciliationJobs. cancel`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `enterpriseknowledgegraph. entityReconciliationJobs. create`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `enterpriseknowledgegraph. entityReconciliationJobs. delete`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| `enterpriseknowledgegraph. entityReconciliationJobs. get`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `enterpriseknowledgegraph. entityReconciliationJobs. list`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `enterpriseknowledgegraph. publicKnowledgeGraphEntities. lookup` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `enterpriseknowledgegraph. publicKnowledgeGraphEntities. search` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Enterprise Knowledge Graph Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.admin) ( `roles/ enterpriseknowledgegraph.admin` ) [Enterprise Knowledge Graph Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.editor) ( `roles/ enterpriseknowledgegraph.editor` ) [Enterprise Knowledge Graph Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/enterpriseknowledgegraph#enterpriseknowledgegraph.viewer) ( `roles/ enterpriseknowledgegraph.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
