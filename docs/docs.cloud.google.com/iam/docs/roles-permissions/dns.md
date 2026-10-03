---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dns
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dns
title: Cloud DNS roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud DNS. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud DNS roles

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
<td>DNS Administrator
<p>( <code>roles/ dns.admin</code> )</p>
<p>Provides read-write access to all Cloud DNS resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Managed zone</li>
</ul></td>
<td><p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
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
<p><code>dns.gkeClusters.*</code></p>
<ul>
<li><code>dns. gkeClusters. bindDNSResponsePolicy</code></li>
<li><code>dns. gkeClusters. bindPrivateDNSZone</code></li>
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
<p><code>dns.policies.*</code></p>
<ul>
<li><code>dns.policies.create</code></li>
<li><code>dns.policies.createTagBinding</code></li>
<li><code>dns.policies.delete</code></li>
<li><code>dns.policies.deleteTagBinding</code></li>
<li><code>dns.policies.get</code></li>
<li><code>dns.policies.list</code></li>
<li><code>dns.policies.listEffectiveTags</code></li>
<li><code>dns.policies.listTagBindings</code></li>
<li><code>dns.policies.update</code></li>
</ul>
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
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DNS Editor
<p>( <code>roles/ dns.editor</code> )</p>
<p>Editor role for DNS resources.</p></td>
<td><p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
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
<p><code>dns.gkeClusters.*</code></p>
<ul>
<li><code>dns. gkeClusters. bindDNSResponsePolicy</code></li>
<li><code>dns. gkeClusters. bindPrivateDNSZone</code></li>
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
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>DNS Viewer
<p>( <code>roles/ dns.viewer</code> )</p>
<p>Viewer role for DNS resources.</p></td>
<td><p><code>compute.networks.get</code></p>
<p><code>dns.changes.get</code></p>
<p><code>dns.changes.list</code></p>
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
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.getIamPolicy</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.policies.get</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>dns.projects.get</code></p>
<p><code>dns.resourceRecordSets.get</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.responsePolicies.get</code></p>
<p><code>dns.responsePolicies.list</code></p>
<p><code>dns.responsePolicyRules.get</code></p>
<p><code>dns.responsePolicyRules.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>DNS Peer
<p>( <code>roles/ dns.peer</code> )</p>
<p>Access to target networks with DNS peering zones</p></td>
<td><p><code>dns. networks. targetWithPeeringZone</code></p></td>
</tr>
<tr class="odd">
<td>DNS Reader
<p>( <code>roles/ dns.reader</code> )</p>
<p>Provides read-only access to all Cloud DNS resources.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Managed zone</li>
</ul></td>
<td><p><code>compute.networks.get</code></p>
<p><code>dns.changes.get</code></p>
<p><code>dns.changes.list</code></p>
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
<p><code>dns.managedZones.get</code></p>
<p><code>dns.managedZones.list</code></p>
<p><code>dns.policies.get</code></p>
<p><code>dns.policies.list</code></p>
<p><code>dns.policies.listEffectiveTags</code></p>
<p><code>dns.policies.listTagBindings</code></p>
<p><code>dns.projects.get</code></p>
<p><code>dns.resourceRecordSets.get</code></p>
<p><code>dns.resourceRecordSets.list</code></p>
<p><code>dns.responsePolicies.get</code></p>
<p><code>dns.responsePolicies.list</code></p>
<p><code>dns.responsePolicyRules.get</code></p>
<p><code>dns.responsePolicyRules.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
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
<td>Cloud DNS Service Agent
<p>( <code>roles/ dns.serviceAgent</code> )</p>
<p>Gives Cloud DNS Service Agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute. globalNetworkEndpointGroups. attachNetworkEndpoints</code></p>
<p><code>compute. globalNetworkEndpointGroups. create</code></p>
<p><code>compute. globalNetworkEndpointGroups. delete</code></p>
<p><code>compute. globalNetworkEndpointGroups. detachNetworkEndpoints</code></p>
<p><code>compute. globalNetworkEndpointGroups. get</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p></td>
</tr>
</tbody>
</table>

