---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher
title: Firebase Extensions Publisher roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Extensions Publisher. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Extensions Publisher roles

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
<td><h4 id="firebaseextensionspublisher.admin" class="role-title add-link" data-text="Firebaseextensionspublisher Admin Beta" tabindex="-1">Firebaseextensionspublisher Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p>Admin role for firebaseextensionspublisher</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseextensionspublisher.viewer" class="role-title add-link" data-text="Firebaseextensionspublisher Viewer Beta" tabindex="-1">Firebaseextensionspublisher Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p>Viewer role for firebaseextensionspublisher</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseextensionspublisher.extensionsAdmin" class="role-title add-link" data-text="Firebase Extensions Publisher - Extensions Admin Beta" tabindex="-1">Firebase Extensions Publisher - Extensions Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p>Fully manage Firebase Extensions</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  create</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  delete</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></li>
<li><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseextensionspublisher.extensionsViewer" class="role-title add-link" data-text="Firebase Extensions Publisher - Extensions Viewer Beta" tabindex="-1">Firebase Extensions Publisher - Extensions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p>View Firebase Extensions</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></p>
<p><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Extensions Publisher permissions

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
<td><h4 id="firebaseextensionspublisher.extensions.create" class="permission-name add-link" data-text="firebaseextensionspublisher.extensions.create" tabindex="-1"><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseextensionspublisher.extensions.delete" class="permission-name add-link" data-text="firebaseextensionspublisher.extensions.delete" tabindex="-1"><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseextensionspublisher.extensions.get" class="permission-name add-link" data-text="firebaseextensionspublisher.extensions.get" tabindex="-1"><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseextensionspublisher.extensions.list" class="permission-name add-link" data-text="firebaseextensionspublisher.extensions.list" tabindex="-1"><code dir="ltr" translate="no">firebaseextensionspublisher.  extensions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.admin">Firebaseextensionspublisher Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.viewer">Firebaseextensionspublisher Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsAdmin">Firebase Extensions Publisher - Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseextensionspublisher#firebaseextensionspublisher.extensionsViewer">Firebase Extensions Publisher - Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseextensionspublisher.extensionsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
