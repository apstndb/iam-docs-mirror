---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors
title: IAM Connectors roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for IAM Connectors. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## IAM Connectors roles

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
<td><h4 id="iamconnectors.admin" class="role-title add-link" data-text="Connector Admin Beta" tabindex="-1">Connector Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p>Grants access to manage connectors, authorizations, and access events.</p></td>
<td><p><code dir="ltr" translate="no">iamconnectors.accessEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.accessEvents.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.authorizations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  delete</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  create</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  delete</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  revokeAuthorizations</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  undelete</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  update</code></p>
<p><code dir="ltr" translate="no">iamconnectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">iamconnectors.operations.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.operations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.editor" class="role-title add-link" data-text="Connector Editor Beta" tabindex="-1">Connector Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p>Grants access to edit connectors, authorizations, and access events.</p></td>
<td><p><code dir="ltr" translate="no">iamconnectors.accessEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.accessEvents.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.authorizations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  delete</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  create</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  delete</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  revokeAuthorizations</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  undelete</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  update</code></p>
<p><code dir="ltr" translate="no">iamconnectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">iamconnectors.operations.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.operations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.viewer" class="role-title add-link" data-text="Connector Viewer Beta" tabindex="-1">Connector Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p>Grants access to view connectors, authorizations, and access events.</p></td>
<td><p><code dir="ltr" translate="no">iamconnectors.accessEvents.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.accessEvents.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.  authorizations.  get</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.get</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">iamconnectors.connectors.list</code></p>
<p><code dir="ltr" translate="no">iamconnectors.  connectors.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">iamconnectors.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">iamconnectors.locations.get</code></li>
<li><code dir="ltr" translate="no">iamconnectors.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">iamconnectors.operations.get</code></p>
<p><code dir="ltr" translate="no">iamconnectors.operations.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.user" class="role-title add-link" data-text="Connector User Beta" tabindex="-1">Connector User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  iamconnectors.user</code> )</p>
<p>Grants access to retrieve credentials from connectors.</p></td>
<td><p><code dir="ltr" translate="no">iamconnectors.  connectors.  retrieveCredentials</code></p></td>
</tr>
</tbody>
</table>

## IAM Connectors permissions

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
<td><h4 id="iamconnectors.accessEvents.get" class="permission-name add-link" data-text="iamconnectors.accessEvents.get" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.accessEvents.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.accessEvents.list" class="permission-name add-link" data-text="iamconnectors.accessEvents.list" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  accessEvents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.authorizations.delete" class="permission-name add-link" data-text="iamconnectors.authorizations.delete" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  authorizations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.authorizations.get" class="permission-name add-link" data-text="iamconnectors.authorizations.get" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  authorizations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.authorizations.list" class="permission-name add-link" data-text="iamconnectors.authorizations.list" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  authorizations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.create" class="permission-name add-link" data-text="iamconnectors.connectors.create" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.connectors.delete" class="permission-name add-link" data-text="iamconnectors.connectors.delete" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.get" class="permission-name add-link" data-text="iamconnectors.connectors.get" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.connectors.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.connectors.getIamPolicy" class="permission-name add-link" data-text="iamconnectors.connectors.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.list" class="permission-name add-link" data-text="iamconnectors.connectors.list" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.connectors.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.connectors.queryWorkloads" class="permission-name add-link" data-text="iamconnectors.connectors.queryWorkloads" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  queryWorkloads</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.retrieveCredentials" class="permission-name add-link" data-text="iamconnectors.connectors.retrieveCredentials" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  retrieveCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.user">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.connectors.revokeAuthorizations" class="permission-name add-link" data-text="iamconnectors.connectors.revokeAuthorizations" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  revokeAuthorizations</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.setIamPolicy" class="permission-name add-link" data-text="iamconnectors.connectors.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.connectors.undelete" class="permission-name add-link" data-text="iamconnectors.connectors.undelete" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.connectors.update" class="permission-name add-link" data-text="iamconnectors.connectors.update" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  connectors.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.locations.get" class="permission-name add-link" data-text="iamconnectors.locations.get" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.locations.list" class="permission-name add-link" data-text="iamconnectors.locations.list" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.operations.cancel" class="permission-name add-link" data-text="iamconnectors.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.operations.delete" class="permission-name add-link" data-text="iamconnectors.operations.delete" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="iamconnectors.operations.get" class="permission-name add-link" data-text="iamconnectors.operations.get" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="iamconnectors.operations.list" class="permission-name add-link" data-text="iamconnectors.operations.list" tabindex="-1"><code dir="ltr" translate="no">iamconnectors.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
