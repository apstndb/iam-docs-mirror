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
<td>Serviceconsumermanagement Admin <sup>Beta</sup>
<p>( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p>Admin role for serviceconsumermanagement</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceconsumermanagement.*</code></p>
<ul>
<li><code>serviceconsumermanagement. consumers. get</code></li>
<li><code>serviceconsumermanagement. quota. get</code></li>
<li><code>serviceconsumermanagement. quota. update</code></li>
<li><code>serviceconsumermanagement. tenancyu. addResource</code></li>
<li><code>serviceconsumermanagement. tenancyu. create</code></li>
<li><code>serviceconsumermanagement. tenancyu. delete</code></li>
<li><code>serviceconsumermanagement. tenancyu. list</code></li>
<li><code>serviceconsumermanagement. tenancyu. removeResource</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Serviceconsumermanagement Viewer <sup>Beta</sup>
<p>( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p>Viewer role for serviceconsumermanagement</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceconsumermanagement. consumers. get</code></p>
<p><code>serviceconsumermanagement. quota. get</code></p>
<p><code>serviceconsumermanagement. tenancyu. list</code></p></td>
</tr>
<tr class="odd">
<td>Admin of Tenancy Units <sup>Beta</sup>
<p>( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p>Administrate tenancy units</p></td>
<td><p><code>serviceconsumermanagement. tenancyu.*</code></p>
<ul>
<li><code>serviceconsumermanagement. tenancyu. addResource</code></li>
<li><code>serviceconsumermanagement. tenancyu. create</code></li>
<li><code>serviceconsumermanagement. tenancyu. delete</code></li>
<li><code>serviceconsumermanagement. tenancyu. list</code></li>
<li><code>serviceconsumermanagement. tenancyu. removeResource</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Viewer of Tenancy Units <sup>Beta</sup>
<p>( <code>roles/ serviceconsumermanagement.tenancyUnitsViewer</code> )</p>
<p>View tenancy units</p></td>
<td><p><code>serviceconsumermanagement. tenancyu. list</code></p></td>
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
<td><code>serviceconsumermanagement. consumers. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceconsumermanagement. quota. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>serviceconsumermanagement. quota. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceconsumermanagement. tenancyu. addResource</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code>roles/ workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceconsumermanagement. tenancyu. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code>roles/ workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceconsumermanagement. tenancyu. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code>roles/ workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>serviceconsumermanagement. tenancyu. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.viewer">Serviceconsumermanagement Viewer</a> ( <code>roles/ serviceconsumermanagement.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsViewer">Viewer of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>serviceconsumermanagement. tenancyu. removeResource</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.admin">Serviceconsumermanagement Admin</a> ( <code>roles/ serviceconsumermanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicemanagement#servicemanagement.admin">Service Management Administrator</a> ( <code>roles/ servicemanagement.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceconsumermanagement#serviceconsumermanagement.tenancyUnitsAdmin">Admin of Tenancy Units</a> ( <code>roles/ serviceconsumermanagement.tenancyUnitsAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workloadcertificate#workloadcertificate.serviceAgent">Workload Certificate Service Agent</a> ( <code>roles/ workloadcertificate.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
