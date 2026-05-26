---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner
title: Cloud Controls Partner API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Controls Partner API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Controls Partner API roles

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
<td><h4 id="cloudcontrolspartner.admin" class="role-title add-link" data-text="Cloud Controls Partner Admin" tabindex="-1">Cloud Controls Partner Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p>Full access to Cloud Controls Partner resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  create</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  delete</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  ekmconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partnerpermissions.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partners.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.editor" class="role-title add-link" data-text="Cloud Controls Partner Editor" tabindex="-1">Cloud Controls Partner Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p>Editor access to Cloud Controls Partner resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  create</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  delete</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  ekmconnections.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  partnerpermissions.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  partners.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.viewer" class="role-title add-link" data-text="Cloudcontrolspartner Viewer" tabindex="-1">Cloudcontrolspartner Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p>Viewer role for cloudcontrolspartner</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  ekmconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partnerpermissions.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partners.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.inspectabilityReader" class="role-title add-link" data-text="Cloud Controls Partner Inspectability Reader" tabindex="-1">Cloud Controls Partner Inspectability Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.inspectabilityReader</code> )</p>
<p>Readonly access to Cloud Controls Partner inspectability resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.monitoringReader" class="role-title add-link" data-text="Cloud Controls Partner Monitoring Reader" tabindex="-1">Cloud Controls Partner Monitoring Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p>Read-only access to Cloud Controls Partner monitoring resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.reader" class="role-title add-link" data-text="Cloud Controls Partner Reader" tabindex="-1">Cloud Controls Partner Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p>Read-only access to Cloud Controls Partner resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  ekmconnections.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partnerpermissions.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  partners.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></p>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  violations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  get</code></li>
<li><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></li>
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
<td><h4 id="cloudcontrolspartner.accessApprovalServiceAgent" class="role-title add-link" data-text="Cloud Controls Partner Access Approval Service Agent" tabindex="-1">Cloud Controls Partner Access Approval Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.accessApprovalServiceAgent</code> )</p>
<p>Gives the Partner Console service account access to read Access Approval Requests for workloads associated with a partner.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">accessapproval.requests.get</code></p>
<p><code dir="ltr" translate="no">accessapproval.requests.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.ekmServiceAgent" class="role-title add-link" data-text="Cloud Controls Partner EKM Service Agent" tabindex="-1">Cloud Controls Partner EKM Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.ekmServiceAgent</code> )</p>
<p>Gives Cloud Controls Partner service agent permission to list EKM connections, get EKM connection status, and provide EKM diagnostic information.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudkms.ekmConnections.get</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">cloudkms.ekmConnections.list</code></p>
<p><code dir="ltr" translate="no">cloudkms.  ekmConnections.  verifyConnectivity</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.monitoringServiceAgent" class="role-title add-link" data-text="Cloud Controls Partner Monitoring Service Agent" tabindex="-1">Cloud Controls Partner Monitoring Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringServiceAgent</code> )</p>
<p>Gives Cloud Controls Partner monitoring service agent permission to view and list Assured Workload violations. The role is assigned to enable partner monitoring capability.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">assuredworkloads.  violations.  get</code></p>
<p><code dir="ltr" translate="no">assuredworkloads.  violations.  list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.supportCaseServiceAgent" class="role-title add-link" data-text="Cloud Controls Partner Support Case Service Agent" tabindex="-1">Cloud Controls Partner Support Case Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudcontrolspartner.supportCaseServiceAgent</code> )</p>
<p>Gives the Partner Console service account access to support cases for workloads associated with a partner.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">cloudsupport.techCases.get</code></p></td>
</tr>
</tbody>
</table>

## Cloud Controls Partner API permissions

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
<td><h4 id="cloudcontrolspartner.accessapprovalrequests.list" class="permission-name add-link" data-text="cloudcontrolspartner.accessapprovalrequests.list" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  accessapprovalrequests.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.customers.create" class="permission-name add-link" data-text="cloudcontrolspartner.customers.create" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.customers.delete" class="permission-name add-link" data-text="cloudcontrolspartner.customers.delete" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.customers.get" class="permission-name add-link" data-text="cloudcontrolspartner.customers.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.inspectabilityReader">Cloud Controls Partner Inspectability Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.inspectabilityReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.customers.list" class="permission-name add-link" data-text="cloudcontrolspartner.customers.list" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  customers.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.inspectabilityReader">Cloud Controls Partner Inspectability Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.inspectabilityReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.ekmconnections.get" class="permission-name add-link" data-text="cloudcontrolspartner.ekmconnections.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  ekmconnections.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.inspectabilityevents.get" class="permission-name add-link" data-text="cloudcontrolspartner.inspectabilityevents.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  inspectabilityevents.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.inspectabilityReader">Cloud Controls Partner Inspectability Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.inspectabilityReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.partnerpermissions.get" class="permission-name add-link" data-text="cloudcontrolspartner.partnerpermissions.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  partnerpermissions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.partners.get" class="permission-name add-link" data-text="cloudcontrolspartner.partners.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  partners.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.platformcontrols.get" class="permission-name add-link" data-text="cloudcontrolspartner.platformcontrols.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  platformcontrols.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.inspectabilityReader">Cloud Controls Partner Inspectability Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.inspectabilityReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.violations.get" class="permission-name add-link" data-text="cloudcontrolspartner.violations.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.violations.list" class="permission-name add-link" data-text="cloudcontrolspartner.violations.list" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  violations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudcontrolspartner.workloads.get" class="permission-name add-link" data-text="cloudcontrolspartner.workloads.get" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudcontrolspartner.workloads.list" class="permission-name add-link" data-text="cloudcontrolspartner.workloads.list" tabindex="-1"><code dir="ltr" translate="no">cloudcontrolspartner.  workloads.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.admin">Cloud Controls Partner Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.editor">Cloud Controls Partner Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.viewer">Cloudcontrolspartner Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.monitoringReader">Cloud Controls Partner Monitoring Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.monitoringReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudcontrolspartner#cloudcontrolspartner.reader">Cloud Controls Partner Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudcontrolspartner.reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
