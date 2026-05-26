---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate
title: Workload Certificate roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Workload Certificate. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Workload Certificate roles

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
<td><h4 id="workloadcertificate.admin" class="role-title add-link" data-text="Workload Certificate Admin Beta" tabindex="-1">Workload Certificate Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p>Full access to all Workload Certificate API resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  update</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  create</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.viewer" class="role-title add-link" data-text="Workload Certificate Viewer Beta" tabindex="-1">Workload Certificate Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p>Read-only access to Workload Certificate all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.registrationAdmin" class="role-title add-link" data-text="Workload Certificate Registration Admin Beta" tabindex="-1">Workload Certificate Registration Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p>Full access to WorkloadRegistration resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  create</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  delete</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.registrationViewer" class="role-title add-link" data-text="Workload Certificate Registration Viewer Beta" tabindex="-1">Workload Certificate Registration Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Read-only access to WorkloadRegistration resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></li>
<li><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p></td>
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
<td><h4 id="workloadcertificate.serviceAgent" class="role-title add-link" data-text="Workload Certificate Service Agent" tabindex="-1">Workload Certificate Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</p>
<p>Gives the Workload Certificate service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">container.  clusterRoleBindings.  get</code></p>
<p><code dir="ltr" translate="no">container.  clusterRoleBindings.  list</code></p>
<p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">container.clusters.update</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  create</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  get</code></p>
<p><code dir="ltr" translate="no">container.  customResourceDefinitions.  list</code></p>
<p><code dir="ltr" translate="no">container.operations.get</code></p>
<p><code dir="ltr" translate="no">container.  thirdPartyObjects.  update</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.create</code></p>
<p><code dir="ltr" translate="no">gkehub.fleet.get</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">gkehub.operations.get</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  addResource</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  create</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  delete</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  removeResource</code></p>
<p><code dir="ltr" translate="no">serviceusage.services.use</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  get</code></p>
<p><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></p></td>
</tr>
</tbody>
</table>

## Workload Certificate permissions

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
<td><h4 id="workloadcertificate.locations.get" class="permission-name add-link" data-text="workloadcertificate.locations.get" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.locations.list" class="permission-name add-link" data-text="workloadcertificate.locations.list" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.operations.cancel" class="permission-name add-link" data-text="workloadcertificate.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.operations.delete" class="permission-name add-link" data-text="workloadcertificate.operations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.operations.get" class="permission-name add-link" data-text="workloadcertificate.operations.get" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.operations.list" class="permission-name add-link" data-text="workloadcertificate.operations.list" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.workloadCertificateFeature.get" class="permission-name add-link" data-text="workloadcertificate.workloadCertificateFeature.get" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.workloadCertificateFeature.update" class="permission-name add-link" data-text="workloadcertificate.workloadCertificateFeature.update" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadCertificateFeature.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.workloadRegistrations.create" class="permission-name add-link" data-text="workloadcertificate.workloadRegistrations.create" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.workloadRegistrations.delete" class="permission-name add-link" data-text="workloadcertificate.workloadRegistrations.delete" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.workloadRegistrations.get" class="permission-name add-link" data-text="workloadcertificate.workloadRegistrations.get" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="workloadcertificate.workloadRegistrations.list" class="permission-name add-link" data-text="workloadcertificate.workloadRegistrations.list" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.viewer">Workload Certificate Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationViewer">Workload Certificate Registration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationViewer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/anthosservicemesh#anthosservicemesh.serviceAgent">Anthos Service Mesh Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  anthosservicemesh.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="workloadcertificate.workloadRegistrations.update" class="permission-name add-link" data-text="workloadcertificate.workloadRegistrations.update" tabindex="-1"><code dir="ltr" translate="no">workloadcertificate.  workloadRegistrations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.admin">Workload Certificate Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.registrationAdmin">Workload Certificate Registration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.registrationAdmin</code> )</p></td>
</tr>
</tbody>
</table>
