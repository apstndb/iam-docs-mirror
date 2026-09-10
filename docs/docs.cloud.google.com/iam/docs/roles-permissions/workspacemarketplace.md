---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace
title: Google Workspace Marketplace roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Workspace Marketplace. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Workspace Marketplace roles

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
<td><h4 id="appmetadata.workspaceMarketplaceAppConfigurationAdmin" class="role-title add-link" data-text="Workspace Marketplace App Configuration Admin" tabindex="-1">Workspace Marketplace App Configuration Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p>Workspace Marketplace App Configuration Admin</p></td>
<td><p><code dir="ltr" translate="no">chat.bots.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.  clients.  create</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.deployments.list</code></p>
<p><code dir="ltr" translate="no">gsuiteaddons.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">workspacemarketplace.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workspacemarketplace.  appConfiguration.  update</code></li>
<li><code dir="ltr" translate="no">workspacemarketplace.  appConfiguration.  view</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Workspace Marketplace permissions

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
<td><h4 id="workspacemarketplace.appConfiguration.update" class="permission-name add-link" data-text="workspacemarketplace.appConfiguration.update" tabindex="-1"><code dir="ltr" translate="no">workspacemarketplace.  appConfiguration.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workspacemarketplace.appConfiguration.view" class="permission-name add-link" data-text="workspacemarketplace.appConfiguration.view" tabindex="-1"><code dir="ltr" translate="no">workspacemarketplace.  appConfiguration.  view</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
