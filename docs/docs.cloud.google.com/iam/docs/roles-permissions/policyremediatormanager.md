---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager
title: Policy Remediator Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Policy Remediator Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Policy Remediator Manager roles

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
<td><h4 id="policyremediatormanager.admin" class="role-title add-link" data-text="Policyremediatormanager Admin Beta" tabindex="-1">Policyremediatormanager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p>Admin role for policyremediatormanager</p></td>
<td><p><code dir="ltr" translate="no">policyremediatormanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  disable</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  enable</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  get</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.viewer" class="role-title add-link" data-text="Policyremediatormanager Viewer Beta" tabindex="-1">Policyremediatormanager Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p>Viewer role for policyremediatormanager</p></td>
<td><p><code dir="ltr" translate="no">policyremediatormanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="policyremediatormanager.policyRemediatorAdmin" class="role-title add-link" data-text="Policy Remediator Admin Beta" tabindex="-1">Policy Remediator Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p>Grants the ability to enable and disable the usage of the policy remediator for the organization</p></td>
<td><p><code dir="ltr" translate="no">policyremediatormanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  disable</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  enable</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  get</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.policyRemediatorReader" class="role-title add-link" data-text="Policy Remediator Reader Beta" tabindex="-1">Policy Remediator Reader <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p>
<p>Grants the ability to read/view the state of the policy remediator for the organization</p></td>
<td><p><code dir="ltr" translate="no">policyremediatormanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  get</code></p></td>
</tr>
</tbody>
</table>

## Policy Remediator Manager permissions

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
<td><h4 id="policyremediatormanager.locations.get" class="permission-name add-link" data-text="policyremediatormanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorReader">Policy Remediator Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.locations.list" class="permission-name add-link" data-text="policyremediatormanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorReader">Policy Remediator Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policyremediatormanager.operations.cancel" class="permission-name add-link" data-text="policyremediatormanager.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.operations.delete" class="permission-name add-link" data-text="policyremediatormanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policyremediatormanager.operations.get" class="permission-name add-link" data-text="policyremediatormanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorReader">Policy Remediator Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.operations.list" class="permission-name add-link" data-text="policyremediatormanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorReader">Policy Remediator Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policyremediatormanager.remediatorServices.disable" class="permission-name add-link" data-text="policyremediatormanager.remediatorServices.disable" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  disable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policyremediatormanager.remediatorServices.enable" class="permission-name add-link" data-text="policyremediatormanager.remediatorServices.enable" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  enable</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policyremediatormanager.remediatorServices.get" class="permission-name add-link" data-text="policyremediatormanager.remediatorServices.get" tabindex="-1"><code dir="ltr" translate="no">policyremediatormanager.  remediatorServices.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.admin">Policyremediatormanager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.viewer">Policyremediatormanager Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorAdmin">Policy Remediator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policyremediatormanager#policyremediatormanager.policyRemediatorReader">Policy Remediator Reader</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policyremediatormanager.policyRemediatorReader</code> )</p></td>
</tr>
</tbody>
</table>
