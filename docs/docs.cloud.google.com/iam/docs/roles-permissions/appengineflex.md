---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/appengineflex
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/appengineflex
title: App Engine flexible environment roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for App Engine flexible environment. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## App Engine flexible environment roles

App Engine flexible environment offers the following service agent roles. Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>App Engine flexible environment Service Agent
<p>( <code>roles/ appengineflex.serviceAgent</code> )</p>
<p>Can edit and manage App Engine Flexible Environment apps. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. projectsettings. get</code></p>
<p><code>artifactregistry. repositories. create</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p>
<p><code>artifactregistry. repositories. get</code></p>
<p><code>artifactregistry. repositories. uploadArtifacts</code></p>
<p><code>billing.accounts.get</code></p>
<p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>compute.addresses.create</code></p>
<p><code>compute.addresses.delete</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.addresses.use</code></p>
<p><code>compute.autoscalers.create</code></p>
<p><code>compute.autoscalers.delete</code></p>
<p><code>compute.autoscalers.get</code></p>
<p><code>compute.autoscalers.update</code></p>
<p><code>compute.backendServices.create</code></p>
<p><code>compute.backendServices.delete</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.backendServices.update</code></p>
<p><code>compute.backendServices.use</code></p>
<p><code>compute.disks.create</code></p>
<p><code>compute.disks.list</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute.forwardingRules.create</code></p>
<p><code>compute.forwardingRules.delete</code></p>
<p><code>compute.forwardingRules.get</code></p>
<p><code>compute.globalAddresses.create</code></p>
<p><code>compute.globalAddresses.delete</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.use</code></p>
<p><code>compute. globalForwardingRules. create</code></p>
<p><code>compute. globalForwardingRules. delete</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute. healthChecks. useReadOnly</code></p>
<p><code>compute. httpHealthChecks. create</code></p>
<p><code>compute. httpHealthChecks. delete</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.use</code></p>
<p><code>compute. httpHealthChecks. useReadOnly</code></p>
<p><code>compute. httpsHealthChecks. create</code></p>
<p><code>compute. httpsHealthChecks. delete</code></p>
<p><code>compute.httpsHealthChecks.get</code></p>
<p><code>compute. httpsHealthChecks. update</code></p>
<p><code>compute.httpsHealthChecks.use</code></p>
<p><code>compute. httpsHealthChecks. useReadOnly</code></p>
<p><code>compute.images.get</code></p>
<p><code>compute.images.useReadOnly</code></p>
<p><code>compute. instanceGroupManagers. create</code></p>
<p><code>compute. instanceGroupManagers. delete</code></p>
<p><code>compute. instanceGroupManagers. get</code></p>
<p><code>compute. instanceGroupManagers. update</code></p>
<p><code>compute. instanceGroupManagers. use</code></p>
<p><code>compute.instanceGroups.create</code></p>
<p><code>compute.instanceGroups.delete</code></p>
<p><code>compute.instanceGroups.get</code></p>
<p><code>compute.instanceGroups.update</code></p>
<p><code>compute.instanceGroups.use</code></p>
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute.instances.attachDisk</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.detachDisk</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute. instances. getSerialPortOutput</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.instances.reset</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute.machineTypes.get</code></p>
<p><code>compute.networks.create</code></p>
<p><code>compute.networks.delete</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.networks.useExternalIp</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute. regionBackendServices. create</code></p>
<p><code>compute. regionBackendServices. delete</code></p>
<p><code>compute. regionBackendServices. get</code></p>
<p><code>compute. regionBackendServices. list</code></p>
<p><code>compute. regionBackendServices. update</code></p>
<p><code>compute. regionBackendServices. use</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regions.get</code></p>
<p><code>compute.routes.create</code></p>
<p><code>compute.routes.delete</code></p>
<p><code>compute.routes.get</code></p>
<p><code>compute.routes.list</code></p>
<p><code>compute.subnetworks.delete</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.use</code></p>
<p><code>compute. subnetworks. useExternalIp</code></p>
<p><code>compute. targetHttpProxies. create</code></p>
<p><code>compute. targetHttpProxies. delete</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.use</code></p>
<p><code>compute. targetHttpsProxies. create</code></p>
<p><code>compute. targetHttpsProxies. delete</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. setSslCertificates</code></p>
<p><code>compute.targetHttpsProxies.use</code></p>
<p><code>compute.urlMaps.create</code></p>
<p><code>compute.urlMaps.delete</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.update</code></p>
<p><code>compute.urlMaps.use</code></p>
<p><code>compute.zoneOperations.get</code></p>
<p><code>compute.zoneOperations.list</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>deploymentmanager. compositeTypes. get</code></p>
<p><code>deploymentmanager. deployments. create</code></p>
<p><code>deploymentmanager. deployments. delete</code></p>
<p><code>deploymentmanager. deployments. get</code></p>
<p><code>deploymentmanager. deployments. list</code></p>
<p><code>deploymentmanager. deployments. update</code></p>
<p><code>deploymentmanager.manifests.*</code></p>
<ul>
<li><code>deploymentmanager. manifests. get</code></li>
<li><code>deploymentmanager. manifests. list</code></li>
</ul>
<p><code>deploymentmanager.operations.*</code></p>
<ul>
<li><code>deploymentmanager. operations. get</code></li>
<li><code>deploymentmanager. operations. list</code></li>
</ul>
<p><code>deploymentmanager. typeProviders. create</code></p>
<p><code>deploymentmanager. typeProviders. get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>iam.serviceAccounts.get</code></p>
<p><code>iam. serviceAccounts. getAccessToken</code></p>
<p><code>iam.serviceAccounts.signBlob</code></p>
<p><code>iam.serviceAccounts.signJwt</code></p>
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logMetrics.create</code></p>
<p><code>logging.logMetrics.delete</code></p>
<p><code>logging.logMetrics.get</code></p>
<p><code>logging.logMetrics.update</code></p>
<p><code>resourcemanager. organizations. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager. projects. getIamPolicy</code></p>
<p><code>resourcemanager. projects. setIamPolicy</code></p>
<p><code>serviceusage.consumerpolicy.*</code></p>
<ul>
<li><code>serviceusage. consumerpolicy. analyze</code></li>
<li><code>serviceusage. consumerpolicy. get</code></li>
<li><code>serviceusage. consumerpolicy. update</code></li>
</ul>
<p><code>serviceusage. effectivepolicy. get</code></p>
<p><code>serviceusage.groups.*</code></p>
<ul>
<li><code>serviceusage.groups.list</code></li>
<li><code>serviceusage. groups. listExpandedMembers</code></li>
<li><code>serviceusage. groups. listMembers</code></li>
</ul>
<p><code>serviceusage.services.enable</code></p>
<p><code>serviceusage.values.test</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.buckets.getIamPolicy</code></p>
<p><code>storage.buckets.setIamPolicy</code></p>
<p><code>storage.buckets.update</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.getIamPolicy</code></p>
<p><code>storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## App Engine flexible environment permissions

There are no IAM permissions for this service.
