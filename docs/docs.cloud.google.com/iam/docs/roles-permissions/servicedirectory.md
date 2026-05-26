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
<td><h4 id="servicedirectory.admin" class="role-title add-link" data-text="Service Directory Admin" tabindex="-1">Service Directory Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p>Full control of all Service Directory resources and permissions.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.endpoints.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  create</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  delete</code></li>
<li><code dir="ltr" translate="no">servicedirectory.endpoints.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  endpoints.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.locations.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.namespaces.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  associatePrivateZone</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  namespaces.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.  networks.  attach</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.services.bind</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  create</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></li>
<li><code dir="ltr" translate="no">servicedirectory.services.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.services.list</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  resolve</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  services.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.editor" class="role-title add-link" data-text="Service Directory Editor" tabindex="-1">Service Directory Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Edit Service Directory resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.endpoints.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  update</code></p>
<p><code dir="ltr" translate="no">servicedirectory.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.locations.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  associatePrivateZone</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  update</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  networks.  attach</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.bind</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  resolve</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  update</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.viewer" class="role-title add-link" data-text="Service Directory Viewer" tabindex="-1">Service Directory Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p>View Service Directory resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.endpoints.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.locations.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  resolve</code></p></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.networkAttacher" class="role-title add-link" data-text="Service Directory Network Attacher" tabindex="-1">Service Directory Network Attacher</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.networkAttacher</code> )</p>
<p>Gives access to attach VPC Networks to Service Directory Endpoints</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  networks.  attach</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.pscAuthorizedService" class="role-title add-link" data-text="Private Service Connect Authorized Service" tabindex="-1">Private Service Connect Authorized Service</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.pscAuthorizedService</code> )</p>
<p>Gives access to VPC Networks via Service Directory</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  networks.  access</code></p></td>
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
<td><h4 id="servicedirectory.serviceAgent" class="role-title add-link" data-text="Service Directory Service Agent" tabindex="-1">Service Directory Service Agent</h4>
<p>( <code dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</p>
<p>Give the Service Directory service agent access to Cloud Platform resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code dir="ltr" translate="no">container.clusters.get</code></p>
<p><code dir="ltr" translate="no">gkehub.features.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.delete</code></p>
<p><code dir="ltr" translate="no">gkehub.  gateway.  generateCredentials</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.get</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.patch</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.post</code></p>
<p><code dir="ltr" translate="no">gkehub.gateway.put</code></p>
<p><code dir="ltr" translate="no">gkehub.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">gkehub.locations.get</code></li>
<li><code dir="ltr" translate="no">gkehub.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">gkehub.memberships.get</code></p>
<p><code dir="ltr" translate="no">gkehub.memberships.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.endpoints.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  endpoints.  update</code></p>
<p><code dir="ltr" translate="no">servicedirectory.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">servicedirectory.locations.get</code></li>
<li><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  associatePrivateZone</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  namespaces.  update</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  networks.  attach</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.bind</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  create</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.get</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">servicedirectory.services.list</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  resolve</code></p>
<p><code dir="ltr" translate="no">servicedirectory.  services.  update</code></p></td>
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
<td><h4 id="servicedirectory.endpoints.create" class="permission-name add-link" data-text="servicedirectory.endpoints.create" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.endpoints.delete" class="permission-name add-link" data-text="servicedirectory.endpoints.delete" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.endpoints.get" class="permission-name add-link" data-text="servicedirectory.endpoints.get" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.endpoints.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.endpoints.getIamPolicy" class="permission-name add-link" data-text="servicedirectory.endpoints.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.endpoints.list" class="permission-name add-link" data-text="servicedirectory.endpoints.list" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.endpoints.setIamPolicy" class="permission-name add-link" data-text="servicedirectory.endpoints.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.endpoints.update" class="permission-name add-link" data-text="servicedirectory.endpoints.update" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  endpoints.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.locations.get" class="permission-name add-link" data-text="servicedirectory.locations.get" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.locations.list" class="permission-name add-link" data-text="servicedirectory.locations.list" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.namespaces.associatePrivateZone" class="permission-name add-link" data-text="servicedirectory.namespaces.associatePrivateZone" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  associatePrivateZone</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.namespaces.create" class="permission-name add-link" data-text="servicedirectory.namespaces.create" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.namespaces.delete" class="permission-name add-link" data-text="servicedirectory.namespaces.delete" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.namespaces.get" class="permission-name add-link" data-text="servicedirectory.namespaces.get" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.namespaces.getIamPolicy" class="permission-name add-link" data-text="servicedirectory.namespaces.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.namespaces.list" class="permission-name add-link" data-text="servicedirectory.namespaces.list" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.namespaces.setIamPolicy" class="permission-name add-link" data-text="servicedirectory.namespaces.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.namespaces.update" class="permission-name add-link" data-text="servicedirectory.namespaces.update" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  namespaces.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.networks.access" class="permission-name add-link" data-text="servicedirectory.networks.access" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  networks.  access</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.pscAuthorizedService">Private Service Connect Authorized Service</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.pscAuthorizedService</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.networks.attach" class="permission-name add-link" data-text="servicedirectory.networks.attach" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  networks.  attach</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.networkAttacher">Service Directory Network Attacher</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.networkAttacher</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.services.bind" class="permission-name add-link" data-text="servicedirectory.services.bind" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.services.bind</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.services.create" class="permission-name add-link" data-text="servicedirectory.services.create" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.services.delete" class="permission-name add-link" data-text="servicedirectory.services.delete" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.networkAdmin">Compute Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/compute#compute.peerSubnetMigrationAdmin">Compute Peer Subnet Migration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  compute.peerSubnetMigrationAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.infrastructureAdmin">Infrastructure Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.infrastructureAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.networkAdmin">Network Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.networkAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.networkAdmin">Cloud Workstations Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.networkAdmin</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/tpu#cloudtpu.serviceAgent">Cloud TPU V2 API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtpu.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/composer#composer.serviceAgent">Cloud Composer API Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  composer.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/container#container.serviceAgent">Kubernetes Engine Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  container.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/dataflow#dataflow.serviceAgent">Cloud Dataflow Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  dataflow.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/managedkafka#managedkafka.serviceAgent">Managed Kafka Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  managedkafka.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/metastore#metastore.serviceAgent">Dataproc Metastore Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  metastore.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/networkconnectivity#networkconnectivity.serviceAgent">Network Connectivity Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  networkconnectivity.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/workstations#workstations.serviceAgent">Workstations Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  workstations.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.services.get" class="permission-name add-link" data-text="servicedirectory.services.get" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.services.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.services.getIamPolicy" class="permission-name add-link" data-text="servicedirectory.services.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.services.list" class="permission-name add-link" data-text="servicedirectory.services.list" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.services.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.services.resolve" class="permission-name add-link" data-text="servicedirectory.services.resolve" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  resolve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.viewer">Service Directory Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudbuild#cloudbuild.serviceAgent">Cloud Build Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudbuild.serviceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/monitoring#monitoring.notificationServiceAgent">Monitoring Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  monitoring.notificationServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="servicedirectory.services.setIamPolicy" class="permission-name add-link" data-text="servicedirectory.services.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="servicedirectory.services.update" class="permission-name add-link" data-text="servicedirectory.services.update" tabindex="-1"><code dir="ltr" translate="no">servicedirectory.  services.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.admin">Service Directory Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.editor">Service Directory Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.editor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/servicedirectory#servicedirectory.serviceAgent">Service Directory Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  servicedirectory.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
