---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/agentidentity
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity
title: Agent Identity API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Agent Identity API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Agent Identity API roles

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
<td><h4 id="agentidentity.admin" class="role-title add-link" data-text="Agent Identity Admin" tabindex="-1">Agent Identity Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p>Grants access to manage auth providers, authorizations, and access summaries.</p></td>
<td><p><code dir="ltr" translate="no">agentidentity.  accessSummaries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  get</code></li>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  create</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  delete</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  get</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  list</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  revokeAuthorizations</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  setIamPolicy</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  undelete</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  update</code></p>
<p><code dir="ltr" translate="no">agentidentity.authorizations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  delete</code></li>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentidentity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.locations.get</code></li>
<li><code dir="ltr" translate="no">agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.editor" class="role-title add-link" data-text="Agent Identity Editor" tabindex="-1">Agent Identity Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p>Grants access to edit auth providers, authorizations, and access summaries.</p></td>
<td><p><code dir="ltr" translate="no">agentidentity.  accessSummaries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  get</code></li>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  create</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  delete</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  get</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  list</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  revokeAuthorizations</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  undelete</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  update</code></p>
<p><code dir="ltr" translate="no">agentidentity.authorizations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  delete</code></li>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  get</code></li>
<li><code dir="ltr" translate="no">agentidentity.  authorizations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentidentity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.locations.get</code></li>
<li><code dir="ltr" translate="no">agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.viewer" class="role-title add-link" data-text="Agent Identity Viewer" tabindex="-1">Agent Identity Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p>Grants access to view auth providers, authorizations, and access summaries.</p></td>
<td><p><code dir="ltr" translate="no">agentidentity.  accessSummaries.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  get</code></li>
<li><code dir="ltr" translate="no">agentidentity.  accessSummaries.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  get</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  list</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authProviders.  queryWorkloads</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authorizations.  get</code></p>
<p><code dir="ltr" translate="no">agentidentity.  authorizations.  list</code></p>
<p><code dir="ltr" translate="no">agentidentity.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">agentidentity.locations.get</code></li>
<li><code dir="ltr" translate="no">agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.user" class="role-title add-link" data-text="Agent Identity User" tabindex="-1">Agent Identity User</h4>
<p>( <code dir="ltr" translate="no">roles/  agentidentity.user</code> )</p>
<p>Grants access to retrieve credentials from auth providers.</p></td>
<td><p><code dir="ltr" translate="no">agentidentity.  authProviders.  retrieveCredentials</code></p></td>
</tr>
</tbody>
</table>

## Agent Identity API permissions

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
<td><h4 id="agentidentity.accessSummaries.get" class="permission-name add-link" data-text="agentidentity.accessSummaries.get" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  accessSummaries.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.accessSummaries.list" class="permission-name add-link" data-text="agentidentity.accessSummaries.list" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  accessSummaries.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.create" class="permission-name add-link" data-text="agentidentity.authProviders.create" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authProviders.delete" class="permission-name add-link" data-text="agentidentity.authProviders.delete" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.get" class="permission-name add-link" data-text="agentidentity.authProviders.get" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authProviders.getIamPolicy" class="permission-name add-link" data-text="agentidentity.authProviders.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.list" class="permission-name add-link" data-text="agentidentity.authProviders.list" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authProviders.queryWorkloads" class="permission-name add-link" data-text="agentidentity.authProviders.queryWorkloads" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  queryWorkloads</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.retrieveCredentials" class="permission-name add-link" data-text="agentidentity.authProviders.retrieveCredentials" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  retrieveCredentials</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.user">Agent Identity User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.user">Connector User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authProviders.revokeAuthorizations" class="permission-name add-link" data-text="agentidentity.authProviders.revokeAuthorizations" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  revokeAuthorizations</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.setIamPolicy" class="permission-name add-link" data-text="agentidentity.authProviders.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authProviders.undelete" class="permission-name add-link" data-text="agentidentity.authProviders.undelete" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  undelete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authProviders.update" class="permission-name add-link" data-text="agentidentity.authProviders.update" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authProviders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authorizations.delete" class="permission-name add-link" data-text="agentidentity.authorizations.delete" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authorizations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.authorizations.get" class="permission-name add-link" data-text="agentidentity.authorizations.get" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authorizations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.authorizations.list" class="permission-name add-link" data-text="agentidentity.authorizations.list" tabindex="-1"><code dir="ltr" translate="no">agentidentity.  authorizations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="agentidentity.locations.get" class="permission-name add-link" data-text="agentidentity.locations.get" tabindex="-1"><code dir="ltr" translate="no">agentidentity.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="agentidentity.locations.list" class="permission-name add-link" data-text="agentidentity.locations.list" tabindex="-1"><code dir="ltr" translate="no">agentidentity.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  agentidentity.viewer</code> )</p>
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
