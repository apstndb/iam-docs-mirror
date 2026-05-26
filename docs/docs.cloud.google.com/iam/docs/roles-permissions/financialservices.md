---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/financialservices
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices
title: Financial Services roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Financial Services. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Financial Services roles

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
<td><h4 id="financialservices.admin" class="role-title add-link" data-text="Financial Services Admin" tabindex="-1">Financial Services Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p>Full access to all Financial Services API resources.</p></td>
<td><p><code dir="ltr" translate="no">financialservices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">financialservices.  locations.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  locations.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">financialservices.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  operations.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  operations.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  exportMetadata</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1backtests.  update</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1datasets.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1datasets.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1datasets.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1datasets.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1datasets.  update</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  exportMetadata</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  update</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineversions.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineversions.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  exportRegisteredParties</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  importRegisteredParties</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1instances.  update</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  copyFrom</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  copyTo</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  exportMetadata</code></li>
<li><code dir="ltr" translate="no">financialservices.v1models.get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1models.  update</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  create</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  delete</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  exportMetadata</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  list</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1predictions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.viewer" class="role-title add-link" data-text="Financial Services Viewer" tabindex="-1">Financial Services Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p>View access to all Financial Services API resources.</p></td>
<td><p><code dir="ltr" translate="no">financialservices.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">financialservices.  locations.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">financialservices.  operations.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  operations.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1backtests.  exportMetadata</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1backtests.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1backtests.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1datasets.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1datasets.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  exportMetadata</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1engineversions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">financialservices.  v1engineversions.  get</code></li>
<li><code dir="ltr" translate="no">financialservices.  v1engineversions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">financialservices.  v1instances.  exportRegisteredParties</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1instances.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1instances.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1models.  copyFrom</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1models.  exportMetadata</code></p>
<p><code dir="ltr" translate="no">financialservices.v1models.get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1models.  list</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1predictions.  exportMetadata</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1predictions.  get</code></p>
<p><code dir="ltr" translate="no">financialservices.  v1predictions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Financial Services permissions

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
<td><h4 id="financialservices.locations.get" class="permission-name add-link" data-text="financialservices.locations.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.locations.list" class="permission-name add-link" data-text="financialservices.locations.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.operations.cancel" class="permission-name add-link" data-text="financialservices.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">financialservices.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.operations.delete" class="permission-name add-link" data-text="financialservices.operations.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.operations.get" class="permission-name add-link" data-text="financialservices.operations.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.operations.list" class="permission-name add-link" data-text="financialservices.operations.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1backtests.create" class="permission-name add-link" data-text="financialservices.v1backtests.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1backtests.delete" class="permission-name add-link" data-text="financialservices.v1backtests.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1backtests.exportMetadata" class="permission-name add-link" data-text="financialservices.v1backtests.exportMetadata" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  exportMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1backtests.get" class="permission-name add-link" data-text="financialservices.v1backtests.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1backtests.list" class="permission-name add-link" data-text="financialservices.v1backtests.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1backtests.update" class="permission-name add-link" data-text="financialservices.v1backtests.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1backtests.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1datasets.create" class="permission-name add-link" data-text="financialservices.v1datasets.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1datasets.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1datasets.delete" class="permission-name add-link" data-text="financialservices.v1datasets.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1datasets.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1datasets.get" class="permission-name add-link" data-text="financialservices.v1datasets.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1datasets.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1datasets.list" class="permission-name add-link" data-text="financialservices.v1datasets.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1datasets.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1datasets.update" class="permission-name add-link" data-text="financialservices.v1datasets.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1datasets.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1engineconfigs.create" class="permission-name add-link" data-text="financialservices.v1engineconfigs.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1engineconfigs.delete" class="permission-name add-link" data-text="financialservices.v1engineconfigs.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1engineconfigs.exportMetadata" class="permission-name add-link" data-text="financialservices.v1engineconfigs.exportMetadata" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  exportMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1engineconfigs.get" class="permission-name add-link" data-text="financialservices.v1engineconfigs.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1engineconfigs.list" class="permission-name add-link" data-text="financialservices.v1engineconfigs.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1engineconfigs.update" class="permission-name add-link" data-text="financialservices.v1engineconfigs.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineconfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1engineversions.get" class="permission-name add-link" data-text="financialservices.v1engineversions.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineversions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1engineversions.list" class="permission-name add-link" data-text="financialservices.v1engineversions.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1engineversions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1instances.create" class="permission-name add-link" data-text="financialservices.v1instances.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1instances.delete" class="permission-name add-link" data-text="financialservices.v1instances.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1instances.exportRegisteredParties" class="permission-name add-link" data-text="financialservices.v1instances.exportRegisteredParties" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  exportRegisteredParties</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1instances.get" class="permission-name add-link" data-text="financialservices.v1instances.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1instances.importRegisteredParties" class="permission-name add-link" data-text="financialservices.v1instances.importRegisteredParties" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  importRegisteredParties</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1instances.list" class="permission-name add-link" data-text="financialservices.v1instances.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1instances.update" class="permission-name add-link" data-text="financialservices.v1instances.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1instances.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1models.copyFrom" class="permission-name add-link" data-text="financialservices.v1models.copyFrom" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  copyFrom</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1models.copyTo" class="permission-name add-link" data-text="financialservices.v1models.copyTo" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  copyTo</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1models.create" class="permission-name add-link" data-text="financialservices.v1models.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1models.delete" class="permission-name add-link" data-text="financialservices.v1models.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1models.exportMetadata" class="permission-name add-link" data-text="financialservices.v1models.exportMetadata" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  exportMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1models.get" class="permission-name add-link" data-text="financialservices.v1models.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.v1models.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1models.list" class="permission-name add-link" data-text="financialservices.v1models.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1models.update" class="permission-name add-link" data-text="financialservices.v1models.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1models.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1predictions.create" class="permission-name add-link" data-text="financialservices.v1predictions.create" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1predictions.delete" class="permission-name add-link" data-text="financialservices.v1predictions.delete" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1predictions.exportMetadata" class="permission-name add-link" data-text="financialservices.v1predictions.exportMetadata" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  exportMetadata</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1predictions.get" class="permission-name add-link" data-text="financialservices.v1predictions.get" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="financialservices.v1predictions.list" class="permission-name add-link" data-text="financialservices.v1predictions.list" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.viewer">Financial Services Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="financialservices.v1predictions.update" class="permission-name add-link" data-text="financialservices.v1predictions.update" tabindex="-1"><code dir="ltr" translate="no">financialservices.  v1predictions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/financialservices#financialservices.admin">Financial Services Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  financialservices.admin</code> )</p></td>
</tr>
</tbody>
</table>
