---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager
title: Blockchain Validator Manager roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Blockchain Validator Manager. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Blockchain Validator Manager roles

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
<td><h4 id="blockchainvalidatormanager.admin" class="role-title add-link" data-text="Blockchain Validator Manager Admin Beta" tabindex="-1">Blockchain Validator Manager Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p>Full access to Blockchain Validator Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">blockchainvalidatormanager.*</code></p>
<ul>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  create</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  delete</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  get</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  list</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  update</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  list</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.viewer" class="role-title add-link" data-text="Blockchain Validator Viewer Beta" tabindex="-1">Blockchain Validator Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p>Readonly access to Blockchain Validator Manager resources.</p></td>
<td><p><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  get</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  list</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  get</code></li>
<li><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  get</code></p>
<p><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Blockchain Validator Manager permissions

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
<td><h4 id="blockchainvalidatormanager.blockchainValidatorConfigs.create" class="permission-name add-link" data-text="blockchainvalidatormanager.blockchainValidatorConfigs.create" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.blockchainValidatorConfigs.delete" class="permission-name add-link" data-text="blockchainvalidatormanager.blockchainValidatorConfigs.delete" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainvalidatormanager.blockchainValidatorConfigs.get" class="permission-name add-link" data-text="blockchainvalidatormanager.blockchainValidatorConfigs.get" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.blockchainValidatorConfigs.list" class="permission-name add-link" data-text="blockchainvalidatormanager.blockchainValidatorConfigs.list" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainvalidatormanager.blockchainValidatorConfigs.update" class="permission-name add-link" data-text="blockchainvalidatormanager.blockchainValidatorConfigs.update" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  blockchainValidatorConfigs.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.locations.get" class="permission-name add-link" data-text="blockchainvalidatormanager.locations.get" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainvalidatormanager.locations.list" class="permission-name add-link" data-text="blockchainvalidatormanager.locations.list" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.operations.cancel" class="permission-name add-link" data-text="blockchainvalidatormanager.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainvalidatormanager.operations.delete" class="permission-name add-link" data-text="blockchainvalidatormanager.operations.delete" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="blockchainvalidatormanager.operations.get" class="permission-name add-link" data-text="blockchainvalidatormanager.operations.get" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="blockchainvalidatormanager.operations.list" class="permission-name add-link" data-text="blockchainvalidatormanager.operations.list" tabindex="-1"><code dir="ltr" translate="no">blockchainvalidatormanager.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.admin">Blockchain Validator Manager Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/blockchainvalidatormanager#blockchainvalidatormanager.viewer">Blockchain Validator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  blockchainvalidatormanager.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
