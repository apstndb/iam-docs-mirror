---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/managedflink
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink
title: BigQuery Engine for Apache Flink roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for BigQuery Engine for Apache Flink. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## BigQuery Engine for Apache Flink roles

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
<td><h4 id="managedflink.admin" class="role-title add-link" data-text="Managed Flink Admin Beta" tabindex="-1">Managed Flink Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p>Full access to Managed Flink resources.</p></td>
<td><p><code dir="ltr" translate="no">managedflink.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedflink.  deployments.  create</code></li>
<li><code dir="ltr" translate="no">managedflink.  deployments.  delete</code></li>
<li><code dir="ltr" translate="no">managedflink.deployments.get</code></li>
<li><code dir="ltr" translate="no">managedflink.deployments.list</code></li>
<li><code dir="ltr" translate="no">managedflink.  deployments.  update</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.create</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.delete</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.get</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.list</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.update</code></li>
<li><code dir="ltr" translate="no">managedflink.locations.get</code></li>
<li><code dir="ltr" translate="no">managedflink.locations.list</code></li>
<li><code dir="ltr" translate="no">managedflink.operations.cancel</code></li>
<li><code dir="ltr" translate="no">managedflink.operations.delete</code></li>
<li><code dir="ltr" translate="no">managedflink.operations.get</code></li>
<li><code dir="ltr" translate="no">managedflink.operations.list</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.create</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.delete</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.get</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.list</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.viewer" class="role-title add-link" data-text="Managed Flink Viewer Beta" tabindex="-1">Managed Flink Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p>Readonly access to Managed Flink resources.</p></td>
<td><p><code dir="ltr" translate="no">managedflink.deployments.get</code></p>
<p><code dir="ltr" translate="no">managedflink.deployments.list</code></p>
<p><code dir="ltr" translate="no">managedflink.jobs.get</code></p>
<p><code dir="ltr" translate="no">managedflink.jobs.list</code></p>
<p><code dir="ltr" translate="no">managedflink.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedflink.locations.get</code></li>
<li><code dir="ltr" translate="no">managedflink.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedflink.operations.get</code></p>
<p><code dir="ltr" translate="no">managedflink.operations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.sessions.get</code></p>
<p><code dir="ltr" translate="no">managedflink.sessions.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.developer" class="role-title add-link" data-text="Managed Flink Developer Beta" tabindex="-1">Managed Flink Developer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  managedflink.developer</code> )</p>
<p>Full access to Managed Flink Jobs and Sessions and read access to Deployments.</p></td>
<td><p><code dir="ltr" translate="no">managedflink.deployments.get</code></p>
<p><code dir="ltr" translate="no">managedflink.deployments.list</code></p>
<p><code dir="ltr" translate="no">managedflink.jobs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedflink.jobs.create</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.delete</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.get</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.list</code></li>
<li><code dir="ltr" translate="no">managedflink.jobs.update</code></li>
</ul>
<p><code dir="ltr" translate="no">managedflink.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedflink.locations.get</code></li>
<li><code dir="ltr" translate="no">managedflink.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">managedflink.operations.get</code></p>
<p><code dir="ltr" translate="no">managedflink.operations.list</code></p>
<p><code dir="ltr" translate="no">managedflink.sessions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">managedflink.sessions.create</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.delete</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.get</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.list</code></li>
<li><code dir="ltr" translate="no">managedflink.sessions.update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
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
<td><h4 id="managedflink.serviceAgent" class="role-title add-link" data-text="Managed Flink Service Agent" tabindex="-1">Managed Flink Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  managedflink.serviceAgent</code> )</p>
<p>Gives Managed Flink Service Agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.  networkAttachments.  create</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">compute.networkAttachments.get</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  list</code></p>
<p><code dir="ltr" translate="no">compute.  networkAttachments.  update</code></p>
<p><code dir="ltr" translate="no">compute.networks.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.list</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">dns.  networks.  targetWithPeeringZone</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.get</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.list</code></p>
<p><code dir="ltr" translate="no">managedkafka.clusters.update</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  create</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  get</code></p>
<p><code dir="ltr" translate="no">monitoring.  metricDescriptors.  list</code></p>
<p><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  get</code></li>
<li><code dir="ltr" translate="no">monitoring.  monitoredResourceDescriptors.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">monitoring.timeSeries.create</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p></td>
</tr>
</tbody>
</table>

