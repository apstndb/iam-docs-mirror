---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/anthosidentityservice
title: GKE Identity Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for GKE Identity Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## GKE Identity Service roles

GKE Identity Service offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Anthos Identity Service Agent
<p>( <code>roles/ anthosidentityservice.serviceAgent</code> )</p>
<p>Gives the Anthos Identity service agent access to Google Cloud resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>gkehub.features.get</code></p>
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

## GKE Identity Service permissions

There are no IAM permissions for this service.
