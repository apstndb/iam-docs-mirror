---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement
title: Service Consumer Management roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Consumer Management. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Consumer Management roles

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
<td><h4 id="serviceconsumermanagement.admin" class="role-title add-link" data-text="Serviceconsumermanagement Admin Beta" tabindex="-1">Serviceconsumermanagement Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p>Admin role for serviceconsumermanagement</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  consumers.  get</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  get</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  update</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  addResource</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  create</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  delete</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  removeResource</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.viewer" class="role-title add-link" data-text="Serviceconsumermanagement Viewer Beta" tabindex="-1">Serviceconsumermanagement Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p>Viewer role for serviceconsumermanagement</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  consumers.  get</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  get</code></p>
<p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="serviceconsumermanagement.tenancyUnitsAdmin" class="role-title add-link" data-text="Admin of Tenancy Units Beta" tabindex="-1">Admin of Tenancy Units <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Administrate tenancy units</p></td>
<td><p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.*</code></p>
<ul>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  addResource</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  create</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  delete</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></li>
<li><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  removeResource</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.tenancyUnitsViewer" class="role-title add-link" data-text="Viewer of Tenancy Units Beta" tabindex="-1">Viewer of Tenancy Units <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsViewer</code> )</p>
<p>View tenancy units</p></td>
<td><p><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></p></td>
</tr>
</tbody>
</table>

## Service Consumer Management permissions

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
<td><h4 id="serviceconsumermanagement.consumers.get" class="permission-name add-link" data-text="serviceconsumermanagement.consumers.get" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  consumers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.quota.get" class="permission-name add-link" data-text="serviceconsumermanagement.quota.get" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="serviceconsumermanagement.quota.update" class="permission-name add-link" data-text="serviceconsumermanagement.quota.update" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  quota.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.tenancyu.addResource" class="permission-name add-link" data-text="serviceconsumermanagement.tenancyu.addResource" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  addResource</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="serviceconsumermanagement.tenancyu.create" class="permission-name add-link" data-text="serviceconsumermanagement.tenancyu.create" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.tenancyu.delete" class="permission-name add-link" data-text="serviceconsumermanagement.tenancyu.delete" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="serviceconsumermanagement.tenancyu.list" class="permission-name add-link" data-text="serviceconsumermanagement.tenancyu.list" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsViewer">Viewer of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="serviceconsumermanagement.tenancyu.removeResource" class="permission-name add-link" data-text="serviceconsumermanagement.tenancyu.removeResource" tabindex="-1"><code dir="ltr" translate="no">serviceconsumermanagement.  tenancyu.  removeResource</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code class="role-name" dir="ltr" translate="no">roles/  serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
