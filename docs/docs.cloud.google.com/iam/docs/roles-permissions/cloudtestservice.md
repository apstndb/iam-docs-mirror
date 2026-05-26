---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice
title: Firebase Test Lab roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Firebase Test Lab. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Firebase Test Lab roles

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
<td><h4 id="cloudtestservice.admin" class="role-title add-link" data-text="Cloud Test Service Admin" tabindex="-1">Cloud Test Service Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p>Admin role for cloudtestservice</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  update</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  use</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.viewer" class="role-title add-link" data-text="Cloud Test Service Viewer" tabindex="-1">Cloud Test Service Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p>Viewer role for cloudtestservice</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.directAccessAdmin" class="role-title add-link" data-text="Firebase Test Lab Direct Access Admin Beta" tabindex="-1">Firebase Test Lab Direct Access Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p>Administrator owning access to Direct Access</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  devicesession.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  update</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  devicesession.  use</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
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
<td><h4 id="cloudtestservice.directAccessViewer" class="role-title add-link" data-text="Firebase Test Lab Direct Access Viewer Beta" tabindex="-1">Firebase Test Lab Direct Access Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p>Viewer, able to see what direct access sessions exist</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  get</code></p>
<p><code dir="ltr" translate="no">devicestreaming.  deviceSessions.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.testAdmin" class="role-title add-link" data-text="Firebase Test Lab Admin" tabindex="-1">Firebase Test Lab Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p>Full access to all Test Lab features</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.matrices.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  create</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></li>
<li><code dir="ltr" translate="no">cloudtestservice.  matrices.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudtoolresults.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  executions.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.histories.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.settings.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.  settings.  update</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.create</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.get</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></li>
<li><code dir="ltr" translate="no">cloudtoolresults.steps.update</code></li>
</ul>
<p><code dir="ltr" translate="no">firebase.billingPlans.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.buckets.create</code></p>
<p><code dir="ltr" translate="no">storage.buckets.get</code></p>
<p><code dir="ltr" translate="no">storage.buckets.update</code></p>
<p><code dir="ltr" translate="no">storage.objects.create</code></p>
<p><code dir="ltr" translate="no">storage.objects.delete</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.testViewer" class="role-title add-link" data-text="Firebase Test Lab Viewer" tabindex="-1">Firebase Test Lab Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p>Read access to Test Lab features</p></td>
<td><p><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></p>
<p><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  executions.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.histories.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.  histories.  list</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.settings.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.get</code></p>
<p><code dir="ltr" translate="no">cloudtoolresults.steps.list</code></p>
<p><code dir="ltr" translate="no">firebase.clients.get</code></p>
<p><code dir="ltr" translate="no">firebase.clients.list</code></p>
<p><code dir="ltr" translate="no">firebase.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">storage.objects.get</code></p>
<p><code dir="ltr" translate="no">storage.objects.list</code></p></td>
</tr>
</tbody>
</table>

## Firebase Test Lab permissions

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
<td><h4 id="cloudtestservice.devicesession.cancel" class="permission-name add-link" data-text="cloudtestservice.devicesession.cancel" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.devicesession.create" class="permission-name add-link" data-text="cloudtestservice.devicesession.create" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.devicesession.get" class="permission-name add-link" data-text="cloudtestservice.devicesession.get" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.devicesession.list" class="permission-name add-link" data-text="cloudtestservice.devicesession.list" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.devicesession.update" class="permission-name add-link" data-text="cloudtestservice.devicesession.update" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.devicesession.use" class="permission-name add-link" data-text="cloudtestservice.devicesession.use" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  devicesession.  use</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.environmentcatalog.get" class="permission-name add-link" data-text="cloudtestservice.environmentcatalog.get" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  environmentcatalog.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.admin">Device Streaming Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/devicestreaming#devicestreaming.viewer">Device Streaming Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  devicestreaming.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessAdmin">Firebase Test Lab Direct Access Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.directAccessViewer">Firebase Test Lab Direct Access Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.directAccessViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.matrices.create" class="permission-name add-link" data-text="cloudtestservice.matrices.create" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  matrices.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudtestservice.matrices.get" class="permission-name add-link" data-text="cloudtestservice.matrices.get" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.matrices.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.viewer">Cloud Test Service Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testViewer">Firebase Test Lab Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudtestservice.matrices.update" class="permission-name add-link" data-text="cloudtestservice.matrices.update" tabindex="-1"><code dir="ltr" translate="no">cloudtestservice.  matrices.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.admin">Cloud Test Service Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudtestservice#cloudtestservice.testAdmin">Firebase Test Lab Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudtestservice.testAdmin</code> )</p></td>
</tr>
</tbody>
</table>
