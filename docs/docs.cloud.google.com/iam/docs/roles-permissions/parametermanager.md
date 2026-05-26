---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/parametermanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager
title: Parameter Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Parameter Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Parameter Manager roles

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
<td><h4 id="parametermanager.admin" class="role-title add-link" data-text="Parameter Manager Admin" tabindex="-1">Parameter Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p>Grants full access to all Parameter Manager resources. Intended for project admins &amp; owners who need to perform all administrative tasks.</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  create</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  delete</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  render</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameterVersions.  update</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  create</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  delete</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.editor" class="role-title add-link" data-text="Parametermanager Editor" tabindex="-1">Parametermanager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p>Editor role for parametermanager</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  create</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  delete</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  update</code></p>
<p><code dir="ltr" translate="no">parametermanager.parameters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  create</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  delete</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></li>
<li><code dir="ltr" translate="no">parametermanager.  parameters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.viewer" class="role-title add-link" data-text="Parametermanager Viewer" tabindex="-1">Parametermanager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p>Viewer role for parametermanager</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameterAccessor" class="role-title add-link" data-text="Parameter Manager Parameter Accessor" tabindex="-1">Parameter Manager Parameter Accessor</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p>
<p>Grants read access to ParameterManager ParameterVersion resources. Intended for users &amp; applications that need to perform read operations on ParameterVersions only.</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  render</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameterVersionAdder" class="role-title add-link" data-text="Parameter Manager Parameter Version Adder" tabindex="-1">Parameter Manager Parameter Version Adder</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p>Grants create access to Parameter Manager ParameterVersion resources. Intended for users &amp; applications that need to perform create operations on ParameterVersions only.</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  create</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameterVersionManager" class="role-title add-link" data-text="Parameter Manager Parameter Version Manager" tabindex="-1">Parameter Manager Parameter Version Manager</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p>Grants read &amp; write access to all Parameter Manager ParameterVersion resources. Intended for users &amp; applications that need to view Parameters and perform create/read/update/delete/list operations on ParameterVersions only.</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  create</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  delete</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  update</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameterViewer" class="role-title add-link" data-text="Parameter Manager Parameter Viewer" tabindex="-1">Parameter Manager Parameter Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p>
<p>Grants read access to Parameter Manager Parameter &amp; ParameterVersion resources. Intended for users &amp; applications that need to perform read/list operations on Parameters and ParameterVersions only.</p></td>
<td><p><code dir="ltr" translate="no">parametermanager.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">parametermanager.locations.get</code></li>
<li><code dir="ltr" translate="no">parametermanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></p>
<p><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Parameter Manager permissions

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
<td><h4 id="parametermanager.locations.get" class="permission-name add-link" data-text="parametermanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">parametermanager.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.locations.list" class="permission-name add-link" data-text="parametermanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameterVersions.create" class="permission-name add-link" data-text="parametermanager.parameterVersions.create" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameterVersions.delete" class="permission-name add-link" data-text="parametermanager.parameterVersions.delete" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameterVersions.get" class="permission-name add-link" data-text="parametermanager.parameterVersions.get" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameterVersions.list" class="permission-name add-link" data-text="parametermanager.parameterVersions.list" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameterVersions.render" class="permission-name add-link" data-text="parametermanager.parameterVersions.render" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  render</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterAccessor">Parameter Manager Parameter Accessor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterAccessor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameterVersions.update" class="permission-name add-link" data-text="parametermanager.parameterVersions.update" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameterVersions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameters.create" class="permission-name add-link" data-text="parametermanager.parameters.create" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameters.delete" class="permission-name add-link" data-text="parametermanager.parameters.delete" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameters.get" class="permission-name add-link" data-text="parametermanager.parameters.get" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="parametermanager.parameters.list" class="permission-name add-link" data-text="parametermanager.parameters.list" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.viewer">Parametermanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionAdder">Parameter Manager Parameter Version Adder</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionAdder</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterVersionManager">Parameter Manager Parameter Version Manager</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterVersionManager</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.parameterViewer">Parameter Manager Parameter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.parameterViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="parametermanager.parameters.update" class="permission-name add-link" data-text="parametermanager.parameters.update" tabindex="-1"><code dir="ltr" translate="no">parametermanager.  parameters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.admin">Parameter Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/parametermanager#parametermanager.editor">Parametermanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  parametermanager.editor</code> )</p></td>
</tr>
</tbody>
</table>
