---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking
title: Service Networking roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Networking. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Networking roles

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
<td><h4 id="servicenetworking.admin" class="role-title add-link" data-text="Servicenetworking Admin Beta" tabindex="-1">Servicenetworking Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p>Admin role for servicenetworking</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addDnsZone</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addSubnetwork</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.services.get</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  getConsumerConfig</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsZone</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  updateConsumerConfig</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  updateDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.services.use</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.editor" class="role-title add-link" data-text="Servicenetworking Editor Beta" tabindex="-1">Servicenetworking Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p>Editor role for servicenetworking</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addDnsRecordSet</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addDnsZone</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  addSubnetwork</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getConsumerConfig</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsRecordSet</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsZone</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  updateConsumerConfig</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  updateDnsRecordSet</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.use</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.viewer" class="role-title add-link" data-text="Servicenetworking Viewer Beta" tabindex="-1">Servicenetworking Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p>Viewer role for servicenetworking</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.get</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getConsumerConfig</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></p>
<p><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></p>
<p><code dir="ltr" translate="no">servicenetworking.services.use</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.networksAdmin" class="role-title add-link" data-text="Service Networking Admin Beta" tabindex="-1">Service Networking Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Full control of service networking with projects.</p></td>
<td><p><code dir="ltr" translate="no">servicenetworking.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addDnsZone</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  addSubnetwork</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.services.get</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  getConsumerConfig</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsZone</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  updateConsumerConfig</code></li>
<li><code dir="ltr" translate="no">servicenetworking.  services.  updateDnsRecordSet</code></li>
<li><code dir="ltr" translate="no">servicenetworking.services.use</code></li>
</ul></td>
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
<td><h4 id="servicenetworking.serviceAgent" class="role-title add-link" data-text="Service Networking Service Agent" tabindex="-1">Service Networking Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  servicenetworking.serviceAgent</code> )</p>
<p>Gives permission to manage network configuration, such as establishing network peering, necessary for service producers</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.addPeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.create</code></p>
<p><code dir="ltr" translate="no">compute.networks.delete</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  networks.  listPeeringRoutes</code></p>
<p><code dir="ltr" translate="no">compute.networks.removePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.update</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePeering</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.get</code></p>
<p><code dir="ltr" translate="no">compute.routers.list</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
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
<p><code dir="ltr" translate="no">dns.gkeClusters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dns.  gkeClusters.  bindDNSResponsePolicy</code></li>
<li><code dir="ltr" translate="no">dns.  gkeClusters.  bindPrivateDNSZone</code></li>
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
<p><code dir="ltr" translate="no">networkconnectivity.  internalRanges.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Service Networking permissions

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th>Permission</th>
<th>Included in roles</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><h4 id="servicenetworking.operations.cancel" class="permission-name add-link" data-text="servicenetworking.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.operations.delete" class="permission-name add-link" data-text="servicenetworking.operations.delete" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.operations.get" class="permission-name add-link" data-text="servicenetworking.operations.get" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.operations.list" class="permission-name add-link" data-text="servicenetworking.operations.list" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.addDnsRecordSet" class="permission-name add-link" data-text="servicenetworking.services.addDnsRecordSet" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  addDnsRecordSet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.addDnsZone" class="permission-name add-link" data-text="servicenetworking.services.addDnsZone" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  addDnsZone</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.addPeering" class="permission-name add-link" data-text="servicenetworking.services.addPeering" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  addPeering</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.addSubnetwork" class="permission-name add-link" data-text="servicenetworking.services.addSubnetwork" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  addSubnetwork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.createPeeredDnsDomain" class="permission-name add-link" data-text="servicenetworking.services.createPeeredDnsDomain" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  createPeeredDnsDomain</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.deleteConnection" class="permission-name add-link" data-text="servicenetworking.services.deleteConnection" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  deleteConnection</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.deletePeeredDnsDomain" class="permission-name add-link" data-text="servicenetworking.services.deletePeeredDnsDomain" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  deletePeeredDnsDomain</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.disableVpcServiceControls" class="permission-name add-link" data-text="servicenetworking.services.disableVpcServiceControls" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  disableVpcServiceControls</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.enableVpcServiceControls" class="permission-name add-link" data-text="servicenetworking.services.enableVpcServiceControls" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  enableVpcServiceControls</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.get" class="permission-name add-link" data-text="servicenetworking.services.get" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkUser">Compute Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkViewer">Compute Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.sharedVpcServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.getConsumerConfig" class="permission-name add-link" data-text="servicenetworking.services.getConsumerConfig" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  getConsumerConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.getVpcServiceControls" class="permission-name add-link" data-text="servicenetworking.services.getVpcServiceControls" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  getVpcServiceControls</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.listPeeredDnsDomains" class="permission-name add-link" data-text="servicenetworking.services.listPeeredDnsDomains" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  listPeeredDnsDomains</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  hypercomputecluster.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.removeDnsRecordSet" class="permission-name add-link" data-text="servicenetworking.services.removeDnsRecordSet" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsRecordSet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.removeDnsZone" class="permission-name add-link" data-text="servicenetworking.services.removeDnsZone" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  removeDnsZone</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.updateConsumerConfig" class="permission-name add-link" data-text="servicenetworking.services.updateConsumerConfig" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  updateConsumerConfig</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicenetworking.services.updateDnsRecordSet" class="permission-name add-link" data-text="servicenetworking.services.updateDnsRecordSet" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.  services.  updateDnsRecordSet</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicenetworking.services.use" class="permission-name add-link" data-text="servicenetworking.services.use" tabindex="-1"><code dir="ltr" translate="no">servicenetworking.services.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.admin">Servicenetworking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.editor">Servicenetworking Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.viewer">Servicenetworking Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.networksAdmin">Service Networking Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicenetworking.networksAdmin</code> )</p></td>
</tr>
</tbody>
</table>
