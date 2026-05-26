---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/biglake
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/biglake
title: BigLake roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigLake. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigLake roles

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
<td><h4 id="biglake.admin" class="role-title add-link" data-text="BigLake Admin" tabindex="-1">BigLake Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p>Provides full access to all BigLake resources.</p></td>
<td><p><code dir="ltr" translate="no">biglake.*</code></p>
<ul>
<li><code dir="ltr" translate="no">biglake.catalogs.create</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.delete</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.get</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.list</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.catalogs.update</code></li>
<li><code dir="ltr" translate="no">biglake.databases.create</code></li>
<li><code dir="ltr" translate="no">biglake.databases.delete</code></li>
<li><code dir="ltr" translate="no">biglake.databases.get</code></li>
<li><code dir="ltr" translate="no">biglake.databases.list</code></li>
<li><code dir="ltr" translate="no">biglake.databases.update</code></li>
<li><code dir="ltr" translate="no">biglake.locks.check</code></li>
<li><code dir="ltr" translate="no">biglake.locks.create</code></li>
<li><code dir="ltr" translate="no">biglake.locks.delete</code></li>
<li><code dir="ltr" translate="no">biglake.locks.list</code></li>
<li><code dir="ltr" translate="no">biglake.namespaces.create</code></li>
<li><code dir="ltr" translate="no">biglake.namespaces.delete</code></li>
<li><code dir="ltr" translate="no">biglake.namespaces.get</code></li>
<li><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.namespaces.list</code></li>
<li><code dir="ltr" translate="no">biglake.  namespaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.namespaces.update</code></li>
<li><code dir="ltr" translate="no">biglake.tables.create</code></li>
<li><code dir="ltr" translate="no">biglake.  tables.  createPartitions</code></li>
<li><code dir="ltr" translate="no">biglake.tables.delete</code></li>
<li><code dir="ltr" translate="no">biglake.  tables.  deletePartitions</code></li>
<li><code dir="ltr" translate="no">biglake.tables.get</code></li>
<li><code dir="ltr" translate="no">biglake.tables.getData</code></li>
<li><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.tables.list</code></li>
<li><code dir="ltr" translate="no">biglake.tables.listPartitions</code></li>
<li><code dir="ltr" translate="no">biglake.tables.lock</code></li>
<li><code dir="ltr" translate="no">biglake.tables.setIamPolicy</code></li>
<li><code dir="ltr" translate="no">biglake.tables.update</code></li>
<li><code dir="ltr" translate="no">biglake.tables.updateData</code></li>
<li><code dir="ltr" translate="no">biglake.  tables.  updatePartitions</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.editor" class="role-title add-link" data-text="BigLake Editor Beta" tabindex="-1">BigLake Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p>Provides read and write access to all BigLake resources.</p></td>
<td><p><code dir="ltr" translate="no">biglake.catalogs.create</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.delete</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.get</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.list</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.create</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.delete</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.get</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.list</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.update</code></p>
<p><code dir="ltr" translate="no">biglake.tables.create</code></p>
<p><code dir="ltr" translate="no">biglake.  tables.  createPartitions</code></p>
<p><code dir="ltr" translate="no">biglake.tables.delete</code></p>
<p><code dir="ltr" translate="no">biglake.  tables.  deletePartitions</code></p>
<p><code dir="ltr" translate="no">biglake.tables.get</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getData</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.listPartitions</code></p>
<p><code dir="ltr" translate="no">biglake.tables.update</code></p>
<p><code dir="ltr" translate="no">biglake.tables.updateData</code></p>
<p><code dir="ltr" translate="no">biglake.  tables.  updatePartitions</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.viewer" class="role-title add-link" data-text="BigLake Viewer" tabindex="-1">BigLake Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p>Provides read-only access to all BigLake resources.</p></td>
<td><p><code dir="ltr" translate="no">biglake.catalogs.get</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.list</code></p>
<p><code dir="ltr" translate="no">biglake.databases.get</code></p>
<p><code dir="ltr" translate="no">biglake.databases.list</code></p>
<p><code dir="ltr" translate="no">biglake.locks.list</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.get</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.get</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getData</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.listPartitions</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.metadataViewer" class="role-title add-link" data-text="BigLake Metadata Viewer Beta" tabindex="-1">BigLake Metadata Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p>Provides read-only metadata access to all BigLake resources.</p></td>
<td><p><code dir="ltr" translate="no">biglake.catalogs.get</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.catalogs.list</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.get</code></p>
<p><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.namespaces.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.get</code></p>
<p><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">biglake.tables.list</code></p>
<p><code dir="ltr" translate="no">biglake.tables.listPartitions</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## BigLake permissions

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
<td><h4 id="biglake.catalogs.create" class="permission-name add-link" data-text="biglake.catalogs.create" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.catalogs.delete" class="permission-name add-link" data-text="biglake.catalogs.delete" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.catalogs.get" class="permission-name add-link" data-text="biglake.catalogs.get" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="biglake.catalogs.getIamPolicy" class="permission-name add-link" data-text="biglake.catalogs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.catalogs.list" class="permission-name add-link" data-text="biglake.catalogs.list" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.catalogs.setIamPolicy" class="permission-name add-link" data-text="biglake.catalogs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.catalogs.update" class="permission-name add-link" data-text="biglake.catalogs.update" tabindex="-1"><code dir="ltr" translate="no">biglake.catalogs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.databases.create" class="permission-name add-link" data-text="biglake.databases.create" tabindex="-1"><code dir="ltr" translate="no">biglake.databases.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.databases.delete" class="permission-name add-link" data-text="biglake.databases.delete" tabindex="-1"><code dir="ltr" translate="no">biglake.databases.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.databases.get" class="permission-name add-link" data-text="biglake.databases.get" tabindex="-1"><code dir="ltr" translate="no">biglake.databases.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.databases.list" class="permission-name add-link" data-text="biglake.databases.list" tabindex="-1"><code dir="ltr" translate="no">biglake.databases.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.databases.update" class="permission-name add-link" data-text="biglake.databases.update" tabindex="-1"><code dir="ltr" translate="no">biglake.databases.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.locks.check" class="permission-name add-link" data-text="biglake.locks.check" tabindex="-1"><code dir="ltr" translate="no">biglake.locks.check</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.locks.create" class="permission-name add-link" data-text="biglake.locks.create" tabindex="-1"><code dir="ltr" translate="no">biglake.locks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.locks.delete" class="permission-name add-link" data-text="biglake.locks.delete" tabindex="-1"><code dir="ltr" translate="no">biglake.locks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.locks.list" class="permission-name add-link" data-text="biglake.locks.list" tabindex="-1"><code dir="ltr" translate="no">biglake.locks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.namespaces.create" class="permission-name add-link" data-text="biglake.namespaces.create" tabindex="-1"><code dir="ltr" translate="no">biglake.namespaces.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.namespaces.delete" class="permission-name add-link" data-text="biglake.namespaces.delete" tabindex="-1"><code dir="ltr" translate="no">biglake.namespaces.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.namespaces.get" class="permission-name add-link" data-text="biglake.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">biglake.namespaces.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="biglake.namespaces.getIamPolicy" class="permission-name add-link" data-text="biglake.namespaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.  namespaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.namespaces.list" class="permission-name add-link" data-text="biglake.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">biglake.namespaces.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.namespaces.setIamPolicy" class="permission-name add-link" data-text="biglake.namespaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.  namespaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.namespaces.update" class="permission-name add-link" data-text="biglake.namespaces.update" tabindex="-1"><code dir="ltr" translate="no">biglake.namespaces.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.create" class="permission-name add-link" data-text="biglake.tables.create" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.createPartitions" class="permission-name add-link" data-text="biglake.tables.createPartitions" tabindex="-1"><code dir="ltr" translate="no">biglake.  tables.  createPartitions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.delete" class="permission-name add-link" data-text="biglake.tables.delete" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.deletePartitions" class="permission-name add-link" data-text="biglake.tables.deletePartitions" tabindex="-1"><code dir="ltr" translate="no">biglake.  tables.  deletePartitions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.get" class="permission-name add-link" data-text="biglake.tables.get" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.getData" class="permission-name add-link" data-text="biglake.tables.getData" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.getData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.getIamPolicy" class="permission-name add-link" data-text="biglake.tables.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.list" class="permission-name add-link" data-text="biglake.tables.list" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataplex#dataplex.serviceAgent">Cloud Dataplex Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataplex.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.listPartitions" class="permission-name add-link" data-text="biglake.tables.listPartitions" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.listPartitions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.viewer">BigLake Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.metadataViewer">BigLake Metadata Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.metadataViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.lock" class="permission-name add-link" data-text="biglake.tables.lock" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.lock</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.setIamPolicy" class="permission-name add-link" data-text="biglake.tables.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.update" class="permission-name add-link" data-text="biglake.tables.update" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="biglake.tables.updateData" class="permission-name add-link" data-text="biglake.tables.updateData" tabindex="-1"><code dir="ltr" translate="no">biglake.tables.updateData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="biglake.tables.updatePartitions" class="permission-name add-link" data-text="biglake.tables.updatePartitions" tabindex="-1"><code dir="ltr" translate="no">biglake.  tables.  updatePartitions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.admin">BigLake Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/biglake#biglake.editor">BigLake Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  biglake.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.databasesAdmin">Databases Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.databasesAdmin</code> )</p></td>
</tr>
</tbody>
</table>
