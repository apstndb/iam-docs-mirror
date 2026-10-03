---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/appdevelopmentexperience
title: App Development Experience roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for App Development Experience. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## App Development Experience roles

App Development Experience offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>App Development Experience Service Agent
<p>( <code>roles/ appdevelopmentexperience.serviceAgent</code> )</p>
<p>Give the App Development Experience service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>container.clusters.get</code></p>
<p><code>container.clusters.update</code></p>
<p><code>gkehub.features.get</code></p>
<p><code>gkehub.gateway.delete</code></p>
<p><code>gkehub. gateway. generateCredentials</code></p>
<p><code>gkehub.gateway.get</code></p>
<p><code>gkehub.gateway.patch</code></p>
<p><code>gkehub.gateway.post</code></p>
<p><code>gkehub.gateway.put</code></p>
<p><code>gkehub.locations.*</code></p>
<ul>
<li><code>gkehub.locations.get</code></li>
<li><code>gkehub.locations.list</code></li>
</ul>
<p><code>gkehub.memberships.get</code></p>
<p><code>gkehub.memberships.list</code></p></td>
</tr>
</tbody>
</table>

## App Development Experience permissions

There are no IAM permissions for this service.