## Cloud DNS permissions

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
<td><code>dns.changes.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.changes.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.changes.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.dnsKeys.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.dnsKeys.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns. gkeClusters. bindDNSResponsePolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns. gkeClusters. bindPrivateDNSZone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.managedZoneOperations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.managedZoneOperations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.managedZones.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.managedZones.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.managedZones.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.sharedVpcAgent">Composer Shared VPC Agent</a> ( <code>roles/ composer.sharedVpcAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.managedZones.getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.managedZones.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.admin">Workload Manager Admin</a> ( <code>roles/ workloadmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.sharedVpcAgent">Composer Shared VPC Agent</a> ( <code>roles/ composer.sharedVpcAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadmanager#workloadmanager.deploymentAdmin">Workload Manager Deployment Admin</a> ( <code>roles/ workloadmanager.deploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/auditmanager#auditmanager.serviceAgent">Audit Manager Auditing Service Agent</a> ( <code>roles/ auditmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudsecuritycompliance#cloudsecuritycompliance.serviceAgent">Cloud Security Compliance Service Agent</a> ( <code>roles/ cloudsecuritycompliance.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackSurfaceManagementScannerServiceAgent">Attack Surface Management Scanner Service Agent</a> ( <code>roles/ securitycenter.attackSurfaceManagementScannerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.managedZones.setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>dns.managedZones.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns. networks. bindDNSResponsePolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns. networks. bindPrivateDNSPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns. networks. bindPrivateDNSZone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns. networks. targetWithPeeringZone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.sharedVpcAgent">Composer Shared VPC Agent</a> ( <code>roles/ composer.sharedVpcAgent</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.peer">DNS Peer</a> ( <code>roles/ dns.peer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentgateway#agentgateway.serviceAgent">Agent Gateway Service Agent</a> ( <code>roles/ agentgateway.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/datafusion#datafusion.serviceAgent">Cloud Data Fusion API Service Agent</a> ( <code>roles/ datafusion.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/eventarc#eventarc.serviceAgent">Eventarc Service Agent</a> ( <code>roles/ eventarc.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.sharedVpcServiceAgent">Cluster Director Shared VPC Service Agent</a> ( <code>roles/ hypercomputecluster.sharedVpcServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.serviceAgent">Managed Flink Service Agent</a> ( <code>roles/ managedflink.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.networks.useHealthSignals</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.policies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.policies.createTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.policies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.policies.deleteTagBinding</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.policies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.policies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.policies.listEffectiveTags</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.policies.listTagBindings</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagUser">Tag User</a> ( <code>roles/ resourcemanager.tagUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/resourcemanager#resourcemanager.tagViewer">Tag Viewer</a> ( <code>roles/ resourcemanager.tagViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.orgdriver">DLP Organization Data Profiles Driver</a> ( <code>roles/ dlp.orgdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dlp#dlp.projectdriver">DLP Project Data Profiles Driver</a> ( <code>roles/ dlp.projectdriver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.policies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.projects.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.resourceRecordSets.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.resourceRecordSets.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.resourceRecordSets.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.resourceRecordSets.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.attackSurfaceManagementScannerServiceAgent">Attack Surface Management Scanner Service Agent</a> ( <code>roles/ securitycenter.attackSurfaceManagementScannerServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.resourceRecordSets.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/hypercomputecluster#hypercomputecluster.serviceAgent">Cluster Director Service Agent</a> ( <code>roles/ hypercomputecluster.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.responsePolicies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.responsePolicies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.responsePolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.responsePolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.responsePolicies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.responsePolicyRules.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.responsePolicyRules.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.responsePolicyRules.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>dns.responsePolicyRules.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.viewer">DNS Viewer</a> ( <code>roles/ dns.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.reader">DNS Reader</a> ( <code>roles/ dns.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>dns.responsePolicyRules.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.admin">DNS Administrator</a> ( <code>roles/ dns.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dns#dns.editor">DNS Editor</a> ( <code>roles/ dns.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.hostServiceAgentUser">Kubernetes Engine Host Service Agent User</a> ( <code>roles/ container.hostServiceAgentUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedidentities#managedidentities.serviceAgent">Cloud Managed Identities Service Agent</a> ( <code>roles/ managedidentities.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery#multiclusterservicediscovery.serviceAgent">Multi-Cluster Service Discovery Service Agent</a> ( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/oci#oci.serviceAgent">Oracle Database@Google Cloud Service Agent</a> ( <code>roles/ oci.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicenetworking#servicenetworking.serviceAgent">Service Networking Service Agent</a> ( <code>roles/ servicenetworking.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vmwareengine#vmwareengine.serviceAgent">VMware Engine Service Agent</a> ( <code>roles/ vmwareengine.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
