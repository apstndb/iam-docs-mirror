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
<td>OAuth Config Editor <sup>Beta</sup>
<p>( <code>roles/ oauthconfig.editor</code> )</p>
<p>Read/write access to OAuth config resources</p></td>
<td><p><code>clientauthconfig.*</code></p>
<ul>
<li><code>clientauthconfig.brands.create</code></li>
<li><code>clientauthconfig.brands.delete</code></li>
<li><code>clientauthconfig.brands.get</code></li>
<li><code>clientauthconfig.brands.list</code></li>
<li><code>clientauthconfig.brands.update</code></li>
<li><code>clientauthconfig. clients. create</code></li>
<li><code>clientauthconfig. clients. createSecret</code></li>
<li><code>clientauthconfig. clients. delete</code></li>
<li><code>clientauthconfig.clients.get</code></li>
<li><code>clientauthconfig. clients. getWithSecret</code></li>
<li><code>clientauthconfig.clients.list</code></li>
<li><code>clientauthconfig. clients. listWithSecrets</code></li>
<li><code>clientauthconfig. clients. undelete</code></li>
<li><code>clientauthconfig. clients. update</code></li>
</ul>
<p><code>firebase.clients.create</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.clients.update</code></p>
<p><code>firebaseappcheck. resourcePolicies.*</code></p>
<ul>
<li><code>firebaseappcheck. resourcePolicies. get</code></li>
<li><code>firebaseappcheck. resourcePolicies. update</code></li>
</ul>
<p><code>oauthconfig.*</code></p>
<ul>
<li><code>oauthconfig.clientpolicy.get</code></li>
<li><code>oauthconfig.testusers.get</code></li>
<li><code>oauthconfig.testusers.update</code></li>
<li><code>oauthconfig.verification.get</code></li>
<li><code>oauthconfig. verification. submit</code></li>
<li><code>oauthconfig. verification. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>OAuth Config Viewer <sup>Beta</sup>
<p>( <code>roles/ oauthconfig.viewer</code> )</p>
<p>Read-only access to OAuth config resources</p></td>
<td><p><code>clientauthconfig.brands.get</code></p>
<p><code>clientauthconfig.brands.list</code></p>
<p><code>clientauthconfig.clients.get</code></p>
<p><code>clientauthconfig.clients.list</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebaseappcheck. resourcePolicies. get</code></p>
<p><code>oauthconfig.clientpolicy.get</code></p>
<p><code>oauthconfig.testusers.get</code></p>
<p><code>oauthconfig.verification.get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## OAuthConfig permissions

| Permission                          | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
|-------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `oauthconfig.clientpolicy.get`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` ) [OAuth Config Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer) ( `roles/ oauthconfig.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `oauthconfig.testusers.get`         | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` ) [OAuth Config Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer) ( `roles/ oauthconfig.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `oauthconfig.testusers.update`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `oauthconfig.verification.get`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Firebase Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin) ( `roles/ firebase.admin` ) [Firebase Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor) ( `roles/ firebase.editor` ) [Firebase Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer) ( `roles/ firebase.viewer` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` ) [OAuth Config Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.viewer) ( `roles/ oauthconfig.viewer` ) [Workspace Marketplace App Configuration Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/workspacemarketplace#appmetadata.workspaceMarketplaceAppConfigurationAdmin) ( `roles/ appmetadata.workspaceMarketplaceAppConfigurationAdmin` ) [Firebase Develop Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin) ( `roles/ firebase.developAdmin` ) [Firebase Develop Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer) ( `roles/ firebase.developViewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `oauthconfig. verification. submit` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `oauthconfig. verification. update` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [OAuth Config Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/oauthconfig#oauthconfig.editor) ( `roles/ oauthconfig.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
