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
<td>Serverless VPC Access Admin
<p>( <code>roles/ vpcaccess.admin</code> )</p>
<p>Full access to all Serverless VPC Access resources</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vpcaccess.*</code></p>
<ul>
<li><code>vpcaccess.connectors.create</code></li>
<li><code>vpcaccess.connectors.delete</code></li>
<li><code>vpcaccess.connectors.get</code></li>
<li><code>vpcaccess.connectors.list</code></li>
<li><code>vpcaccess.connectors.update</code></li>
<li><code>vpcaccess.locations.list</code></li>
<li><code>vpcaccess.operations.get</code></li>
<li><code>vpcaccess.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Serverless VPC Access User
<p>( <code>roles/ vpcaccess.user</code> )</p>
<p>User of Serverless VPC Access connectors</p></td>
<td><p><code>compute.networks.access</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vpcaccess.connectors.get</code></p>
<p><code>vpcaccess.connectors.list</code></p>
<p><code>vpcaccess.locations.list</code></p>
<p><code>vpcaccess.operations.*</code></p>
<ul>
<li><code>vpcaccess.operations.get</code></li>
<li><code>vpcaccess.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Serverless VPC Access Viewer
<p>( <code>roles/ vpcaccess.viewer</code> )</p>
<p>Viewer of all Serverless VPC Access resources</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>vpcaccess.connectors.get</code></p>
<p><code>vpcaccess.connectors.list</code></p>
<p><code>vpcaccess.locations.list</code></p>
<p><code>vpcaccess.operations.*</code></p>
<ul>
<li><code>vpcaccess.operations.get</code></li>
<li><code>vpcaccess.operations.list</code></li>
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
<td>Serverless VPC Access Service Agent
<p>( <code>roles/ vpcaccess.serviceAgent</code> )</p>
<p>Can create and manage resources to support serverless application to connect to virtual private cloud.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>billing.accounts.get</code></p>
<p><code>compute. addresses. createInternal</code></p>
<p><code>compute. addresses. deleteInternal</code></p>
<p><code>compute.addresses.get</code></p>
<p><code>compute.addresses.list</code></p>
<p><code>compute.autoscalers.*</code></p>
<ul>
<li><code>compute.autoscalers.create</code></li>
<li><code>compute.autoscalers.delete</code></li>
<li><code>compute.autoscalers.get</code></li>
<li><code>compute.autoscalers.list</code></li>
<li><code>compute.autoscalers.update</code></li>
</ul>
<p><code>compute.disks.create</code></p>
<p><code>compute.firewalls.create</code></p>
<p><code>compute.firewalls.delete</code></p>
<p><code>compute.firewalls.get</code></p>
<p><code>compute.firewalls.list</code></p>
<p><code>compute.firewalls.update</code></p>
<p><code>compute.healthChecks.create</code></p>
<p><code>compute.healthChecks.delete</code></p>
<p><code>compute.healthChecks.get</code></p>
<p><code>compute.healthChecks.list</code></p>
<p><code>compute.healthChecks.update</code></p>
<p><code>compute.healthChecks.use</code></p>
<p><code>compute. healthChecks. useReadOnly</code></p>
<p><code>compute. httpHealthChecks. create</code></p>
<p><code>compute. httpHealthChecks. delete</code></p>
<p><code>compute.httpHealthChecks.get</code></p>
<p><code>compute.httpHealthChecks.list</code></p>
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
<p><code>compute. instanceTemplates. create</code></p>
<p><code>compute. instanceTemplates. delete</code></p>
<p><code>compute.instanceTemplates.get</code></p>
<p><code>compute. instanceTemplates. useReadOnly</code></p>
<p><code>compute.instances.create</code></p>
<p><code>compute.instances.delete</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.instances.reset</code></p>
<p><code>compute.instances.setLabels</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute.instances.setTags</code></p>
<p><code>compute.instances.start</code></p>
<p><code>compute.instances.stop</code></p>
<p><code>compute.instances.use</code></p>
<p><code>compute.machineTypes.get</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.updatePolicy</code></p>
<p><code>compute.networks.use</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute.regionOperations.get</code></p>
<p><code>compute.regionOperations.list</code></p>
<p><code>compute.regions.*</code></p>
<ul>
<li><code>compute.regions.get</code></li>
<li><code>compute.regions.list</code></li>
</ul>
<p><code>compute.subnetworks.create</code></p>
<p><code>compute.subnetworks.delete</code></p>
<p><code>compute.subnetworks.get</code></p>
<p><code>compute.subnetworks.list</code></p>
<p><code>compute.subnetworks.use</code></p>
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
<p><code>logging.logEntries.create</code></p>
<p><code>logging.logMetrics.create</code></p>
<p><code>logging.logMetrics.delete</code></p>
<p><code>logging.logMetrics.get</code></p>
<p><code>logging.logMetrics.update</code></p>
<p><code>resourcemanager.projects.get</code></p></td>
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
<td><code>vpcaccess.connectors.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vpcaccess.connectors.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vpcaccess.connectors.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudfunctions#cloudfunctions.serviceAgent">(Deprecated) Cloud Functions Service Agent</a> ( <code>roles/ cloudfunctions.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.serviceAgent">Data Connectors Service Agent</a> ( <code>roles/ dataconnectors.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/run#run.serviceAgent">Cloud Run Service Agent</a> ( <code>roles/ run.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vpcaccess.connectors.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.serviceAgent">Serverless Integrations Service Agent</a> ( <code>roles/ runapps.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>vpcaccess.connectors.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>vpcaccess.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>vpcaccess.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>vpcaccess.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.admin">Serverless VPC Access Admin</a> ( <code>roles/ vpcaccess.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.user">Serverless VPC Access User</a> ( <code>roles/ vpcaccess.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/vpcaccess#vpcaccess.viewer">Serverless VPC Access Viewer</a> ( <code>roles/ vpcaccess.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
