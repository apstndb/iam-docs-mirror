---
name: documents/docs.cloud.google.com/iam/docs/roles-permissions/osconfig
uri: https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig
title: Cloud OS Config roles and permissions
description: Fine-grained access control and visibility for centrally managing cloud resources.
data_source: docs.cloud.google.com
---

This page lists the IAM roles and permissions for Cloud OS Config. To search through all roles and permissions, see the [role and permission index](https://docs.cloud.google.com/iam/docs/roles-permissions) .

## Cloud OS Config roles

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
<td>OS Config Admin
<p>( <code>roles/ osconfig.admin</code> )</p>
<p>Full access to OS Config resources</p></td>
<td><p><code>osconfig.*</code></p>
<ul>
<li><code>osconfig.guestPolicies.create</code></li>
<li><code>osconfig.guestPolicies.delete</code></li>
<li><code>osconfig.guestPolicies.get</code></li>
<li><code>osconfig.guestPolicies.list</code></li>
<li><code>osconfig.guestPolicies.update</code></li>
<li><code>osconfig. instanceOSPoliciesCompliances. get</code></li>
<li><code>osconfig. instanceOSPoliciesCompliances. list</code></li>
<li><code>osconfig.inventories.get</code></li>
<li><code>osconfig.inventories.list</code></li>
<li><code>osconfig.locations.get</code></li>
<li><code>osconfig.locations.list</code></li>
<li><code>osconfig.operations.cancel</code></li>
<li><code>osconfig.operations.delete</code></li>
<li><code>osconfig.operations.get</code></li>
<li><code>osconfig.operations.list</code></li>
<li><code>osconfig. osPolicyAssignmentReports. get</code></li>
<li><code>osconfig. osPolicyAssignmentReports. list</code></li>
<li><code>osconfig. osPolicyAssignmentReports. searchSummaries</code></li>
<li><code>osconfig. osPolicyAssignments. create</code></li>
<li><code>osconfig. osPolicyAssignments. delete</code></li>
<li><code>osconfig. osPolicyAssignments. get</code></li>
<li><code>osconfig. osPolicyAssignments. list</code></li>
<li><code>osconfig. osPolicyAssignments. searchPolicies</code></li>
<li><code>osconfig. osPolicyAssignments. update</code></li>
<li><code>osconfig. patchDeployments. create</code></li>
<li><code>osconfig. patchDeployments. delete</code></li>
<li><code>osconfig. patchDeployments. execute</code></li>
<li><code>osconfig.patchDeployments.get</code></li>
<li><code>osconfig.patchDeployments.list</code></li>
<li><code>osconfig. patchDeployments. pause</code></li>
<li><code>osconfig. patchDeployments. resume</code></li>
<li><code>osconfig. patchDeployments. update</code></li>
<li><code>osconfig.patchJobs.exec</code></li>
<li><code>osconfig.patchJobs.get</code></li>
<li><code>osconfig.patchJobs.list</code></li>
<li><code>osconfig. policyOrchestrators. create</code></li>
<li><code>osconfig. policyOrchestrators. delete</code></li>
<li><code>osconfig. policyOrchestrators. get</code></li>
<li><code>osconfig. policyOrchestrators. list</code></li>
<li><code>osconfig. policyOrchestrators. update</code></li>
<li><code>osconfig. projectFeatureSettings. get</code></li>
<li><code>osconfig. projectFeatureSettings. update</code></li>
<li><code>osconfig.upgradeReports.get</code></li>
<li><code>osconfig. upgradeReports. getSummary</code></li>
<li><code>osconfig.upgradeReports.list</code></li>
<li><code>osconfig. upgradeReports. searchSummaries</code></li>
<li><code>osconfig. vulnerabilityReports. get</code></li>
<li><code>osconfig. vulnerabilityReports. list</code></li>
</ul></td>
</tr>
<tr class="even">
<td>OS Config Viewer
<p>( <code>roles/ osconfig.viewer</code> )</p>
<p>Readonly access to OS Config resources</p></td>
<td><p><code>osconfig.guestPolicies.get</code></p>
<p><code>osconfig.guestPolicies.list</code></p>
<p><code>osconfig. instanceOSPoliciesCompliances.*</code></p>
<ul>
<li><code>osconfig. instanceOSPoliciesCompliances. get</code></li>
<li><code>osconfig. instanceOSPoliciesCompliances. list</code></li>
</ul>
<p><code>osconfig.inventories.*</code></p>
<ul>
<li><code>osconfig.inventories.get</code></li>
<li><code>osconfig.inventories.list</code></li>
</ul>
<p><code>osconfig.locations.*</code></p>
<ul>
<li><code>osconfig.locations.get</code></li>
<li><code>osconfig.locations.list</code></li>
</ul>
<p><code>osconfig.operations.get</code></p>
<p><code>osconfig.operations.list</code></p>
<p><code>osconfig. osPolicyAssignmentReports.*</code></p>
<ul>
<li><code>osconfig. osPolicyAssignmentReports. get</code></li>
<li><code>osconfig. osPolicyAssignmentReports. list</code></li>
<li><code>osconfig. osPolicyAssignmentReports. searchSummaries</code></li>
</ul>
<p><code>osconfig. osPolicyAssignments. get</code></p>
<p><code>osconfig. osPolicyAssignments. list</code></p>
<p><code>osconfig. osPolicyAssignments. searchPolicies</code></p>
<p><code>osconfig.patchDeployments.get</code></p>
<p><code>osconfig.patchDeployments.list</code></p>
<p><code>osconfig.patchJobs.get</code></p>
<p><code>osconfig.patchJobs.list</code></p>
<p><code>osconfig. policyOrchestrators. get</code></p>
<p><code>osconfig. policyOrchestrators. list</code></p>
<p><code>osconfig. projectFeatureSettings. get</code></p>
<p><code>osconfig.upgradeReports.*</code></p>
<ul>
<li><code>osconfig.upgradeReports.get</code></li>
<li><code>osconfig. upgradeReports. getSummary</code></li>
<li><code>osconfig.upgradeReports.list</code></li>
<li><code>osconfig. upgradeReports. searchSummaries</code></li>
</ul>
<p><code>osconfig. vulnerabilityReports.*</code></p>
<ul>
<li><code>osconfig. vulnerabilityReports. get</code></li>
<li><code>osconfig. vulnerabilityReports. list</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>GuestPolicy Admin <sup>Beta</sup>
<p>( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p>Full admin access to GuestPolicies</p></td>
<td><p><code>osconfig.guestPolicies.*</code></p>
<ul>
<li><code>osconfig.guestPolicies.create</code></li>
<li><code>osconfig.guestPolicies.delete</code></li>
<li><code>osconfig.guestPolicies.get</code></li>
<li><code>osconfig.guestPolicies.list</code></li>
<li><code>osconfig.guestPolicies.update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>GuestPolicy Editor <sup>Beta</sup>
<p>( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p>Editor of GuestPolicy resources</p></td>
<td><p><code>osconfig.guestPolicies.get</code></p>
<p><code>osconfig.guestPolicies.list</code></p>
<p><code>osconfig.guestPolicies.update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>GuestPolicy Viewer <sup>Beta</sup>
<p>( <code>roles/ osconfig.guestPolicyViewer</code> )</p>
<p>Viewer of GuestPolicy resources</p></td>
<td><p><code>osconfig.guestPolicies.get</code></p>
<p><code>osconfig.guestPolicies.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>InstanceOSPoliciesCompliance Viewer <sup>Beta</sup>
<p>( <code>roles/ osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p>Viewer of OS Policies Compliance of VM instances</p></td>
<td><p><code>osconfig. instanceOSPoliciesCompliances.*</code></p>
<ul>
<li><code>osconfig. instanceOSPoliciesCompliances. get</code></li>
<li><code>osconfig. instanceOSPoliciesCompliances. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>OS Inventory Viewer
<p>( <code>roles/ osconfig.inventoryViewer</code> )</p>
<p>Viewer of OS Inventories</p></td>
<td><p><code>osconfig.inventories.*</code></p>
<ul>
<li><code>osconfig.inventories.get</code></li>
<li><code>osconfig.inventories.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>OSPolicyAssignment Admin
<p>( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p>Full admin access to OS Policy Assignments</p></td>
<td><p><code>osconfig.osPolicyAssignments.*</code></p>
<ul>
<li><code>osconfig. osPolicyAssignments. create</code></li>
<li><code>osconfig. osPolicyAssignments. delete</code></li>
<li><code>osconfig. osPolicyAssignments. get</code></li>
<li><code>osconfig. osPolicyAssignments. list</code></li>
<li><code>osconfig. osPolicyAssignments. searchPolicies</code></li>
<li><code>osconfig. osPolicyAssignments. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>OSPolicyAssignment Editor
<p>( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p>Editor of OS Policy Assignments</p></td>
<td><p><code>osconfig. osPolicyAssignments. get</code></p>
<p><code>osconfig. osPolicyAssignments. list</code></p>
<p><code>osconfig. osPolicyAssignments. searchPolicies</code></p>
<p><code>osconfig. osPolicyAssignments. update</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>OSPolicyAssignmentReport Viewer
<p>( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p>Viewer of OS policy assignment reports for VM instances</p></td>
<td><p><code>osconfig. osPolicyAssignmentReports.*</code></p>
<ul>
<li><code>osconfig. osPolicyAssignmentReports. get</code></li>
<li><code>osconfig. osPolicyAssignmentReports. list</code></li>
<li><code>osconfig. osPolicyAssignmentReports. searchSummaries</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>OSPolicyAssignment Viewer
<p>( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p>Viewer of OS Policy Assignments</p></td>
<td><p><code>osconfig. osPolicyAssignments. get</code></p>
<p><code>osconfig. osPolicyAssignments. list</code></p>
<p><code>osconfig. osPolicyAssignments. searchPolicies</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>PatchDeployment Admin
<p>( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p>Full admin access to PatchDeployments</p></td>
<td><p><code>osconfig.patchDeployments.*</code></p>
<ul>
<li><code>osconfig. patchDeployments. create</code></li>
<li><code>osconfig. patchDeployments. delete</code></li>
<li><code>osconfig. patchDeployments. execute</code></li>
<li><code>osconfig.patchDeployments.get</code></li>
<li><code>osconfig.patchDeployments.list</code></li>
<li><code>osconfig. patchDeployments. pause</code></li>
<li><code>osconfig. patchDeployments. resume</code></li>
<li><code>osconfig. patchDeployments. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>PatchDeployment Viewer
<p>( <code>roles/ osconfig.patchDeploymentViewer</code> )</p>
<p>Viewer of PatchDeployment resources</p></td>
<td><p><code>osconfig.patchDeployments.get</code></p>
<p><code>osconfig.patchDeployments.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Patch Job Executor
<p>( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p>Access to execute Patch Jobs.</p></td>
<td><p><code>osconfig.patchJobs.*</code></p>
<ul>
<li><code>osconfig.patchJobs.exec</code></li>
<li><code>osconfig.patchJobs.get</code></li>
<li><code>osconfig.patchJobs.list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Patch Job Viewer
<p>( <code>roles/ osconfig.patchJobViewer</code> )</p>
<p>Get and list Patch Jobs.</p></td>
<td><p><code>osconfig.patchJobs.get</code></p>
<p><code>osconfig.patchJobs.list</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>PolicyOrchestrator Admin <sup>Beta</sup>
<p>( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p>Admin of PolicyOrchestrator resources</p></td>
<td><p><code>osconfig.locations.*</code></p>
<ul>
<li><code>osconfig.locations.get</code></li>
<li><code>osconfig.locations.list</code></li>
</ul>
<p><code>osconfig.operations.get</code></p>
<p><code>osconfig.policyOrchestrators.*</code></p>
<ul>
<li><code>osconfig. policyOrchestrators. create</code></li>
<li><code>osconfig. policyOrchestrators. delete</code></li>
<li><code>osconfig. policyOrchestrators. get</code></li>
<li><code>osconfig. policyOrchestrators. list</code></li>
<li><code>osconfig. policyOrchestrators. update</code></li>
</ul></td>
</tr>
<tr class="odd">
<td>PolicyOrchestrator Viewer <sup>Beta</sup>
<p>( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p>Viewer of PolicyOrchestrator resources</p></td>
<td><p><code>osconfig.locations.*</code></p>
<ul>
<li><code>osconfig.locations.get</code></li>
<li><code>osconfig.locations.list</code></li>
</ul>
<p><code>osconfig.operations.get</code></p>
<p><code>osconfig. policyOrchestrators. get</code></p>
<p><code>osconfig. policyOrchestrators. list</code></p></td>
</tr>
<tr class="even">
<td>Project Feature Settings Editor
<p>( <code>roles/ osconfig.projectFeatureSettingsEditor</code> )</p>
<p>Read/write access to project feature settings</p></td>
<td><p><code>osconfig. projectFeatureSettings.*</code></p>
<ul>
<li><code>osconfig. projectFeatureSettings. get</code></li>
<li><code>osconfig. projectFeatureSettings. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>Project Feature Settings Viewer
<p>( <code>roles/ osconfig.projectFeatureSettingsViewer</code> )</p>
<p>Read access to project feature settings</p></td>
<td><p><code>osconfig. projectFeatureSettings. get</code></p>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="even">
<td>Upgrade Report Viewer <sup>Beta</sup>
<p>( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p>Provides read-only access to VM Manager Upgrade Reports</p></td>
<td><p><code>osconfig.upgradeReports.*</code></p>
<ul>
<li><code>osconfig.upgradeReports.get</code></li>
<li><code>osconfig. upgradeReports. getSummary</code></li>
<li><code>osconfig.upgradeReports.list</code></li>
<li><code>osconfig. upgradeReports. searchSummaries</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
<tr class="odd">
<td>OS VulnerabilityReport Viewer
<p>( <code>roles/ osconfig.vulnerabilityReportViewer</code> )</p>
<p>Viewer of OS VulnerabilityReports</p></td>
<td><p><code>osconfig. vulnerabilityReports.*</code></p>
<ul>
<li><code>osconfig. vulnerabilityReports. get</code></li>
<li><code>osconfig. vulnerabilityReports. list</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

### Service agent roles

Service agent roles should only be granted to [service agents](https://docs.cloud.google.com/iam/docs/service-agents) .

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
<td>Cloud OS Config Rollout Service Agent
<p>( <code>roles/ osconfig.rolloutServiceAgent</code> )</p>
<p>Grants OS Config Rollout Service Account access to zonal OS Config resources.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>osconfig.operations.get</code></p>
<p><code>osconfig. osPolicyAssignments. delete</code></p>
<p><code>osconfig. osPolicyAssignments. get</code></p>
<p><code>osconfig. osPolicyAssignments. update</code></p></td>
</tr>
<tr class="even">
<td>Cloud OS Config Service Agent
<p>( <code>roles/ osconfig.serviceAgent</code> )</p>
<p>Grants OS Config Service Account access to Google Compute Engine instances.</p>
<blockquote>
<strong>Warning:</strong> Do not grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote></td>
<td><p><code>cloudasset. assets. listOSConfigOSPolicyAssignments</code></p>
<p><code>cloudasset. assets. listPatchDeployments</code></p>
<p><code>compute.globalOperations.get</code></p>
<p><code>compute.instances.get</code></p>
<p><code>compute. instances. getGuestAttributes</code></p>
<p><code>compute.instances.list</code></p>
<p><code>compute.instances.setMetadata</code></p>
<p><code>compute.projects.get</code></p>
<p><code>compute. projects. setCommonInstanceMetadata</code></p>
<p><code>compute.zones.*</code></p>
<ul>
<li><code>compute.zones.get</code></li>
<li><code>compute.zones.list</code></li>
</ul>
<p><code>containeranalysis. notes. attachOccurrence</code></p>
<p><code>containeranalysis.notes.create</code></p>
<p><code>containeranalysis.notes.delete</code></p>
<p><code>containeranalysis.notes.get</code></p>
<p><code>containeranalysis.notes.list</code></p>
<p><code>containeranalysis.notes.update</code></p>
<p><code>containeranalysis. occurrences. create</code></p>
<p><code>containeranalysis. occurrences. delete</code></p>
<p><code>containeranalysis. occurrences. get</code></p>
<p><code>containeranalysis. occurrences. list</code></p>
<p><code>containeranalysis. occurrences. update</code></p>
<p><code>iam.serviceAccounts.actAs</code></p>
<p><code>osconfig. projectFeatureSettings.*</code></p>
<ul>
<li><code>osconfig. projectFeatureSettings. get</code></li>
<li><code>osconfig. projectFeatureSettings. update</code></li>
</ul>
<p><code>resourcemanager.projects.get</code></p>
<p><code>resourcemanager.projects.list</code></p></td>
</tr>
</tbody>
</table>

## Cloud OS Config permissions

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
<td><code>osconfig.guestPolicies.create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.guestPolicies.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.guestPolicies.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code>roles/ osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.guestPolicies.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyViewer">GuestPolicy Viewer</a> ( <code>roles/ osconfig.guestPolicyViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.guestPolicies.update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyAdmin">GuestPolicy Admin</a> ( <code>roles/ osconfig.guestPolicyAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.guestPolicyEditor">GuestPolicy Editor</a> ( <code>roles/ osconfig.guestPolicyEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. instanceOSPoliciesCompliances. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code>roles/ osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. instanceOSPoliciesCompliances. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.instanceOSPoliciesComplianceViewer">InstanceOSPoliciesCompliance Viewer</a> ( <code>roles/ osconfig.instanceOSPoliciesComplianceViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.inventories.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code>roles/ osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.inventories.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.inventoryViewer">OS Inventory Viewer</a> ( <code>roles/ osconfig.inventoryViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.locations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.locations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.operations.cancel</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.operations.delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.operations.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code>roles/ osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>osconfig.operations.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. osPolicyAssignmentReports. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. osPolicyAssignmentReports. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. osPolicyAssignmentReports. searchSummaries</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentReportViewer">OSPolicyAssignmentReport Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. osPolicyAssignments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. osPolicyAssignments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code>roles/ osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>osconfig. osPolicyAssignments. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code>roles/ osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>osconfig. osPolicyAssignments. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. osPolicyAssignments. searchPolicies</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentViewer">OSPolicyAssignment Viewer</a> ( <code>roles/ osconfig.osPolicyAssignmentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. osPolicyAssignments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentAdmin">OSPolicyAssignment Admin</a> ( <code>roles/ osconfig.osPolicyAssignmentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.osPolicyAssignmentEditor">OSPolicyAssignment Editor</a> ( <code>roles/ osconfig.osPolicyAssignmentEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.rolloutServiceAgent">Cloud OS Config Rollout Service Agent</a> ( <code>roles/ osconfig.rolloutServiceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>osconfig. patchDeployments. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. patchDeployments. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. patchDeployments. execute</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.patchDeployments.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code>roles/ osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.patchDeployments.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentViewer">PatchDeployment Viewer</a> ( <code>roles/ osconfig.patchDeploymentViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. patchDeployments. pause</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. patchDeployments. resume</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. patchDeployments. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchDeploymentAdmin">PatchDeployment Admin</a> ( <code>roles/ osconfig.patchDeploymentAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.patchJobs.exec</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig.patchJobs.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code>roles/ osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.patchJobs.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobExecutor">Patch Job Executor</a> ( <code>roles/ osconfig.patchJobExecutor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.patchJobViewer">Patch Job Viewer</a> ( <code>roles/ osconfig.patchJobViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. policyOrchestrators. create</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. policyOrchestrators. delete</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. policyOrchestrators. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. policyOrchestrators. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorViewer">PolicyOrchestrator Viewer</a> ( <code>roles/ osconfig.policyOrchestratorViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. policyOrchestrators. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.policyOrchestratorAdmin">PolicyOrchestrator Admin</a> ( <code>roles/ osconfig.policyOrchestratorAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. projectFeatureSettings. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code>roles/ osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsViewer">Project Feature Settings Viewer</a> ( <code>roles/ osconfig.projectFeatureSettingsViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code>roles/ osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="even">
<td><code>osconfig. projectFeatureSettings. update</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.projectFeatureSettingsEditor">Project Feature Settings Editor</a> ( <code>roles/ osconfig.projectFeatureSettingsEditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p>
<p>Service agent roles</p>
<blockquote>
<strong>Warning:</strong> Don't grant service agent roles to any principals except <a href="https://docs.cloud.google.com/iam/docs/service-agents">service agents</a> .
</blockquote>
<ul>
<li><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.serviceAgent">Cloud OS Config Service Agent</a> ( <code>roles/ osconfig.serviceAgent</code> )</li>
</ul></td>
</tr>
<tr class="odd">
<td><code>osconfig.upgradeReports.get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. upgradeReports. getSummary</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig.upgradeReports.list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. upgradeReports. searchSummaries</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.upgradeReportViewer">Upgrade Report Viewer</a> ( <code>roles/ osconfig.upgradeReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="odd">
<td><code>osconfig. vulnerabilityReports. get</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code>roles/ osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
<tr class="even">
<td><code>osconfig. vulnerabilityReports. list</code></td>
<td><p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Owner</a> ( <code>roles/ owner</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Editor</a> ( <code>roles/ editor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Viewer</a> ( <code>roles/ viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityAdmin">Security Admin</a> ( <code>roles/ iam.securityAdmin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/iam#iam.securityReviewer">Security Reviewer</a> ( <code>roles/ iam.securityReviewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.admin">OS Config Admin</a> ( <code>roles/ osconfig.admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.viewer">OS Config Viewer</a> ( <code>roles/ osconfig.viewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Admin</a> ( <code>roles/ admin</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.securityAuditor">Security Auditor</a> ( <code>roles/ iam.securityAuditor</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/jobfunctions#iam.supportUser">Support User</a> ( <code>roles/ iam.supportUser</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-permissions/osconfig#osconfig.vulnerabilityReportViewer">OS VulnerabilityReport Viewer</a> ( <code>roles/ osconfig.vulnerabilityReportViewer</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Reader</a> ( <code>roles/ reader</code> )</p>
<p><a href="https://docs.cloud.google.com/iam/docs/roles-overview#basic">Writer</a> ( <code>roles/ writer</code> )</p></td>
</tr>
</tbody>
</table>
