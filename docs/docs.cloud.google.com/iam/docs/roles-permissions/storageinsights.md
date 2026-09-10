---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/storageinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights
title: Storage Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Storage Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Storage Insights roles

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
<td><h4 id="storageinsights.admin" class="role-title add-link" data-text="Storage Insights Admin" tabindex="-1">Storage Insights Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p>Full access to Storage Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storageinsights.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  create</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  linkDataset</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  unlinkDataset</code></li>
<li><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  update</code></li>
<li><code dir="ltr" translate="no">storageinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">storageinsights.locations.list</code></li>
<li><code dir="ltr" translate="no">storageinsights.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">storageinsights.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">storageinsights.operations.get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  operations.  list</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportConfigs.  create</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportConfigs.  get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportConfigs.  update</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.viewer" class="role-title add-link" data-text="Storage Insights Viewer" tabindex="-1">Storage Insights Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p>Read-only access to Storage Insights resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storageinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">storageinsights.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storageinsights.operations.get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.analyst" class="role-title add-link" data-text="Storage Insights Analyst" tabindex="-1">Storage Insights Analyst</h4>
<p>( <code dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p>
<p>Data access to Storage Insights.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  linkDataset</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  unlinkDataset</code></p>
<p><code dir="ltr" translate="no">storageinsights.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storageinsights.locations.get</code></li>
<li><code dir="ltr" translate="no">storageinsights.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">storageinsights.operations.get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  operations.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  get</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportDetails.*</code></p>
<ul>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  get</code></li>
<li><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></li>
</ul></td>
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
<td><h4 id="storageinsights.serviceAgent" class="role-title add-link" data-text="StorageInsights Service Agent" tabindex="-1">StorageInsights Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  storageinsights.serviceAgent</code> )</p>
<p>Permissions for Insights to write reports into customer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.datasets.create</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></p></td>
</tr>
</tbody>
</table>

## Storage Insights permissions

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
<td><h4 id="storageinsights.datasetConfigs.create" class="permission-name add-link" data-text="storageinsights.datasetConfigs.create" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.datasetConfigs.delete" class="permission-name add-link" data-text="storageinsights.datasetConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.datasetConfigs.get" class="permission-name add-link" data-text="storageinsights.datasetConfigs.get" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.datasetConfigs.linkDataset" class="permission-name add-link" data-text="storageinsights.datasetConfigs.linkDataset" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  linkDataset</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.datasetConfigs.list" class="permission-name add-link" data-text="storageinsights.datasetConfigs.list" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.datasetConfigs.unlinkDataset" class="permission-name add-link" data-text="storageinsights.datasetConfigs.unlinkDataset" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  unlinkDataset</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.datasetConfigs.update" class="permission-name add-link" data-text="storageinsights.datasetConfigs.update" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  datasetConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.locations.get" class="permission-name add-link" data-text="storageinsights.locations.get" tabindex="-1"><code dir="ltr" translate="no">storageinsights.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.locations.list" class="permission-name add-link" data-text="storageinsights.locations.list" tabindex="-1"><code dir="ltr" translate="no">storageinsights.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.operations.cancel" class="permission-name add-link" data-text="storageinsights.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.operations.delete" class="permission-name add-link" data-text="storageinsights.operations.delete" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.operations.get" class="permission-name add-link" data-text="storageinsights.operations.get" tabindex="-1"><code dir="ltr" translate="no">storageinsights.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.operations.list" class="permission-name add-link" data-text="storageinsights.operations.list" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.reportConfigs.create" class="permission-name add-link" data-text="storageinsights.reportConfigs.create" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.reportConfigs.delete" class="permission-name add-link" data-text="storageinsights.reportConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.reportConfigs.get" class="permission-name add-link" data-text="storageinsights.reportConfigs.get" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.reportConfigs.list" class="permission-name add-link" data-text="storageinsights.reportConfigs.list" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.reportConfigs.update" class="permission-name add-link" data-text="storageinsights.reportConfigs.update" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="storageinsights.reportDetails.get" class="permission-name add-link" data-text="storageinsights.reportDetails.get" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportDetails.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="storageinsights.reportDetails.list" class="permission-name add-link" data-text="storageinsights.reportDetails.list" tabindex="-1"><code dir="ltr" translate="no">storageinsights.  reportDetails.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.admin">Storage Insights Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.viewer">Storage Insights Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.analyst">Storage Insights Analyst</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.analyst</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/storageinsights#storageinsights.serviceAgent">StorageInsights Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  storageinsights.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
