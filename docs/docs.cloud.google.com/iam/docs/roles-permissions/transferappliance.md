---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/transferappliance
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance
title: Transfer Appliance roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Transfer Appliance. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Transfer Appliance roles

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
<td><h4 id="transferappliance.admin" class="role-title add-link" data-text="Transfer Appliance Admin Beta" tabindex="-1">Transfer Appliance Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p>Full access to Transfer Appliance all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.*</code></p>
<ul>
<li><code dir="ltr" translate="no">transferappliance.  appliances.  create</code></li>
<li><code dir="ltr" translate="no">transferappliance.  appliances.  delete</code></li>
<li><code dir="ltr" translate="no">transferappliance.  appliances.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  appliances.  list</code></li>
<li><code dir="ltr" translate="no">transferappliance.  appliances.  update</code></li>
<li><code dir="ltr" translate="no">transferappliance.  credentials.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  locations.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  locations.  list</code></li>
<li><code dir="ltr" translate="no">transferappliance.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">transferappliance.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">transferappliance.  operations.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  operations.  list</code></li>
<li><code dir="ltr" translate="no">transferappliance.  orders.  create</code></li>
<li><code dir="ltr" translate="no">transferappliance.  orders.  delete</code></li>
<li><code dir="ltr" translate="no">transferappliance.orders.get</code></li>
<li><code dir="ltr" translate="no">transferappliance.orders.list</code></li>
<li><code dir="ltr" translate="no">transferappliance.  orders.  update</code></li>
<li><code dir="ltr" translate="no">transferappliance.  savedAddresses.  create</code></li>
<li><code dir="ltr" translate="no">transferappliance.  savedAddresses.  delete</code></li>
<li><code dir="ltr" translate="no">transferappliance.  savedAddresses.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  savedAddresses.  list</code></li>
<li><code dir="ltr" translate="no">transferappliance.  savedAddresses.  update</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.viewer" class="role-title add-link" data-text="Transfer Appliance Viewer Beta" tabindex="-1">Transfer Appliance Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p>Read-only access to Transfer Appliance all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  appliances.  get</code></p>
<p><code dir="ltr" translate="no">transferappliance.  appliances.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">transferappliance.  locations.  get</code></li>
<li><code dir="ltr" translate="no">transferappliance.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">transferappliance.  operations.  get</code></p>
<p><code dir="ltr" translate="no">transferappliance.  operations.  list</code></p>
<p><code dir="ltr" translate="no">transferappliance.orders.get</code></p>
<p><code dir="ltr" translate="no">transferappliance.orders.list</code></p>
<p><code dir="ltr" translate="no">transferappliance.  savedAddresses.  get</code></p>
<p><code dir="ltr" translate="no">transferappliance.  savedAddresses.  list</code></p></td>
</tr>
</tbody>
</table>

## Transfer Appliance permissions

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
<td><h4 id="transferappliance.appliances.create" class="permission-name add-link" data-text="transferappliance.appliances.create" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  appliances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.appliances.delete" class="permission-name add-link" data-text="transferappliance.appliances.delete" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  appliances.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.appliances.get" class="permission-name add-link" data-text="transferappliance.appliances.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  appliances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.appliances.list" class="permission-name add-link" data-text="transferappliance.appliances.list" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  appliances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.appliances.update" class="permission-name add-link" data-text="transferappliance.appliances.update" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  appliances.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.credentials.get" class="permission-name add-link" data-text="transferappliance.credentials.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  credentials.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.locations.get" class="permission-name add-link" data-text="transferappliance.locations.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.locations.list" class="permission-name add-link" data-text="transferappliance.locations.list" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.operations.cancel" class="permission-name add-link" data-text="transferappliance.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.operations.delete" class="permission-name add-link" data-text="transferappliance.operations.delete" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.operations.get" class="permission-name add-link" data-text="transferappliance.operations.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.operations.list" class="permission-name add-link" data-text="transferappliance.operations.list" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.orders.create" class="permission-name add-link" data-text="transferappliance.orders.create" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  orders.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.orders.delete" class="permission-name add-link" data-text="transferappliance.orders.delete" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  orders.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.orders.get" class="permission-name add-link" data-text="transferappliance.orders.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.orders.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.orders.list" class="permission-name add-link" data-text="transferappliance.orders.list" tabindex="-1"><code dir="ltr" translate="no">transferappliance.orders.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.orders.update" class="permission-name add-link" data-text="transferappliance.orders.update" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  orders.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.savedAddresses.create" class="permission-name add-link" data-text="transferappliance.savedAddresses.create" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  savedAddresses.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.savedAddresses.delete" class="permission-name add-link" data-text="transferappliance.savedAddresses.delete" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  savedAddresses.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.savedAddresses.get" class="permission-name add-link" data-text="transferappliance.savedAddresses.get" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  savedAddresses.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="transferappliance.savedAddresses.list" class="permission-name add-link" data-text="transferappliance.savedAddresses.list" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  savedAddresses.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.viewer">Transfer Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="transferappliance.savedAddresses.update" class="permission-name add-link" data-text="transferappliance.savedAddresses.update" tabindex="-1"><code dir="ltr" translate="no">transferappliance.  savedAddresses.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/transferappliance#transferappliance.admin">Transfer Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  transferappliance.admin</code> )</p></td>
</tr>
</tbody>
</table>
