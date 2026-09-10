---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth
title: Firebase Authentication roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Authentication. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Authentication roles

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
<td><h4 id="firebaseauth.admin" class="role-title add-link" data-text="Firebase Authentication Admin" tabindex="-1">Firebase Authentication Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p>Full read/write access to Firebase Authentication resources.</p></td>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseauth.editor" class="role-title add-link" data-text="Firebase Authentication editor" tabindex="-1">Firebase Authentication editor</h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p>Write access to Firebase Authentication resources.</p></td>
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
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.viewer" class="role-title add-link" data-text="Firebase Authentication Viewer" tabindex="-1">Firebase Authentication Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p>Read-only access to Firebase Authentication resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.configs.get</code></p>
<p><code dir="ltr" translate="no">firebaseauth.users.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Authentication permissions

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
<td><h4 id="firebaseauth.configs.create" class="permission-name add-link" data-text="firebaseauth.configs.create" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.configs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebaseauth.configs.get" class="permission-name add-link" data-text="firebaseauth.configs.get" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.configs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.configs.getHashConfig" class="permission-name add-link" data-text="firebaseauth.configs.getHashConfig" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.  configs.  getHashConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseauth.configs.getSecret" class="permission-name add-link" data-text="firebaseauth.configs.getSecret" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.configs.getSecret</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.configs.update" class="permission-name add-link" data-text="firebaseauth.configs.update" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.configs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebaseauth.users.create" class="permission-name add-link" data-text="firebaseauth.users.create" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.users.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.users.createSession" class="permission-name add-link" data-text="firebaseauth.users.createSession" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.  users.  createSession</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebaseauth.users.delete" class="permission-name add-link" data-text="firebaseauth.users.delete" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.users.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.users.get" class="permission-name add-link" data-text="firebaseauth.users.get" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.users.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.viewer">Firebase Authentication Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.viewer">Identity Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.viewer">Identity Toolkit Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
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
<td><h4 id="firebaseauth.users.sendEmail" class="permission-name add-link" data-text="firebaseauth.users.sendEmail" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.users.sendEmail</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.sdkAdminServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseauth.users.update" class="permission-name add-link" data-text="firebaseauth.users.update" tabindex="-1"><code dir="ltr" translate="no">firebaseauth.users.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.admin">Firebase Authentication Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseauth#firebaseauth.editor">Firebase Authentication editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseauth.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identityplatform#identityplatform.admin">Identity Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identityplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.admin">Identity Toolkit Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/identitytoolkit#identitytoolkit.editor">Identity Toolkit editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  identitytoolkit.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
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