## BigQuery Engine for Apache Flink permissions

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
<td><h4 id="managedflink.deployments.create" class="permission-name add-link" data-text="managedflink.deployments.create" tabindex="-1"><code dir="ltr" translate="no">managedflink.  deployments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.deployments.delete" class="permission-name add-link" data-text="managedflink.deployments.delete" tabindex="-1"><code dir="ltr" translate="no">managedflink.  deployments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.deployments.get" class="permission-name add-link" data-text="managedflink.deployments.get" tabindex="-1"><code dir="ltr" translate="no">managedflink.deployments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.deployments.list" class="permission-name add-link" data-text="managedflink.deployments.list" tabindex="-1"><code dir="ltr" translate="no">managedflink.deployments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.deployments.update" class="permission-name add-link" data-text="managedflink.deployments.update" tabindex="-1"><code dir="ltr" translate="no">managedflink.  deployments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.jobs.create" class="permission-name add-link" data-text="managedflink.jobs.create" tabindex="-1"><code dir="ltr" translate="no">managedflink.jobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.jobs.delete" class="permission-name add-link" data-text="managedflink.jobs.delete" tabindex="-1"><code dir="ltr" translate="no">managedflink.jobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.jobs.get" class="permission-name add-link" data-text="managedflink.jobs.get" tabindex="-1"><code dir="ltr" translate="no">managedflink.jobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.jobs.list" class="permission-name add-link" data-text="managedflink.jobs.list" tabindex="-1"><code dir="ltr" translate="no">managedflink.jobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.jobs.update" class="permission-name add-link" data-text="managedflink.jobs.update" tabindex="-1"><code dir="ltr" translate="no">managedflink.jobs.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.locations.get" class="permission-name add-link" data-text="managedflink.locations.get" tabindex="-1"><code dir="ltr" translate="no">managedflink.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.locations.list" class="permission-name add-link" data-text="managedflink.locations.list" tabindex="-1"><code dir="ltr" translate="no">managedflink.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.operations.cancel" class="permission-name add-link" data-text="managedflink.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">managedflink.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.operations.delete" class="permission-name add-link" data-text="managedflink.operations.delete" tabindex="-1"><code dir="ltr" translate="no">managedflink.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.operations.get" class="permission-name add-link" data-text="managedflink.operations.get" tabindex="-1"><code dir="ltr" translate="no">managedflink.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.operations.list" class="permission-name add-link" data-text="managedflink.operations.list" tabindex="-1"><code dir="ltr" translate="no">managedflink.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.sessions.create" class="permission-name add-link" data-text="managedflink.sessions.create" tabindex="-1"><code dir="ltr" translate="no">managedflink.sessions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.sessions.delete" class="permission-name add-link" data-text="managedflink.sessions.delete" tabindex="-1"><code dir="ltr" translate="no">managedflink.sessions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.sessions.get" class="permission-name add-link" data-text="managedflink.sessions.get" tabindex="-1"><code dir="ltr" translate="no">managedflink.sessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="managedflink.sessions.list" class="permission-name add-link" data-text="managedflink.sessions.list" tabindex="-1"><code dir="ltr" translate="no">managedflink.sessions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.viewer">Managed Flink Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="managedflink.sessions.update" class="permission-name add-link" data-text="managedflink.sessions.update" tabindex="-1"><code dir="ltr" translate="no">managedflink.sessions.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.admin">Managed Flink Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedflink#managedflink.developer">Managed Flink Developer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedflink.developer</code> )</p></td>
</tr>
</tbody>
</table>
