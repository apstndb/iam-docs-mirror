---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork
title: Distributed Cloud Edge Network roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Distributed Cloud Edge Network. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Distributed Cloud Edge Network roles

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
<td><h4 id="edgenetwork.admin" class="role-title add-link" data-text="Edge Network Admin" tabindex="-1">Edge Network Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p>Full access to Edge Network all resources.</p></td>
<td><p><code dir="ltr" translate="no">edgenetwork.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  update</code></li>
<li><code dir="ltr" translate="no">edgenetwork.interconnects.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnects.  getDiagnostics</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  interconnects.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.locations.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.locations.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.getStatus</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  networks.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.networks.update</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.cancel</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  routers.  getRouterStatus</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.patch</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  routers.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routers.update</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.subnetworks.create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.subnetworks.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.subnetworks.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getStatus</code></li>
<li><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></li>
<li><code dir="ltr" translate="no">edgenetwork.  subnetworks.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">edgenetwork.subnetworks.update</code></li>
<li><code dir="ltr" translate="no">edgenetwork.zones.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.zones.initialize</code></li>
<li><code dir="ltr" translate="no">edgenetwork.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.editor" class="role-title add-link" data-text="Edge Network Editor" tabindex="-1">Edge Network Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p>Editor role for Edge Network</p></td>
<td><p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  create</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  delete</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  update</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getDiagnostics</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.locations.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgenetwork.networks.create</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.delete</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.getStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.update</code></p>
<p><code dir="ltr" translate="no">edgenetwork.operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.operations.cancel</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.operations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgenetwork.routers.create</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.delete</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getRouterStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.patch</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.update</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.routes.create</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.delete</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.routes.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.create</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.delete</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.update</code></p>
<p><code dir="ltr" translate="no">edgenetwork.zones.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.zones.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.zones.initialize</code></li>
<li><code dir="ltr" translate="no">edgenetwork.zones.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.viewer" class="role-title add-link" data-text="Edge Network Viewer" tabindex="-1">Edge Network Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p>Read-only access to Edge Network all resources.</p></td>
<td><p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getDiagnostics</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">edgenetwork.locations.get</code></li>
<li><code dir="ltr" translate="no">edgenetwork.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">edgenetwork.networks.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.getStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.networks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.operations.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.operations.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  routers.  getRouterStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routers.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routes.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.routes.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getStatus</code></p>
<p><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></p>
<p><code dir="ltr" translate="no">edgenetwork.zones.get</code></p>
<p><code dir="ltr" translate="no">edgenetwork.zones.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Distributed Cloud Edge Network permissions

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
<td><h4 id="edgenetwork.interconnectAttachments.create" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.create" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnectAttachments.delete" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.interconnectAttachments.get" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnectAttachments.getIamPolicy" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.interconnectAttachments.list" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnectAttachments.setIamPolicy" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.interconnectAttachments.update" class="permission-name add-link" data-text="edgenetwork.interconnectAttachments.update" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnectAttachments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnects.get" class="permission-name add-link" data-text="edgenetwork.interconnects.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.interconnects.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.interconnects.getDiagnostics" class="permission-name add-link" data-text="edgenetwork.interconnects.getDiagnostics" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnects.  getDiagnostics</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnects.getIamPolicy" class="permission-name add-link" data-text="edgenetwork.interconnects.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnects.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.interconnects.list" class="permission-name add-link" data-text="edgenetwork.interconnects.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.interconnects.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.interconnects.setIamPolicy" class="permission-name add-link" data-text="edgenetwork.interconnects.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  interconnects.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.locations.get" class="permission-name add-link" data-text="edgenetwork.locations.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.locations.list" class="permission-name add-link" data-text="edgenetwork.locations.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.networks.create" class="permission-name add-link" data-text="edgenetwork.networks.create" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.networks.delete" class="permission-name add-link" data-text="edgenetwork.networks.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.networks.get" class="permission-name add-link" data-text="edgenetwork.networks.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.networks.getIamPolicy" class="permission-name add-link" data-text="edgenetwork.networks.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  networks.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.networks.getStatus" class="permission-name add-link" data-text="edgenetwork.networks.getStatus" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.getStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.networks.list" class="permission-name add-link" data-text="edgenetwork.networks.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.networks.setIamPolicy" class="permission-name add-link" data-text="edgenetwork.networks.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  networks.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.networks.update" class="permission-name add-link" data-text="edgenetwork.networks.update" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.networks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.operations.cancel" class="permission-name add-link" data-text="edgenetwork.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.operations.delete" class="permission-name add-link" data-text="edgenetwork.operations.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.operations.get" class="permission-name add-link" data-text="edgenetwork.operations.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.operations.list" class="permission-name add-link" data-text="edgenetwork.operations.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routers.create" class="permission-name add-link" data-text="edgenetwork.routers.create" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routers.delete" class="permission-name add-link" data-text="edgenetwork.routers.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routers.get" class="permission-name add-link" data-text="edgenetwork.routers.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routers.getIamPolicy" class="permission-name add-link" data-text="edgenetwork.routers.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  routers.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routers.getRouterStatus" class="permission-name add-link" data-text="edgenetwork.routers.getRouterStatus" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  routers.  getRouterStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routers.list" class="permission-name add-link" data-text="edgenetwork.routers.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routers.patch" class="permission-name add-link" data-text="edgenetwork.routers.patch" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.patch</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routers.setIamPolicy" class="permission-name add-link" data-text="edgenetwork.routers.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  routers.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routers.update" class="permission-name add-link" data-text="edgenetwork.routers.update" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routers.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routes.create" class="permission-name add-link" data-text="edgenetwork.routes.create" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routes.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routes.delete" class="permission-name add-link" data-text="edgenetwork.routes.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routes.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.routes.get" class="permission-name add-link" data-text="edgenetwork.routes.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routes.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.routes.list" class="permission-name add-link" data-text="edgenetwork.routes.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.routes.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.subnetworks.create" class="permission-name add-link" data-text="edgenetwork.subnetworks.create" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.subnetworks.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.subnetworks.delete" class="permission-name add-link" data-text="edgenetwork.subnetworks.delete" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.subnetworks.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.subnetworks.get" class="permission-name add-link" data-text="edgenetwork.subnetworks.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.subnetworks.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.subnetworks.getIamPolicy" class="permission-name add-link" data-text="edgenetwork.subnetworks.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.subnetworks.getStatus" class="permission-name add-link" data-text="edgenetwork.subnetworks.getStatus" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  subnetworks.  getStatus</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.subnetworks.list" class="permission-name add-link" data-text="edgenetwork.subnetworks.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.subnetworks.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.subnetworks.setIamPolicy" class="permission-name add-link" data-text="edgenetwork.subnetworks.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.  subnetworks.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.subnetworks.update" class="permission-name add-link" data-text="edgenetwork.subnetworks.update" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.subnetworks.update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.zones.get" class="permission-name add-link" data-text="edgenetwork.zones.get" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.zones.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="edgenetwork.zones.initialize" class="permission-name add-link" data-text="edgenetwork.zones.initialize" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.zones.initialize</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="edgenetwork.zones.list" class="permission-name add-link" data-text="edgenetwork.zones.list" tabindex="-1"><code dir="ltr" translate="no">edgenetwork.zones.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.admin">Edge Network Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.editor">Edge Network Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/edgenetwork#edgenetwork.viewer">Edge Network Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  edgenetwork.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
