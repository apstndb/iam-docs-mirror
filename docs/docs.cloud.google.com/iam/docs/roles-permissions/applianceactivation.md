---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation
title: Appliance Activation Service roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Appliance Activation Service. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Appliance Activation Service roles

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
<td><h4 id="applianceactivation.admin" class="role-title add-link" data-text="Appliance Admin Beta" tabindex="-1">Appliance Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p>Admin role for Appliance</p></td>
<td><p><code dir="ltr" translate="no">applianceactivation.*</code></p>
<ul>
<li><code dir="ltr" translate="no">applianceactivation.  rttCommands.  approve</code></li>
<li><code dir="ltr" translate="no">applianceactivation.  rttCommands.  create</code></li>
<li><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></li>
<li><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></li>
<li><code dir="ltr" translate="no">applianceactivation.  rttCommands.  sendResult</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="applianceactivation.viewer" class="role-title add-link" data-text="Appliance Viewer Beta" tabindex="-1">Appliance Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  applianceactivation.viewer</code> )</p>
<p>Viewer role for Appliance</p></td>
<td><p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="applianceactivation.approver" class="role-title add-link" data-text="Appliance troubleshooting commands approver Beta" tabindex="-1">Appliance troubleshooting commands approver <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  applianceactivation.approver</code> )</p>
<p>Grants access to approve commands to run on appliances</p></td>
<td><p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  approve</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td><h4 id="applianceactivation.client" class="role-title add-link" data-text="On-appliance troubleshooting client Beta" tabindex="-1">On-appliance troubleshooting client <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  applianceactivation.client</code> )</p>
<p>Grants access to read commands for an appliance and send its result.</p></td>
<td><p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  sendResult</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="applianceactivation.troubleshooter" class="role-title add-link" data-text="Appliance troubleshooter Beta" tabindex="-1">Appliance troubleshooter <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p>
<p>Grants access to send new commands to run on appliances and view the outputs</p></td>
<td><p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  create</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></p>
<p><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Appliance Activation Service permissions

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
<td><h4 id="applianceactivation.rttCommands.approve" class="permission-name add-link" data-text="applianceactivation.rttCommands.approve" tabindex="-1"><code dir="ltr" translate="no">applianceactivation.  rttCommands.  approve</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.approver</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="applianceactivation.rttCommands.create" class="permission-name add-link" data-text="applianceactivation.rttCommands.create" tabindex="-1"><code dir="ltr" translate="no">applianceactivation.  rttCommands.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="applianceactivation.rttCommands.get" class="permission-name add-link" data-text="applianceactivation.rttCommands.get" tabindex="-1"><code dir="ltr" translate="no">applianceactivation.  rttCommands.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.approver">Appliance troubleshooting commands approver</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.approver</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.client">On-appliance troubleshooting client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.client</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="applianceactivation.rttCommands.list" class="permission-name add-link" data-text="applianceactivation.rttCommands.list" tabindex="-1"><code dir="ltr" translate="no">applianceactivation.  rttCommands.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.viewer">Appliance Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.troubleshooter">Appliance troubleshooter</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.troubleshooter</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="applianceactivation.rttCommands.sendResult" class="permission-name add-link" data-text="applianceactivation.rttCommands.sendResult" tabindex="-1"><code dir="ltr" translate="no">applianceactivation.  rttCommands.  sendResult</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.admin">Appliance Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/applianceactivation#applianceactivation.client">On-appliance troubleshooting client</a> ( <code class="role-name" dir="ltr" translate="no">roles/  applianceactivation.client</code> )</p></td>
</tr>
</tbody>
</table>
