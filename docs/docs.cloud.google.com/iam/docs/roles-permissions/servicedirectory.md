---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory
title: Service Directory roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Service Directory. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Service Directory roles

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
<td>Service Directory Admin
<p>( <code>roles/ servicedirectory.admin</code> )</p>
<p>Full control of all Service Directory resources and permissions.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory.endpoints.*</code></p>
<ul>
<li><code>servicedirectory. endpoints. create</code></li>
<li><code>servicedirectory. endpoints. delete</code></li>
<li><code>servicedirectory.endpoints.get</code></li>
<li><code>servicedirectory. endpoints. getIamPolicy</code></li>
<li><code>servicedirectory. endpoints. list</code></li>
<li><code>servicedirectory. endpoints. setIamPolicy</code></li>
<li><code>servicedirectory. endpoints. update</code></li>
</ul>
<p><code>servicedirectory.locations.*</code></p>
<ul>
<li><code>servicedirectory.locations.get</code></li>
<li><code>servicedirectory. locations. list</code></li>
</ul>
<p><code>servicedirectory.namespaces.*</code></p>
<ul>
<li><code>servicedirectory. namespaces. associatePrivateZone</code></li>
<li><code>servicedirectory. namespaces. create</code></li>
<li><code>servicedirectory. namespaces. delete</code></li>
<li><code>servicedirectory. namespaces. get</code></li>
<li><code>servicedirectory. namespaces. getIamPolicy</code></li>
<li><code>servicedirectory. namespaces. list</code></li>
<li><code>servicedirectory. namespaces. setIamPolicy</code></li>
<li><code>servicedirectory. namespaces. update</code></li>
</ul>
<p><code>servicedirectory. networks. attach</code></p>
<p><code>servicedirectory.services.*</code></p>
<ul>
<li><code>servicedirectory.services.bind</code></li>
<li><code>servicedirectory. services. create</code></li>
<li><code>servicedirectory. services. delete</code></li>
<li><code>servicedirectory.services.get</code></li>
<li><code>servicedirectory. services. getIamPolicy</code></li>
<li><code>servicedirectory.services.list</code></li>
<li><code>servicedirectory. services. resolve</code></li>
<li><code>servicedirectory. services. setIamPolicy</code></li>
<li><code>servicedirectory. services. update</code></li>
</ul></td>
</tr>
<tr class="even">
<td>Service Directory Editor
<p>( <code>roles/ servicedirectory.editor</code> )</p>
<p>Edit Service Directory resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory. endpoints. create</code></p>
<p><code>servicedirectory. endpoints. delete</code></p>
<p><code>servicedirectory.endpoints.get</code></p>
<p><code>servicedirectory. endpoints. getIamPolicy</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory. endpoints. update</code></p>
<p><code>servicedirectory.locations.*</code></p>
<ul>
<li><code>servicedirectory.locations.get</code></li>
<li><code>servicedirectory. locations. list</code></li>
</ul>
<p><code>servicedirectory. namespaces. associatePrivateZone</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. namespaces. get</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory. namespaces. update</code></p>
<p><code>servicedirectory. networks. attach</code></p>
<p><code>servicedirectory.services.bind</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p>
<p><code>servicedirectory.services.get</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>servicedirectory. services. resolve</code></p>
<p><code>servicedirectory. services. update</code></p></td>
</tr>
<tr class="odd">
<td>Service Directory Viewer
<p>( <code>roles/ servicedirectory.viewer</code> )</p>
<p>View Service Directory resources.</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory.endpoints.get</code></p>
<p><code>servicedirectory. endpoints. getIamPolicy</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory.locations.*</code></p>
<ul>
<li><code>servicedirectory.locations.get</code></li>
<li><code>servicedirectory. locations. list</code></li>
</ul>
<p><code>servicedirectory. namespaces. get</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory.services.get</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>servicedirectory. services. resolve</code></p></td>
</tr>
<tr class="even">
<td>Service Directory Network Attacher
<p>( <code>roles/ servicedirectory.networkAttacher</code> )</p>
<p>Gives access to attach VPC Networks to Service Directory Endpoints</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory. networks. attach</code></p></td>
</tr>
<tr class="odd">
<td>Private Service Connect Authorized Service
<p>( <code>roles/ servicedirectory.pscAuthorizedService</code> )</p>
<p>Gives access to VPC Networks via Service Directory</p></td>
<td><p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory. networks. access</code></p></td>
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
<td>Service Directory Service Agent
<p>( <code>roles/ servicedirectory.serviceAgent</code> )</p>
<p>Give the Service Directory service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>container.clusters.get</code></p>
<p><code>gkehub.features.get</code></p>
<p><code>gkehub.gateway.delete</code></p>
<p><code>gkehub. gateway. generateCredentials</code></p>
<p><code>gkehub.gateway.get</code></p>
<p><code>gkehub.gateway.patch</code></p>
<p><code>gkehub.gateway.post</code></p>
<p><code>gkehub.gateway.put</code></p>
<p><code>gkehub.locations.*</code></p>
<ul>
<li><code>gkehub.locations.get</code></li>
<li><code>gkehub.locations.list</code></li>
</ul>
<p><code>gkehub.memberships.get</code></p>
<p><code>gkehub.memberships.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p>
<p><code>servicedirectory. endpoints. create</code></p>
<p><code>servicedirectory. endpoints. delete</code></p>
<p><code>servicedirectory.endpoints.get</code></p>
<p><code>servicedirectory. endpoints. getIamPolicy</code></p>
<p><code>servicedirectory. endpoints. list</code></p>
<p><code>servicedirectory. endpoints. update</code></p>
<p><code>servicedirectory.locations.*</code></p>
<ul>
<li><code>servicedirectory.locations.get</code></li>
<li><code>servicedirectory. locations. list</code></li>
</ul>
<p><code>servicedirectory. namespaces. associatePrivateZone</code></p>
<p><code>servicedirectory. namespaces. create</code></p>
<p><code>servicedirectory. namespaces. delete</code></p>
<p><code>servicedirectory. namespaces. get</code></p>
<p><code>servicedirectory. namespaces. getIamPolicy</code></p>
<p><code>servicedirectory. namespaces. list</code></p>
<p><code>servicedirectory. namespaces. update</code></p>
<p><code>servicedirectory. networks. attach</code></p>
<p><code>servicedirectory.services.bind</code></p>
<p><code>servicedirectory. services. create</code></p>
<p><code>servicedirectory. services. delete</code></p>
<p><code>servicedirectory.services.get</code></p>
<p><code>servicedirectory. services. getIamPolicy</code></p>
<p><code>servicedirectory.services.list</code></p>
<p><code>servicedirectory. services. resolve</code></p>
<p><code>servicedirectory. services. update</code></p></td>
</tr>
</tbody>
</table>

