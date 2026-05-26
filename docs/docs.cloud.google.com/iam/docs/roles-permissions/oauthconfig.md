---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig
title: OAuthConfig roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for OAuthConfig. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## OAuthConfig roles

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
<td><h4 id="oauthconfig.editor" class="role-title add-link" data-text="OAuth Config Editor Beta" tabindex="-1">OAuth Config Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p>Read/write access to OAuth config resources</p></td>
<td><p><code dir="ltr" translate="no">clientauthconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">clientauthconfig.brands.create</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.brands.delete</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.brands.get</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.brands.list</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.brands.update</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  create</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  createSecret</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  delete</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.clients.get</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  getWithSecret</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.clients.list</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  listWithSecrets</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  undelete</code></li>
<li><code dir="ltr" translate="no">clientauthconfig.  clients.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.clients.create</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.update</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></li>
<li><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">oauthconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">oauthconfig.clientpolicy.get</code></li>
<li><code dir="ltr" translate="no">oauthconfig.testusers.get</code></li>
<li><code dir="ltr" translate="no">oauthconfig.testusers.update</code></li>
<li><code dir="ltr" translate="no">oauthconfig.verification.get</code></li>
<li><code dir="ltr" translate="no">oauthconfig.  verification.  submit</code></li>
<li><code dir="ltr" translate="no">oauthconfig.  verification.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="oauthconfig.viewer" class="role-title add-link" data-text="OAuth Config Viewer Beta" tabindex="-1">OAuth Config Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p>Read-only access to OAuth config resources</p></td>
<td><p><code dir="ltr" translate="no">clientauthconfig.brands.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.brands.list</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.get</code></p>
<p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebaseappcheck.  resourcePolicies.  get</code></p>
<p><code dir="ltr" translate="no">oauthconfig.clientpolicy.get</code></p>
<p><code dir="ltr" translate="no">oauthconfig.testusers.get</code></p>
<p><code dir="ltr" translate="no">oauthconfig.verification.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## OAuthConfig permissions

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
<td><h4 id="oauthconfig.clientpolicy.get" class="permission-name add-link" data-text="oauthconfig.clientpolicy.get" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.clientpolicy.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oauthconfig.testusers.get" class="permission-name add-link" data-text="oauthconfig.testusers.get" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.testusers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oauthconfig.testusers.update" class="permission-name add-link" data-text="oauthconfig.testusers.update" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.testusers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oauthconfig.verification.get" class="permission-name add-link" data-text="oauthconfig.verification.get" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.verification.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer">OAuth Config Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin">Workspace Marketplace App Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  appmetadata.workspaceMarketplaceAppConfigurationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="oauthconfig.verification.submit" class="permission-name add-link" data-text="oauthconfig.verification.submit" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.  verification.  submit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="oauthconfig.verification.update" class="permission-name add-link" data-text="oauthconfig.verification.update" tabindex="-1"><code dir="ltr" translate="no">oauthconfig.  verification.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor">OAuth Config Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  oauthconfig.editor</code> )</p></td>
</tr>
</tbody>
</table>
