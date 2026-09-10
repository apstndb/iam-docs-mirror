---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons
title: Google Workspace add-ons roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Workspace add-ons. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Workspace add-ons roles

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
<td><h4 id="gsuiteaddons.admin" class="role-title add-link" data-text="Google Workspace Add-ons Admin" tabindex="-1">Google Workspace Add-ons Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p>Admin role for Google Workspace Add-ons</p></td>
<td><p><code dir="ltr" translate="no">gsuiteaddons.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gsuiteaddons.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  execute</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.deployments.get</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  install</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  installStatus</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  uninstall</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.viewer" class="role-title add-link" data-text="Google Workspace Add-ons Viewer" tabindex="-1">Google Workspace Add-ons Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p>Viewer role for Google Workspace Add-ons</p></td>
<td><p><code dir="ltr" translate="no">gsuiteaddons.  authorizations.  get</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.get</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.developer" class="role-title add-link" data-text="Google Workspace Add-ons Developer" tabindex="-1">Google Workspace Add-ons Developer</h4>
<p>( <code dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p>Full access to Google Workspace Add-ons resources</p></td>
<td><p><code dir="ltr" translate="no">gsuiteaddons.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gsuiteaddons.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  execute</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.deployments.get</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  install</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  installStatus</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  uninstall</code></li>
<li><code dir="ltr" translate="no">gsuiteaddons.  deployments.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.reader" class="role-title add-link" data-text="Google Workspace Add-ons Reader" tabindex="-1">Google Workspace Add-ons Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p>Read-only access to Google Workspace Add-ons resources</p></td>
<td><p><code dir="ltr" translate="no">gsuiteaddons.  authorizations.  get</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.get</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.tester" class="role-title add-link" data-text="Google Workspace Add-ons Tester" tabindex="-1">Google Workspace Add-ons Tester</h4>
<p>( <code dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p>
<p>Testing execution access to Google Workspace Add-ons resources</p></td>
<td><p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  execute</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  install</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  installStatus</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  uninstall</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Google Workspace add-ons permissions

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
<td><h4 id="gsuiteaddons.authorizations.get" class="permission-name add-link" data-text="gsuiteaddons.authorizations.get" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  authorizations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.deployments.create" class="permission-name add-link" data-text="gsuiteaddons.deployments.create" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.deployments.delete" class="permission-name add-link" data-text="gsuiteaddons.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.deployments.execute" class="permission-name add-link" data-text="gsuiteaddons.deployments.execute" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  execute</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.deployments.get" class="permission-name add-link" data-text="gsuiteaddons.deployments.get" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.deployments.install" class="permission-name add-link" data-text="gsuiteaddons.deployments.install" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  install</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.deployments.installStatus" class="permission-name add-link" data-text="gsuiteaddons.deployments.installStatus" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  installStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.deployments.list" class="permission-name add-link" data-text="gsuiteaddons.deployments.list" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.viewer">Google Workspace Add-ons Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.reader">Google Workspace Add-ons Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="gsuiteaddons.deployments.uninstall" class="permission-name add-link" data-text="gsuiteaddons.deployments.uninstall" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  uninstall</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.tester">Google Workspace Add-ons Tester</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.tester</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="gsuiteaddons.deployments.update" class="permission-name add-link" data-text="gsuiteaddons.deployments.update" tabindex="-1"><code dir="ltr" translate="no">gsuiteaddons.  deployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.admin">Google Workspace Add-ons Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/gsuiteaddons#gsuiteaddons.developer">Google Workspace Add-ons Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  gsuiteaddons.developer</code> )</p></td>
</tr>
</tbody>
</table>
