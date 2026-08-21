---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/prodactuation
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation
title: Production Actuation Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Production Actuation Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Production Actuation Service roles

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
<td><h4 id="prodactuation.admin" class="role-title add-link" data-text="ProdActuation API Admin Beta" tabindex="-1">ProdActuation API Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p>Full access to ProdActuation API resources.</p></td>
<td><p><code dir="ltr" translate="no">prodactuation.*</code></p>
<ul>
<li><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  create</code></li>
<li><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">prodactuation.dnsConfigs.get</code></li>
<li><code dir="ltr" translate="no">prodactuation.dnsConfigs.list</code></li>
<li><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  update</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  create</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  createMembership</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  delete</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  get</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  list</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  listMemberships</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  update</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  delete</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  get</code></li>
<li><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  update</code></li>
<li><code dir="ltr" translate="no">prodactuation.locations.get</code></li>
<li><code dir="ltr" translate="no">prodactuation.locations.list</code></li>
<li><code dir="ltr" translate="no">prodactuation.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">prodactuation.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">prodactuation.operations.get</code></li>
<li><code dir="ltr" translate="no">prodactuation.operations.list</code></li>
<li><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  create</code></li>
<li><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  delete</code></li>
<li><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  get</code></li>
<li><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  list</code></li>
<li><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.viewer" class="role-title add-link" data-text="ProdActuation API Viewer Beta" tabindex="-1">ProdActuation API Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p>Readonly access to ProdActuation API resources.</p></td>
<td><p><code dir="ltr" translate="no">prodactuation.dnsConfigs.get</code></p>
<p><code dir="ltr" translate="no">prodactuation.dnsConfigs.list</code></p>
<p><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  get</code></p>
<p><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  list</code></p>
<p><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  listMemberships</code></p>
<p><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  get</code></p>
<p><code dir="ltr" translate="no">prodactuation.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">prodactuation.locations.get</code></li>
<li><code dir="ltr" translate="no">prodactuation.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">prodactuation.operations.get</code></p>
<p><code dir="ltr" translate="no">prodactuation.operations.list</code></p>
<p><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  get</code></p>
<p><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Production Actuation Service permissions

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
<td><h4 id="prodactuation.dnsConfigs.create" class="permission-name add-link" data-text="prodactuation.dnsConfigs.create" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.dnsConfigs.delete" class="permission-name add-link" data-text="prodactuation.dnsConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.dnsConfigs.get" class="permission-name add-link" data-text="prodactuation.dnsConfigs.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.dnsConfigs.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.dnsConfigs.list" class="permission-name add-link" data-text="prodactuation.dnsConfigs.list" tabindex="-1"><code dir="ltr" translate="no">prodactuation.dnsConfigs.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.dnsConfigs.update" class="permission-name add-link" data-text="prodactuation.dnsConfigs.update" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  dnsConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.ganpatiGroups.create" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.create" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.ganpatiGroups.createMembership" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.createMembership" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  createMembership</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.ganpatiGroups.delete" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.delete" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.ganpatiGroups.get" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.ganpatiGroups.list" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.list" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.ganpatiGroups.listMemberships" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.listMemberships" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  listMemberships</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.ganpatiGroups.update" class="permission-name add-link" data-text="prodactuation.ganpatiGroups.update" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiGroups.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.ganpatiMemberships.delete" class="permission-name add-link" data-text="prodactuation.ganpatiMemberships.delete" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.ganpatiMemberships.get" class="permission-name add-link" data-text="prodactuation.ganpatiMemberships.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.ganpatiMemberships.update" class="permission-name add-link" data-text="prodactuation.ganpatiMemberships.update" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  ganpatiMemberships.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.locations.get" class="permission-name add-link" data-text="prodactuation.locations.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.locations.list" class="permission-name add-link" data-text="prodactuation.locations.list" tabindex="-1"><code dir="ltr" translate="no">prodactuation.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.operations.cancel" class="permission-name add-link" data-text="prodactuation.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.operations.delete" class="permission-name add-link" data-text="prodactuation.operations.delete" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.operations.get" class="permission-name add-link" data-text="prodactuation.operations.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.operations.list" class="permission-name add-link" data-text="prodactuation.operations.list" tabindex="-1"><code dir="ltr" translate="no">prodactuation.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.uberProxyServices.create" class="permission-name add-link" data-text="prodactuation.uberProxyServices.create" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.uberProxyServices.delete" class="permission-name add-link" data-text="prodactuation.uberProxyServices.delete" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.uberProxyServices.get" class="permission-name add-link" data-text="prodactuation.uberProxyServices.get" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="prodactuation.uberProxyServices.list" class="permission-name add-link" data-text="prodactuation.uberProxyServices.list" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.viewer">ProdActuation API Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="prodactuation.uberProxyServices.update" class="permission-name add-link" data-text="prodactuation.uberProxyServices.update" tabindex="-1"><code dir="ltr" translate="no">prodactuation.  uberProxyServices.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/prodactuation#prodactuation.admin">ProdActuation API Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  prodactuation.admin</code> )</p></td>
</tr>
</tbody>
</table>
