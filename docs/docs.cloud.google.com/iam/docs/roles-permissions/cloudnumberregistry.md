---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry
title: Cloud Number Registry roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud Number Registry. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud Number Registry roles

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
<td><h4 id="cloudnumberregistry.ipamAdmin" class="role-title add-link" data-text="Cloud Number Registry IPAM Admin Beta" tabindex="-1">Cloud Number Registry IPAM Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p>Full access to Cloud Number Registry resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudnumberregistry.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  create</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  delete</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  update</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  create</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  delete</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  update</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  locations.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  locations.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  operations.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  operations.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  realms.  create</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  realms.  delete</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.realms.get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  realms.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  realms.  update</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  create</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  delete</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  list</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.ipamViewer" class="role-title add-link" data-text="Cloud Number Registry IPAM Viewer Beta" tabindex="-1">Cloud Number Registry IPAM Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p>Readonly access to Cloud Number Registry resources.</p></td>
<td><p><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  get</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  get</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">cloudnumberregistry.  locations.  get</code></li>
<li><code dir="ltr" translate="no">cloudnumberregistry.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">cloudnumberregistry.  operations.  get</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  operations.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.realms.get</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  realms.  list</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  get</code></p>
<p><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud Number Registry permissions

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
<td><h4 id="cloudnumberregistry.customRanges.create" class="permission-name add-link" data-text="cloudnumberregistry.customRanges.create" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.customRanges.delete" class="permission-name add-link" data-text="cloudnumberregistry.customRanges.delete" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.customRanges.get" class="permission-name add-link" data-text="cloudnumberregistry.customRanges.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.customRanges.list" class="permission-name add-link" data-text="cloudnumberregistry.customRanges.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.customRanges.update" class="permission-name add-link" data-text="cloudnumberregistry.customRanges.update" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  customRanges.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.discoveredRanges.get" class="permission-name add-link" data-text="cloudnumberregistry.discoveredRanges.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.discoveredRanges.list" class="permission-name add-link" data-text="cloudnumberregistry.discoveredRanges.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  discoveredRanges.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.ipamAdminScopes.create" class="permission-name add-link" data-text="cloudnumberregistry.ipamAdminScopes.create" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.ipamAdminScopes.delete" class="permission-name add-link" data-text="cloudnumberregistry.ipamAdminScopes.delete" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.ipamAdminScopes.get" class="permission-name add-link" data-text="cloudnumberregistry.ipamAdminScopes.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.ipamAdminScopes.list" class="permission-name add-link" data-text="cloudnumberregistry.ipamAdminScopes.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.ipamAdminScopes.update" class="permission-name add-link" data-text="cloudnumberregistry.ipamAdminScopes.update" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  ipamAdminScopes.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.locations.get" class="permission-name add-link" data-text="cloudnumberregistry.locations.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.locations.list" class="permission-name add-link" data-text="cloudnumberregistry.locations.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.operations.cancel" class="permission-name add-link" data-text="cloudnumberregistry.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.operations.delete" class="permission-name add-link" data-text="cloudnumberregistry.operations.delete" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.operations.get" class="permission-name add-link" data-text="cloudnumberregistry.operations.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.operations.list" class="permission-name add-link" data-text="cloudnumberregistry.operations.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.realms.create" class="permission-name add-link" data-text="cloudnumberregistry.realms.create" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  realms.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.realms.delete" class="permission-name add-link" data-text="cloudnumberregistry.realms.delete" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  realms.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.realms.get" class="permission-name add-link" data-text="cloudnumberregistry.realms.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.realms.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.realms.list" class="permission-name add-link" data-text="cloudnumberregistry.realms.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  realms.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.realms.update" class="permission-name add-link" data-text="cloudnumberregistry.realms.update" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  realms.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.registryBooks.create" class="permission-name add-link" data-text="cloudnumberregistry.registryBooks.create" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.registryBooks.delete" class="permission-name add-link" data-text="cloudnumberregistry.registryBooks.delete" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.registryBooks.get" class="permission-name add-link" data-text="cloudnumberregistry.registryBooks.get" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="cloudnumberregistry.registryBooks.list" class="permission-name add-link" data-text="cloudnumberregistry.registryBooks.list" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamViewer">Cloud Number Registry IPAM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="cloudnumberregistry.registryBooks.update" class="permission-name add-link" data-text="cloudnumberregistry.registryBooks.update" tabindex="-1"><code dir="ltr" translate="no">cloudnumberregistry.  registryBooks.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudnumberregistry#cloudnumberregistry.ipamAdmin">Cloud Number Registry IPAM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudnumberregistry.ipamAdmin</code> )</p></td>
</tr>
</tbody>
</table>
