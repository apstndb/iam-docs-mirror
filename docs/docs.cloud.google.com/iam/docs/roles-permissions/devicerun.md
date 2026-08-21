---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/devicerun
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun
title: Device Run roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Device Run. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Device Run roles

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
<td><h4 id="devicerun.admin" class="role-title add-link" data-text="Device Run Admin Beta" tabindex="-1">Device Run Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p>Full access to Device Run resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">devicerun.*</code></p>
<ul>
<li><code dir="ltr" translate="no">devicerun.devices.get</code></li>
<li><code dir="ltr" translate="no">devicerun.devices.list</code></li>
<li><code dir="ltr" translate="no">devicerun.locations.get</code></li>
<li><code dir="ltr" translate="no">devicerun.locations.list</code></li>
<li><code dir="ltr" translate="no">devicerun.operations.cancel</code></li>
<li><code dir="ltr" translate="no">devicerun.operations.delete</code></li>
<li><code dir="ltr" translate="no">devicerun.operations.get</code></li>
<li><code dir="ltr" translate="no">devicerun.operations.list</code></li>
<li><code dir="ltr" translate="no">devicerun.sessions.create</code></li>
<li><code dir="ltr" translate="no">devicerun.sessions.delete</code></li>
<li><code dir="ltr" translate="no">devicerun.sessions.get</code></li>
<li><code dir="ltr" translate="no">devicerun.sessions.list</code></li>
</ul>
<p><code dir="ltr" translate="no">devicestreaming.*</code></p>
<ul>
<li><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  cancel</code></li>
<li><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  create</code></li>
<li><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  get</code></li>
<li><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></li>
<li><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.viewer" class="role-title add-link" data-text="Device Run Viewer Beta" tabindex="-1">Device Run Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p>Readonly access to Device Run resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">devicerun.devices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">devicerun.devices.get</code></li>
<li><code dir="ltr" translate="no">devicerun.devices.list</code></li>
</ul>
<p><code dir="ltr" translate="no">devicerun.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">devicerun.locations.get</code></li>
<li><code dir="ltr" translate="no">devicerun.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">devicerun.operations.get</code></p>
<p><code dir="ltr" translate="no">devicerun.operations.list</code></p>
<p><code dir="ltr" translate="no">devicerun.sessions.get</code></p>
<p><code dir="ltr" translate="no">devicerun.sessions.list</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  get</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Device Run permissions

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
<td><h4 id="devicerun.devices.get" class="permission-name add-link" data-text="devicerun.devices.get" tabindex="-1"><code dir="ltr" translate="no">devicerun.devices.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.devices.list" class="permission-name add-link" data-text="devicerun.devices.list" tabindex="-1"><code dir="ltr" translate="no">devicerun.devices.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicerun.locations.get" class="permission-name add-link" data-text="devicerun.locations.get" tabindex="-1"><code dir="ltr" translate="no">devicerun.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.locations.list" class="permission-name add-link" data-text="devicerun.locations.list" tabindex="-1"><code dir="ltr" translate="no">devicerun.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicerun.operations.cancel" class="permission-name add-link" data-text="devicerun.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">devicerun.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.operations.delete" class="permission-name add-link" data-text="devicerun.operations.delete" tabindex="-1"><code dir="ltr" translate="no">devicerun.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicerun.operations.get" class="permission-name add-link" data-text="devicerun.operations.get" tabindex="-1"><code dir="ltr" translate="no">devicerun.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.operations.list" class="permission-name add-link" data-text="devicerun.operations.list" tabindex="-1"><code dir="ltr" translate="no">devicerun.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicerun.sessions.create" class="permission-name add-link" data-text="devicerun.sessions.create" tabindex="-1"><code dir="ltr" translate="no">devicerun.sessions.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.sessions.delete" class="permission-name add-link" data-text="devicerun.sessions.delete" tabindex="-1"><code dir="ltr" translate="no">devicerun.sessions.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicerun.sessions.get" class="permission-name add-link" data-text="devicerun.sessions.get" tabindex="-1"><code dir="ltr" translate="no">devicerun.sessions.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicerun.sessions.list" class="permission-name add-link" data-text="devicerun.sessions.list" tabindex="-1"><code dir="ltr" translate="no">devicerun.sessions.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.admin">Device Run Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicerun#devicerun.viewer">Device Run Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicerun.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
