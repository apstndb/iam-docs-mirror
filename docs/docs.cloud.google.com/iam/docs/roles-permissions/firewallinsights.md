---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/firewallinsights
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/firewallinsights
title: Firewall Insights roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firewall Insights. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firewall Insights roles

Firewall Insights offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Cloud Firewall Insights Service Agent
<p>( <code>roles/ firewallinsights.serviceAgent</code> )</p>
<p>Gives Cloud Firewall Insights service agent permissions to retrieve Firewall, VM and route resources on user behalf.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.backendServices.list</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.forwardingRules.list</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
<p><code>compute.httpsHealthChecks.list</code></p>
<p><code>compute.instanceGroups.list</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute. networks. getEffectiveFirewalls</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.targetPools.list</code></p>
<p><code>compute.targetSslProxies.list</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute.targetVpnGateways.list</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>compute.vpnGateways.list</code></p>
<p><code>compute.vpnTunnels.list</code></p></td>
</tr>
</tbody>
</table>

## Firewall Insights permissions

There are no IAM permissions for this service.
