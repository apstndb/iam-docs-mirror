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
<td><h4 id="appengineflex.serviceAgent" class="role-title add-link" data-text="App Engine flexible environment Service Agent" tabindex="-1">App Engine flexible environment Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  appengineflex.serviceAgent</code> )</p>
<p>Can edit and manage App Engine Flexible Environment apps. Includes access to service accounts.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">artifactregistry.  projectsettings.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  create</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  downloadArtifacts</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  get</code></p>
<p><code dir="ltr" translate="no">artifactregistry.  repositories.  uploadArtifacts</code></p>
<p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.create</code></p>
<p><code dir="ltr" translate="no">compute.addresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.addresses.use</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.create</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.delete</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.get</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.create</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.use</code></p>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.disks.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.create</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.delete</code></p>
<p><code dir="ltr" translate="no">compute.forwardingRules.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.create</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.delete</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.use</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  create</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  update</code></p>
<p><code dir="ltr" translate="no">compute.httpsHealthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  httpsHealthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.images.get</code></p>
<p><code dir="ltr" translate="no">compute.images.useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  update</code></p>
<p><code dir="ltr" translate="no">compute.  instanceGroupManagers.  use</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.create</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.get</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.update</code></p>
<p><code dir="ltr" translate="no">compute.instanceGroups.use</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.attachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.detachDisk</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getSerialPortOutput</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.reset</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.start</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.instances.use</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.create</code></p>
<p><code dir="ltr" translate="no">compute.networks.delete</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.networks.useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regions.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.create</code></p>
<p><code dir="ltr" translate="no">compute.routes.delete</code></p>
<p><code dir="ltr" translate="no">compute.routes.get</code></p>
<p><code dir="ltr" translate="no">compute.routes.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">compute.  subnetworks.  useExternalIp</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  create</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  delete</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  setSslCertificates</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.use</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.create</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.delete</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.update</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.use</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.zoneOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.zones.get</code></li>
<li><code dir="ltr" translate="no">compute.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  compositeTypes.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  delete</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  get</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  list</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  deployments.  update</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.manifests.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  manifests.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">deploymentmanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  create</code></p>
<p><code dir="ltr" translate="no">deploymentmanager.  typeProviders.  get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.get</code></p>
<p><code dir="ltr" translate="no">iam.  serviceAccounts.  getAccessToken</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signBlob</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.signJwt</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.delete</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  projects.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.enable</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.setIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.getIamPolicy</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## App Engine flexible environment permissions

There are no IAM permissions for this service.
