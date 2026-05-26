---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming
title: Device Streaming API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Device Streaming API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Device Streaming API roles

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
<td><h4 id="devicestreaming.admin" class="role-title add-link" data-text="Device Streaming Admin" tabindex="-1">Device Streaming Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p>Administrator owning access to Direct Access</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
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
<td><h4 id="devicestreaming.viewer" class="role-title add-link" data-text="Device Streaming Viewer" tabindex="-1">Device Streaming Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p>Viewer, able to see what device streaming sessions exist</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  get</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Device Streaming API permissions

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
<td><h4 id="devicestreaming.deviceSessions.cancel" class="permission-name add-link" data-text="devicestreaming.deviceSessions.cancel" tabindex="-1"><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicestreaming.deviceSessions.create" class="permission-name add-link" data-text="devicestreaming.deviceSessions.create" tabindex="-1"><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicestreaming.deviceSessions.get" class="permission-name add-link" data-text="devicestreaming.deviceSessions.get" tabindex="-1"><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="devicestreaming.deviceSessions.list" class="permission-name add-link" data-text="devicestreaming.deviceSessions.list" tabindex="-1"><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="devicestreaming.deviceSessions.update" class="permission-name add-link" data-text="devicestreaming.deviceSessions.update" tabindex="-1"><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
</tbody>
</table>
