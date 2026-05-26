---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/policysimulator
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator
title: Policy Simulator roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Policy Simulator. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Policy Simulator roles

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
<td><h4 id="policysimulator.admin" class="role-title add-link" data-text="Simulator Admin Beta" tabindex="-1">Simulator Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p>Admin user that can run and access replays.</p></td>
<td><p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  create</code></li>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  get</code></li>
<li><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">policysimulator.  replayResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.replays.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policysimulator.replays.create</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.get</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.list</code></li>
<li><code dir="ltr" translate="no">policysimulator.replays.run</code></li>
</ul></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.orgPolicyAdmin" class="role-title add-link" data-text="OrgPolicy Simulator Admin Beta" tabindex="-1">OrgPolicy Simulator Admin <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p>
<p>OrgPolicy Admin that can run and access simulations.</p></td>
<td><p><code dir="ltr" translate="no">cloudasset.  assets.  analyzeOrgPolicy</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  exportResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.assets.listResource</code></p>
<p><code dir="ltr" translate="no">cloudasset.  assets.  searchAllResources</code></p>
<p><code dir="ltr" translate="no">orgpolicy.  customConstraints.  get</code></p>
<p><code dir="ltr" translate="no">orgpolicy.  customConstraints.  list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policies.list</code></p>
<p><code dir="ltr" translate="no">orgpolicy.policy.get</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.*</code></p>
<ul>
<li><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  create</code></li>
<li><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  get</code></li>
<li><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  list</code></li>
</ul>
<p><code dir="ltr" translate="no">resourcemanager.  organizations.  get</code></p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.viewer" class="role-title add-link" data-text="Policysimulator Viewer Beta" tabindex="-1">Policysimulator Viewer <sup>Beta</sup></h4>
<p>( <code dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p>Viewer role for policysimulator</p></td>
<td><p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  get</code></p>
<p><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolations.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  get</code></p>
<p><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.  replayResults.  list</code></p>
<p><code dir="ltr" translate="no">policysimulator.replays.get</code></p>
<p><code dir="ltr" translate="no">policysimulator.replays.list</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.get</code></p>
<p><code dir="ltr" translate="no">resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Policy Simulator permissions

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
<td><h4 id="policysimulator.accessPolicySimulationResults.list" class="permission-name add-link" data-text="policysimulator.accessPolicySimulationResults.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  accessPolicySimulationResults.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.accessPolicySimulations.create" class="permission-name add-link" data-text="policysimulator.accessPolicySimulations.create" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.accessPolicySimulations.get" class="permission-name add-link" data-text="policysimulator.accessPolicySimulations.get" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.accessPolicySimulations.list" class="permission-name add-link" data-text="policysimulator.accessPolicySimulations.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  accessPolicySimulations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.denyAdmin">Deny Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.denyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.orgPolicyViolations.list" class="permission-name add-link" data-text="policysimulator.orgPolicyViolations.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  orgPolicyViolations.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.orgPolicyViolationsPreviews.create" class="permission-name add-link" data-text="policysimulator.orgPolicyViolationsPreviews.create" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.orgPolicyViolationsPreviews.get" class="permission-name add-link" data-text="policysimulator.orgPolicyViolationsPreviews.get" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.orgPolicyViolationsPreviews.list" class="permission-name add-link" data-text="policysimulator.orgPolicyViolationsPreviews.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  orgPolicyViolationsPreviews.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/orgpolicy#orgpolicy.policyAdmin">Organization Policy Administrator</a> ( <code class="role-name" dir="ltr" translate="no">roles/  orgpolicy.policyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.orgPolicyAdmin">OrgPolicy Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.orgPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.replayResults.list" class="permission-name add-link" data-text="policysimulator.replayResults.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.  replayResults.  list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.replays.create" class="permission-name add-link" data-text="policysimulator.replays.create" tabindex="-1"><code dir="ltr" translate="no">policysimulator.replays.create</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.replays.get" class="permission-name add-link" data-text="policysimulator.replays.get" tabindex="-1"><code dir="ltr" translate="no">policysimulator.replays.get</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="even">
<td><h4 id="policysimulator.replays.list" class="permission-name add-link" data-text="policysimulator.replays.list" tabindex="-1"><code dir="ltr" translate="no">policysimulator.replays.list</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.viewer">Policysimulator Viewer</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.supportUser</code> )</p></td>
</tr>
<tr class="odd">
<td><h4 id="policysimulator.replays.run" class="permission-name add-link" data-text="policysimulator.replays.run" tabindex="-1"><code dir="ltr" translate="no">policysimulator.replays.run</code></h4></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code class="role-name" dir="ltr" translate="no">roles/  owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/policysimulator#policysimulator.admin">Simulator Admin</a> ( <code class="role-name" dir="ltr" translate="no">roles/  policysimulator.admin</code> )</p></td>
</tr>
</tbody>
</table>
