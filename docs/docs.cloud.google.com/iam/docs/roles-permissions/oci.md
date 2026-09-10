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
<td><h4 id="oci.serviceAgent" class="role-title add-link" data-text="Oracle Database@Google Cloud Service Agent" tabindex="-1">Oracle Database@Google Cloud Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  oci.serviceAgent</code> )</p>
<p>Grants Oracle Database@Google Cloud access to services and APIs in the user project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectAttachments.  use</code></p>
<p><code dir="ltr" translate="no">compute.  interconnectLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  get</code></li>
<li><code dir="ltr" translate="no">compute.  interconnectRemoteLocations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.interconnects.create</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.delete</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.get</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  getMacsecConfig</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.list</code></p>
<p><code dir="ltr" translate="no">compute.  interconnects.  setLabels</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.update</code></p>
<p><code dir="ltr" translate="no">compute.interconnects.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.routers.create</code></p>
<p><code dir="ltr" translate="no">compute.routers.delete</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routers.update</code></p>
<p><code dir="ltr" translate="no">compute.routers.use</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.changes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.changes.create</code></li>
<li><code dir="ltr" translate="no">dns.changes.get</code></li>
<li><code dir="ltr" translate="no">dns.changes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.dnsKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.dnsKeys.get</code></li>
<li><code dir="ltr" translate="no">dns.dnsKeys.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZoneOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.get</code></li>
<li><code dir="ltr" translate="no">dns.managedZoneOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.managedZones.create</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.delete</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.get</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.list</code></p>
<p><code dir="ltr" translate="no">dns.managedZones.update</code></p>
<p><code dir="ltr" translate="no">dns.networks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.  networks.  bindDNSResponsePolicy</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSPolicy</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  bindPrivateDNSZone</code></li>
<li><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></li>
<li><code dir="ltr" translate="no">dns.networks.useHealthSignals</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.policies.create</code></p>
<p><code dir="ltr" translate="no">dns.policies.delete</code></p>
<p><code dir="ltr" translate="no">dns.policies.get</code></p>
<p><code dir="ltr" translate="no">dns.policies.list</code></p>
<p><code dir="ltr" translate="no">dns.policies.listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">dns.policies.listTagBindings</code></p>
<p><code dir="ltr" translate="no">dns.policies.update</code></p>
<p><code dir="ltr" translate="no">dns.projects.get</code></p>
<p><code dir="ltr" translate="no">dns.resourceRecordSets.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.create</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.delete</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.get</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.list</code></li>
<li><code dir="ltr" translate="no">dns.resourceRecordSets.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicies.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicies.update</code></li>
</ul>
<p><code dir="ltr" translate="no">dns.responsePolicyRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.create</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.delete</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.get</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.list</code></li>
<li><code dir="ltr" translate="no">dns.responsePolicyRules.update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  create</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  delete</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  update</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  get</code></p>
<p><code dir="ltr" translate="no">networkconnectivity.  operations.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbNetworks.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbNetworks.  list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.  odbSubnets.  create</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.list</code></p>
<p><code dir="ltr" translate="no">oracledatabase.odbSubnets.use</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.get</code></p>
<p><code dir="ltr" translate="no">oracledatabase.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  updateLiens</code></p></td>
</tr>
</tbody>
</table>

## Oracle Database@Google Cloud service agent permissions

There are no IAM permissions for this service.
