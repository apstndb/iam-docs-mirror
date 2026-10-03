---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions
title: Service Extensions roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Extensions. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Extensions roles

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
<td>Service Extensions Admin <sup>Beta</sup>
<p>( <code>roles/ serviceextensions.admin</code> )</p>
<p>Grants full access to Service Extensions resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceextensions.*</code></p>
<ul>
<li><code>serviceextensions. callouts. invoke</code></li>
<li><code>serviceextensions. locations. get</code></li>
<li><code>serviceextensions. locations. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Service Extensions Editor <sup>Beta</sup>
<p>( <code>roles/ serviceextensions.editor</code> )</p>
<p>Grants access to edit Service Extensions resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceextensions.*</code></p>
<ul>
<li><code>serviceextensions. callouts. invoke</code></li>
<li><code>serviceextensions. locations. get</code></li>
<li><code>serviceextensions. locations. list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Service Extensions Viewer <sup>Beta</sup>
<p>( <code>roles/ serviceextensions.viewer</code> )</p>
<p>Grants read access to Service Extensions resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>serviceextensions.locations.*</code></p>
<ul>
<li><code>serviceextensions. locations. get</code></li>
<li><code>serviceextensions. locations. list</code></li>
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
<td>Network Actions Service Agent
<p>( <code>roles/ networkactions.serviceAgent</code> )</p>
<p>Gives Network Actions service account access to read required resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>artifactregistry. files. download</code></p>
<p><code>artifactregistry. repositories. downloadArtifacts</code></p></td>
</tr>
</tbody>
</table>

## Service Extensions permissions

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
<td><code>serviceextensions. callouts. invoke</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code>roles/ serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code>roles/ serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/discoveryengine#discoveryengine.serviceAgent">Discovery Engine Service Agent</a> ( <code>roles/ discoveryengine.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>serviceextensions. locations. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code>roles/ serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code>roles/ serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code>roles/ serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>serviceextensions. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.admin">Service Extensions Admin</a> ( <code>roles/ serviceextensions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.editor">Service Extensions Editor</a> ( <code>roles/ serviceextensions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/serviceextensions#serviceextensions.viewer">Service Extensions Viewer</a> ( <code>roles/ serviceextensions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
