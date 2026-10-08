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
<td>Routeoptimization Admin
<p>( <code>roles/ routeoptimization.admin</code> )</p>
<p>Admin role for routeoptimization</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>routeoptimization.*</code></p>
<ul>
<li><code>routeoptimization. locations. use</code></li>
<li><code>routeoptimization. operations. create</code></li>
<li><code>routeoptimization. operations. get</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Route Optimization Editor
<p>( <code>roles/ routeoptimization.editor</code> )</p>
<p>This role can create long-running operations via BatchOptimizeTours.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>routeoptimization.*</code></p>
<ul>
<li><code>routeoptimization. locations. use</code></li>
<li><code>routeoptimization. operations. create</code></li>
<li><code>routeoptimization. operations. get</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Route Optimization Viewer
<p>( <code>roles/ routeoptimization.viewer</code> )</p>
<p>This role can view any long-running Operations.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>routeoptimization. locations. use</code></p>
<p><code>routeoptimization. operations. get</code></p></td>
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
<td>Route Optimization Service Agent
<p>( <code>roles/ routeoptimization.serviceAgent</code> )</p>
<p>Grants Route Optimization Service Account access to read and write GCS objects in the host project.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>storage.objects.update</code></p></td>
</tr>
</tbody>
</table>

## Route Optimization permissions

| Permission                              | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           |
|-----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `routeoptimization. locations. use`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Routeoptimization Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin) ( `roles/ routeoptimization.admin` ) [Route Optimization Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor) ( `roles/ routeoptimization.editor` ) [Route Optimization Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer) ( `roles/ routeoptimization.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
| `routeoptimization. operations. create` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Routeoptimization Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin) ( `roles/ routeoptimization.admin` ) [Route Optimization Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor) ( `roles/ routeoptimization.editor` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| `routeoptimization. operations. get`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Routeoptimization Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.admin) ( `roles/ routeoptimization.admin` ) [Route Optimization Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.editor) ( `roles/ routeoptimization.editor` ) [Route Optimization Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/routeoptimization#routeoptimization.viewer) ( `roles/ routeoptimization.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) |
