---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice
title: RISC Configuration Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for RISC Configuration Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## RISC Configuration Service roles

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
<td><h4 id="riscconfigs.admin" class="role-title add-link" data-text="RISC Configuration Admin Beta" tabindex="-1">RISC Configuration Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riscconfigs.admin</code> )</p>
<p>Read/write access to RISC config resources.</p></td>
<td><p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">riscconfigurationservice.*</code></p>
<ul>
<li><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  createOrUpdate</code></li>
<li><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  delete</code></li>
<li><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  get</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="riscconfigs.viewer" class="role-title add-link" data-text="RISC Configuration Viewer Beta" tabindex="-1">RISC Configuration Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  riscconfigs.viewer</code> )</p>
<p>Read-only access to RISC config resources.</p></td>
<td><p><code dir="ltr" translate="no">clientauthconfig.clients.list</code></p>
<p><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  get</code></p></td>
</tr>
</tbody>
</table>

## RISC Configuration Service permissions

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
<td><h4 id="riscconfigurationservice.riscconfigs.createOrUpdate" class="permission-name add-link" data-text="riscconfigurationservice.riscconfigs.createOrUpdate" tabindex="-1"><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  createOrUpdate</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin">RISC Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riscconfigs.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="riscconfigurationservice.riscconfigs.delete" class="permission-name add-link" data-text="riscconfigurationservice.riscconfigs.delete" tabindex="-1"><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin">RISC Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riscconfigs.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="riscconfigurationservice.riscconfigs.get" class="permission-name add-link" data-text="riscconfigurationservice.riscconfigs.get" tabindex="-1"><code dir="ltr" translate="no">riscconfigurationservice.  riscconfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.admin">RISC Configuration Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riscconfigs.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/riscconfigurationservice#riscconfigs.viewer">RISC Configuration Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  riscconfigs.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
