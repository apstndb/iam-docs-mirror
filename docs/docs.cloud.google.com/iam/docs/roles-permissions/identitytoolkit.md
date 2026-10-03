---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit
title: Identity Toolkit roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Identity Toolkit. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Identity Toolkit roles

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
<td>Identity Toolkit Admin
<p>( <code>roles/ identitytoolkit.admin</code> )</p>
<p>Full access to Identity Toolkit resources.</p></td>
<td><p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>identitytoolkit.*</code></p>
<ul>
<li><code>identitytoolkit.tenants.create</code></li>
<li><code>identitytoolkit.tenants.delete</code></li>
<li><code>identitytoolkit.tenants.get</code></li>
<li><code>identitytoolkit. tenants. getIamPolicy</code></li>
<li><code>identitytoolkit.tenants.list</code></li>
<li><code>identitytoolkit. tenants. setIamPolicy</code></li>
<li><code>identitytoolkit.tenants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Identity Toolkit editor
<p>( <code>roles/ identitytoolkit.editor</code> )</p>
<p>Write access to Identity Toolkit resources.</p></td>
<td><p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebaseauth.*</code></p>
<ul>
<li><code>firebaseauth.configs.create</code></li>
<li><code>firebaseauth.configs.get</code></li>
<li><code>firebaseauth. configs. getHashConfig</code></li>
<li><code>firebaseauth.configs.getSecret</code></li>
<li><code>firebaseauth.configs.update</code></li>
<li><code>firebaseauth.users.create</code></li>
<li><code>firebaseauth. users. createSession</code></li>
<li><code>firebaseauth.users.delete</code></li>
<li><code>firebaseauth.users.get</code></li>
<li><code>firebaseauth.users.sendEmail</code></li>
<li><code>firebaseauth.users.update</code></li>
</ul>
<p><code>identitytoolkit.tenants.create</code></p>
<p><code>identitytoolkit.tenants.delete</code></p>
<p><code>identitytoolkit.tenants.get</code></p>
<p><code>identitytoolkit. tenants. getIamPolicy</code></p>
<p><code>identitytoolkit.tenants.list</code></p>
<p><code>identitytoolkit.tenants.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Identity Toolkit Viewer
<p>( <code>roles/ identitytoolkit.viewer</code> )</p>
<p>Read access to Identity Toolkit resources.</p></td>
<td><p><code>firebaseauth.configs.get</code></p>
<p><code>firebaseauth.users.get</code></p>
<p><code>identitytoolkit.tenants.get</code></p>
<p><code>identitytoolkit. tenants. getIamPolicy</code></p>
<p><code>identitytoolkit.tenants.list</code></p></td>
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
<td>Identity Platform Service Agent
<p>( <code>roles/ identitytoolkit.serviceAgent</code> )</p>
<p>Gives Identity Platform service account access to customer project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudfunctions. functions. invoke</code></p>
<p><code>recaptchaenterprise. assessments. create</code></p>
<p><code>recaptchaenterprise. keys. create</code></p>
<p><code>recaptchaenterprise. keys. delete</code></p>
<p><code>recaptchaenterprise.keys.get</code></p></td>
</tr>
</tbody>
</table>

## Identity Toolkit permissions

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
<td><code>identitytoolkit.tenants.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>identitytoolkit.tenants.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>identitytoolkit.tenants.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code>roles/ identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code>roles/ identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>identitytoolkit. tenants. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code>roles/ identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code>roles/ identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>identitytoolkit.tenants.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code>roles/ identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code>roles/ identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>identitytoolkit. tenants. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>identitytoolkit.tenants.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code>roles/ identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code>roles/ identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code>roles/ identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
