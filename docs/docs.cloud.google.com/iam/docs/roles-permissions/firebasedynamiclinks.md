---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks
title: Firebase Dynamic Links roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Dynamic Links. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Dynamic Links roles

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
<td><h4 id="firebasedynamiclinks.admin" class="role-title add-link" data-text="Firebase Dynamic Links Admin" tabindex="-1">Firebase Dynamic Links Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p>Full read/write access to Firebase Dynamic Links resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  delete</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.editor" class="role-title add-link" data-text="Firebasedynamiclinks Editor" tabindex="-1">Firebasedynamiclinks Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p>Editor role for firebasedynamiclinks</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.links.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></li>
<li><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.viewer" class="role-title add-link" data-text="Firebase Dynamic Links Viewer" tabindex="-1">Firebase Dynamic Links Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p>Read-only access to Firebase Dynamic Links resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></p>
<p><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Dynamic Links permissions

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
<td><h4 id="firebasedynamiclinks.destinations.list" class="permission-name add-link" data-text="firebasedynamiclinks.destinations.list" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.destinations.update" class="permission-name add-link" data-text="firebasedynamiclinks.destinations.update" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  destinations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.domains.create" class="permission-name add-link" data-text="firebasedynamiclinks.domains.create" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.domains.delete" class="permission-name add-link" data-text="firebasedynamiclinks.domains.delete" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.domains.get" class="permission-name add-link" data-text="firebasedynamiclinks.domains.get" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.domains.list" class="permission-name add-link" data-text="firebasedynamiclinks.domains.list" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.domains.update" class="permission-name add-link" data-text="firebasedynamiclinks.domains.update" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  domains.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.links.create" class="permission-name add-link" data-text="firebasedynamiclinks.links.create" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  links.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.links.get" class="permission-name add-link" data-text="firebasedynamiclinks.links.get" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.links.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.links.list" class="permission-name add-link" data-text="firebasedynamiclinks.links.list" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  links.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebasedynamiclinks.links.update" class="permission-name add-link" data-text="firebasedynamiclinks.links.update" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.  links.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebasedynamiclinks.stats.get" class="permission-name add-link" data-text="firebasedynamiclinks.stats.get" tabindex="-1"><code dir="ltr" translate="no">firebasedynamiclinks.stats.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.admin">Firebase Dynamic Links Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.editor">Firebasedynamiclinks Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebasedynamiclinks#firebasedynamiclinks.viewer">Firebase Dynamic Links Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebasedynamiclinks.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
