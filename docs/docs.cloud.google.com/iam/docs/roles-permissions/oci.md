---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/oci
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/oci
title: Oracle Database@Google Cloud service agent roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Oracle Database@Google Cloud service agent. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Oracle Database@Google Cloud service agent roles

Oracle Database@Google Cloud service agent offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Oracle Database@Google Cloud Service Agent
<p>( <code>roles/ oci.serviceAgent</code> )</p>
<p>Grants Oracle Database@Google Cloud access to services and APIs in the user project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.globalOperations.list</code></p>
<p><code>compute. interconnectAttachments. create</code></p>
<p><code>compute. interconnectAttachments. delete</code></p>
<p><code>compute. interconnectAttachments. get</code></p>
<p><code>compute. interconnectAttachments. list</code></p>
<p><code>compute. interconnectAttachments. setLabels</code></p>
<p><code>compute. interconnectAttachments. update</code></p>
<p><code>compute. interconnectAttachments. use</code></p>
<p><code>compute. interconnectLocations.*</code></p>
<ul>
<li><code>compute. interconnectLocations. get</code></li>
<li><code>compute. interconnectLocations. list</code></li>
</ul>
<p><code>compute. interconnectRemoteLocations.*</code></p>
<ul>
<li><code>compute. interconnectRemoteLocations. get</code></li>
<li><code>compute. interconnectRemoteLocations. list</code></li>
</ul>
<p><code>compute.interconnects.create</code></p>
<p><code>compute.interconnects.delete</code></p>
<p><code>compute.interconnects.get</code></p>
<p><code>compute. interconnects. getMacsecConfig</code></p>
<p><code>compute.interconnects.list</code></p>
<p><code>compute. interconnects. setLabels</code></p>
<p><code>compute.interconnects.update</code></p>
<p><code>compute.interconnects.use</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.routers.create</code></p>
<p><code>compute.routers.delete</code></p>
<p><code>compute.routers.get</code></p>
<p><code>compute.routers.list</code></p>
<p><code>compute.routers.update</code></p>
<p><code>compute.routers.use</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>dns.changes.*</code></p>
<ul>
<li><code>dns.changes.create</code></li>
<li><code>dns.changes.get</code></li>
<li><code>dns.changes.list</code></li>
</ul>
<p><code>dns.dnsKeys.*</code></p>
<ul>
<li><code>dns.dnsKeys.get</code></li>
<li><code>dns.dnsKeys.list</code></li>
</ul>
<p><code>dns.managedZoneOperations.*</code></p>
<ul>
<li><code>dns.managedZoneOperations.get</code></li>
<li><code>dns.managedZoneOperations.list</code></li>
</ul>
<p><code>dns.managedZones.create</code></p>
<p><code>dns.managedZones.delete</code></p>
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.getIamPolicy</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.managedZones.update</code></p>
<p><code>dns.networks.*</code></p>
<ul>
<li><code>dns. networks. bindDNSResponsePolicy</code></li>
<li><code>dns. networks. bindPrivateDNSPolicy</code></li>
<li><code>dns. networks. bindPrivateDNSZone</code></li>
<li><code>dns. networks. targetWithPeeringZone</code></li>
<li><code>dns.networks.useHealthSignals</code></li>
</ul>
<p><code>dns.policies.create</code></p>
<p><code>dns.policies.delete</code></p>
<p><code>dns.policies.get</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>dns.policies.update</code></p>
<p><code>dns.projects.get</code></p>
<p><code>dns.resourceRecordSets.*</code></p>
<ul>
<li><code>dns.resourceRecordSets.create</code></li>
<li><code>dns.resourceRecordSets.delete</code></li>
<li><code>dns.resourceRecordSets.get</code></li>
<li><code>dns.resourceRecordSets.list</code></li>
<li><code>dns.resourceRecordSets.update</code></li>
</ul>
<p><code>dns.responsePolicies.*</code></p>
<ul>
<li><code>dns.responsePolicies.create</code></li>
<li><code>dns.responsePolicies.delete</code></li>
<li><code>dns.responsePolicies.get</code></li>
<li><code>dns.responsePolicies.list</code></li>
<li><code>dns.responsePolicies.update</code></li>
</ul>
<p><code>dns.responsePolicyRules.*</code></p>
<ul>
<li><code>dns.responsePolicyRules.create</code></li>
<li><code>dns.responsePolicyRules.delete</code></li>
<li><code>dns.responsePolicyRules.get</code></li>
<li><code>dns.responsePolicyRules.list</code></li>
<li><code>dns.responsePolicyRules.update</code></li>
</ul>
<p><code>networkconnectivity. internalRanges. create</code></p>
<p><code>networkconnectivity. internalRanges. delete</code></p>
<p><code>networkconnectivity. internalRanges. get</code></p>
<p><code>networkconnectivity. internalRanges. list</code></p>
<p><code>networkconnectivity. internalRanges. update</code></p>
<p><code>networkconnectivity. operations. get</code></p>
<p><code>networkconnectivity. operations. list</code></p>
<p><code>oracledatabase. odbNetworks. create</code></p>
<p><code>oracledatabase.odbNetworks.get</code></p>
<p><code>oracledatabase. odbNetworks. list</code></p>
<p><code>oracledatabase. odbSubnets. create</code></p>
<p><code>oracledatabase.odbSubnets.get</code></p>
<p><code>oracledatabase.odbSubnets.list</code></p>
<p><code>oracledatabase.odbSubnets.use</code></p>
<p><code>oracledatabase.operations.get</code></p>
<p><code>oracledatabase.operations.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. updateLiens</code></p></td>
</tr>
</tbody>
</table>

## Oracle Database@Google Cloud service agent permissions

There are no IAM permissions for this service.
