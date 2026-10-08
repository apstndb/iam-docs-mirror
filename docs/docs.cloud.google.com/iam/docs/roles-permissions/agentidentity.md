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
<td>Agent Identity Admin
<p>( <code>roles/ agentidentity.admin</code> )</p>
<p>Grants access to manage auth providers, authorizations, and access summaries.</p></td>
<td><p><code>agentidentity. accessSummaries.*</code></p>
<ul>
<li><code>agentidentity. accessSummaries. get</code></li>
<li><code>agentidentity. accessSummaries. list</code></li>
</ul>
<p><code>agentidentity. authProviders. create</code></p>
<p><code>agentidentity. authProviders. delete</code></p>
<p><code>agentidentity. authProviders. get</code></p>
<p><code>agentidentity. authProviders. getIamPolicy</code></p>
<p><code>agentidentity. authProviders. list</code></p>
<p><code>agentidentity. authProviders. queryWorkloads</code></p>
<p><code>agentidentity. authProviders. revokeAuthorizations</code></p>
<p><code>agentidentity. authProviders. setIamPolicy</code></p>
<p><code>agentidentity. authProviders. undelete</code></p>
<p><code>agentidentity. authProviders. update</code></p>
<p><code>agentidentity.authorizations.*</code></p>
<ul>
<li><code>agentidentity. authorizations. delete</code></li>
<li><code>agentidentity. authorizations. get</code></li>
<li><code>agentidentity. authorizations. list</code></li>
</ul>
<p><code>agentidentity.locations.*</code></p>
<ul>
<li><code>agentidentity.locations.get</code></li>
<li><code>agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Agent Identity Editor
<p>( <code>roles/ agentidentity.editor</code> )</p>
<p>Grants access to edit auth providers, authorizations, and access summaries.</p></td>
<td><p><code>agentidentity. accessSummaries.*</code></p>
<ul>
<li><code>agentidentity. accessSummaries. get</code></li>
<li><code>agentidentity. accessSummaries. list</code></li>
</ul>
<p><code>agentidentity. authProviders. create</code></p>
<p><code>agentidentity. authProviders. delete</code></p>
<p><code>agentidentity. authProviders. get</code></p>
<p><code>agentidentity. authProviders. getIamPolicy</code></p>
<p><code>agentidentity. authProviders. list</code></p>
<p><code>agentidentity. authProviders. queryWorkloads</code></p>
<p><code>agentidentity. authProviders. revokeAuthorizations</code></p>
<p><code>agentidentity. authProviders. undelete</code></p>
<p><code>agentidentity. authProviders. update</code></p>
<p><code>agentidentity.authorizations.*</code></p>
<ul>
<li><code>agentidentity. authorizations. delete</code></li>
<li><code>agentidentity. authorizations. get</code></li>
<li><code>agentidentity. authorizations. list</code></li>
</ul>
<p><code>agentidentity.locations.*</code></p>
<ul>
<li><code>agentidentity.locations.get</code></li>
<li><code>agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Agent Identity Viewer
<p>( <code>roles/ agentidentity.viewer</code> )</p>
<p>Grants access to view auth providers, authorizations, and access summaries.</p></td>
<td><p><code>agentidentity. accessSummaries.*</code></p>
<ul>
<li><code>agentidentity. accessSummaries. get</code></li>
<li><code>agentidentity. accessSummaries. list</code></li>
</ul>
<p><code>agentidentity. authProviders. get</code></p>
<p><code>agentidentity. authProviders. getIamPolicy</code></p>
<p><code>agentidentity. authProviders. list</code></p>
<p><code>agentidentity. authProviders. queryWorkloads</code></p>
<p><code>agentidentity. authorizations. get</code></p>
<p><code>agentidentity. authorizations. list</code></p>
<p><code>agentidentity.locations.*</code></p>
<ul>
<li><code>agentidentity.locations.get</code></li>
<li><code>agentidentity.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Agent Identity User
<p>( <code>roles/ agentidentity.user</code> )</p>
<p>Grants access to retrieve and exchange credentials from auth providers and authorizations.</p></td>
<td><p><code>agentidentity. authProviders. retrieveCredentials</code></p></td>
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
<td><code>agentidentity. accessSummaries. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity. accessSummaries. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>agentidentity. authProviders. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>agentidentity. authProviders. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity. authProviders. queryWorkloads</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. retrieveCredentials</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.user">Agent Identity User</a> ( <code>roles/ agentidentity.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.user">Connector User</a> ( <code>roles/ iamconnectors.user</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity. authProviders. revokeAuthorizations</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity. authProviders. undelete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authProviders. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>agentidentity. authorizations. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity. authorizations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity. authorizations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><code>agentidentity.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><code>agentidentity.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.admin">Agent Identity Admin</a> ( <code>roles/ agentidentity.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.editor">Agent Identity Editor</a> ( <code>roles/ agentidentity.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/agentidentity#agentidentity.viewer">Agent Identity Viewer</a> ( <code>roles/ agentidentity.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.admin">Connector Admin</a> ( <code>roles/ iamconnectors.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.editor">Connector Editor</a> ( <code>roles/ iamconnectors.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iamconnectors#iamconnectors.viewer">Connector Viewer</a> ( <code>roles/ iamconnectors.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
