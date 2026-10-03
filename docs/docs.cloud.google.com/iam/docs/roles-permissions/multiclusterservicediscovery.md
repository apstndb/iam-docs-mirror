---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusterservicediscovery
title: Multi-Cluster Service Discovery roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Multi-Cluster Service Discovery. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Multi-Cluster Service Discovery roles

Multi-Cluster Service Discovery offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Multi-Cluster Service Discovery Service Agent
<p>( <code>roles/ multiclusterservicediscovery.serviceAgent</code> )</p>
<p>Gives the Multi-Cluster Service Discovery service access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>compute.backendServices.*</code></p>
<ul>
<li><code>compute. backendServices. addSignedUrlKey</code></li>
<li><code>compute.backendServices.create</code></li>
<li><code>compute. backendServices. createTagBinding</code></li>
<li><code>compute.backendServices.delete</code></li>
<li><code>compute. backendServices. deleteSignedUrlKey</code></li>
<li><code>compute. backendServices. deleteTagBinding</code></li>
<li><code>compute.backendServices.get</code></li>
<li><code>compute. backendServices. getIamPolicy</code></li>
<li><code>compute.backendServices.list</code></li>
<li><code>compute. backendServices. listEffectiveTags</code></li>
<li><code>compute. backendServices. listTagBindings</code></li>
<li><code>compute. backendServices. setIamPolicy</code></li>
<li><code>compute. backendServices. setSecurityPolicy</code></li>
<li><code>compute.backendServices.update</code></li>
<li><code>compute.backendServices.use</code></li>
</ul>
<p><code>compute.firewalls.*</code></p>
<ul>
<li><code>compute.firewalls.create</code></li>
<li><code>compute. firewalls. createTagBinding</code></li>
<li><code>compute.firewalls.delete</code></li>
<li><code>compute. firewalls. deleteTagBinding</code></li>
<li><code>compute.firewalls.get</code></li>
<li><code>compute.firewalls.list</code></li>
<li><code>compute. firewalls. listEffectiveTags</code></li>
<li><code>compute. firewalls. listTagBindings</code></li>
<li><code>compute.firewalls.update</code></li>
</ul>
<p><code>compute.forwardingRules.*</code></p>
<ul>
<li><code>compute.forwardingRules.create</code></li>
<li><code>compute. forwardingRules. createTagBinding</code></li>
<li><code>compute.forwardingRules.delete</code></li>
<li><code>compute. forwardingRules. deleteTagBinding</code></li>
<li><code>compute.forwardingRules.get</code></li>
<li><code>compute.forwardingRules.list</code></li>
<li><code>compute. forwardingRules. listEffectiveTags</code></li>
<li><code>compute. forwardingRules. listTagBindings</code></li>
<li><code>compute. forwardingRules. pscCreate</code></li>
<li><code>compute. forwardingRules. pscDelete</code></li>
<li><code>compute. forwardingRules. pscSetLabels</code></li>
<li><code>compute. forwardingRules. pscUpdate</code></li>
<li><code>compute. forwardingRules. setLabels</code></li>
<li><code>compute. forwardingRules. setTarget</code></li>
<li><code>compute.forwardingRules.update</code></li>
<li><code>compute.forwardingRules.use</code></li>
</ul>
<p><code>compute. globalForwardingRules.*</code></p>
<ul>
<li><code>compute. globalForwardingRules. create</code></li>
<li><code>compute. globalForwardingRules. createTagBinding</code></li>
<li><code>compute. globalForwardingRules. delete</code></li>
<li><code>compute. globalForwardingRules. deleteTagBinding</code></li>
<li><code>compute. globalForwardingRules. get</code></li>
<li><code>compute. globalForwardingRules. list</code></li>
<li><code>compute. globalForwardingRules. listEffectiveTags</code></li>
<li><code>compute. globalForwardingRules. listTagBindings</code></li>
<li><code>compute. globalForwardingRules. pscCreate</code></li>
<li><code>compute. globalForwardingRules. pscDelete</code></li>
<li><code>compute. globalForwardingRules. pscSetLabels</code></li>
<li><code>compute. globalForwardingRules. pscUpdate</code></li>
<li><code>compute. globalForwardingRules. setLabels</code></li>
<li><code>compute. globalForwardingRules. setTarget</code></li>
<li><code>compute. globalForwardingRules. update</code></li>
</ul>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.*</code></p>
<ul>
<li><code>compute.healthChecks.create</code></li>
<li><code>compute. healthChecks. createTagBinding</code></li>
<li><code>compute.healthChecks.delete</code></li>
<li><code>compute. healthChecks. deleteTagBinding</code></li>
<li><code>compute.healthChecks.get</code></li>
<li><code>compute.healthChecks.list</code></li>
<li><code>compute. healthChecks. listEffectiveTags</code></li>
<li><code>compute. healthChecks. listTagBindings</code></li>
<li><code>compute.healthChecks.update</code></li>
<li><code>compute.healthChecks.use</code></li>
<li><code>compute. healthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.httpHealthChecks.*</code></p>
<ul>
<li><code>compute. httpHealthChecks. create</code></li>
<li><code>compute. httpHealthChecks. createTagBinding</code></li>
<li><code>compute. httpHealthChecks. delete</code></li>
<li><code>compute. httpHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpHealthChecks.get</code></li>
<li><code>compute.httpHealthChecks.list</code></li>
<li><code>compute. httpHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpHealthChecks. listTagBindings</code></li>
<li><code>compute. httpHealthChecks. update</code></li>
<li><code>compute.httpHealthChecks.use</code></li>
<li><code>compute. httpHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.httpsHealthChecks.*</code></p>
<ul>
<li><code>compute. httpsHealthChecks. create</code></li>
<li><code>compute. httpsHealthChecks. createTagBinding</code></li>
<li><code>compute. httpsHealthChecks. delete</code></li>
<li><code>compute. httpsHealthChecks. deleteTagBinding</code></li>
<li><code>compute.httpsHealthChecks.get</code></li>
<li><code>compute.httpsHealthChecks.list</code></li>
<li><code>compute. httpsHealthChecks. listEffectiveTags</code></li>
<li><code>compute. httpsHealthChecks. listTagBindings</code></li>
<li><code>compute. httpsHealthChecks. update</code></li>
<li><code>compute.httpsHealthChecks.use</code></li>
<li><code>compute. httpsHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute. networkEndpointGroups. use</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute. regionTargetTcpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetTcpProxies. attach</code></li>
<li><code>compute. regionTargetTcpProxies. create</code></li>
<li><code>compute. regionTargetTcpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. delete</code></li>
<li><code>compute. regionTargetTcpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetTcpProxies. get</code></li>
<li><code>compute. regionTargetTcpProxies. list</code></li>
<li><code>compute. regionTargetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetTcpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetTcpProxies. use</code></li>
</ul>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.targetHttpProxies.*</code></p>
<ul>
<li><code>compute. targetHttpProxies. create</code></li>
<li><code>compute. targetHttpProxies. createTagBinding</code></li>
<li><code>compute. targetHttpProxies. delete</code></li>
<li><code>compute. targetHttpProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpProxies.get</code></li>
<li><code>compute.targetHttpProxies.list</code></li>
<li><code>compute. targetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpProxies. listTagBindings</code></li>
<li><code>compute. targetHttpProxies. setUrlMap</code></li>
<li><code>compute. targetHttpProxies. update</code></li>
<li><code>compute.targetHttpProxies.use</code></li>
</ul>
<p><code>compute.targetHttpsProxies.*</code></p>
<ul>
<li><code>compute. targetHttpsProxies. create</code></li>
<li><code>compute. targetHttpsProxies. createTagBinding</code></li>
<li><code>compute. targetHttpsProxies. delete</code></li>
<li><code>compute. targetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute.targetHttpsProxies.get</code></li>
<li><code>compute. targetHttpsProxies. list</code></li>
<li><code>compute. targetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. targetHttpsProxies. listTagBindings</code></li>
<li><code>compute. targetHttpsProxies. setCertificateMap</code></li>
<li><code>compute. targetHttpsProxies. setQuicOverride</code></li>
<li><code>compute. targetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. targetHttpsProxies. setSslPolicy</code></li>
<li><code>compute. targetHttpsProxies. setUrlMap</code></li>
<li><code>compute. targetHttpsProxies. update</code></li>
<li><code>compute.targetHttpsProxies.use</code></li>
</ul>
<p><code>compute.targetTcpProxies.*</code></p>
<ul>
<li><code>compute. targetTcpProxies. attach</code></li>
<li><code>compute. targetTcpProxies. create</code></li>
<li><code>compute. targetTcpProxies. createTagBinding</code></li>
<li><code>compute. targetTcpProxies. delete</code></li>
<li><code>compute. targetTcpProxies. deleteTagBinding</code></li>
<li><code>compute.targetTcpProxies.get</code></li>
<li><code>compute.targetTcpProxies.list</code></li>
<li><code>compute. targetTcpProxies. listEffectiveTags</code></li>
<li><code>compute. targetTcpProxies. listTagBindings</code></li>
<li><code>compute. targetTcpProxies. update</code></li>
<li><code>compute.targetTcpProxies.use</code></li>
</ul>
<p><code>compute.urlMaps.*</code></p>
<ul>
<li><code>compute.urlMaps.create</code></li>
<li><code>compute. urlMaps. createTagBinding</code></li>
<li><code>compute.urlMaps.delete</code></li>
<li><code>compute. urlMaps. deleteTagBinding</code></li>
<li><code>compute.urlMaps.get</code></li>
<li><code>compute. urlMaps. invalidateCache</code></li>
<li><code>compute.urlMaps.list</code></li>
<li><code>compute. urlMaps. listEffectiveTags</code></li>
<li><code>compute. urlMaps. listTagBindings</code></li>
<li><code>compute.urlMaps.update</code></li>
<li><code>compute.urlMaps.use</code></li>
<li><code>compute.urlMaps.validate</code></li>
</ul>
<p><code>container.clusters.get</code></p>
<p><code>container.clusters.list</code></p>
<p><code>container. thirdPartyObjects. list</code></p>
<p><code>container. thirdPartyObjects. update</code></p>
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
<p><code>gkehub.features.get</code></p>
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
<p><code>gkehub.memberships.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Multi-Cluster Service Discovery permissions

There are no IAM permissions for this service.
