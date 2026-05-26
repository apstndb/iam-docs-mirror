---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/looker
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/looker
title: Looker roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Looker. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Looker roles

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
<td><h4 id="looker.admin" class="role-title add-link" data-text="Looker Admin" tabindex="-1">Looker Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p>Full access to all Looker resources.</p></td>
<td><p><code dir="ltr" translate="no">looker.*</code></p>
<ul>
<li><code dir="ltr" translate="no">looker.backups.create</code></li>
<li><code dir="ltr" translate="no">looker.backups.delete</code></li>
<li><code dir="ltr" translate="no">looker.backups.get</code></li>
<li><code dir="ltr" translate="no">looker.backups.list</code></li>
<li><code dir="ltr" translate="no">looker.instances.create</code></li>
<li><code dir="ltr" translate="no">looker.instances.delete</code></li>
<li><code dir="ltr" translate="no">looker.instances.export</code></li>
<li><code dir="ltr" translate="no">looker.instances.get</code></li>
<li><code dir="ltr" translate="no">looker.instances.import</code></li>
<li><code dir="ltr" translate="no">looker.instances.list</code></li>
<li><code dir="ltr" translate="no">looker.instances.login</code></li>
<li><code dir="ltr" translate="no">looker.instances.update</code></li>
<li><code dir="ltr" translate="no">looker.locations.get</code></li>
<li><code dir="ltr" translate="no">looker.locations.list</code></li>
<li><code dir="ltr" translate="no">looker.operations.cancel</code></li>
<li><code dir="ltr" translate="no">looker.operations.delete</code></li>
<li><code dir="ltr" translate="no">looker.operations.get</code></li>
<li><code dir="ltr" translate="no">looker.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.quotas.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="looker.viewer" class="role-title add-link" data-text="Looker Viewer" tabindex="-1">Looker Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p>Read-only access to all Looker resources.</p></td>
<td><p><code dir="ltr" translate="no">looker.backups.get</code></p>
<p><code dir="ltr" translate="no">looker.backups.list</code></p>
<p><code dir="ltr" translate="no">looker.instances.get</code></p>
<p><code dir="ltr" translate="no">looker.instances.list</code></p>
<p><code dir="ltr" translate="no">looker.instances.login</code></p>
<p><code dir="ltr" translate="no">looker.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">looker.locations.get</code></li>
<li><code dir="ltr" translate="no">looker.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">looker.operations.get</code></p>
<p><code dir="ltr" translate="no">looker.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.instanceUser" class="role-title add-link" data-text="Looker Instance User" tabindex="-1">Looker Instance User</h4>
<p>( <code dir="ltr" translate="no">roles/  looker.instanceUser</code> )</p>
<p>Access to log in to a Looker instance.</p></td>
<td><p><code dir="ltr" translate="no">looker.instances.get</code></p>
<p><code dir="ltr" translate="no">looker.instances.login</code></p>
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
<td><h4 id="looker.restrictedServiceAgent" class="role-title add-link" data-text="Looker Service Agent" tabindex="-1">Looker Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  looker.restrictedServiceAgent</code> )</p>
<p>Gives the Looker service account permission to manage customer resources. Does not include permissions to access BigQuery.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">looker.backups.create</code></p>
<p><code dir="ltr" translate="no">looker.instances.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="looker.serviceAgent" class="role-title add-link" data-text="Looker Service Agent" tabindex="-1">Looker Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  looker.serviceAgent</code> )</p>
<p>Gives the Looker service account permission to manage customer resources</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">bigquery.config.get</code></p>
<p><code dir="ltr" translate="no">bigquery.datasets.get</code></p>
<p><code dir="ltr" translate="no">bigquery.jobs.create</code></p>
<p><code dir="ltr" translate="no">bigquery.models.export</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.models.getMetadata</code></p>
<p><code dir="ltr" translate="no">bigquery.models.list</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.create</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.createSnapshot</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.export</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.get</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.getData</code></p>
<p><code dir="ltr" translate="no">bigquery.tables.list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">looker.backups.create</code></p>
<p><code dir="ltr" translate="no">looker.instances.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p></td>
</tr>
</tbody>
</table>

## Looker permissions

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
<td><h4 id="looker.backups.create" class="permission-name add-link" data-text="looker.backups.create" tabindex="-1"><code dir="ltr" translate="no">looker.backups.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.restrictedServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.serviceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="looker.backups.delete" class="permission-name add-link" data-text="looker.backups.delete" tabindex="-1"><code dir="ltr" translate="no">looker.backups.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.backups.get" class="permission-name add-link" data-text="looker.backups.get" tabindex="-1"><code dir="ltr" translate="no">looker.backups.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.backups.list" class="permission-name add-link" data-text="looker.backups.list" tabindex="-1"><code dir="ltr" translate="no">looker.backups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.instances.create" class="permission-name add-link" data-text="looker.instances.create" tabindex="-1"><code dir="ltr" translate="no">looker.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.instances.delete" class="permission-name add-link" data-text="looker.instances.delete" tabindex="-1"><code dir="ltr" translate="no">looker.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.instances.export" class="permission-name add-link" data-text="looker.instances.export" tabindex="-1"><code dir="ltr" translate="no">looker.instances.export</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.instances.get" class="permission-name add-link" data-text="looker.instances.get" tabindex="-1"><code dir="ltr" translate="no">looker.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.instanceUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.restrictedServiceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.restrictedServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.serviceAgent">Looker Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="looker.instances.import" class="permission-name add-link" data-text="looker.instances.import" tabindex="-1"><code dir="ltr" translate="no">looker.instances.import</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.instances.list" class="permission-name add-link" data-text="looker.instances.list" tabindex="-1"><code dir="ltr" translate="no">looker.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.instances.login" class="permission-name add-link" data-text="looker.instances.login" tabindex="-1"><code dir="ltr" translate="no">looker.instances.login</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.instanceUser">Looker Instance User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.instanceUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.instances.update" class="permission-name add-link" data-text="looker.instances.update" tabindex="-1"><code dir="ltr" translate="no">looker.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.locations.get" class="permission-name add-link" data-text="looker.locations.get" tabindex="-1"><code dir="ltr" translate="no">looker.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.locations.list" class="permission-name add-link" data-text="looker.locations.list" tabindex="-1"><code dir="ltr" translate="no">looker.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.operations.cancel" class="permission-name add-link" data-text="looker.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">looker.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.operations.delete" class="permission-name add-link" data-text="looker.operations.delete" tabindex="-1"><code dir="ltr" translate="no">looker.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="looker.operations.get" class="permission-name add-link" data-text="looker.operations.get" tabindex="-1"><code dir="ltr" translate="no">looker.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="looker.operations.list" class="permission-name add-link" data-text="looker.operations.list" tabindex="-1"><code dir="ltr" translate="no">looker.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.admin">Looker Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/looker#looker.viewer">Looker Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  looker.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
