---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt
title: Firebase A/B Testing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase A/B Testing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase A/B Testing roles

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
<td><h4 id="firebaseabt.admin" class="role-title add-link" data-text="Firebase A/B Testing Admin Beta" tabindex="-1">Firebase A/B Testing Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p>Full read/write access to Firebase A/B Testing resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.*</code></p>
<ul>
<li><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.create</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.get</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.list</code></li>
<li><code dir="ltr" translate="no">firebaseabt.experiments.update</code></li>
<li><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseabt.viewer" class="role-title add-link" data-text="Firebase A/B Testing Viewer Beta" tabindex="-1">Firebase A/B Testing Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p>Read-only access to Firebase A/B Testing resources.</p></td>
<td><p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.get</code></p>
<p><code dir="ltr" translate="no">firebaseabt.experiments.list</code></p>
<p><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase A/B Testing permissions

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
<td><h4 id="firebaseabt.experimentresults.get" class="permission-name add-link" data-text="firebaseabt.experimentresults.get" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.  experimentresults.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseabt.experiments.create" class="permission-name add-link" data-text="firebaseabt.experiments.create" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.experiments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseabt.experiments.delete" class="permission-name add-link" data-text="firebaseabt.experiments.delete" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.experiments.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.managementServiceAgent">Firebase Service Management Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.managementServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="firebaseabt.experiments.get" class="permission-name add-link" data-text="firebaseabt.experiments.get" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.experiments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseabt.experiments.list" class="permission-name add-link" data-text="firebaseabt.experiments.list" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.experiments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="firebaseabt.experiments.update" class="permission-name add-link" data-text="firebaseabt.experiments.update" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.experiments.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="firebaseabt.projectmetadata.get" class="permission-name add-link" data-text="firebaseabt.projectmetadata.get" tabindex="-1"><code dir="ltr" translate="no">firebaseabt.  projectmetadata.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.admin">Firebase A/B Testing Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebaseabt#firebaseabt.viewer">Firebase A/B Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebaseabt.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthAdmin">Firebase Grow Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.growthViewer">Firebase Grow Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.growthViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