## Service Directory permissions

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
<td><code>servicedirectory. endpoints. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. endpoints. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory.endpoints.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. endpoints. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. endpoints. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. endpoints. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. endpoints. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. locations. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. namespaces. associatePrivateZone</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. namespaces. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code>roles/ compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code>roles/ workstations.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. namespaces. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code>roles/ workstations.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. namespaces. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. namespaces. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. namespaces. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. namespaces. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. namespaces. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. networks. access</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code>roles/ servicedirectory.pscAuthorizedService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. networks. attach</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code>roles/ servicedirectory.networkAttacher</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory.services.bind</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. services. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code>roles/ compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code>roles/ workstations.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code>roles/ clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. services. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code>roles/ compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code>roles/ compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code>roles/ iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code>roles/ iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code>roles/ workstations.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code>roles/ cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code>roles/ composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code>roles/ container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code>roles/ dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code>roles/ managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code>roles/ metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code>roles/ networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code>roles/ workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory.services.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. services. getIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory.services.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>servicedirectory. services. resolve</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code>roles/ servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code>roles/ cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code>roles/ monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>servicedirectory. services. setIamPolicy</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p></td>
</tr>
<tr class="even">
<td><code>servicedirectory. services. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code>roles/ servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code>roles/ servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code>roles/ servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
