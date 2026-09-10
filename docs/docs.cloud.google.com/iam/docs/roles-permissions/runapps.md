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
<td><h4 id="runapps.admin" class="role-title add-link" data-text="Runapps Admin Beta" tabindex="-1">Runapps Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p>Admin role for runapps</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runapps.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.applications.create</code></li>
<li><code dir="ltr" translate="no">runapps.applications.delete</code></li>
<li><code dir="ltr" translate="no">runapps.applications.get</code></li>
<li><code dir="ltr" translate="no">runapps.applications.getStatus</code></li>
<li><code dir="ltr" translate="no">runapps.applications.list</code></li>
<li><code dir="ltr" translate="no">runapps.applications.update</code></li>
<li><code dir="ltr" translate="no">runapps.deployments.create</code></li>
<li><code dir="ltr" translate="no">runapps.deployments.get</code></li>
<li><code dir="ltr" translate="no">runapps.deployments.list</code></li>
<li><code dir="ltr" translate="no">runapps.locations.get</code></li>
<li><code dir="ltr" translate="no">runapps.locations.list</code></li>
<li><code dir="ltr" translate="no">runapps.operations.cancel</code></li>
<li><code dir="ltr" translate="no">runapps.operations.delete</code></li>
<li><code dir="ltr" translate="no">runapps.operations.get</code></li>
<li><code dir="ltr" translate="no">runapps.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runapps.viewer" class="role-title add-link" data-text="Serverless Integrations Viewer Beta" tabindex="-1">Serverless Integrations Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p>Read-only access to Serverless Integrations resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runapps.applications.get</code></p>
<p><code dir="ltr" translate="no">runapps.applications.getStatus</code></p>
<p><code dir="ltr" translate="no">runapps.applications.list</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.get</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.list</code></p>
<p><code dir="ltr" translate="no">runapps.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.locations.get</code></li>
<li><code dir="ltr" translate="no">runapps.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runapps.operations.get</code></p>
<p><code dir="ltr" translate="no">runapps.operations.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.developer" class="role-title add-link" data-text="Serverless Integrations Developer Beta" tabindex="-1">Serverless Integrations Developer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p>Access to create and change Serverless Integrations and their configuration.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runapps.applications.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.applications.create</code></li>
<li><code dir="ltr" translate="no">runapps.applications.delete</code></li>
<li><code dir="ltr" translate="no">runapps.applications.get</code></li>
<li><code dir="ltr" translate="no">runapps.applications.getStatus</code></li>
<li><code dir="ltr" translate="no">runapps.applications.list</code></li>
<li><code dir="ltr" translate="no">runapps.applications.update</code></li>
</ul>
<p><code dir="ltr" translate="no">runapps.deployments.get</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.list</code></p>
<p><code dir="ltr" translate="no">runapps.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.locations.get</code></li>
<li><code dir="ltr" translate="no">runapps.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runapps.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.operations.cancel</code></li>
<li><code dir="ltr" translate="no">runapps.operations.delete</code></li>
<li><code dir="ltr" translate="no">runapps.operations.get</code></li>
<li><code dir="ltr" translate="no">runapps.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="runapps.operator" class="role-title add-link" data-text="Serverless Integrations Operator Beta" tabindex="-1">Serverless Integrations Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  runapps.operator</code> )</p>
<p>Access to deploy Serverless Integrations.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">runapps.applications.get</code></p>
<p><code dir="ltr" translate="no">runapps.applications.getStatus</code></p>
<p><code dir="ltr" translate="no">runapps.applications.list</code></p>
<p><code dir="ltr" translate="no">runapps.deployments.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.deployments.create</code></li>
<li><code dir="ltr" translate="no">runapps.deployments.get</code></li>
<li><code dir="ltr" translate="no">runapps.deployments.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runapps.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.locations.get</code></li>
<li><code dir="ltr" translate="no">runapps.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">runapps.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">runapps.operations.cancel</code></li>
<li><code dir="ltr" translate="no">runapps.operations.delete</code></li>
<li><code dir="ltr" translate="no">runapps.operations.get</code></li>
<li><code dir="ltr" translate="no">runapps.operations.list</code></li>
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
<td><h4 id="runapps.serviceAgent" class="role-title add-link" data-text="Serverless Integrations Service Agent" tabindex="-1">Serverless Integrations Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  runapps.serviceAgent</code> )</p>
<p>Gives Serverless Integrations Service Account access to customer project resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudbuild.builds.create</code></p>
<p><code dir="ltr" translate="no">cloudbuild.builds.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.databases.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.instances.get</code></p>
<p><code dir="ltr" translate="no">cloudsql.users.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.get</code></p>
<p><code dir="ltr" translate="no">compute.globalAddresses.list</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  get</code></p>
<p><code dir="ltr" translate="no">compute.  globalForwardingRules.  list</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.get</code></p>
<p><code dir="ltr" translate="no">compute.sslCertificates.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpProxies.list</code></p>
<p><code dir="ltr" translate="no">compute.targetHttpsProxies.get</code></p>
<p><code dir="ltr" translate="no">compute.  targetHttpsProxies.  list</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.get</code></p>
<p><code dir="ltr" translate="no">compute.urlMaps.list</code></p>
<p><code dir="ltr" translate="no">firebasehosting.sites.get</code></p>
<p><code dir="ltr" translate="no">iam.serviceAccounts.actAs</code></p>
<p><code dir="ltr" translate="no">redis.instances.get</code></p>
<p><code dir="ltr" translate="no">redis.instances.list</code></p>
<p><code dir="ltr" translate="no">run.jobs.get</code></p>
<p><code dir="ltr" translate="no">run.jobs.list</code></p>
<p><code dir="ltr" translate="no">run.services.get</code></p>
<p><code dir="ltr" translate="no">run.services.list</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.delete</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.list</code></p></td>
</tr>
</tbody>
</table>

