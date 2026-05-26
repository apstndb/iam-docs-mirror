---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing
title: Customer Usage Data Processing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Customer Usage Data Processing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Customer Usage Data Processing roles

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
<td><h4 id="dataprocessing.admin" class="role-title add-link" data-text="Data Processing Controls Resource Admin" tabindex="-1">Data Processing Controls Resource Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p>Data processing controls admin who can fully manage data processing controls settings and view all datasource data.</p></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">billing.accounts.list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataprocessing.datasources.get</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  datasources.  update</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  update</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.editor" class="role-title add-link" data-text="Dataprocessing Editor" tabindex="-1">Dataprocessing Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p>Editor role for dataprocessing</p></td>
<td><p><code dir="ltr" translate="no">dataprocessing.datasources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataprocessing.datasources.get</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></li>
<li><code dir="ltr" translate="no">dataprocessing.  datasources.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataprocessing.viewer" class="role-title add-link" data-text="Dataprocessing Viewer" tabindex="-1">Dataprocessing Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p>Viewer role for dataprocessing</p></td>
<td><p><code dir="ltr" translate="no">dataprocessing.datasources.get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.dataSourceManager" class="role-title add-link" data-text="Data Processing Controls Data Source Manager" tabindex="-1">Data Processing Controls Data Source Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  dataprocessing.dataSourceManager</code> )</p>
<p>Data processing controls data source manager who can get, list, and update the underlying data.</p></td>
<td><p><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></p>
<p><code dir="ltr" translate="no">dataprocessing.  datasources.  update</code></p></td>
</tr>
</tbody>
</table>

## Customer Usage Data Processing permissions

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
<td><h4 id="dataprocessing.datasources.get" class="permission-name add-link" data-text="dataprocessing.datasources.get" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.datasources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.datasources.list" class="permission-name add-link" data-text="dataprocessing.datasources.list" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  datasources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.dataSourceManager">Data Processing Controls Data Source Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.dataSourceManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataprocessing.datasources.update" class="permission-name add-link" data-text="dataprocessing.datasources.update" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  datasources.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.dataSourceManager">Data Processing Controls Data Source Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.dataSourceManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.featurecontrols.list" class="permission-name add-link" data-text="dataprocessing.featurecontrols.list" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataprocessing.featurecontrols.update" class="permission-name add-link" data-text="dataprocessing.featurecontrols.update" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  featurecontrols.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.groupcontrols.get" class="permission-name add-link" data-text="dataprocessing.groupcontrols.get" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataprocessing.groupcontrols.list" class="permission-name add-link" data-text="dataprocessing.groupcontrols.list" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.admin">Billing Account Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.viewer">Billing Account Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.editor">Dataprocessing Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.viewer">Dataprocessing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/billing#billing.linkAdmin">Account Hierarchy Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  billing.linkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataprocessing.groupcontrols.update" class="permission-name add-link" data-text="dataprocessing.groupcontrols.update" tabindex="-1"><code dir="ltr" translate="no">dataprocessing.  groupcontrols.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataprocessing#dataprocessing.admin">Data Processing Controls Resource Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataprocessing.admin</code> )</p></td>
</tr>
</tbody>
</table>
