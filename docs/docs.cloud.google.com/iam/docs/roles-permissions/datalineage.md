---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/datalineage
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage
title: Data Lineage API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Data Lineage API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Data Lineage API roles

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
<td>Data Lineage Administrator
<p>( <code>roles/ datalineage.admin</code> )</p>
<p>Grants full access to all resources in Data Lineage API</p></td>
<td><p><code>datalineage.*</code></p>
<ul>
<li><code>datalineage.configs.get</code></li>
<li><code>datalineage.configs.update</code></li>
<li><code>datalineage.events.create</code></li>
<li><code>datalineage.events.delete</code></li>
<li><code>datalineage.events.get</code></li>
<li><code>datalineage.events.getFields</code></li>
<li><code>datalineage.events.list</code></li>
<li><code>datalineage. locations. importLineage</code></li>
<li><code>datalineage. locations. processOpenLineageMessage</code></li>
<li><code>datalineage. locations. searchLinks</code></li>
<li><code>datalineage.operations.get</code></li>
<li><code>datalineage. processRevisions. delete</code></li>
<li><code>datalineage. processRevisions. get</code></li>
<li><code>datalineage. processRevisions. insert</code></li>
<li><code>datalineage. processRevisions. list</code></li>
<li><code>datalineage.processes.create</code></li>
<li><code>datalineage.processes.delete</code></li>
<li><code>datalineage.processes.get</code></li>
<li><code>datalineage.processes.list</code></li>
<li><code>datalineage. processes. markAsDeleted</code></li>
<li><code>datalineage.processes.update</code></li>
<li><code>datalineage.runs.create</code></li>
<li><code>datalineage.runs.delete</code></li>
<li><code>datalineage.runs.get</code></li>
<li><code>datalineage.runs.list</code></li>
<li><code>datalineage.runs.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Data Lineage Editor
<p>( <code>roles/ datalineage.editor</code> )</p>
<p>Grants edit access to all resources in Data Lineage API</p></td>
<td><p><code>datalineage.events.*</code></p>
<ul>
<li><code>datalineage.events.create</code></li>
<li><code>datalineage.events.delete</code></li>
<li><code>datalineage.events.get</code></li>
<li><code>datalineage.events.getFields</code></li>
<li><code>datalineage.events.list</code></li>
</ul>
<p><code>datalineage. locations. processOpenLineageMessage</code></p>
<p><code>datalineage. locations. searchLinks</code></p>
<p><code>datalineage.operations.get</code></p>
<p><code>datalineage.processRevisions.*</code></p>
<ul>
<li><code>datalineage. processRevisions. delete</code></li>
<li><code>datalineage. processRevisions. get</code></li>
<li><code>datalineage. processRevisions. insert</code></li>
<li><code>datalineage. processRevisions. list</code></li>
</ul>
<p><code>datalineage.processes.*</code></p>
<ul>
<li><code>datalineage.processes.create</code></li>
<li><code>datalineage.processes.delete</code></li>
<li><code>datalineage.processes.get</code></li>
<li><code>datalineage.processes.list</code></li>
<li><code>datalineage. processes. markAsDeleted</code></li>
<li><code>datalineage.processes.update</code></li>
</ul>
<p><code>datalineage.runs.*</code></p>
<ul>
<li><code>datalineage.runs.create</code></li>
<li><code>datalineage.runs.delete</code></li>
<li><code>datalineage.runs.get</code></li>
<li><code>datalineage.runs.list</code></li>
<li><code>datalineage.runs.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Data Lineage Viewer
<p>( <code>roles/ datalineage.viewer</code> )</p>
<p>Grants read access to all resources in Data Lineage API</p></td>
<td><p><code>datalineage.events.get</code></p>
<p><code>datalineage.events.getFields</code></p>
<p><code>datalineage.events.list</code></p>
<p><code>datalineage. locations. searchLinks</code></p>
<p><code>datalineage. processRevisions. get</code></p>
<p><code>datalineage. processRevisions. list</code></p>
<p><code>datalineage.processes.get</code></p>
<p><code>datalineage.processes.list</code></p>
<p><code>datalineage.runs.get</code></p>
<p><code>datalineage.runs.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Data Lineage Events Producer
<p>( <code>roles/ datalineage.producer</code> )</p>
<p>Grants access to creating all resources in Data Lineage API</p></td>
<td><p><code>datalineage.events.create</code></p>
<p><code>datalineage. locations. processOpenLineageMessage</code></p>
<p><code>datalineage. processRevisions. insert</code></p>
<p><code>datalineage.processes.create</code></p>
<p><code>datalineage.processes.get</code></p>
<p><code>datalineage. processes. markAsDeleted</code></p>
<p><code>datalineage.processes.update</code></p>
<p><code>datalineage.runs.create</code></p>
<p><code>datalineage.runs.get</code></p>
<p><code>datalineage.runs.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Data Lineage API permissions

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
<td><code>datalineage.configs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.configs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.events.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.events.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.events.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.events.getFields</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.events.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage. locations. importLineage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>datalineage. locations. processOpenLineageMessage</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code>roles/ dataproc.worker</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage. locations. searchLinks</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/bigquerydatatransfer#bigquerydatatransfer.serviceAgent">BigQuery Data Transfer Service Agent</a> ( <code>roles/ bigquerydatatransfer.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>datalineage. processRevisions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage. processRevisions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage. processRevisions. insert</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage. processRevisions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.processes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.processes.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.processes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.processes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage. processes. markAsDeleted</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.processes.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.runs.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.runs.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.runs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>datalineage.runs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer (Legacy)</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code>roles/ datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>datalineage.runs.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner (Legacy)</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor (Legacy)</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code>roles/ datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code>roles/ datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code>roles/ composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code>roles/ datalineage.producer</code> )</p></td>
</tr>
</tbody>
</table>
