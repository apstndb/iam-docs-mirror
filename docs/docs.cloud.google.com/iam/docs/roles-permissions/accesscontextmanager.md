---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager
title: Access Context Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Access Context Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Access Context Manager roles

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
<td><h4 id="accesscontextmanager.admin" class="role-title add-link" data-text="Accesscontextmanager Admin" tabindex="-1">Accesscontextmanager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p>Admin role for accesscontextmanager</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  update</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  update</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  update</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  commit</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.editor" class="role-title add-link" data-text="Accesscontextmanager Editor" tabindex="-1">Accesscontextmanager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p>Editor role for accesscontextmanager</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  create</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  delete</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  update</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  commit</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policyAdmin" class="role-title add-link" data-text="Access Context Manager Admin" tabindex="-1">Access Context Manager Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p>Full access to policies, access levels, access zones and authorized orgs descs.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  setIamPolicy</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  policies.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  commit</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.viewer" class="role-title add-link" data-text="Accesscontextmanager Viewer" tabindex="-1">Accesscontextmanager Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p>Viewer role for accesscontextmanager</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.gcpAccessAdmin" class="role-title add-link" data-text="Cloud Access Binding Admin" tabindex="-1">Cloud Access Binding Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p>
<p>Create, edit, and change Cloud access bindings.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.gcpAccessReader" class="role-title add-link" data-text="Cloud Access Binding Reader" tabindex="-1">Cloud Access Binding Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessReader</code> )</p>
<p>Read access to Cloud access bindings.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policyEditor" class="role-title add-link" data-text="Access Context Manager Editor" tabindex="-1">Access Context Manager Editor</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Edit access to policies. Create, edit, and change access levels, access zones and authorized orgs descs.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  create</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  delete</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  update</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  commit</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  replaceAll</code></li>
<li><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.policyReader" class="role-title add-link" data-text="Access Context Manager Reader" tabindex="-1">Access Context Manager Reader</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p>Read access to policies, access levels, access zones and authorized orgs descs.</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.vpcScTroubleshooterViewer" class="role-title add-link" data-text="VPC Service Controls Troubleshooter Viewer" tabindex="-1">VPC Service Controls Troubleshooter Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p></td>
<td><p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></p>
<p><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.get</code></p>
<p><code dir="ltr" translate="no">logging.exclusions.list</code></p>
<p><code dir="ltr" translate="no">logging.logEntries.list</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.get</code></p>
<p><code dir="ltr" translate="no">logging.logMetrics.list</code></p>
<p><code dir="ltr" translate="no">logging.logServiceIndexes.list</code></p>
<p><code dir="ltr" translate="no">logging.logServices.list</code></p>
<p><code dir="ltr" translate="no">logging.logs.list</code></p>
<p><code dir="ltr" translate="no">logging.sinks.get</code></p>
<p><code dir="ltr" translate="no">logging.sinks.list</code></p>
<p><code dir="ltr" translate="no">logging.usage.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Access Context Manager permissions

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
<td><h4 id="accesscontextmanager.accessLevels.create" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.create" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.accessLevels.delete" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.delete" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.accessLevels.get" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.get" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.accessLevels.list" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.list" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.accessLevels.replaceAll" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.replaceAll" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  replaceAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.accessLevels.update" class="permission-name add-link" data-text="accesscontextmanager.accessLevels.update" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  accessLevels.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.authorizedOrgsDescs.create" class="permission-name add-link" data-text="accesscontextmanager.authorizedOrgsDescs.create" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.authorizedOrgsDescs.delete" class="permission-name add-link" data-text="accesscontextmanager.authorizedOrgsDescs.delete" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.authorizedOrgsDescs.get" class="permission-name add-link" data-text="accesscontextmanager.authorizedOrgsDescs.get" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.authorizedOrgsDescs.list" class="permission-name add-link" data-text="accesscontextmanager.authorizedOrgsDescs.list" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.authorizedOrgsDescs.update" class="permission-name add-link" data-text="accesscontextmanager.authorizedOrgsDescs.update" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  authorizedOrgsDescs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.gcpUserAccessBindings.create" class="permission-name add-link" data-text="accesscontextmanager.gcpUserAccessBindings.create" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.gcpUserAccessBindings.delete" class="permission-name add-link" data-text="accesscontextmanager.gcpUserAccessBindings.delete" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.gcpUserAccessBindings.get" class="permission-name add-link" data-text="accesscontextmanager.gcpUserAccessBindings.get" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessReader">Cloud Access Binding Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.gcpUserAccessBindings.list" class="permission-name add-link" data-text="accesscontextmanager.gcpUserAccessBindings.list" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessReader">Cloud Access Binding Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.controlServiceAgent">Security Center Control Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.controlServiceAgent</code> )</li>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securitycenter#securitycenter.serviceAgent">Security Center Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securitycenter.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.gcpUserAccessBindings.update" class="permission-name add-link" data-text="accesscontextmanager.gcpUserAccessBindings.update" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  gcpUserAccessBindings.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.gcpAccessAdmin">Cloud Access Binding Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.gcpAccessAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policies.create" class="permission-name add-link" data-text="accesscontextmanager.policies.create" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.policies.delete" class="permission-name add-link" data-text="accesscontextmanager.policies.delete" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policies.get" class="permission-name add-link" data-text="accesscontextmanager.policies.get" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.policies.getIamPolicy" class="permission-name add-link" data-text="accesscontextmanager.policies.getIamPolicy" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  getIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policies.list" class="permission-name add-link" data-text="accesscontextmanager.policies.list" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.policies.setIamPolicy" class="permission-name add-link" data-text="accesscontextmanager.policies.setIamPolicy" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  setIamPolicy</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.policies.update" class="permission-name add-link" data-text="accesscontextmanager.policies.update" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  policies.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.servicePerimeters.commit" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.commit" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  commit</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.servicePerimeters.create" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.create" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.servicePerimeters.delete" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.delete" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.servicePerimeters.get" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.get" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.servicePerimeters.list" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.list" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.viewer">Accesscontextmanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyReader">Access Context Manager Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyReader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.vpcScTroubleshooterViewer">VPC Service Controls Troubleshooter Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.vpcScTroubleshooterViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwOrgRemediator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="accesscontextmanager.servicePerimeters.replaceAll" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.replaceAll" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  replaceAll</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="accesscontextmanager.servicePerimeters.update" class="permission-name add-link" data-text="accesscontextmanager.servicePerimeters.update" tabindex="-1"><code dir="ltr" translate="no">accesscontextmanager.  servicePerimeters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.admin">Accesscontextmanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.editor">Accesscontextmanager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyAdmin">Access Context Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/accesscontextmanager#accesscontextmanager.policyEditor">Access Context Manager Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  accesscontextmanager.policyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/securedlandingzone#securedlandingzone.bqdwOrgRemediator">SLZ BQDW Blueprint Organization Level Remediator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  securedlandingzone.bqdwOrgRemediator</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/deploymentmanager#clouddeploymentmanager.serviceAgent">Cloud Deployment Manager Service Agent</a> ( <code class="role-name" dir="ltr" translate="no">roles/  clouddeploymentmanager.serviceAgent</code> )</li>
</ul></td>
</tr>
</tbody>
</table>
