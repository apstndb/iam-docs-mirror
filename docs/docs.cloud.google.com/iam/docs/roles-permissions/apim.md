---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/apim
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/apim
title: API Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for API Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## API Management roles

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
<td><h4 id="apim.admin" class="role-title add-link" data-text="API Management Admin Beta" tabindex="-1">API Management Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p>Full access to API Management resources.</p></td>
<td><p><code dir="ltr" translate="no">apim.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apim.  apiObservations.  batchEditTags</code></li>
<li><code dir="ltr" translate="no">apim.apiObservations.get</code></li>
<li><code dir="ltr" translate="no">apim.apiObservations.list</code></li>
<li><code dir="ltr" translate="no">apim.apiOperations.get</code></li>
<li><code dir="ltr" translate="no">apim.apiOperations.list</code></li>
<li><code dir="ltr" translate="no">apim.entitlements.get</code></li>
<li><code dir="ltr" translate="no">apim.locations.get</code></li>
<li><code dir="ltr" translate="no">apim.locations.list</code></li>
<li><code dir="ltr" translate="no">apim.  locations.  listApiObservationTags</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.create</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.delete</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.disable</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.enable</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.get</code></li>
<li><code dir="ltr" translate="no">apim.observationJobs.list</code></li>
<li><code dir="ltr" translate="no">apim.observationSources.create</code></li>
<li><code dir="ltr" translate="no">apim.observationSources.delete</code></li>
<li><code dir="ltr" translate="no">apim.observationSources.get</code></li>
<li><code dir="ltr" translate="no">apim.observationSources.list</code></li>
<li><code dir="ltr" translate="no">apim.operations.cancel</code></li>
<li><code dir="ltr" translate="no">apim.operations.delete</code></li>
<li><code dir="ltr" translate="no">apim.operations.get</code></li>
<li><code dir="ltr" translate="no">apim.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apim.viewer" class="role-title add-link" data-text="API Management Viewer Beta" tabindex="-1">API Management Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p>Readonly access to API Management resources.</p></td>
<td><p><code dir="ltr" translate="no">apim.apiObservations.get</code></p>
<p><code dir="ltr" translate="no">apim.apiObservations.list</code></p>
<p><code dir="ltr" translate="no">apim.apiOperations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apim.apiOperations.get</code></li>
<li><code dir="ltr" translate="no">apim.apiOperations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">apim.entitlements.get</code></p>
<p><code dir="ltr" translate="no">apim.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">apim.locations.get</code></li>
<li><code dir="ltr" translate="no">apim.locations.list</code></li>
<li><code dir="ltr" translate="no">apim.  locations.  listApiObservationTags</code></li>
</ul>
<p><code dir="ltr" translate="no">apim.observationJobs.get</code></p>
<p><code dir="ltr" translate="no">apim.observationJobs.list</code></p>
<p><code dir="ltr" translate="no">apim.observationSources.get</code></p>
<p><code dir="ltr" translate="no">apim.observationSources.list</code></p>
<p><code dir="ltr" translate="no">apim.operations.get</code></p>
<p><code dir="ltr" translate="no">apim.operations.list</code></p>
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
<td><h4 id="apim.apiDiscoveryServiceAgent" class="role-title add-link" data-text="APIM API Discovery Service Agent" tabindex="-1">APIM API Discovery Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  apim.apiDiscoveryServiceAgent</code> )</p>
<p>Gives APIM the ability to manage resources in consumer project</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.backendServices.create</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.delete</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.get</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.list</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.update</code></p>
<p><code dir="ltr" translate="no">compute.backendServices.use</code></p>
<p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.use</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  update</code></p>
<p><code dir="ltr" translate="no">compute.  regionBackendServices.  use</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  attachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  create</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  delete</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  detachNetworkEndpoints</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  get</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  list</code></p>
<p><code dir="ltr" translate="no">compute.  regionNetworkEndpointGroups.  use</code></p>
<p><code dir="ltr" translate="no">compute.regionOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.subnetworks.use</code></p>
<p><code dir="ltr" translate="no">networkservices.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">networkservices.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">networkservices.operations.get</code></li>
<li><code dir="ltr" translate="no">networkservices.  operations.  list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## API Management permissions

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
<td><h4 id="apim.apiObservations.batchEditTags" class="permission-name add-link" data-text="apim.apiObservations.batchEditTags" tabindex="-1"><code dir="ltr" translate="no">apim.  apiObservations.  batchEditTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.apiObservations.get" class="permission-name add-link" data-text="apim.apiObservations.get" tabindex="-1"><code dir="ltr" translate="no">apim.apiObservations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.apiObservations.list" class="permission-name add-link" data-text="apim.apiObservations.list" tabindex="-1"><code dir="ltr" translate="no">apim.apiObservations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.apiOperations.get" class="permission-name add-link" data-text="apim.apiOperations.get" tabindex="-1"><code dir="ltr" translate="no">apim.apiOperations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.apiOperations.list" class="permission-name add-link" data-text="apim.apiOperations.list" tabindex="-1"><code dir="ltr" translate="no">apim.apiOperations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.entitlements.get" class="permission-name add-link" data-text="apim.entitlements.get" tabindex="-1"><code dir="ltr" translate="no">apim.entitlements.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.locations.get" class="permission-name add-link" data-text="apim.locations.get" tabindex="-1"><code dir="ltr" translate="no">apim.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.locations.list" class="permission-name add-link" data-text="apim.locations.list" tabindex="-1"><code dir="ltr" translate="no">apim.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.locations.listApiObservationTags" class="permission-name add-link" data-text="apim.locations.listApiObservationTags" tabindex="-1"><code dir="ltr" translate="no">apim.  locations.  listApiObservationTags</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.observationJobs.create" class="permission-name add-link" data-text="apim.observationJobs.create" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.observationJobs.delete" class="permission-name add-link" data-text="apim.observationJobs.delete" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.observationJobs.disable" class="permission-name add-link" data-text="apim.observationJobs.disable" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.observationJobs.enable" class="permission-name add-link" data-text="apim.observationJobs.enable" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.observationJobs.get" class="permission-name add-link" data-text="apim.observationJobs.get" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.observationJobs.list" class="permission-name add-link" data-text="apim.observationJobs.list" tabindex="-1"><code dir="ltr" translate="no">apim.observationJobs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.observationSources.create" class="permission-name add-link" data-text="apim.observationSources.create" tabindex="-1"><code dir="ltr" translate="no">apim.observationSources.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.observationSources.delete" class="permission-name add-link" data-text="apim.observationSources.delete" tabindex="-1"><code dir="ltr" translate="no">apim.observationSources.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.observationSources.get" class="permission-name add-link" data-text="apim.observationSources.get" tabindex="-1"><code dir="ltr" translate="no">apim.observationSources.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.observationSources.list" class="permission-name add-link" data-text="apim.observationSources.list" tabindex="-1"><code dir="ltr" translate="no">apim.observationSources.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.operations.cancel" class="permission-name add-link" data-text="apim.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">apim.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.operations.delete" class="permission-name add-link" data-text="apim.operations.delete" tabindex="-1"><code dir="ltr" translate="no">apim.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apim.operations.get" class="permission-name add-link" data-text="apim.operations.get" tabindex="-1"><code dir="ltr" translate="no">apim.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="apim.operations.list" class="permission-name add-link" data-text="apim.operations.list" tabindex="-1"><code dir="ltr" translate="no">apim.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.admin">API Management Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apim#apim.viewer">API Management Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apim.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
