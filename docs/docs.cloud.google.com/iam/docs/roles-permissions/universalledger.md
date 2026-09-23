---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/universalledger
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger
title: Universal Ledger roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Universal Ledger. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Universal Ledger roles

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
<td><h4 id="universalledger.admin" class="role-title add-link" data-text="Universal Ledger Admin Beta" tabindex="-1">Universal Ledger Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p>Grants access to endpoints and networks, including the ability to submit transactions. Currently, this role has the same permissions as the Universal Ledger Editor role.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.endpoints.get</code></li>
<li><code dir="ltr" translate="no">universalledger.endpoints.list</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  submit</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.editor" class="role-title add-link" data-text="Universal Ledger Editor Beta" tabindex="-1">Universal Ledger Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p>Grants access to endpoints and networks, including the ability to submit transactions.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.endpoints.get</code></li>
<li><code dir="ltr" translate="no">universalledger.endpoints.list</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  submit</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="universalledger.viewer" class="role-title add-link" data-text="Universal Ledger Viewer Beta" tabindex="-1">Universal Ledger Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p>Grants the ability to view endpoints, and query the network via an endpoint.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.endpoints.get</code></p>
<p><code dir="ltr" translate="no">universalledger.endpoints.list</code></p>
<p><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></p>
<p><code dir="ltr" translate="no">universalledger.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.endpointViewer" class="role-title add-link" data-text="Universal Ledger Endpoint Viewer Beta" tabindex="-1">Universal Ledger Endpoint Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.endpointViewer</code> )</p>
<p>Grants the ability to read the endpoints for a given project.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.endpoints.get</code></p>
<p><code dir="ltr" translate="no">universalledger.endpoints.list</code></p>
<p><code dir="ltr" translate="no">universalledger.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="universalledger.networkUser" class="role-title add-link" data-text="Universal Ledger Network User Beta" tabindex="-1">Universal Ledger Network User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p>Grants full access to the GCUL Network, including the ability to send transactions.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.endpoints.get</code></li>
<li><code dir="ltr" translate="no">universalledger.endpoints.list</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></li>
<li><code dir="ltr" translate="no">universalledger.  endpoints.  submit</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.networkViewer" class="role-title add-link" data-text="Universal Ledger Network Viewer Beta" tabindex="-1">Universal Ledger Network Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p>Grants the ability to retrieve a specific endpoint and query the network with it.</p></td>
<td><p><code dir="ltr" translate="no">universalledger.endpoints.get</code></p>
<p><code dir="ltr" translate="no">universalledger.endpoints.list</code></p>
<p><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></p>
<p><code dir="ltr" translate="no">universalledger.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">universalledger.locations.get</code></li>
<li><code dir="ltr" translate="no">universalledger.locations.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Universal Ledger permissions

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
<td><h4 id="universalledger.endpoints.get" class="permission-name add-link" data-text="universalledger.endpoints.get" tabindex="-1"><code dir="ltr" translate="no">universalledger.endpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer">Universal Ledger Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer">Universal Ledger Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.endpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer">Universal Ledger Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.endpoints.list" class="permission-name add-link" data-text="universalledger.endpoints.list" tabindex="-1"><code dir="ltr" translate="no">universalledger.endpoints.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer">Universal Ledger Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer">Universal Ledger Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.endpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer">Universal Ledger Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="universalledger.endpoints.readNetwork" class="permission-name add-link" data-text="universalledger.endpoints.readNetwork" tabindex="-1"><code dir="ltr" translate="no">universalledger.  endpoints.  readNetwork</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer">Universal Ledger Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer">Universal Ledger Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.endpoints.submit" class="permission-name add-link" data-text="universalledger.endpoints.submit" tabindex="-1"><code dir="ltr" translate="no">universalledger.  endpoints.  submit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="universalledger.locations.get" class="permission-name add-link" data-text="universalledger.locations.get" tabindex="-1"><code dir="ltr" translate="no">universalledger.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer">Universal Ledger Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer">Universal Ledger Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.endpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer">Universal Ledger Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="universalledger.locations.list" class="permission-name add-link" data-text="universalledger.locations.list" tabindex="-1"><code dir="ltr" translate="no">universalledger.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin">Universal Ledger Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor">Universal Ledger Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer">Universal Ledger Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer">Universal Ledger Endpoint Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.endpointViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser">Universal Ledger Network User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer">Universal Ledger Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  universalledger.networkViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  writer</code> )</p></td>
</tr>
</tbody>
</table>
