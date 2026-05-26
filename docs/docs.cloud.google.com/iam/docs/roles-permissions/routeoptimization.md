---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization
title: Route Optimization roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Route Optimization. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Route Optimization roles

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
<td><h4 id="routeoptimization.admin" class="role-title add-link" data-text="Routeoptimization Admin" tabindex="-1">Routeoptimization Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p>Admin role for routeoptimization</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">routeoptimization.*</code></p>
<ul>
<li><code dir="ltr" translate="no">routeoptimization.  locations.  use</code></li>
<li><code dir="ltr" translate="no">routeoptimization.  operations.  create</code></li>
<li><code dir="ltr" translate="no">routeoptimization.  operations.  get</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="routeoptimization.editor" class="role-title add-link" data-text="Route Optimization Editor" tabindex="-1">Route Optimization Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p>
<p>This role can create long-running operations via BatchOptimizeTours.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">routeoptimization.*</code></p>
<ul>
<li><code dir="ltr" translate="no">routeoptimization.  locations.  use</code></li>
<li><code dir="ltr" translate="no">routeoptimization.  operations.  create</code></li>
<li><code dir="ltr" translate="no">routeoptimization.  operations.  get</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="routeoptimization.viewer" class="role-title add-link" data-text="Route Optimization Viewer" tabindex="-1">Route Optimization Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  routeoptimization.viewer</code> )</p>
<p>This role can view any long-running Operations.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">routeoptimization.  operations.  get</code></p></td>
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
<td><h4 id="routeoptimization.serviceAgent" class="role-title add-link" data-text="Route Optimization Service Agent" tabindex="-1">Route Optimization Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  routeoptimization.serviceAgent</code> )</p>
<p>Grants Route Optimization Service Account access to read and write GCS objects in the host project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Route Optimization permissions

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
<td><h4 id="routeoptimization.locations.use" class="permission-name add-link" data-text="routeoptimization.locations.use" tabindex="-1"><code dir="ltr" translate="no">routeoptimization.  locations.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="routeoptimization.operations.create" class="permission-name add-link" data-text="routeoptimization.operations.create" tabindex="-1"><code dir="ltr" translate="no">routeoptimization.  operations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="routeoptimization.operations.get" class="permission-name add-link" data-text="routeoptimization.operations.get" tabindex="-1"><code dir="ltr" translate="no">routeoptimization.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin">Routeoptimization Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor">Route Optimization Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer">Route Optimization Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  routeoptimization.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
