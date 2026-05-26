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
<td><h4 id="datalineage.admin" class="role-title add-link" data-text="Data Lineage Administrator" tabindex="-1">Data Lineage Administrator</h4>
<p>( <code dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p>Grants full access to all resources in Data Lineage API</p></td>
<td><p><code dir="ltr" translate="no">datalineage.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalineage.configs.get</code></li>
<li><code dir="ltr" translate="no">datalineage.configs.update</code></li>
<li><code dir="ltr" translate="no">datalineage.events.create</code></li>
<li><code dir="ltr" translate="no">datalineage.events.delete</code></li>
<li><code dir="ltr" translate="no">datalineage.events.get</code></li>
<li><code dir="ltr" translate="no">datalineage.events.getFields</code></li>
<li><code dir="ltr" translate="no">datalineage.events.list</code></li>
<li><code dir="ltr" translate="no">datalineage.  locations.  processOpenLineageMessage</code></li>
<li><code dir="ltr" translate="no">datalineage.  locations.  searchLinks</code></li>
<li><code dir="ltr" translate="no">datalineage.operations.get</code></li>
<li><code dir="ltr" translate="no">datalineage.processes.create</code></li>
<li><code dir="ltr" translate="no">datalineage.processes.delete</code></li>
<li><code dir="ltr" translate="no">datalineage.processes.get</code></li>
<li><code dir="ltr" translate="no">datalineage.processes.list</code></li>
<li><code dir="ltr" translate="no">datalineage.processes.update</code></li>
<li><code dir="ltr" translate="no">datalineage.runs.create</code></li>
<li><code dir="ltr" translate="no">datalineage.runs.delete</code></li>
<li><code dir="ltr" translate="no">datalineage.runs.get</code></li>
<li><code dir="ltr" translate="no">datalineage.runs.list</code></li>
<li><code dir="ltr" translate="no">datalineage.runs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.editor" class="role-title add-link" data-text="Data Lineage Editor" tabindex="-1">Data Lineage Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p>Grants edit access to all resources in Data Lineage API</p></td>
<td><p><code dir="ltr" translate="no">datalineage.events.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalineage.events.create</code></li>
<li><code dir="ltr" translate="no">datalineage.events.delete</code></li>
<li><code dir="ltr" translate="no">datalineage.events.get</code></li>
<li><code dir="ltr" translate="no">datalineage.events.getFields</code></li>
<li><code dir="ltr" translate="no">datalineage.events.list</code></li>
</ul>
<p><code dir="ltr" translate="no">datalineage.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">datalineage.  locations.  processOpenLineageMessage</code></li>
<li><code dir="ltr" translate="no">datalineage.  locations.  searchLinks</code></li>
</ul>
<p><code dir="ltr" translate="no">datalineage.operations.get</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.create</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.get</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.list</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.update</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.create</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.get</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.list</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.viewer" class="role-title add-link" data-text="Data Lineage Viewer" tabindex="-1">Data Lineage Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p>Grants read access to all resources in Data Lineage API</p></td>
<td><p><code dir="ltr" translate="no">datalineage.events.get</code></p>
<p><code dir="ltr" translate="no">datalineage.events.getFields</code></p>
<p><code dir="ltr" translate="no">datalineage.events.list</code></p>
<p><code dir="ltr" translate="no">datalineage.  locations.  searchLinks</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.get</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.list</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.get</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.producer" class="role-title add-link" data-text="Data Lineage Events Producer" tabindex="-1">Data Lineage Events Producer</h4>
<p>( <code dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p>Grants access to creating all resources in Data Lineage API</p></td>
<td><p><code dir="ltr" translate="no">datalineage.events.create</code></p>
<p><code dir="ltr" translate="no">datalineage.  locations.  processOpenLineageMessage</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.create</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.get</code></p>
<p><code dir="ltr" translate="no">datalineage.processes.update</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.create</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.get</code></p>
<p><code dir="ltr" translate="no">datalineage.runs.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="datalineage.configs.get" class="permission-name add-link" data-text="datalineage.configs.get" tabindex="-1"><code dir="ltr" translate="no">datalineage.configs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.configs.update" class="permission-name add-link" data-text="datalineage.configs.update" tabindex="-1"><code dir="ltr" translate="no">datalineage.configs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.events.create" class="permission-name add-link" data-text="datalineage.events.create" tabindex="-1"><code dir="ltr" translate="no">datalineage.events.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.events.delete" class="permission-name add-link" data-text="datalineage.events.delete" tabindex="-1"><code dir="ltr" translate="no">datalineage.events.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.events.get" class="permission-name add-link" data-text="datalineage.events.get" tabindex="-1"><code dir="ltr" translate="no">datalineage.events.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.events.getFields" class="permission-name add-link" data-text="datalineage.events.getFields" tabindex="-1"><code dir="ltr" translate="no">datalineage.events.getFields</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.events.list" class="permission-name add-link" data-text="datalineage.events.list" tabindex="-1"><code dir="ltr" translate="no">datalineage.events.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.locations.processOpenLineageMessage" class="permission-name add-link" data-text="datalineage.locations.processOpenLineageMessage" tabindex="-1"><code dir="ltr" translate="no">datalineage.  locations.  processOpenLineageMessage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataproc#dataproc.worker">Dataproc Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataproc.worker</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.locations.searchLinks" class="permission-name add-link" data-text="datalineage.locations.searchLinks" tabindex="-1"><code dir="ltr" translate="no">datalineage.  locations.  searchLinks</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.operations.get" class="permission-name add-link" data-text="datalineage.operations.get" tabindex="-1"><code dir="ltr" translate="no">datalineage.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.processes.create" class="permission-name add-link" data-text="datalineage.processes.create" tabindex="-1"><code dir="ltr" translate="no">datalineage.processes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.processes.delete" class="permission-name add-link" data-text="datalineage.processes.delete" tabindex="-1"><code dir="ltr" translate="no">datalineage.processes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.processes.get" class="permission-name add-link" data-text="datalineage.processes.get" tabindex="-1"><code dir="ltr" translate="no">datalineage.processes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.processes.list" class="permission-name add-link" data-text="datalineage.processes.list" tabindex="-1"><code dir="ltr" translate="no">datalineage.processes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.processes.update" class="permission-name add-link" data-text="datalineage.processes.update" tabindex="-1"><code dir="ltr" translate="no">datalineage.processes.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.runs.create" class="permission-name add-link" data-text="datalineage.runs.create" tabindex="-1"><code dir="ltr" translate="no">datalineage.runs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.runs.delete" class="permission-name add-link" data-text="datalineage.runs.delete" tabindex="-1"><code dir="ltr" translate="no">datalineage.runs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.runs.get" class="permission-name add-link" data-text="datalineage.runs.get" tabindex="-1"><code dir="ltr" translate="no">datalineage.runs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="datalineage.runs.list" class="permission-name add-link" data-text="datalineage.runs.list" tabindex="-1"><code dir="ltr" translate="no">datalineage.runs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.viewer">Data Lineage Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="datalineage.runs.update" class="permission-name add-link" data-text="datalineage.runs.update" tabindex="-1"><code dir="ltr" translate="no">datalineage.runs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.admin">Data Lineage Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.editor">Data Lineage Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.worker">Composer Worker</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.worker</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datalineage#datalineage.producer">Data Lineage Events Producer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datalineage.producer</code> )</p></td>
</tr>
</tbody>
</table>
