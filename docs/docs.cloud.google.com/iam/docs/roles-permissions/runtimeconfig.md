---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig
title: Cloud Runtime Configuration API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Runtime Configuration API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Runtime Configuration API roles

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
<td><h4 id="runtimeconfig.admin" class="role-title add-link" data-text="Cloud RuntimeConfig Admin" tabindex="-1">Cloud RuntimeConfig Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p>Full access to RuntimeConfig resources.</p></td>
<td><p><code dir="ltr" translate="no">runtimeconfig.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runtimeconfig.configs.create</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.configs.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  configs.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.configs.list</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  configs.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.configs.update</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.list</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.create</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  variables.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.list</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  variables.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.update</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  waiters.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.  waiters.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.waiters.update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.editor" class="role-title add-link" data-text="Runtimeconfig Editor" tabindex="-1">Runtimeconfig Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p>Editor role for runtimeconfig</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runtimeconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runtimeconfig.variables.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.update</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.viewer" class="role-title add-link" data-text="Runtimeconfig Viewer" tabindex="-1">Runtimeconfig Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p>Viewer role for runtimeconfig</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.configs.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runtimeconfig.operations.get</code></li>
<li><code dir="ltr" translate="no">runtimeconfig.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runtimeconfig.variables.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.list</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></p>
<p><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Runtime Configuration API permissions

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
<td><h4 id="runtimeconfig.configs.create" class="permission-name add-link" data-text="runtimeconfig.configs.create" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.configs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.configs.delete" class="permission-name add-link" data-text="runtimeconfig.configs.delete" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.configs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.configs.get" class="permission-name add-link" data-text="runtimeconfig.configs.get" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.configs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.configs.getIamPolicy" class="permission-name add-link" data-text="runtimeconfig.configs.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  configs.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.configs.list" class="permission-name add-link" data-text="runtimeconfig.configs.list" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.configs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.configs.setIamPolicy" class="permission-name add-link" data-text="runtimeconfig.configs.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  configs.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.configs.update" class="permission-name add-link" data-text="runtimeconfig.configs.update" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.configs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.operations.get" class="permission-name add-link" data-text="runtimeconfig.operations.get" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.operations.list" class="permission-name add-link" data-text="runtimeconfig.operations.list" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.variables.create" class="permission-name add-link" data-text="runtimeconfig.variables.create" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.variables.delete" class="permission-name add-link" data-text="runtimeconfig.variables.delete" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.variables.get" class="permission-name add-link" data-text="runtimeconfig.variables.get" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.variables.getIamPolicy" class="permission-name add-link" data-text="runtimeconfig.variables.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  variables.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.variables.list" class="permission-name add-link" data-text="runtimeconfig.variables.list" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.variables.setIamPolicy" class="permission-name add-link" data-text="runtimeconfig.variables.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  variables.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.variables.update" class="permission-name add-link" data-text="runtimeconfig.variables.update" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.variables.watch" class="permission-name add-link" data-text="runtimeconfig.variables.watch" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.variables.watch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.waiters.create" class="permission-name add-link" data-text="runtimeconfig.waiters.create" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.waiters.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.waiters.delete" class="permission-name add-link" data-text="runtimeconfig.waiters.delete" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.waiters.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.waiters.get" class="permission-name add-link" data-text="runtimeconfig.waiters.get" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.waiters.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.waiters.getIamPolicy" class="permission-name add-link" data-text="runtimeconfig.waiters.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  waiters.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.waiters.list" class="permission-name add-link" data-text="runtimeconfig.waiters.list" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.waiters.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.viewer">Runtimeconfig Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="runtimeconfig.waiters.setIamPolicy" class="permission-name add-link" data-text="runtimeconfig.waiters.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.  waiters.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runtimeconfig.waiters.update" class="permission-name add-link" data-text="runtimeconfig.waiters.update" tabindex="-1"><code dir="ltr" translate="no">runtimeconfig.waiters.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.admin">Cloud RuntimeConfig Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runtimeconfig#runtimeconfig.editor">Runtimeconfig Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runtimeconfig.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p></td>
</tr>
</tbody>
</table>
