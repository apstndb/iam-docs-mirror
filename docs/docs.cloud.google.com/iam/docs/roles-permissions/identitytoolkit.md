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
<td><h4 id="identitytoolkit.admin" class="role-title add-link" data-text="Identity Toolkit Admin" tabindex="-1">Identity Toolkit Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p>Full access to Identity Toolkit resources.</p></td>
<td><p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">identitytoolkit.*</code></p>
<ul>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.create</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.delete</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.  tenants.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">identitytoolkit.tenants.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="identitytoolkit.editor" class="role-title add-link" data-text="Identity Toolkit editor" tabindex="-1">Identity Toolkit editor</h4>
<p>( <code dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p>Write access to Identity Toolkit resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseauth.configs.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></li>
<li><code dir="ltr" translate="no">firebaseauth.configs.update</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.create</code></li>
<li><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.delete</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.get</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></li>
<li><code dir="ltr" translate="no">firebaseauth.users.update</code></li>
</ul>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.create</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.delete</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="identitytoolkit.viewer" class="role-title add-link" data-text="Identity Toolkit Viewer" tabindex="-1">Identity Toolkit Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p>Read access to Identity Toolkit resources.</p></td>
<td><p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.get</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></p></td>
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
<td><h4 id="identitytoolkit.serviceAgent" class="role-title add-link" data-text="Identity Platform Service Agent" tabindex="-1">Identity Platform Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  identitytoolkit.serviceAgent</code> )</p>
<p>Gives Identity Platform service account access to customer project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudfunctions.  functions.  invoke</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  assessments.  create</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  create</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.  keys.  delete</code></p>
<p><code dir="ltr" translate="no">recaptchaenterprise.keys.get</code></p></td>
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
<td><h4 id="identitytoolkit.tenants.create" class="permission-name add-link" data-text="identitytoolkit.tenants.create" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.tenants.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="identitytoolkit.tenants.delete" class="permission-name add-link" data-text="identitytoolkit.tenants.delete" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.tenants.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="identitytoolkit.tenants.get" class="permission-name add-link" data-text="identitytoolkit.tenants.get" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.tenants.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="identitytoolkit.tenants.getIamPolicy" class="permission-name add-link" data-text="identitytoolkit.tenants.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.  tenants.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="identitytoolkit.tenants.list" class="permission-name add-link" data-text="identitytoolkit.tenants.list" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.tenants.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="identitytoolkit.tenants.setIamPolicy" class="permission-name add-link" data-text="identitytoolkit.tenants.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.  tenants.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="identitytoolkit.tenants.update" class="permission-name add-link" data-text="identitytoolkit.tenants.update" tabindex="-1"><code dir="ltr" translate="no">identitytoolkit.tenants.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
