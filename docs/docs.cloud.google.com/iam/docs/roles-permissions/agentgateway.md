---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/agentgateway
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/agentgateway
title: Agent Gateway roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Agent Gateway. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Agent Gateway roles

Agent Gateway offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="agentgateway.serviceAgent" class="role-title add-link" data-text="Agent Gateway Service Agent" tabindex="-1">Agent Gateway Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  agentgateway.serviceAgent</code> )</p>
<p>Grants Agent Gateway Service Agent permissions required to do DNS peering.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p></td>
</tr>
</tbody>
</table>

## Agent Gateway permissions

There are no IAM permissions for this service.
