---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/errorreporting
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting
title: Error Reporting roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Error Reporting. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Error Reporting roles

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
<td><h4 id="errorreporting.admin" class="role-title add-link" data-text="Error Reporting Admin Beta" tabindex="-1">Error Reporting Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p>Provides full access to Error Reporting data.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.*</code></p>
<ul>
<li><code dir="ltr" translate="no">errorreporting.  applications.  list</code></li>
<li><code dir="ltr" translate="no">errorreporting.  errorEvents.  create</code></li>
<li><code dir="ltr" translate="no">errorreporting.  errorEvents.  delete</code></li>
<li><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></li>
<li><code dir="ltr" translate="no">errorreporting.  groupMetadata.  get</code></li>
<li><code dir="ltr" translate="no">errorreporting.  groupMetadata.  update</code></li>
<li><code dir="ltr" translate="no">errorreporting.groups.list</code></li>
</ul>
<p><code dir="ltr" translate="no">logging.notificationRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.  notificationRules.  create</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  delete</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.get</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.list</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="errorreporting.user" class="role-title add-link" data-text="Error Reporting User Beta" tabindex="-1">Error Reporting User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p>Provides the permissions to read and write Error Reporting data, except for sending new error events.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  applications.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  delete</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.groupMetadata.*</code></p>
<ul>
<li><code dir="ltr" translate="no">errorreporting.  groupMetadata.  get</code></li>
<li><code dir="ltr" translate="no">errorreporting.  groupMetadata.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.*</code></p>
<ul>
<li><code dir="ltr" translate="no">logging.  notificationRules.  create</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  delete</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.get</code></li>
<li><code dir="ltr" translate="no">logging.notificationRules.list</code></li>
<li><code dir="ltr" translate="no">logging.  notificationRules.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="errorreporting.viewer" class="role-title add-link" data-text="Error Reporting Viewer Beta" tabindex="-1">Error Reporting Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p>Provides read-only access to Error Reporting data.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Project</li>
</ul></td>
<td><p><code dir="ltr" translate="no">cloudnotifications.  activities.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  applications.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></p>
<p><code dir="ltr" translate="no">errorreporting.  groupMetadata.  get</code></p>
<p><code dir="ltr" translate="no">errorreporting.groups.list</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.get</code></p>
<p><code dir="ltr" translate="no">logging.notificationRules.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">stackdriver.projects.get</code></p></td>
</tr>
<tr class="even">
<td><h4 id="errorreporting.writer" class="role-title add-link" data-text="Error Reporting Writer Beta" tabindex="-1">Error Reporting Writer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  errorreporting.writer</code> )</p>
<p>Provides the permissions to send error events to Error Reporting.</p>
<p>Lowest-level resources where you can grant this role:</p>
<ul>
<li>Service Account</li>
</ul></td>
<td><p><code dir="ltr" translate="no">errorreporting.  errorEvents.  create</code></p></td>
</tr>
</tbody>
</table>

## Error Reporting permissions

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
<td><h4 id="errorreporting.applications.list" class="permission-name add-link" data-text="errorreporting.applications.list" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  applications.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="errorreporting.errorEvents.create" class="permission-name add-link" data-text="errorreporting.errorEvents.create" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  errorEvents.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.writer">Error Reporting Writer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.writer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="errorreporting.errorEvents.delete" class="permission-name add-link" data-text="errorreporting.errorEvents.delete" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  errorEvents.  delete</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="errorreporting.errorEvents.list" class="permission-name add-link" data-text="errorreporting.errorEvents.list" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  errorEvents.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="errorreporting.groupMetadata.get" class="permission-name add-link" data-text="errorreporting.groupMetadata.get" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  groupMetadata.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="errorreporting.groupMetadata.update" class="permission-name add-link" data-text="errorreporting.groupMetadata.update" tabindex="-1"><code dir="ltr" translate="no">errorreporting.  groupMetadata.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="errorreporting.groups.list" class="permission-name add-link" data-text="errorreporting.groups.list" tabindex="-1"><code dir="ltr" translate="no">errorreporting.groups.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.admin">Error Reporting Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.user">Error Reporting User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.user</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/errorreporting#errorreporting.viewer">Error Reporting Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  errorreporting.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.admin">Firebase Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.editor">Firebase Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.viewer">Firebase Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/cloudhub#cloudhub.operator">Cloud Hub Operator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  cloudhub.operator</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developAdmin">Firebase Develop Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/firebase#firebase.developViewer">Firebase Develop Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  firebase.developViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.siteReliabilityEngineer">Site Reliability Engineer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.siteReliabilityEngineer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
</tbody>
</table>
