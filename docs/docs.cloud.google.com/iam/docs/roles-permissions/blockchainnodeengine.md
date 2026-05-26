---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine
title: Blockchain Node Engine roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Blockchain Node Engine. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Blockchain Node Engine roles

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
<td><h4 id="blockchainnodeengine.admin" class="role-title add-link" data-text="Blockchain Node Engine Admin" tabindex="-1">Blockchain Node Engine Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p>Full access to Blockchain Node Engine resources.</p></td>
<td><p><code dir="ltr" translate="no">blockchainnodeengine.*</code></p>
<ul>
<li><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  create</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  delete</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  get</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  list</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  update</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  locations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  locations.  list</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  operations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.viewer" class="role-title add-link" data-text="Blockchain Node Engine Viewer" tabindex="-1">Blockchain Node Engine Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p>Read-only access to Blockchain Node Engine resources.</p></td>
<td><p><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  get</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  list</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">blockchainnodeengine.  locations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainnodeengine.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">blockchainnodeengine.  operations.  get</code></p>
<p><code dir="ltr" translate="no">blockchainnodeengine.  operations.  list</code></p>
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
<td><h4 id="blockchainnodeengine.serviceAgent" class="role-title add-link" data-text="Blockchain Node Engine Service Agent" tabindex="-1">Blockchain Node Engine Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  blockchainnodeengine.serviceAgent</code> )</p>
<p>Grants Blockchain Node Engine access to metrics in user project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">monitoring.timeSeries.list</code></p></td>
</tr>
</tbody>
</table>

## Blockchain Node Engine permissions

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
<td><h4 id="blockchainnodeengine.blockchainNodes.create" class="permission-name add-link" data-text="blockchainnodeengine.blockchainNodes.create" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.blockchainNodes.delete" class="permission-name add-link" data-text="blockchainnodeengine.blockchainNodes.delete" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainnodeengine.blockchainNodes.get" class="permission-name add-link" data-text="blockchainnodeengine.blockchainNodes.get" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.blockchainNodes.list" class="permission-name add-link" data-text="blockchainnodeengine.blockchainNodes.list" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainnodeengine.blockchainNodes.update" class="permission-name add-link" data-text="blockchainnodeengine.blockchainNodes.update" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  blockchainNodes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.locations.get" class="permission-name add-link" data-text="blockchainnodeengine.locations.get" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainnodeengine.locations.list" class="permission-name add-link" data-text="blockchainnodeengine.locations.list" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.operations.cancel" class="permission-name add-link" data-text="blockchainnodeengine.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainnodeengine.operations.delete" class="permission-name add-link" data-text="blockchainnodeengine.operations.delete" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainnodeengine.operations.get" class="permission-name add-link" data-text="blockchainnodeengine.operations.get" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainnodeengine.operations.list" class="permission-name add-link" data-text="blockchainnodeengine.operations.list" tabindex="-1"><code dir="ltr" translate="no">blockchainnodeengine.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.admin">Blockchain Node Engine Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainnodeengine#blockchainnodeengine.viewer">Blockchain Node Engine Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainnodeengine.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
