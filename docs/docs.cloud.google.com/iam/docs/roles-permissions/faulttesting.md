---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/faulttesting
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting
title: Fault Injection Testing roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Fault Injection Testing. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Fault Injection Testing roles

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
<td><h4 id="faulttesting.viewer" class="role-title add-link" data-text="Fault Testing Viewer Beta" tabindex="-1">Fault Testing Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p>Readonly access to Fault Testing resources.</p></td>
<td><p><code dir="ltr" translate="no">faulttesting.  affectedResources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">faulttesting.  affectedResources.  get</code></li>
<li><code dir="ltr" translate="no">faulttesting.  affectedResources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  get</code></p>
<p><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  list</code></p>
<p><code dir="ltr" translate="no">faulttesting.experiments.get</code></p>
<p><code dir="ltr" translate="no">faulttesting.experiments.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.locations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">faulttesting.locations.get</code></li>
<li><code dir="ltr" translate="no">faulttesting.locations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">faulttesting.operations.get</code></p>
<p><code dir="ltr" translate="no">faulttesting.operations.list</code></p>
<p><code dir="ltr" translate="no">faulttesting.  validationResources.*</code></p>
<ul>
<li><code dir="ltr" translate="no">faulttesting.  validationResources.  get</code></li>
<li><code dir="ltr" translate="no">faulttesting.  validationResources.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">faulttesting.validations.get</code></p>
<p><code dir="ltr" translate="no">faulttesting.validations.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.operator" class="role-title add-link" data-text="Fault Testing Admin/Operator Beta" tabindex="-1">Fault Testing Admin/Operator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p>Full access to Fault Testing resources.</p></td>
<td><p><code dir="ltr" translate="no">faulttesting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">faulttesting.  affectedResources.  get</code></li>
<li><code dir="ltr" translate="no">faulttesting.  affectedResources.  list</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  create</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  delete</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  get</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  list</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  update</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experiments.  create</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experiments.  delete</code></li>
<li><code dir="ltr" translate="no">faulttesting.experiments.get</code></li>
<li><code dir="ltr" translate="no">faulttesting.experiments.list</code></li>
<li><code dir="ltr" translate="no">faulttesting.  experiments.  update</code></li>
<li><code dir="ltr" translate="no">faulttesting.locations.get</code></li>
<li><code dir="ltr" translate="no">faulttesting.locations.list</code></li>
<li><code dir="ltr" translate="no">faulttesting.operations.cancel</code></li>
<li><code dir="ltr" translate="no">faulttesting.operations.delete</code></li>
<li><code dir="ltr" translate="no">faulttesting.operations.get</code></li>
<li><code dir="ltr" translate="no">faulttesting.operations.list</code></li>
<li><code dir="ltr" translate="no">faulttesting.  validationResources.  get</code></li>
<li><code dir="ltr" translate="no">faulttesting.  validationResources.  list</code></li>
<li><code dir="ltr" translate="no">faulttesting.  validations.  create</code></li>
<li><code dir="ltr" translate="no">faulttesting.  validations.  delete</code></li>
<li><code dir="ltr" translate="no">faulttesting.validations.get</code></li>
<li><code dir="ltr" translate="no">faulttesting.validations.list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Fault Injection Testing permissions

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
<td><h4 id="faulttesting.affectedResources.get" class="permission-name add-link" data-text="faulttesting.affectedResources.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  affectedResources.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.affectedResources.list" class="permission-name add-link" data-text="faulttesting.affectedResources.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  affectedResources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.experimentTemplates.create" class="permission-name add-link" data-text="faulttesting.experimentTemplates.create" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.experimentTemplates.delete" class="permission-name add-link" data-text="faulttesting.experimentTemplates.delete" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.experimentTemplates.get" class="permission-name add-link" data-text="faulttesting.experimentTemplates.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.experimentTemplates.list" class="permission-name add-link" data-text="faulttesting.experimentTemplates.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.experimentTemplates.update" class="permission-name add-link" data-text="faulttesting.experimentTemplates.update" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experimentTemplates.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.experiments.create" class="permission-name add-link" data-text="faulttesting.experiments.create" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experiments.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.experiments.delete" class="permission-name add-link" data-text="faulttesting.experiments.delete" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experiments.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.experiments.get" class="permission-name add-link" data-text="faulttesting.experiments.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.experiments.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.experiments.list" class="permission-name add-link" data-text="faulttesting.experiments.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.experiments.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.experiments.update" class="permission-name add-link" data-text="faulttesting.experiments.update" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  experiments.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.locations.get" class="permission-name add-link" data-text="faulttesting.locations.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.locations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.locations.list" class="permission-name add-link" data-text="faulttesting.locations.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.locations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.operations.cancel" class="permission-name add-link" data-text="faulttesting.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">faulttesting.operations.cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.operations.delete" class="permission-name add-link" data-text="faulttesting.operations.delete" tabindex="-1"><code dir="ltr" translate="no">faulttesting.operations.delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.operations.get" class="permission-name add-link" data-text="faulttesting.operations.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.operations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.operations.list" class="permission-name add-link" data-text="faulttesting.operations.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.operations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.validationResources.get" class="permission-name add-link" data-text="faulttesting.validationResources.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  validationResources.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.validationResources.list" class="permission-name add-link" data-text="faulttesting.validationResources.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  validationResources.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.validations.create" class="permission-name add-link" data-text="faulttesting.validations.create" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  validations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.validations.delete" class="permission-name add-link" data-text="faulttesting.validations.delete" tabindex="-1"><code dir="ltr" translate="no">faulttesting.  validations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="faulttesting.validations.get" class="permission-name add-link" data-text="faulttesting.validations.get" tabindex="-1"><code dir="ltr" translate="no">faulttesting.validations.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="faulttesting.validations.list" class="permission-name add-link" data-text="faulttesting.validations.list" tabindex="-1"><code dir="ltr" translate="no">faulttesting.validations.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.viewer">Fault Testing Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/faulttesting#faulttesting.operator">Fault Testing Admin/Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  faulttesting.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
