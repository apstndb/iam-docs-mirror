---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/multiclusteringress
title: Multi-Cluster Ingress roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Multi-Cluster Ingress. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Multi-Cluster Ingress roles

Multi-Cluster Ingress offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td><h4 id="multiclusteringress.serviceAgent" class="role-title add-link" data-text="Multi Cluster Ingress Service Agent" tabindex="-1">Multi Cluster Ingress Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  multiclusteringress.serviceAgent</code> )</p>
<p>Gives the Multi Cluster Ingress service agent access to CloudPlatform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certissuanceconfigs.  use</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmapentries.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certmaps.  use</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  certs.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.certs.use</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  dnsauthorizations.  use</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  create</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  delete</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  get</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  list</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  update</code></p>
<p><code dir="ltr" translate="no">certificatemanager.  trustconfigs.  use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.addresses.useInternal</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.*</code></p>
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
<p><code dir="ltr" translate="no">compute.globalAddresses.create</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.use</code></p>
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
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  setSecurityPolicy</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionHealthChecks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  update</code></li>
<li><code dir="ltr" translate="no">compute.regionHealthChecks.use</code></li>
<li><code dir="ltr" translate="no">compute.  regionHealthChecks.  useReadOnly</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.  regionSslCertificates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionSslCertificates.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.regionSslPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  create</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  get</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  list</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setSslCertificates</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  setUrlMap</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  update</code></li>
<li><code dir="ltr" translate="no">compute.  regionTargetHttpsProxies.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  attach</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  regionTargetTcpProxies.  use</code></p>
<p><code dir="ltr" translate="no">compute.regionUrlMaps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.create</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.delete</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.get</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  invalidateCache</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.list</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  regionUrlMaps.  listTagBindings</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.update</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.use</code></li>
<li><code dir="ltr" translate="no">compute.regionUrlMaps.validate</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.securityPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.sslCertificates.create</code></li>
<li><code dir="ltr" translate="no">compute.  sslCertificates.  createTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslCertificates.delete</code></li>
<li><code dir="ltr" translate="no">compute.  sslCertificates.  deleteTagBinding</code></li>
<li><code dir="ltr" translate="no">compute.sslCertificates.get</code></li>
<li><code dir="ltr" translate="no">compute.sslCertificates.list</code></li>
<li><code dir="ltr" translate="no">compute.  sslCertificates.  listEffectiveTags</code></li>
<li><code dir="ltr" translate="no">compute.  sslCertificates.  listTagBindings</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.sslPolicies.use</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
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
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  attach</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listEffectiveTags</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  listTagBindings</code></p>
<p><code dir="ltr" translate="no">compute.  targetTcpProxies.  update</code></p>
<p><code dir="ltr" translate="no">compute.targetTcpProxies.use</code></p>
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
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">container.backendConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  backendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.backendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  backendConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  delete</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  update</code></p>
<p><code dir="ltr" translate="no">container.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.deployments.create</code></li>
<li><code dir="ltr" translate="no">container.deployments.delete</code></li>
<li><code dir="ltr" translate="no">container.deployments.get</code></li>
<li><code dir="ltr" translate="no">container.deployments.getScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  getStatus</code></li>
<li><code dir="ltr" translate="no">container.deployments.list</code></li>
<li><code dir="ltr" translate="no">container.deployments.rollback</code></li>
<li><code dir="ltr" translate="no">container.deployments.update</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateScale</code></li>
<li><code dir="ltr" translate="no">container.  deployments.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.events.create</code></p>
<p><code dir="ltr" translate="no">container.events.update</code></p>
<p><code dir="ltr" translate="no">container.frontendConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  create</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.get</code></li>
<li><code dir="ltr" translate="no">container.frontendConfigs.list</code></li>
<li><code dir="ltr" translate="no">container.  frontendConfigs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">container.namespaces.list</code></p>
<p><code dir="ltr" translate="no">container.secrets.get</code></p>
<p><code dir="ltr" translate="no">container.secrets.list</code></p>
<p><code dir="ltr" translate="no">container.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.services.create</code></li>
<li><code dir="ltr" translate="no">container.services.delete</code></li>
<li><code dir="ltr" translate="no">container.services.get</code></li>
<li><code dir="ltr" translate="no">container.services.getStatus</code></li>
<li><code dir="ltr" translate="no">container.services.list</code></li>
<li><code dir="ltr" translate="no">container.services.proxy</code></li>
<li><code dir="ltr" translate="no">container.services.update</code></li>
<li><code dir="ltr" translate="no">container.  services.  updateStatus</code></li>
</ul>
<p><code dir="ltr" translate="no">container.thirdPartyObjects.*</code></p>
<ul>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  create</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  delete</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  get</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  list</code></li>
<li><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></li>
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
<p><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  create</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  get</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  list</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  update</code></li>
<li><code dir="ltr" translate="no">networksecurity.  backendAuthenticationConfigs.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">networksecurity.operations.get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  create</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  delete</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  get</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  list</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  update</code></p>
<p><code dir="ltr" translate="no">networksecurity.  serverTlsPolicies.  use</code></p>
<p><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbEdgeExtensions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbRouteExtensions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  lbTrafficExtensions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">networkservices.operations.get</code></p>
<p><code dir="ltr" translate="no">networkservices.wasmPlugins.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  create</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  get</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  list</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  update</code></li>
<li><code dir="ltr" translate="no">networkservices.  wasmPlugins.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  analyze</code></p>
<p><code dir="ltr" translate="no">serviceusage.  consumerpolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.  effectivepolicy.  get</code></p>
<p><code dir="ltr" translate="no">serviceusage.groups.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceusage.groups.list</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listExpandedMembers</code></li>
<li><code dir="ltr" translate="no">serviceusage.  groups.  listMembers</code></li>
</ul>
<p><code dir="ltr" translate="no">serviceusage.services.get</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Multi-Cluster Ingress permissions

There are no IAM permissions for this service.
