---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect
title: Apigee Connect roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Apigee Connect. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Apigee Connect roles

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
<td><h4 id="apigeeconnect.Admin" class="role-title add-link" data-text="Apigee Connect Admin" tabindex="-1">Apigee Connect Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  apigeeconnect.Admin</code> )</p>
<p>Admin of Apigee Connect</p></td>
<td><p><code dir="ltr" translate="no">apigeeconnect.connections.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="apigeeconnect.viewer" class="role-title add-link" data-text="Apigeeconnect Viewer" tabindex="-1">Apigeeconnect Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  apigeeconnect.viewer</code> )</p>
<p>Viewer role for apigeeconnect</p></td>
<td><p><code dir="ltr" translate="no">apigeeconnect.connections.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="apigeeconnect.Agent" class="role-title add-link" data-text="Apigee Connect Agent" tabindex="-1">Apigee Connect Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  apigeeconnect.Agent</code> )</p>
<p>Ability to set up Apigee Connect agent between external clusters and Google.</p></td>
<td><p><code dir="ltr" translate="no">apigeeconnect.  endpoints.  connect</code></p></td>
</tr>
</tbody>
</table>

## Apigee Connect permissions

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
<td><h4 id="apigeeconnect.connections.list" class="permission-name add-link" data-text="apigeeconnect.connections.list" tabindex="-1"><code dir="ltr" translate="no">apigeeconnect.connections.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.Admin">Apigee Connect Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeconnect.Admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.viewer">Apigeeconnect Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeconnect.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="apigeeconnect.endpoints.connect" class="permission-name add-link" data-text="apigeeconnect.endpoints.connect" tabindex="-1"><code dir="ltr" translate="no">apigeeconnect.  endpoints.  connect</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/apigeeconnect#apigeeconnect.Agent">Apigee Connect Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  apigeeconnect.Agent</code> )</p></td>
</tr>
</tbody>
</table>
