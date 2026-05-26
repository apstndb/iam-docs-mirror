---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors
title: Data Connectors roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Data Connectors. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Data Connectors roles

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
<td><h4 id="dataconnectors.admin" class="role-title add-link" data-text="Data Connectors Admin Beta" tabindex="-1">Data Connectors Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p>Admin role for Data Connectors</p></td>
<td><p><code dir="ltr" translate="no">dataconnectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  create</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  delete</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.list</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  update</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.use</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.list</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.editor" class="role-title add-link" data-text="Data Connectors Editor Beta" tabindex="-1">Data Connectors Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p>Editor role for Data Connectors</p></td>
<td><p><code dir="ltr" translate="no">dataconnectors.  connectors.  create</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  delete</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  update</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.use</code></p>
<p><code dir="ltr" translate="no">dataconnectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataconnectors.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.viewer" class="role-title add-link" data-text="Data Connectors Viewer Beta" tabindex="-1">Data Connectors Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p>Viewer role for Data Connectors</p></td>
<td><p><code dir="ltr" translate="no">dataconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">dataconnectors.operations.get</code></p>
<p><code dir="ltr" translate="no">dataconnectors.operations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.connectorAdmin" class="role-title add-link" data-text="Connector Admin Beta" tabindex="-1">Connector Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p>Full access to Data Connectors.</p></td>
<td><p><code dir="ltr" translate="no">dataconnectors.*</code></p>
<ul>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  create</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  delete</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.list</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  connectors.  update</code></li>
<li><code dir="ltr" translate="no">dataconnectors.connectors.use</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.locations.list</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">dataconnectors.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.get</code></li>
<li><code dir="ltr" translate="no">dataconnectors.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.connectorUser" class="role-title add-link" data-text="Connector User Beta" tabindex="-1">Connector User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.connectorUser</code> )</p>
<p>Access to use Data Connectors.</p></td>
<td><p><code dir="ltr" translate="no">dataconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">dataconnectors.connectors.use</code></p></td>
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
<td><h4 id="dataconnectors.serviceAgent" class="role-title add-link" data-text="Data Connectors Service Agent" tabindex="-1">Data Connectors Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  dataconnectors.serviceAgent</code> )</p>
<p>Gives Data Connectors service agent permission to access the virtual private cloud</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">compute.globalOperations.get</code></p>
<p><code dir="ltr" translate="no">compute.networks.access</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.get</code></p>
<p><code dir="ltr" translate="no">vpcaccess.connectors.use</code></p></td>
</tr>
</tbody>
</table>

## Data Connectors permissions

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
<td><h4 id="dataconnectors.connectors.create" class="permission-name add-link" data-text="dataconnectors.connectors.create" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  connectors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.connectors.delete" class="permission-name add-link" data-text="dataconnectors.connectors.delete" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  connectors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.connectors.get" class="permission-name add-link" data-text="dataconnectors.connectors.get" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.connectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorUser">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.connectors.getIamPolicy" class="permission-name add-link" data-text="dataconnectors.connectors.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  connectors.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorUser">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.connectors.list" class="permission-name add-link" data-text="dataconnectors.connectors.list" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.connectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorUser">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.connectors.setIamPolicy" class="permission-name add-link" data-text="dataconnectors.connectors.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  connectors.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.connectors.update" class="permission-name add-link" data-text="dataconnectors.connectors.update" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  connectors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.connectors.use" class="permission-name add-link" data-text="dataconnectors.connectors.use" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.connectors.use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorUser">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.locations.get" class="permission-name add-link" data-text="dataconnectors.locations.get" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.locations.list" class="permission-name add-link" data-text="dataconnectors.locations.list" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.operations.cancel" class="permission-name add-link" data-text="dataconnectors.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.operations.delete" class="permission-name add-link" data-text="dataconnectors.operations.delete" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="dataconnectors.operations.get" class="permission-name add-link" data-text="dataconnectors.operations.get" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="dataconnectors.operations.list" class="permission-name add-link" data-text="dataconnectors.operations.list" tabindex="-1"><code dir="ltr" translate="no">dataconnectors.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.admin">Data Connectors Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.editor">Data Connectors Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.viewer">Data Connectors Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataconnectors#dataconnectors.connectorAdmin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataconnectors.connectorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
