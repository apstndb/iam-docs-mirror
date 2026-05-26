---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/parallelstore
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore
title: Parallelstore roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Parallelstore. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Parallelstore roles

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
<td><h4 id="parallelstore.admin" class="role-title add-link" data-text="Parallelstore Admin" tabindex="-1">Parallelstore Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Full access to Parallelstore resources.</p></td>
<td><p><code dir="ltr" translate="no">parallelstore.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parallelstore.instances.create</code></li>
<li><code dir="ltr" translate="no">parallelstore.instances.delete</code></li>
<li><code dir="ltr" translate="no">parallelstore.  instances.  exportData</code></li>
<li><code dir="ltr" translate="no">parallelstore.instances.get</code></li>
<li><code dir="ltr" translate="no">parallelstore.  instances.  importData</code></li>
<li><code dir="ltr" translate="no">parallelstore.instances.list</code></li>
<li><code dir="ltr" translate="no">parallelstore.instances.update</code></li>
<li><code dir="ltr" translate="no">parallelstore.locations.get</code></li>
<li><code dir="ltr" translate="no">parallelstore.locations.list</code></li>
<li><code dir="ltr" translate="no">parallelstore.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">parallelstore.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">parallelstore.operations.get</code></li>
<li><code dir="ltr" translate="no">parallelstore.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.viewer" class="role-title add-link" data-text="Parallelstore Viewer" tabindex="-1">Parallelstore Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p>Readonly access to Parallelstore resources.</p></td>
<td><p><code dir="ltr" translate="no">parallelstore.instances.get</code></p>
<p><code dir="ltr" translate="no">parallelstore.instances.list</code></p>
<p><code dir="ltr" translate="no">parallelstore.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parallelstore.locations.get</code></li>
<li><code dir="ltr" translate="no">parallelstore.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">parallelstore.operations.get</code></p>
<p><code dir="ltr" translate="no">parallelstore.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="parallelstore.serviceAgent" class="role-title add-link" data-text="Parallelstore Service Agent" tabindex="-1">Parallelstore Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  parallelstore.serviceAgent</code> )</p>
<p>Gives the Parallelstore service agent ability to access customer resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Parallelstore permissions

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
<td><h4 id="parallelstore.instances.create" class="permission-name add-link" data-text="parallelstore.instances.create" tabindex="-1"><code dir="ltr" translate="no">parallelstore.instances.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.instances.delete" class="permission-name add-link" data-text="parallelstore.instances.delete" tabindex="-1"><code dir="ltr" translate="no">parallelstore.instances.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.instances.exportData" class="permission-name add-link" data-text="parallelstore.instances.exportData" tabindex="-1"><code dir="ltr" translate="no">parallelstore.  instances.  exportData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.instances.get" class="permission-name add-link" data-text="parallelstore.instances.get" tabindex="-1"><code dir="ltr" translate="no">parallelstore.instances.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.instances.importData" class="permission-name add-link" data-text="parallelstore.instances.importData" tabindex="-1"><code dir="ltr" translate="no">parallelstore.  instances.  importData</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.instances.list" class="permission-name add-link" data-text="parallelstore.instances.list" tabindex="-1"><code dir="ltr" translate="no">parallelstore.instances.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.instances.update" class="permission-name add-link" data-text="parallelstore.instances.update" tabindex="-1"><code dir="ltr" translate="no">parallelstore.instances.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.locations.get" class="permission-name add-link" data-text="parallelstore.locations.get" tabindex="-1"><code dir="ltr" translate="no">parallelstore.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.locations.list" class="permission-name add-link" data-text="parallelstore.locations.list" tabindex="-1"><code dir="ltr" translate="no">parallelstore.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.operations.cancel" class="permission-name add-link" data-text="parallelstore.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">parallelstore.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.operations.delete" class="permission-name add-link" data-text="parallelstore.operations.delete" tabindex="-1"><code dir="ltr" translate="no">parallelstore.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="parallelstore.operations.get" class="permission-name add-link" data-text="parallelstore.operations.get" tabindex="-1"><code dir="ltr" translate="no">parallelstore.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="parallelstore.operations.list" class="permission-name add-link" data-text="parallelstore.operations.list" tabindex="-1"><code dir="ltr" translate="no">parallelstore.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.admin">Parallelstore Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parallelstore#parallelstore.viewer">Parallelstore Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parallelstore.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
