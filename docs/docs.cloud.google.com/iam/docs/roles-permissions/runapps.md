---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/runapps
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/runapps
title: Serverless Integrations roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Serverless Integrations. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Serverless Integrations roles

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
<td>Runapps Admin <sup>Beta</sup>
<p>( <code>roles/ runapps.admin</code> )</p>
<p>Admin role for runapps</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>runapps.*</code></p>
<ul>
<li><code>runapps.applications.create</code></li>
<li><code>runapps.applications.delete</code></li>
<li><code>runapps.applications.get</code></li>
<li><code>runapps.applications.getStatus</code></li>
<li><code>runapps.applications.list</code></li>
<li><code>runapps.applications.update</code></li>
<li><code>runapps.deployments.create</code></li>
<li><code>runapps.deployments.get</code></li>
<li><code>runapps.deployments.list</code></li>
<li><code>runapps.locations.get</code></li>
<li><code>runapps.locations.list</code></li>
<li><code>runapps.operations.cancel</code></li>
<li><code>runapps.operations.delete</code></li>
<li><code>runapps.operations.get</code></li>
<li><code>runapps.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Serverless Integrations Viewer <sup>Beta</sup>
<p>( <code>roles/ runapps.viewer</code> )</p>
<p>Read-only access to Serverless Integrations resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>runapps.applications.get</code></p>
<p><code>runapps.applications.getStatus</code></p>
<p><code>runapps.applications.list</code></p>
<p><code>runapps.deployments.get</code></p>
<p><code>runapps.deployments.list</code></p>
<p><code>runapps.locations.*</code></p>
<ul>
<li><code>runapps.locations.get</code></li>
<li><code>runapps.locations.list</code></li>
</ul>
<p><code>runapps.operations.get</code></p>
<p><code>runapps.operations.list</code></p></td>
</tr>
<tr class="odd">
<td>Serverless Integrations Developer <sup>Beta</sup>
<p>( <code>roles/ runapps.developer</code> )</p>
<p>Access to create and change Serverless Integrations and their configuration.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>runapps.applications.*</code></p>
<ul>
<li><code>runapps.applications.create</code></li>
<li><code>runapps.applications.delete</code></li>
<li><code>runapps.applications.get</code></li>
<li><code>runapps.applications.getStatus</code></li>
<li><code>runapps.applications.list</code></li>
<li><code>runapps.applications.update</code></li>
</ul>
<p><code>runapps.deployments.get</code></p>
<p><code>runapps.deployments.list</code></p>
<p><code>runapps.locations.*</code></p>
<ul>
<li><code>runapps.locations.get</code></li>
<li><code>runapps.locations.list</code></li>
</ul>
<p><code>runapps.operations.*</code></p>
<ul>
<li><code>runapps.operations.cancel</code></li>
<li><code>runapps.operations.delete</code></li>
<li><code>runapps.operations.get</code></li>
<li><code>runapps.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Serverless Integrations Operator <sup>Beta</sup>
<p>( <code>roles/ runapps.operator</code> )</p>
<p>Access to deploy Serverless Integrations.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>runapps.applications.get</code></p>
<p><code>runapps.applications.getStatus</code></p>
<p><code>runapps.applications.list</code></p>
<p><code>runapps.deployments.*</code></p>
<ul>
<li><code>runapps.deployments.create</code></li>
<li><code>runapps.deployments.get</code></li>
<li><code>runapps.deployments.list</code></li>
</ul>
<p><code>runapps.locations.*</code></p>
<ul>
<li><code>runapps.locations.get</code></li>
<li><code>runapps.locations.list</code></li>
</ul>
<p><code>runapps.operations.*</code></p>
<ul>
<li><code>runapps.operations.cancel</code></li>
<li><code>runapps.operations.delete</code></li>
<li><code>runapps.operations.get</code></li>
<li><code>runapps.operations.list</code></li>
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
<td>Serverless Integrations Service Agent
<p>( <code>roles/ runapps.serviceAgent</code> )</p>
<p>Gives Serverless Integrations Service Account access to customer project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudbuild.builds.create</code></p>
<p><code>cloudbuild.builds.get</code></p>
<p><code>cloudsql.databases.get</code></p>
<p><code>cloudsql.instances.get</code></p>
<p><code>cloudsql.users.get</code></p>
<p><code>compute.backendServices.get</code></p>
<p><code>compute.backendServices.list</code></p>
<p><code>compute.globalAddresses.get</code></p>
<p><code>compute.globalAddresses.list</code></p>
<p><code>compute. globalForwardingRules. get</code></p>
<p><code>compute. globalForwardingRules. list</code></p>
<p><code>compute.networks.get</code></p>
<p><code>compute.networks.list</code></p>
<p><code>compute. regionNetworkEndpointGroups. get</code></p>
<p><code>compute. regionNetworkEndpointGroups. list</code></p>
<p><code>compute.sslCertificates.get</code></p>
<p><code>compute.sslCertificates.list</code></p>
<p><code>compute.targetHttpProxies.get</code></p>
<p><code>compute.targetHttpProxies.list</code></p>
<p><code>compute.targetHttpsProxies.get</code></p>
<p><code>compute. targetHttpsProxies. list</code></p>
<p><code>compute.urlMaps.get</code></p>
<p><code>compute.urlMaps.list</code></p>
<p><code>firebasehosting.sites.get</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>redis.instances.get</code></p>
<p><code>redis.instances.list</code></p>
<p><code>run.jobs.get</code></p>
<p><code>run.jobs.list</code></p>
<p><code>run.services.get</code></p>
<p><code>run.services.list</code></p>
<p><code>serviceusage.services.use</code></p>
<p><code>storage.buckets.create</code></p>
<p><code>storage.buckets.delete</code></p>
<p><code>storage.buckets.get</code></p>
<p><code>storage.objects.create</code></p>
<p><code>storage.objects.delete</code></p>
<p><code>storage.objects.get</code></p>
<p><code>storage.objects.list</code></p>
<p><code>vpcaccess.connectors.get</code></p>
<p><code>vpcaccess.connectors.list</code></p></td>
</tr>
</tbody>
</table>

## Serverless Integrations permissions

| Permission                       | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `runapps.applications.create`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `runapps.applications.delete`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `runapps.applications.get`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `runapps.applications.getStatus` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `runapps.applications.list`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` ) |
| `runapps.applications.update`    | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| `runapps.deployments.create`     | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| `runapps.deployments.get`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `runapps.deployments.list`       | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` ) |
| `runapps.locations.get`          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `runapps.locations.list`         | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` ) |
| `runapps.operations.cancel`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `runapps.operations.delete`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| `runapps.operations.get`         | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `runapps.operations.list`        | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Runapps Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin) ( `roles/ runapps.admin` ) [Serverless Integrations Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer) ( `roles/ runapps.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Serverless Integrations Developer](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer) ( `roles/ runapps.developer` ) [Serverless Integrations Operator](https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator) ( `roles/ runapps.operator` ) |