## Serverless Integrations permissions

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
<td><h4 id="runapps.applications.create" class="permission-name add-link" data-text="runapps.applications.create" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.applications.delete" class="permission-name add-link" data-text="runapps.applications.delete" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.applications.get" class="permission-name add-link" data-text="runapps.applications.get" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.applications.getStatus" class="permission-name add-link" data-text="runapps.applications.getStatus" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.getStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.applications.list" class="permission-name add-link" data-text="runapps.applications.list" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.applications.update" class="permission-name add-link" data-text="runapps.applications.update" tabindex="-1"><code dir="ltr" translate="no">runapps.applications.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.deployments.create" class="permission-name add-link" data-text="runapps.deployments.create" tabindex="-1"><code dir="ltr" translate="no">runapps.deployments.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.deployments.get" class="permission-name add-link" data-text="runapps.deployments.get" tabindex="-1"><code dir="ltr" translate="no">runapps.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.deployments.list" class="permission-name add-link" data-text="runapps.deployments.list" tabindex="-1"><code dir="ltr" translate="no">runapps.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.locations.get" class="permission-name add-link" data-text="runapps.locations.get" tabindex="-1"><code dir="ltr" translate="no">runapps.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.locations.list" class="permission-name add-link" data-text="runapps.locations.list" tabindex="-1"><code dir="ltr" translate="no">runapps.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.operations.cancel" class="permission-name add-link" data-text="runapps.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">runapps.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.operations.delete" class="permission-name add-link" data-text="runapps.operations.delete" tabindex="-1"><code dir="ltr" translate="no">runapps.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="runapps.operations.get" class="permission-name add-link" data-text="runapps.operations.get" tabindex="-1"><code dir="ltr" translate="no">runapps.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="runapps.operations.list" class="permission-name add-link" data-text="runapps.operations.list" tabindex="-1"><code dir="ltr" translate="no">runapps.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.admin">Runapps Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.viewer">Serverless Integrations Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.developer">Serverless Integrations Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.developer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/runapps#runapps.operator">Serverless Integrations Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  runapps.operator</code> )</p></td>
</tr>
</tbody>
</table>
