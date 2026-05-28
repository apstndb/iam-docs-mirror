---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess
title: Serverless VPC Access roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Serverless VPC Access. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Serverless VPC Access roles

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
<td><h4 id="vpcaccess.admin" class="role-title add-link" data-text="Serverless VPC Access Admin" tabindex="-1">Serverless VPC Access Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p>Full access to all Serverless VPC Access resources</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vpcaccess.connectors.create</code></li>
<li><code dir="ltr" translate="no">vpcaccess.connectors.delete</code></li>
<li><code dir="ltr" translate="no">vpcaccess.connectors.get</code></li>
<li><code dir="ltr" translate="no">vpcaccess.connectors.list</code></li>
<li><code dir="ltr" translate="no">vpcaccess.connectors.update</code></li>
<li><code dir="ltr" translate="no">vpcaccess.connectors.use</code></li>
<li><code dir="ltr" translate="no">vpcaccess.locations.list</code></li>
<li><code dir="ltr" translate="no">vpcaccess.operations.get</code></li>
<li><code dir="ltr" translate="no">vpcaccess.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vpcaccess.user" class="role-title add-link" data-text="Serverless VPC Access User" tabindex="-1">Serverless VPC Access User</h4>
<p>( <code dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p>User of Serverless VPC Access connectors</p></td>
<td><p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.use</code></p>
<p><code dir="ltr" translate="no">vpcaccess.locations.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vpcaccess.operations.get</code></li>
<li><code dir="ltr" translate="no">vpcaccess.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vpcaccess.viewer" class="role-title add-link" data-text="Serverless VPC Access Viewer" tabindex="-1">Serverless VPC Access Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p>Viewer of all Serverless VPC Access resources</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.locations.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">vpcaccess.operations.get</code></li>
<li><code dir="ltr" translate="no">vpcaccess.operations.list</code></li>
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
<td><h4 id="vpcaccess.serviceAgent" class="role-title add-link" data-text="Serverless VPC Access Service Agent" tabindex="-1">Serverless VPC Access Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  vpcaccess.serviceAgent</code> )</p>
<p>Can create and manage resources to support serverless application to connect to virtual private cloud.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">billing.accounts.get</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  createInternal</code></p>
<p><code dir="ltr" translate="no">compute.  addresses.  deleteInternal</code></p>
<p><code dir="ltr" translate="no">compute.addresses.get</code></p>
<p><code dir="ltr" translate="no">compute.addresses.list</code></p>
<p><code dir="ltr" translate="no">compute.autoscalers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.autoscalers.create</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.delete</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.get</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.list</code></li>
<li><code dir="ltr" translate="no">compute.autoscalers.update</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.disks.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.create</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.delete</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.get</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.list</code></p>
<p><code dir="ltr" translate="no">compute.firewalls.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.create</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.delete</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.list</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.update</code></p>
<p><code dir="ltr" translate="no">compute.healthChecks.use</code></p>
<p><code dir="ltr" translate="no">compute.  healthChecks.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  create</code></p>
<p><code dir="ltr" translate="no">compute.  httpHealthChecks.  delete</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.get</code></p>
<p><code dir="ltr" translate="no">compute.httpHealthChecks.list</code></p>
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
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  create</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  delete</code></p>
<p><code dir="ltr" translate="no">compute.instanceTemplates.get</code></p>
<p><code dir="ltr" translate="no">compute.  instanceTemplates.  useReadOnly</code></p>
<p><code dir="ltr" translate="no">compute.instances.create</code></p>
<p><code dir="ltr" translate="no">compute.instances.delete</code></p>
<p><code dir="ltr" translate="no">compute.instances.get</code></p>
<p><code dir="ltr" translate="no">compute.  instances.  getGuestAttributes</code></p>
<p><code dir="ltr" translate="no">compute.instances.list</code></p>
<p><code dir="ltr" translate="no">compute.instances.reset</code></p>
<p><code dir="ltr" translate="no">compute.instances.setLabels</code></p>
<p><code dir="ltr" translate="no">compute.instances.setMetadata</code></p>
<p><code dir="ltr" translate="no">compute.instances.setTags</code></p>
<p><code dir="ltr" translate="no">compute.instances.start</code></p>
<p><code dir="ltr" translate="no">compute.instances.stop</code></p>
<p><code dir="ltr" translate="no">compute.instances.use</code></p>
<p><code dir="ltr" translate="no">compute.machineTypes.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.updatePolicy</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.projects.get</code></p>
<p><code dir="ltr" translate="no">compute.  projects.  setCommonInstanceMetadata</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.list</code></p>
<p><code dir="ltr" translate="no">compute.regions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">compute.regions.get</code></li>
<li><code dir="ltr" translate="no">compute.regions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">compute.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
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
<p><code dir="ltr" translate="no">logging.logEntries.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.create</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.delete</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.update</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p></td>
</tr>
</tbody>
</table>

## Serverless VPC Access permissions

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
<td><h4 id="vpcaccess.connectors.create" class="permission-name add-link" data-text="vpcaccess.connectors.create" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vpcaccess.connectors.delete" class="permission-name add-link" data-text="vpcaccess.connectors.delete" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vpcaccess.connectors.get" class="permission-name add-link" data-text="vpcaccess.connectors.get" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.serviceAgent">Data Connectors Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="vpcaccess.connectors.list" class="permission-name add-link" data-text="vpcaccess.connectors.list" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vpcaccess.connectors.update" class="permission-name add-link" data-text="vpcaccess.connectors.update" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vpcaccess.connectors.use" class="permission-name add-link" data-text="vpcaccess.connectors.use" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.connectors.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">Cloud Functions Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.serviceAgent">Data Connectors Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  run.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vpcaccess.locations.list" class="permission-name add-link" data-text="vpcaccess.locations.list" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="vpcaccess.operations.get" class="permission-name add-link" data-text="vpcaccess.operations.get" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="vpcaccess.operations.list" class="permission-name add-link" data-text="vpcaccess.operations.list" tabindex="-1"><code dir="ltr" translate="no">vpcaccess.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
