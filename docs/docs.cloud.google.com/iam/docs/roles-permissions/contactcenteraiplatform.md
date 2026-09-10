---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform
title: Google Cloud Contact Center as a Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Cloud Contact Center as a Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Cloud Contact Center as a Service roles

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
<td><h4 id="contactcenteraiplatform.admin" class="role-title add-link" data-text="Contact Center AI Platform Admin" tabindex="-1">Contact Center AI Platform Admin</h4>
<p>( <code dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p>Full access to Contact Center AI Platform resources.</p></td>
<td><p><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  create</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  delete</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  get</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  list</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  program</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  queryQuota</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  get</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  operations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  cancel</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  delete</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  get</code></li>
<li><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.viewer" class="role-title add-link" data-text="Contact Center AI Platform Viewer" tabindex="-1">Contact Center AI Platform Viewer</h4>
<p>( <code dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p>Read-only access to Contact Center AI Platform resources.</p></td>
<td><p><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  get</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  get</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  list</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  get</code></p>
<p><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.workforceSchedulingShiftGenerator" class="role-title add-link" data-text="Workforce Scheduling Shift Generator Beta" tabindex="-1">Workforce Scheduling Shift Generator <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  contactcenteraiplatform.workforceSchedulingShiftGenerator</code> )</p>
<p>Access to generating shifts using Workforce Scheduling.</p></td>
<td><p><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  generateShifts</code></p></td>
</tr>
</tbody>
</table>

## Google Cloud Contact Center as a Service permissions

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
<td><h4 id="contactcenteraiplatform.contactCenters.create" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.create" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.contactCenters.delete" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.delete" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.contactCenters.get" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.get" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.contactCenters.list" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.list" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.contactCenters.program" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.program" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  program</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.contactCenters.queryQuota" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.queryQuota" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  queryQuota</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.contactCenters.update" class="permission-name add-link" data-text="contactcenteraiplatform.contactCenters.update" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  contactCenters.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.locations.generateShifts" class="permission-name add-link" data-text="contactcenteraiplatform.locations.generateShifts" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  generateShifts</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.workforceSchedulingShiftGenerator">Workforce Scheduling Shift Generator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.workforceSchedulingShiftGenerator</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.locations.get" class="permission-name add-link" data-text="contactcenteraiplatform.locations.get" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.locations.list" class="permission-name add-link" data-text="contactcenteraiplatform.locations.list" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  locations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.operations.cancel" class="permission-name add-link" data-text="contactcenteraiplatform.operations.cancel" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  cancel</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.operations.delete" class="permission-name add-link" data-text="contactcenteraiplatform.operations.delete" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="contactcenteraiplatform.operations.get" class="permission-name add-link" data-text="contactcenteraiplatform.operations.get" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="contactcenteraiplatform.operations.list" class="permission-name add-link" data-text="contactcenteraiplatform.operations.list" tabindex="-1"><code dir="ltr" translate="no">contactcenteraiplatform.  operations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.admin">Contact Center AI Platform Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/contactcenteraiplatform#contactcenteraiplatform.viewer">Contact Center AI Platform Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  contactcenteraiplatform.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
