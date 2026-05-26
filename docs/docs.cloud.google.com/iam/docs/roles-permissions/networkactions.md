---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/networkactions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/networkactions
title: Service Extensions roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Extensions. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Extensions roles

Service Extensions offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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

There are no IAM permissions for this service.
