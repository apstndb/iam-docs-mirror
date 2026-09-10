---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/gkedataplanemanagement
title: GKE Dataplane Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for GKE Dataplane Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## GKE Dataplane Management roles

GKE Dataplane Management offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="gkedataplanemanagement.warpRunServiceAgent" class="role-title add-link" data-text="Warp Run Service Agent" tabindex="-1">Warp Run Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  gkedataplanemanagement.warpRunServiceAgent</code> )</p>
<p>Gives the Warp Run service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## GKE Dataplane Management permissions

There are no IAM permissions for this service.
