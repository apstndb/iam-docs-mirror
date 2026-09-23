---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions
title: Service Extensions roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Extensions. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Extensions roles

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
<td><h4 id="serviceextensions.admin" class="role-title add-link" data-text="Service Extensions Admin Beta" tabindex="-1">Service Extensions Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceextensions.admin</code> )</p>
<p>Grants full access to Service Extensions resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceextensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceextensions.  callouts.  invoke</code></li>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="serviceextensions.editor" class="role-title add-link" data-text="Service Extensions Editor Beta" tabindex="-1">Service Extensions Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceextensions.editor</code> )</p>
<p>Grants access to edit Service Extensions resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceextensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceextensions.  callouts.  invoke</code></li>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="serviceextensions.viewer" class="role-title add-link" data-text="Service Extensions Viewer Beta" tabindex="-1">Service Extensions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceextensions.viewer</code> )</p>
<p>Grants read access to Service Extensions resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceextensions.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">serviceextensions.  locations.  list</code></li>
</ul></td>
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
<td><h4 id="networkactions.serviceAgent" class="role-title add-link" data-text="Network Actions Service Agent" tabindex="-1">Network Actions Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  networkactions.serviceAgent</code> )</p>
<p>Gives Network Actions service account access to read required resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  files.  download</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p></td>
</tr>
</tbody>
</table>

## Service Extensions permissions

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
<td><h4 id="serviceextensions.callouts.invoke" class="permission-name add-link" data-text="serviceextensions.callouts.invoke" tabindex="-1"><code dir="ltr" translate="no">serviceextensions.  callouts.  invoke</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="serviceextensions.locations.get" class="permission-name add-link" data-text="serviceextensions.locations.get" tabindex="-1"><code dir="ltr" translate="no">serviceextensions.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="serviceextensions.locations.list" class="permission-name add-link" data-text="serviceextensions.locations.list" tabindex="-1"><code dir="ltr" translate="no">serviceextensions.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
</tbody>
</table>
