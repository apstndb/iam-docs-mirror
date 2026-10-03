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
<td>Multi Cluster Ingress Service Agent
<p>( <code>roles/ multiclusteringress.serviceAgent</code> )</p>
<p>Gives the Multi Cluster Ingress service agent access to CloudPlatform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>certificatemanager. certissuanceconfigs. create</code></p>
<p><code>certificatemanager. certissuanceconfigs. delete</code></p>
<p><code>certificatemanager. certissuanceconfigs. get</code></p>
<p><code>certificatemanager. certissuanceconfigs. list</code></p>
<p><code>certificatemanager. certissuanceconfigs. listEffectiveTags</code></p>
<p><code>certificatemanager. certissuanceconfigs. listTagBindings</code></p>
<p><code>certificatemanager. certissuanceconfigs. update</code></p>
<p><code>certificatemanager. certissuanceconfigs. use</code></p>
<p><code>certificatemanager. certmapentries. create</code></p>
<p><code>certificatemanager. certmapentries. delete</code></p>
<p><code>certificatemanager. certmapentries. get</code></p>
<p><code>certificatemanager. certmapentries. list</code></p>
<p><code>certificatemanager. certmapentries. listEffectiveTags</code></p>
<p><code>certificatemanager. certmapentries. listTagBindings</code></p>
<p><code>certificatemanager. certmapentries. update</code></p>
<p><code>certificatemanager. certmaps. create</code></p>
<p><code>certificatemanager. certmaps. delete</code></p>
<p><code>certificatemanager. certmaps. get</code></p>
<p><code>certificatemanager. certmaps. list</code></p>
<p><code>certificatemanager. certmaps. listEffectiveTags</code></p>
<p><code>certificatemanager. certmaps. listTagBindings</code></p>
<p><code>certificatemanager. certmaps. update</code></p>
<p><code>certificatemanager. certmaps. use</code></p>
<p><code>certificatemanager. certs. create</code></p>
<p><code>certificatemanager. certs. delete</code></p>
<p><code>certificatemanager.certs.get</code></p>
<p><code>certificatemanager.certs.list</code></p>
<p><code>certificatemanager. certs. listEffectiveTags</code></p>
<p><code>certificatemanager. certs. listTagBindings</code></p>
<p><code>certificatemanager. certs. update</code></p>
<p><code>certificatemanager.certs.use</code></p>
<p><code>certificatemanager. dnsauthorizations. create</code></p>
<p><code>certificatemanager. dnsauthorizations. delete</code></p>
<p><code>certificatemanager. dnsauthorizations. get</code></p>
<p><code>certificatemanager. dnsauthorizations. list</code></p>
<p><code>certificatemanager. dnsauthorizations. listEffectiveTags</code></p>
<p><code>certificatemanager. dnsauthorizations. listTagBindings</code></p>
<p><code>certificatemanager. dnsauthorizations. update</code></p>
<p><code>certificatemanager. dnsauthorizations. use</code></p>
<p><code>certificatemanager. operations. get</code></p>
<p><code>certificatemanager. trustconfigs. create</code></p>
<p><code>certificatemanager. trustconfigs. delete</code></p>
<p><code>certificatemanager. trustconfigs. get</code></p>
<p><code>certificatemanager. trustconfigs. list</code></p>
<p><code>certificatemanager. trustconfigs. update</code></p>
<p><code>certificatemanager. trustconfigs. use</code></p>
<p><code>compute.addresses.create</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.addresses.useInternal</code></p>
<p><code>compute.backendServices.*</code></p>
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
<p><code>compute.globalAddresses.create</code></p>
<p><code>compute.globalAddresses.delete</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute.globalAddresses.use</code></p>
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
<p><code>compute. networkEndpointGroups. get</code></p>
<p><code>compute. networkEndpointGroups. list</code></p>
<p><code>compute. networkEndpointGroups. use</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute. regionBackendServices.*</code></p>
<ul>
<li><code>compute. regionBackendServices. create</code></li>
<li><code>compute. regionBackendServices. createTagBinding</code></li>
<li><code>compute. regionBackendServices. delete</code></li>
<li><code>compute. regionBackendServices. deleteTagBinding</code></li>
<li><code>compute. regionBackendServices. get</code></li>
<li><code>compute. regionBackendServices. getIamPolicy</code></li>
<li><code>compute. regionBackendServices. list</code></li>
<li><code>compute. regionBackendServices. listEffectiveTags</code></li>
<li><code>compute. regionBackendServices. listTagBindings</code></li>
<li><code>compute. regionBackendServices. setIamPolicy</code></li>
<li><code>compute. regionBackendServices. setSecurityPolicy</code></li>
<li><code>compute. regionBackendServices. update</code></li>
<li><code>compute. regionBackendServices. use</code></li>
</ul>
<p><code>compute.regionHealthChecks.*</code></p>
<ul>
<li><code>compute. regionHealthChecks. create</code></li>
<li><code>compute. regionHealthChecks. createTagBinding</code></li>
<li><code>compute. regionHealthChecks. delete</code></li>
<li><code>compute. regionHealthChecks. deleteTagBinding</code></li>
<li><code>compute.regionHealthChecks.get</code></li>
<li><code>compute. regionHealthChecks. list</code></li>
<li><code>compute. regionHealthChecks. listEffectiveTags</code></li>
<li><code>compute. regionHealthChecks. listTagBindings</code></li>
<li><code>compute. regionHealthChecks. update</code></li>
<li><code>compute.regionHealthChecks.use</code></li>
<li><code>compute. regionHealthChecks. useReadOnly</code></li>
</ul>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute. regionSslCertificates.*</code></p>
<ul>
<li><code>compute. regionSslCertificates. create</code></li>
<li><code>compute. regionSslCertificates. createTagBinding</code></li>
<li><code>compute. regionSslCertificates. delete</code></li>
<li><code>compute. regionSslCertificates. deleteTagBinding</code></li>
<li><code>compute. regionSslCertificates. get</code></li>
<li><code>compute. regionSslCertificates. list</code></li>
<li><code>compute. regionSslCertificates. listEffectiveTags</code></li>
<li><code>compute. regionSslCertificates. listTagBindings</code></li>
</ul>
<p><code>compute.regionSslPolicies.use</code></p>
<p><code>compute. regionTargetHttpProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpProxies. create</code></li>
<li><code>compute. regionTargetHttpProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. delete</code></li>
<li><code>compute. regionTargetHttpProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpProxies. get</code></li>
<li><code>compute. regionTargetHttpProxies. list</code></li>
<li><code>compute. regionTargetHttpProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpProxies. use</code></li>
</ul>
<p><code>compute. regionTargetHttpsProxies.*</code></p>
<ul>
<li><code>compute. regionTargetHttpsProxies. create</code></li>
<li><code>compute. regionTargetHttpsProxies. createTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. delete</code></li>
<li><code>compute. regionTargetHttpsProxies. deleteTagBinding</code></li>
<li><code>compute. regionTargetHttpsProxies. get</code></li>
<li><code>compute. regionTargetHttpsProxies. list</code></li>
<li><code>compute. regionTargetHttpsProxies. listEffectiveTags</code></li>
<li><code>compute. regionTargetHttpsProxies. listTagBindings</code></li>
<li><code>compute. regionTargetHttpsProxies. setSslCertificates</code></li>
<li><code>compute. regionTargetHttpsProxies. setUrlMap</code></li>
<li><code>compute. regionTargetHttpsProxies. update</code></li>
<li><code>compute. regionTargetHttpsProxies. use</code></li>
</ul>
<p><code>compute. regionTargetTcpProxies. attach</code></p>
<p><code>compute. regionTargetTcpProxies. create</code></p>
<p><code>compute. regionTargetTcpProxies. delete</code></p>
<p><code>compute. regionTargetTcpProxies. get</code></p>
<p><code>compute. regionTargetTcpProxies. list</code></p>
<p><code>compute. regionTargetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. regionTargetTcpProxies. listTagBindings</code></p>
<p><code>compute. regionTargetTcpProxies. use</code></p>
<p><code>compute.regionUrlMaps.*</code></p>
<ul>
<li><code>compute.regionUrlMaps.create</code></li>
<li><code>compute. regionUrlMaps. createTagBinding</code></li>
<li><code>compute.regionUrlMaps.delete</code></li>
<li><code>compute. regionUrlMaps. deleteTagBinding</code></li>
<li><code>compute.regionUrlMaps.get</code></li>
<li><code>compute. regionUrlMaps. invalidateCache</code></li>
<li><code>compute.regionUrlMaps.list</code></li>
<li><code>compute. regionUrlMaps. listEffectiveTags</code></li>
<li><code>compute. regionUrlMaps. listTagBindings</code></li>
<li><code>compute.regionUrlMaps.update</code></li>
<li><code>compute.regionUrlMaps.use</code></li>
<li><code>compute.regionUrlMaps.validate</code></li>
</ul>
<p><code>compute.securityPolicies.use</code></p>
<p><code>compute.sslCertificates.*</code></p>
<ul>
<li><code>compute.sslCertificates.create</code></li>
<li><code>compute. sslCertificates. createTagBinding</code></li>
<li><code>compute.sslCertificates.delete</code></li>
<li><code>compute. sslCertificates. deleteTagBinding</code></li>
<li><code>compute.sslCertificates.get</code></li>
<li><code>compute.sslCertificates.list</code></li>
<li><code>compute. sslCertificates. listEffectiveTags</code></li>
<li><code>compute. sslCertificates. listTagBindings</code></li>
</ul>
<p><code>compute.sslPolicies.use</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
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
<p><code>compute. targetTcpProxies. attach</code></p>
<p><code>compute. targetTcpProxies. create</code></p>
<p><code>compute. targetTcpProxies. delete</code></p>
<p><code>compute.targetTcpProxies.get</code></p>
<p><code>compute.targetTcpProxies.list</code></p>
<p><code>compute. targetTcpProxies. listEffectiveTags</code></p>
<p><code>compute. targetTcpProxies. listTagBindings</code></p>
<p><code>compute. targetTcpProxies. update</code></p>
<p><code>compute.targetTcpProxies.use</code></p>
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
<p><code>compute.zoneOperations.get</code></p>
<p><code>container.backendConfigs.*</code></p>
<ul>
<li><code>container. backendConfigs. create</code></li>
<li><code>container. backendConfigs. delete</code></li>
<li><code>container.backendConfigs.get</code></li>
<li><code>container.backendConfigs.list</code></li>
<li><code>container. backendConfigs. update</code></li>
</ul>
<p><code>container.clusters.get</code></p>
<p><code>container. customResourceDefinitions. create</code></p>
<p><code>container. customResourceDefinitions. delete</code></p>
<p><code>container. customResourceDefinitions. get</code></p>
<p><code>container. customResourceDefinitions. list</code></p>
<p><code>container. customResourceDefinitions. update</code></p>
<p><code>container.deployments.*</code></p>
<ul>
<li><code>container.deployments.create</code></li>
<li><code>container.deployments.delete</code></li>
<li><code>container.deployments.get</code></li>
<li><code>container.deployments.getScale</code></li>
<li><code>container. deployments. getStatus</code></li>
<li><code>container.deployments.list</code></li>
<li><code>container.deployments.rollback</code></li>
<li><code>container.deployments.update</code></li>
<li><code>container. deployments. updateScale</code></li>
<li><code>container. deployments. updateStatus</code></li>
</ul>
<p><code>container.events.create</code></p>
<p><code>container.events.update</code></p>
<p><code>container.frontendConfigs.*</code></p>
<ul>
<li><code>container. frontendConfigs. create</code></li>
<li><code>container. frontendConfigs. delete</code></li>
<li><code>container.frontendConfigs.get</code></li>
<li><code>container.frontendConfigs.list</code></li>
<li><code>container. frontendConfigs. update</code></li>
</ul>
<p><code>container.namespaces.list</code></p>
<p><code>container.secrets.get</code></p>
<p><code>container.secrets.list</code></p>
<p><code>container.services.*</code></p>
<ul>
<li><code>container.services.create</code></li>
<li><code>container.services.delete</code></li>
<li><code>container.services.get</code></li>
<li><code>container.services.getStatus</code></li>
<li><code>container.services.list</code></li>
<li><code>container.services.proxy</code></li>
<li><code>container.services.update</code></li>
<li><code>container. services. updateStatus</code></li>
</ul>
<p><code>container.thirdPartyObjects.*</code></p>
<ul>
<li><code>container. thirdPartyObjects. create</code></li>
<li><code>container. thirdPartyObjects. delete</code></li>
<li><code>container. thirdPartyObjects. get</code></li>
<li><code>container. thirdPartyObjects. list</code></li>
<li><code>container. thirdPartyObjects. update</code></li>
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
<p><code>networksecurity. backendAuthenticationConfigs.*</code></p>
<ul>
<li><code>networksecurity. backendAuthenticationConfigs. create</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. delete</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. get</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. list</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. update</code></li>
<li><code>networksecurity. backendAuthenticationConfigs. use</code></li>
</ul>
<p><code>networksecurity.operations.get</code></p>
<p><code>networksecurity. serverTlsPolicies. create</code></p>
<p><code>networksecurity. serverTlsPolicies. delete</code></p>
<p><code>networksecurity. serverTlsPolicies. get</code></p>
<p><code>networksecurity. serverTlsPolicies. list</code></p>
<p><code>networksecurity. serverTlsPolicies. update</code></p>
<p><code>networksecurity. serverTlsPolicies. use</code></p>
<p><code>networkservices. lbEdgeExtensions.*</code></p>
<ul>
<li><code>networkservices. lbEdgeExtensions. create</code></li>
<li><code>networkservices. lbEdgeExtensions. delete</code></li>
<li><code>networkservices. lbEdgeExtensions. get</code></li>
<li><code>networkservices. lbEdgeExtensions. list</code></li>
<li><code>networkservices. lbEdgeExtensions. update</code></li>
</ul>
<p><code>networkservices. lbRouteExtensions.*</code></p>
<ul>
<li><code>networkservices. lbRouteExtensions. create</code></li>
<li><code>networkservices. lbRouteExtensions. delete</code></li>
<li><code>networkservices. lbRouteExtensions. get</code></li>
<li><code>networkservices. lbRouteExtensions. list</code></li>
<li><code>networkservices. lbRouteExtensions. update</code></li>
</ul>
<p><code>networkservices. lbTrafficExtensions.*</code></p>
<ul>
<li><code>networkservices. lbTrafficExtensions. create</code></li>
<li><code>networkservices. lbTrafficExtensions. delete</code></li>
<li><code>networkservices. lbTrafficExtensions. get</code></li>
<li><code>networkservices. lbTrafficExtensions. list</code></li>
<li><code>networkservices. lbTrafficExtensions. update</code></li>
</ul>
<p><code>networkservices.operations.get</code></p>
<p><code>networkservices. serviceLbPolicies.*</code></p>
<ul>
<li><code>networkservices. serviceLbPolicies. create</code></li>
<li><code>networkservices. serviceLbPolicies. delete</code></li>
<li><code>networkservices. serviceLbPolicies. get</code></li>
<li><code>networkservices. serviceLbPolicies. list</code></li>
<li><code>networkservices. serviceLbPolicies. update</code></li>
</ul>
<p><code>networkservices.tlsRoutes.*</code></p>
<ul>
<li><code>networkservices. tlsRoutes. create</code></li>
<li><code>networkservices. tlsRoutes. delete</code></li>
<li><code>networkservices.tlsRoutes.get</code></li>
<li><code>networkservices.tlsRoutes.list</code></li>
<li><code>networkservices. tlsRoutes. update</code></li>
</ul>
<p><code>networkservices.wasmPlugins.*</code></p>
<ul>
<li><code>networkservices. wasmPlugins. create</code></li>
<li><code>networkservices. wasmPlugins. delete</code></li>
<li><code>networkservices. wasmPlugins. get</code></li>
<li><code>networkservices. wasmPlugins. list</code></li>
<li><code>networkservices. wasmPlugins. update</code></li>
<li><code>networkservices. wasmPlugins. use</code></li>
</ul>
<p><code>serviceusage. consumerpolicy. analyze</code></p>
<p><code>serviceusage. consumerpolicy. get</code></p>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.get</code></p>
<p><code>serviceusage.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>serviceusage.values.test</code></p></td>
</tr>
</tbody>
</table>

## Multi-Cluster Ingress permissions

There are no IAM permissions for this service.
