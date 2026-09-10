---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/licensemanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager
title: Cloud License Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud License Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud License Manager roles

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
<td><h4 id="licensemanager.admin" class="role-title add-link" data-text="Cloud License Manager Admin" tabindex="-1">Cloud License Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p>Full access to Cloud License Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">licensemanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  aggregateUsage</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  create</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  delete</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  get</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  list</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  queryLicenseUsage</code></li>
<li><code dir="ltr" translate="no">licensemanager.  configurations.  update</code></li>
<li><code dir="ltr" translate="no">licensemanager.instances.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.instances.list</code></li>
<li><code dir="ltr" translate="no">licensemanager.locations.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.locations.list</code></li>
<li><code dir="ltr" translate="no">licensemanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">licensemanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">licensemanager.operations.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.operations.list</code></li>
<li><code dir="ltr" translate="no">licensemanager.products.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.products.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.viewer" class="role-title add-link" data-text="Cloud License Manager Viewer" tabindex="-1">Cloud License Manager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p>Readonly access to Cloud License Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">licensemanager.  configurations.  get</code></p>
<p><code dir="ltr" translate="no">licensemanager.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">licensemanager.instances.*</code></p>
<ul>
<li><code dir="ltr" translate="no">licensemanager.instances.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.instances.list</code></li>
</ul>
<p><code dir="ltr" translate="no">licensemanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">licensemanager.locations.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">licensemanager.operations.get</code></p>
<p><code dir="ltr" translate="no">licensemanager.operations.list</code></p>
<p><code dir="ltr" translate="no">licensemanager.products.*</code></p>
<ul>
<li><code dir="ltr" translate="no">licensemanager.products.get</code></li>
<li><code dir="ltr" translate="no">licensemanager.products.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud License Manager permissions

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
<td><h4 id="licensemanager.configurations.aggregateUsage" class="permission-name add-link" data-text="licensemanager.configurations.aggregateUsage" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  aggregateUsage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.configurations.create" class="permission-name add-link" data-text="licensemanager.configurations.create" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.configurations.delete" class="permission-name add-link" data-text="licensemanager.configurations.delete" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.configurations.get" class="permission-name add-link" data-text="licensemanager.configurations.get" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.configurations.list" class="permission-name add-link" data-text="licensemanager.configurations.list" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.configurations.queryLicenseUsage" class="permission-name add-link" data-text="licensemanager.configurations.queryLicenseUsage" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  queryLicenseUsage</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.configurations.update" class="permission-name add-link" data-text="licensemanager.configurations.update" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  configurations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.instances.get" class="permission-name add-link" data-text="licensemanager.instances.get" tabindex="-1"><code dir="ltr" translate="no">licensemanager.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.instances.list" class="permission-name add-link" data-text="licensemanager.instances.list" tabindex="-1"><code dir="ltr" translate="no">licensemanager.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.locations.get" class="permission-name add-link" data-text="licensemanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">licensemanager.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.locations.list" class="permission-name add-link" data-text="licensemanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">licensemanager.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.operations.cancel" class="permission-name add-link" data-text="licensemanager.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.operations.delete" class="permission-name add-link" data-text="licensemanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">licensemanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.operations.get" class="permission-name add-link" data-text="licensemanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">licensemanager.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.operations.list" class="permission-name add-link" data-text="licensemanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">licensemanager.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="licensemanager.products.get" class="permission-name add-link" data-text="licensemanager.products.get" tabindex="-1"><code dir="ltr" translate="no">licensemanager.products.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="licensemanager.products.list" class="permission-name add-link" data-text="licensemanager.products.list" tabindex="-1"><code dir="ltr" translate="no">licensemanager.products.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.admin">Cloud License Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/licensemanager#licensemanager.viewer">Cloud License Manager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  licensemanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
