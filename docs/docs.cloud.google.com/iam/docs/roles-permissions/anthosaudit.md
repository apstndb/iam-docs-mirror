---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/anthosaudit
title: Anthos Audit API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Anthos Audit API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Anthos Audit API roles

Anthos Audit API offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="anthosaudit.serviceAgent" class="role-title add-link" data-text="Anthos Audit Service Agent" tabindex="-1">Anthos Audit Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  anthosaudit.serviceAgent</code> )</p>
<p>Gives the Anthos Audit service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p></td>
</tr>
</tbody>
</table>

## Anthos Audit API permissions

There are no IAM permissions for this service.
