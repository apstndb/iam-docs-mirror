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
<td><h4 id="multiclusterservicediscovery.serviceAgent" class="role-title add-link" data-text="Multi-Cluster Service Discovery Service Agent" tabindex="-1">Multi-Cluster Service Discovery Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  multiclusterservicediscovery.serviceAgent</code> )</p>
<p>Gives the Multi-Cluster Service Discovery service access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.backendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  backendServices.  addSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.create</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.delete</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteSignedUrlKey</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.get</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.list</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  backendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.update</code></li>
<li><code dir="ltr" translate="no">compute.backendServices.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.firewalls.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.firewalls.create</code></li>
<li><code dir="ltr" translate="no">compute.  firewalls.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.firewalls.delete</code></li>
<li><code dir="ltr" translate="no">compute.  firewalls.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.firewalls.get</code></li>
<li><code dir="ltr" translate="no">compute.firewalls.list</code></li>
<li><code dir="ltr" translate="no">compute.  firewalls.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  firewalls.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.firewalls.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.forwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.forwardingRules.create</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.delete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.get</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.list</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  forwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.update</code></li>
<li><code dir="ltr" translate="no">compute.forwardingRules.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscCreate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscDelete</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscSetLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  pscUpdate</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setLabels</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  setTarget</code></li>
<li><code dir="ltr" translate="no">compute.  globalForwardingRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.healthChecks.create</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.delete</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.update</code></li>
<li><code dir="ltr" translate="no">compute.healthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.list</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  httpsHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setCertificateMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setQuicOverride</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  targetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  attach</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  targetTcpProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.urlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.urlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  urlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.urlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></p>
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
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Multi-Cluster Service Discovery permissions

There are no IAM permissions for this service.
