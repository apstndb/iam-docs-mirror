---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging
title: Firebase Cloud Messaging roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Cloud Messaging. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Cloud Messaging roles

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
<td>Firebase Cloud Messaging Service Editor
<p>( <code>roles/ cloudmessaging.editor</code> )</p>
<p>Editor of Firebase Cloud Messaging resources</p></td>
<td><p><code>cloudmessaging.*</code></p>
<ul>
<li><code>cloudmessaging.messages.create</code></li>
<li><code>cloudmessaging. topicSubscriptions. create</code></li>
<li><code>cloudmessaging. topicSubscriptions. delete</code></li>
<li><code>cloudmessaging. topicSubscriptions. get</code></li>
<li><code>cloudmessaging. topicSubscriptions. list</code></li>
<li><code>cloudmessaging. topicSubscriptions. update</code></li>
</ul>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Cloud Messaging API Admin
<p>( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p>Full read/write access to Firebase Cloud Messaging API resources.</p></td>
<td><p><code>cloudmessaging.*</code></p>
<ul>
<li><code>cloudmessaging.messages.create</code></li>
<li><code>cloudmessaging. topicSubscriptions. create</code></li>
<li><code>cloudmessaging. topicSubscriptions. delete</code></li>
<li><code>cloudmessaging. topicSubscriptions. get</code></li>
<li><code>cloudmessaging. topicSubscriptions. list</code></li>
<li><code>cloudmessaging. topicSubscriptions. update</code></li>
</ul>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Cloud Messaging API Viewer
<p>( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p>Read-only access to Firebase Cloud Messaging API resources.</p></td>
<td><p><code>cloudmessaging. topicSubscriptions. get</code></p>
<p><code>cloudmessaging. topicSubscriptions. list</code></p>
<p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebasenotifications. messages. get</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Firebase Cloud Messaging Admin
<p>( <code>roles/ firebasenotifications.admin</code> )</p>
<p>Full read/write access to Firebase Cloud Messaging resources.</p></td>
<td><p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebasenotifications.*</code></p>
<ul>
<li><code>firebasenotifications. messages. create</code></li>
<li><code>firebasenotifications. messages. delete</code></li>
<li><code>firebasenotifications. messages. get</code></li>
<li><code>firebasenotifications. messages. list</code></li>
<li><code>firebasenotifications. messages. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Firebase Cloud Messaging Viewer
<p>( <code>roles/ firebasenotifications.viewer</code> )</p>
<p>Read-only access to Firebase Cloud Messaging resources.</p></td>
<td><p><code>fcmdata.deliverydata.list</code></p>
<p><code>firebase.clients.get</code></p>
<p><code>firebase.clients.list</code></p>
<p><code>firebase.projects.get</code></p>
<p><code>firebasenotifications. messages. get</code></p>
<p><code>firebasenotifications. messages. list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Cloud Messaging permissions

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
<td><code>cloudmessaging.messages.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkAdminServiceAgent">Firebase Admin SDK Administrator Service Agent</a> ( <code>roles/ firebase.sdkAdminServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.sdkProvisioningServiceAgent">Firebase SDK Provisioning Service Agent</a> ( <code>roles/ firebase.sdkProvisioningServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>cloudmessaging. topicSubscriptions. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudmessaging. topicSubscriptions. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudmessaging. topicSubscriptions. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>cloudmessaging. topicSubscriptions. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>cloudmessaging. topicSubscriptions. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#cloudmessaging.editor">Firebase Cloud Messaging Service Editor</a> ( <code>roles/ cloudmessaging.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.admin">Firebase Cloud Messaging API Admin</a> ( <code>roles/ firebasecloudmessaging.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>firebasenotifications. messages. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
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
<td><code>firebasenotifications. messages. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
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
<td><code>firebasenotifications. messages. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
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
<td><code>firebasenotifications. messages. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code>roles/ firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasecloudmessaging.viewer">Firebase Cloud Messaging API Viewer</a> ( <code>roles/ firebasecloudmessaging.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.viewer">Firebase Cloud Messaging Viewer</a> ( <code>roles/ firebasenotifications.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code>roles/ firebase.growthViewer</code> )</p>
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
<td><code>firebasenotifications. messages. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code>roles/ firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code>roles/ firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasecloudmessaging#firebasenotifications.admin">Firebase Cloud Messaging Admin</a> ( <code>roles/ firebasenotifications.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code>roles/ firebase.growthAdmin</code> )</p>
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
