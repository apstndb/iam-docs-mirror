---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions
title: Marketplace Solutions API roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Marketplace Solutions API. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Marketplace Solutions API roles

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
<td><h4 id="marketplacesolutions.admin" class="role-title add-link" data-text="Marketplace Solutions Admin Beta" tabindex="-1">Marketplace Solutions Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p>Full access to Marketplace Solutions resources.</p></td>
<td><p><code dir="ltr" translate="no">marketplacesolutions.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  operations.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  applyPowerAction</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  create</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  delete</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  reset</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  update</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.editor" class="role-title add-link" data-text="Marketplace Solutions Editor Beta" tabindex="-1">Marketplace Solutions Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p>Edit access to Marketplace Solutions resources.</p></td>
<td><p><code dir="ltr" translate="no">marketplacesolutions.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  get</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerImages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  get</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  update</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.viewer" class="role-title add-link" data-text="Marketplace Solutions Viewer Beta" tabindex="-1">Marketplace Solutions Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p>Readonly access to Marketplace Solutions resources.</p></td>
<td><p><code dir="ltr" translate="no">marketplacesolutions.  locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  get</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerImages.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  get</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></p>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.*</code></p>
<ul>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  get</code></li>
<li><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Marketplace Solutions API permissions

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
<td><h4 id="marketplacesolutions.locations.get" class="permission-name add-link" data-text="marketplacesolutions.locations.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.locations.list" class="permission-name add-link" data-text="marketplacesolutions.locations.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.operations.cancel" class="permission-name add-link" data-text="marketplacesolutions.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.operations.delete" class="permission-name add-link" data-text="marketplacesolutions.operations.delete" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.operations.get" class="permission-name add-link" data-text="marketplacesolutions.operations.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.operations.list" class="permission-name add-link" data-text="marketplacesolutions.operations.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerImages.get" class="permission-name add-link" data-text="marketplacesolutions.powerImages.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerImages.list" class="permission-name add-link" data-text="marketplacesolutions.powerImages.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerImages.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerInstances.applyPowerAction" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.applyPowerAction" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  applyPowerAction</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerInstances.create" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.create" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerInstances.delete" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.delete" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerInstances.get" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerInstances.list" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerInstances.reset" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.reset" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  reset</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerInstances.update" class="permission-name add-link" data-text="marketplacesolutions.powerInstances.update" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerInstances.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerNetworks.get" class="permission-name add-link" data-text="marketplacesolutions.powerNetworks.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerNetworks.list" class="permission-name add-link" data-text="marketplacesolutions.powerNetworks.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerNetworks.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerSshKeys.get" class="permission-name add-link" data-text="marketplacesolutions.powerSshKeys.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerSshKeys.list" class="permission-name add-link" data-text="marketplacesolutions.powerSshKeys.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerSshKeys.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="marketplacesolutions.powerVolumes.get" class="permission-name add-link" data-text="marketplacesolutions.powerVolumes.get" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="marketplacesolutions.powerVolumes.list" class="permission-name add-link" data-text="marketplacesolutions.powerVolumes.list" tabindex="-1"><code dir="ltr" translate="no">marketplacesolutions.  powerVolumes.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.admin">Marketplace Solutions Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.editor">Marketplace Solutions Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/marketplacesolutions#marketplacesolutions.viewer">Marketplace Solutions Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  marketplacesolutions.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
