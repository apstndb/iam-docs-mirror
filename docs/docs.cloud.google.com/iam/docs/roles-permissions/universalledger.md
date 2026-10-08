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
<td>Universal Ledger Admin <sup>Beta</sup>
<p>( <code>roles/ universalledger.admin</code> )</p>
<p>Grants access to endpoints and networks, including the ability to submit transactions. Currently, this role has the same permissions as the Universal Ledger Editor role.</p></td>
<td><p><code>universalledger.*</code></p>
<ul>
<li><code>universalledger.endpoints.get</code></li>
<li><code>universalledger.endpoints.list</code></li>
<li><code>universalledger. endpoints. readNetwork</code></li>
<li><code>universalledger. endpoints. submit</code></li>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Universal Ledger Editor <sup>Beta</sup>
<p>( <code>roles/ universalledger.editor</code> )</p>
<p>Grants access to endpoints and networks, including the ability to submit transactions.</p></td>
<td><p><code>universalledger.*</code></p>
<ul>
<li><code>universalledger.endpoints.get</code></li>
<li><code>universalledger.endpoints.list</code></li>
<li><code>universalledger. endpoints. readNetwork</code></li>
<li><code>universalledger. endpoints. submit</code></li>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Universal Ledger Viewer <sup>Beta</sup>
<p>( <code>roles/ universalledger.viewer</code> )</p>
<p>Grants the ability to view endpoints, and query the network via an endpoint.</p></td>
<td><p><code>universalledger.endpoints.get</code></p>
<p><code>universalledger.endpoints.list</code></p>
<p><code>universalledger. endpoints. readNetwork</code></p>
<p><code>universalledger.locations.*</code></p>
<ul>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Universal Ledger Endpoint Viewer <sup>Beta</sup>
<p>( <code>roles/ universalledger.endpointViewer</code> )</p>
<p>Grants the ability to read the endpoints for a given project.</p></td>
<td><p><code>universalledger.endpoints.get</code></p>
<p><code>universalledger.endpoints.list</code></p>
<p><code>universalledger.locations.*</code></p>
<ul>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>Universal Ledger Network User <sup>Beta</sup>
<p>( <code>roles/ universalledger.networkUser</code> )</p>
<p>Grants full access to the GCUL Network, including the ability to send transactions.</p></td>
<td><p><code>universalledger.*</code></p>
<ul>
<li><code>universalledger.endpoints.get</code></li>
<li><code>universalledger.endpoints.list</code></li>
<li><code>universalledger. endpoints. readNetwork</code></li>
<li><code>universalledger. endpoints. submit</code></li>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Universal Ledger Network Viewer <sup>Beta</sup>
<p>( <code>roles/ universalledger.networkViewer</code> )</p>
<p>Grants the ability to retrieve a specific endpoint and query the network with it.</p></td>
<td><p><code>universalledger.endpoints.get</code></p>
<p><code>universalledger.endpoints.list</code></p>
<p><code>universalledger. endpoints. readNetwork</code></p>
<p><code>universalledger.locations.*</code></p>
<ul>
<li><code>universalledger.locations.get</code></li>
<li><code>universalledger.locations.list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Universal Ledger permissions

| Permission                                | Included in roles                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `universalledger.endpoints.get`           | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer) ( `roles/ universalledger.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Universal Ledger Endpoint Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer) ( `roles/ universalledger.endpointViewer` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` ) [Universal Ledger Network Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer) ( `roles/ universalledger.networkViewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `universalledger.endpoints.list`          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer) ( `roles/ universalledger.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Universal Ledger Endpoint Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer) ( `roles/ universalledger.endpointViewer` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` ) [Universal Ledger Network Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer) ( `roles/ universalledger.networkViewer` ) |
| `universalledger. endpoints. readNetwork` | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer) ( `roles/ universalledger.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` ) [Universal Ledger Network Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer) ( `roles/ universalledger.networkViewer` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| `universalledger. endpoints. submit`      | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` )                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| `universalledger.locations.get`           | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer) ( `roles/ universalledger.viewer` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Universal Ledger Endpoint Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer) ( `roles/ universalledger.endpointViewer` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` ) [Universal Ledger Network Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer) ( `roles/ universalledger.networkViewer` )                                                                                                                                                                                                                                                                                                                                                                                                                         |
| `universalledger.locations.list`          | [Admin](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ admin` ) [Owner](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ owner` ) [Writer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ writer` ) [Editor](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ editor` ) [Reader](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ reader` ) [Viewer](https://docs.cloud.google.com/iam/docs/roles-overview#basic) ( `roles/ viewer` ) [Security Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin) ( `roles/ iam.securityAdmin` ) [Security Reviewer](https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer) ( `roles/ iam.securityReviewer` ) [Universal Ledger Admin](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.admin) ( `roles/ universalledger.admin` ) [Universal Ledger Editor](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.editor) ( `roles/ universalledger.editor` ) [Universal Ledger Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.viewer) ( `roles/ universalledger.viewer` ) [Security Auditor](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor) ( `roles/ iam.securityAuditor` ) [Support User](https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser) ( `roles/ iam.supportUser` ) [Universal Ledger Endpoint Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.endpointViewer) ( `roles/ universalledger.endpointViewer` ) [Universal Ledger Network User](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkUser) ( `roles/ universalledger.networkUser` ) [Universal Ledger Network Viewer](https://docs.cloud.google.com/iam/docs/roles-permissions/universalledger#universalledger.networkViewer) ( `roles/ universalledger.networkViewer` ) |
