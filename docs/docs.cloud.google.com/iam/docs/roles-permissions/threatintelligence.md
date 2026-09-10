---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence
title: Google Threat Intelligence roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Google Threat Intelligence. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Google Threat Intelligence roles

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
<td><h4 id="threatintelligence.alertAdmin" class="role-title add-link" data-text="GTI Alert Admin Beta" tabindex="-1">GTI Alert Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p>This role can view and edit all properties of resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  alertdocuments.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.alerts.get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.alerts.list</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  alerts.  update</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  update</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.alertUser" class="role-title add-link" data-text="GTI Alert User Beta" tabindex="-1">GTI Alert User <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p>This role can view and edit properties of resources, except for editing configurations and exporting alerts.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  alertdocuments.  get</code></p>
<p><code dir="ltr" translate="no">threatintelligence.alerts.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.alerts.get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.alerts.list</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  alerts.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></p>
<p><code dir="ltr" translate="no">threatintelligence.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.ctemAdmin" class="role-title add-link" data-text="CTEM Admin Beta" tabindex="-1">CTEM Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p>This role can view and edit all properties of resources along with the Projects.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">threatintelligence.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.ctemEditor" class="role-title add-link" data-text="CTEM Editor Beta" tabindex="-1">CTEM Editor <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p>This role can view and edit all properties of resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  configurations.  update</code></li>
</ul>
<p><code dir="ltr" translate="no">threatintelligence.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.ctemProjectAdmin" class="role-title add-link" data-text="CTEM Project Admin Beta" tabindex="-1">CTEM Project Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p>CTEM Project Admin</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  update</code></p>
<p><code dir="ltr" translate="no">threatintelligence.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.ctemViewer" class="role-title add-link" data-text="CTEM Viewer Beta" tabindex="-1">CTEM Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p>
<p>This role can view all resources.</p></td>
<td><p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></p>
<p><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></p>
<p><code dir="ltr" translate="no">threatintelligence.findings.*</code></p>
<ul>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></li>
<li><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></li>
</ul></td>
</tr>
</tbody>
</table>

## Google Threat Intelligence permissions

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
<td><h4 id="threatintelligence.alertdocuments.get" class="permission-name add-link" data-text="threatintelligence.alertdocuments.get" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  alertdocuments.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.alerts.get" class="permission-name add-link" data-text="threatintelligence.alerts.get" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.alerts.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.alerts.list" class="permission-name add-link" data-text="threatintelligence.alerts.list" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.alerts.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.alerts.update" class="permission-name add-link" data-text="threatintelligence.alerts.update" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  alerts.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.configurations.get" class="permission-name add-link" data-text="threatintelligence.configurations.get" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  configurations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.configurations.list" class="permission-name add-link" data-text="threatintelligence.configurations.list" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  configurations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.configurations.listRevisions" class="permission-name add-link" data-text="threatintelligence.configurations.listRevisions" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  configurations.  listRevisions</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.configurations.update" class="permission-name add-link" data-text="threatintelligence.configurations.update" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  configurations.  update</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="threatintelligence.findings.get" class="permission-name add-link" data-text="threatintelligence.findings.get" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  findings.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="threatintelligence.findings.list" class="permission-name add-link" data-text="threatintelligence.findings.list" tabindex="-1"><code dir="ltr" translate="no">threatintelligence.  findings.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertAdmin">GTI Alert Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.alertUser">GTI Alert User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.alertUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemAdmin">CTEM Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemEditor">CTEM Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemProjectAdmin">CTEM Project Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemProjectAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/threatintelligence#threatintelligence.ctemViewer">CTEM Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  threatintelligence.ctemViewer</code> )</p></td>
</tr>
</tbody>
</table>
